# Jupyter-Notebook - Atom Scheme 

This is a completely dark theme for the Jupyter Notebook interface. 

Jupyter includes iPython 4 as its default kernel (which, confusingly, supports both Python 2.x and 3.x). Since the iPython 3 to 4 transition, it has gained better support for other interpreters like R and Ruby. It is possible to upgrade iPython 2 or 3 to Jupyter + iPython 4.

Source code coloring is based on the Twilight theme for Textmate. Print preview output for notebooks retains a white background with printable foreground colors.

## Installing

To install this theme, copy or symlink custom.css into ~/.jupyter/custom/ 

```unix
cd ~/.jupyter/custom/ 
```

(create that directory if it doesn't exist: mkdir ) 

```unix
vi custom.css
```

Then, whenever you run jupyter notebook, iruby notebook, etc. it will use this theme.

## Tips

most of the coloring information can be modified after line 300.

For more information on color code please click [here](http://html-color-codes.info/)
