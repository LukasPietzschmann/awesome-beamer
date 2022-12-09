# Awesome-Beamer
The kinda awesome beamer theme!

## Using the theme
Your project structure has to look like this:

```
|--main.tex (your root document)
|--styles/
|  |--<all .sty files from this repo + use_me.tex>
|  |--use_me.tex
|  |--beamercolorthemeAwesome.sty
|  |-- ...
```

You have to include `use_me.tex` in your main LaTeX file.
If you follow the above directory structure, this should be enough to get you started.

## Compilation
Using this theme requires you to run pdflatex (or whatever compiler you prefer) multiple times on your main LaTeX file. This is required for those litte dots in the footer to work.
If you're using latexmk you don't have to do this manually as latexmk can figure this stuff out by itself.


## Example slides
![example.pdf](https://github.com/LukasPietzschmann/awesome-beamer/blob/master/example/example.pdf)
