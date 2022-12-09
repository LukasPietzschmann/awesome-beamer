# Awesome-Beamer
The kinda awesome beamer theme!

## Using the theme
Just copy and paste `beamerthemeawesome.sty` into your project, add `\usetheme{awesome}` into your main file and your good to go :)

## Options
This theme provides some settings you can tweak:
- Language: Possible values are `english` or `german`. This changes the value passed to babel and csquotes. If none of both is selected, `german` is used.
- Extra slides: For each section and subsection an extra slide containing the title can be inserted. This is controlled by passing `secslide` and `subsecslide`. The absence of `secslide` indicates that you don't want an extra slide for every section. This is analog for `subsecslide`.

## Compilation
Using this theme requires you to run your compiler multiple times on your main LaTeX file. This is required for those litte dots in the footer to work.
If you're using latexmk you don't have to do this manually as latexmk can figure this stuff out by itself.


## Example slides
![example.pdf](https://github.com/LukasPietzschmann/awesome-beamer/blob/master/example.pdf)
