# 全国大学生数学建模竞赛LaTeX模板
这个库是我从 `sikouhjw` 那里 fork 出来的.在此感谢原作者

然后降低了这个模板的使用门槛（**有手就行**）(~~没手也行~~)

改正了了原库的一些错误
## 使用方法
1. 首先下载`TeX Live`
2. 安装`TeX Live`（非便携安装）
3. Clone 这个库，得到模板源代码文件
4. 安装一个合适的`LaTeX`编辑器（例如`TeX Studio`或`Visual Studio Code` 搭配`LaTeX Workshop`插件）
8. 安装`Python`高版本及`pygments`（安装命令`pip install Pygments`)
5. 设置正确的编译选项(用`XeLaTeX`编译，编译选项`-shell-escape`等)
6. 简短的编译命令`xelatex 源代码文件`（有目录需要编译两遍）
7. 加上引用的话就是用`xelatex`编译一遍，再用`bibtex`编译一遍，再用`xelatex`编译一遍
7. 完整的编译命令`xelatex -synctex=1 -shell-escape -interaction=nonstopmode -file-line-error 源代码文件`
9. 开心的写完论文并完美完成编译
