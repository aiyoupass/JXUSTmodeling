# 全国大学生数学建模竞赛LaTeX模板
这个库是我从 `sikouhjw` 那里 fork 出来的.在此感谢原作者

然后降低了这个模板的使用门槛（**有手就行**）(~~没手也行~~)

改正了了原库的一些错误

过不久就要校赛了，大家加油鸭
## 使用方法
0. 浏览（阅读）库中所有`pdf`文件（包括子文件夹），获取信息。
1. 首先下载`TeX Live`
2. 安装`TeX Live`（非便携安装）
3. Clone 这个库，得到模板源代码文件
4. 安装一个合适的`LaTeX`编辑器（例如`TeX Studio`或`Visual Studio Code` 搭配`LaTeX Workshop`插件）
8. 安装`Python`高版本及`pygments`（安装命令`pip install Pygments`),如果不在论文中加代码的话不需要这一步
5. 设置正确的编译选项(用`XeLaTeX`编译，编译选项`-shell-escape`等)
6. 简短的编译命令`xelatex 源代码文件`（目录需要编译两遍）
7. 完整的编译命令`xelatex -synctex=1 -shell-escape -interaction=nonstopmode -file-line-error 源代码文件`（这个模板必须加上这些参数才能编译成功）
8. 建立一个文件夹，把`JXUSTmodeling.cls`文件放进去，如果有图片需要建立`figures`文件夹，将图片放入。创建一个后缀名为`tex`的文件，编写代码
9. 开心的完成编译

## 备注
1. `document`文件夹中的两个文件可以当词典来用，不需要完整阅读
2. 推荐（可以）根据`sample`中的一个简单实例以及`example.pdf`来学习
3. 遇到不会的问题学会使用`google\baidu`等搜索引擎查找答案，通常`stackexchange`中的`TeX`专区<https://www.tex.stackexchange.com>会找到令人满意的答案。
4. 插入代码可以使用`minted`,`listings`两种方式，定义了`mma`,`python`,`matlab`,`cpp`四种代码的环境