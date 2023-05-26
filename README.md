# Awesome-Beamer
The kinda awesome beamer theme!

## Using the theme
First of all you will need the [smile](https://github.com/LukasPietzschmann/smile) package. If that's available, just copy and paste `beamerthemeawesome.sty` into your project, add `\usetheme{awesome}` into your main file and you're good to go :)

## Options
This theme provides some settings you can tweak:
- Language: Possible values are `english` or `german`. This changes the value passed to babel and csquotes. If none of both is selected, `german` is used.
- Extra slides: For each section and subsection an extra slide containing the title can be inserted. This is controlled by passing `secslide` or/and `subsecslide`. The absence of `secslide` indicates that you don't want an extra slide for every section. Analog for `subsecslide`.
- Automatic toc: A table of contents is automatically inserted with the `\maketitle` command (After the title slide). If you want to disable this behavior, you have to set the `notoc` option.

If you wanna set one (or more) of those values, you have to pass it to `\usetheme`. Look at ![example.tex](https://github.com/LukasPietzschmann/awesome-beamer/blob/master/example.tex) for, well, an example.

## Compilation
Using this theme requires you to run your compiler multiple times on your main LaTeX file. This is required for those litte dots in the footer to work.
If you're using latexmk you don't have to do this manually as latexmk can figure this stuff out by itself.


## Example slides
![example.pdf](https://github.com/LukasPietzschmann/awesome-beamer/blob/master/example.pdf)

## Related stuff
If you're looking for other LaTeX classes in the same style, you may want to take a look at this repo: [tex-classes](https://github.com/LukasPietzschmann/tex-classes).
