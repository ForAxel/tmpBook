
# MyST格式转化

需要使用 jupytext 库

You can convert an .ipynb file to a MyST notebook with the following command:

> jupytext mynotebook.ipynb --to myst

To add Jupytext syntax to a Markdown file (that will tell Jupytext it is a MyST Markdown file), run the following command:

>jupyter-book myst init mymarkdownfile.md --kernel kernelname



# book内容清除

> jupyter-book clean mybookname/
> jupyter-book clean mybookname/ --all

build 过程debug
> jupyter-book build -W -n --keep-going mybookname/