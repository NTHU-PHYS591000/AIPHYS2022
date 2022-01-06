# 11020PHYS591000

This course website source codes is powered by [Jupyter Book](https://jupyterbook.org). 
You can install it by following this [instruction](https://jupyterbook.org/intro.html#install-jupyter-book)

## Edit this book

Clone the current repository to a location on your local computer. You can do this via the command line with:

```
git clone https://github.com/NTHU-PHYS591000/AIPHYS2022
```
## Build your book

Once you’ve added content and configured your book, you can build outputs for your book..
```
jupyter-book build AIPHYS2022
```
## Local preview

To preview your book, you can open the generated HTML files in your browser. 
Either double-click the html file in your local folder, 
or enter the absolute path to the file in your browser navigation bar adding 
file:// at the beginning (e.g. file://Users/my_path_to_book/_build/index.html).

## Sync repositories 

Now you need to sync your local and remote (i.e., online) repositories. 
You can do this with the following commands:

```
cd AIPHYS2022
git add ./*
git commit -m "your comments"
git push
```

## Publish Book On-line

The easiest way to use GitHub Pages with your built HTML is to use the ghp-import package. 
ghp-import is a lightweight Python package that makes it easy to push HTML content to the 
GitHub branch gh-pages. It can be installed by following [instruction](https://jupyterbook.org/publish/gh-pages.html)

From the master branch of your book’s root directory (which contains the _build/html folder) 
call ghp-import and point it to your HTML files, like so:
``` 
cd AIPHYS2022
ghp-import -n -p -f _build/html
```

Typically after a few minutes your site should be viewable online at a url such as: 
https://NTHU-PHYS591000.github.io/AIPHYS2022/. 