# Awesome-Beamer
The kinda awesome beamer theme!

## Using the theme
First of all you will need the [smile](https://github.com/LukasPietzschmann/smile) package. If that's available, just copy and paste `beamerthemeawesome.sty` into your project, add `\usetheme{awesome}` into your main file and you're good to go :)

## Options
This theme provides some settings you can tweak:
- Language: Possible values are `english` or `german`. This changes the value passed to babel and csquotes. If none of both is selected, `german` is used.
- Extra slides: For each section and subsection an extra slide containing the title can be inserted. This is controlled by passing `secslide` or/and `subsecslide`. The absence of `secslide` indicates that you don't want an extra slide for every section. Analog for `subsecslide`.
- Automatic toc: A table of contents is automatically inserted with the `\maketitle` command (After the title slide). If you want to disable this behavior, you have to set the `notoc` option.
- Section numbers in frame title: Each frage contains the current section (and subsection) number in its title. To disable this, you have to pass the `nonumbersinframetitle` option. If you disable section numbers in the title, and you use use the `wide` environment inside a frame, it can look weird when the title is shifted to the right, but the content is not. To cope with this, you can pass the `wide` option to the frame. This will also shift the title to the left.
- Others: Every option that is not recognized by awesome-beamer will be passed to [smile](https://github.com/LukasPietzschmann/smile).

If you wanna set one (or more) of those values, you have to pass it to `\usetheme`. The usage of different options can be seen in the examples below (just click on the 'Repo' link).

## Compilation
Using this theme requires you to run your compiler multiple times on your main LaTeX file. This is required for those litte dots in the footer to work.
If you're using latexmk you don't have to do this manually as latexmk can figure this stuff out by itself.


## Example slides
I already prepared many presentations using this style. Here are some examples:
- [Hydrogen is an energy carrier](https://raw.githubusercontent.com/LukasPietzschmann/hydrogen-energy/build/talk.pdf) ([Repo](https://github.com/LukasPietzschmann/hydrogen-energy))
- [SIMD intrinsics](https://github.com/LukasPietzschmann/SIMD-Intrinsics/files/12775327/talk.pdf) ([Repo](https://github.com/LukasPietzschmann/SIMD-Intrinsics))
- [Building a dataflow graph for java](https://github.com/LukasPietzschmann/java-dataflow-graph/files/13249805/main.pdf) ([Repo](https://github.com/LukasPietzschmann/java-dataflow-graph))
- [Distributed configuration stores](https://github.com/LukasPietzschmann/Configuration-Stores/files/12793983/main.pdf) ([Repo](https://github.com/LukasPietzschmann/Configuration-Stores))
