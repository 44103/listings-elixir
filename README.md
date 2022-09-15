# listings-elixir
$\LaTeX$ listings package extension for [Elixir](https://elixir-lang.org/docs.html).

## Usage
1. place the `listings-elixir.sty` where $\LaTeX$ can find it
1. import `listings` and `listings-elixir` in your $\LaTeX$ document with `\usepackage{listings,listings-elixir}`
1. select the language `Elixir` in the `lstlistings` environment, e.g.
   ```tex
   \begin{lstlisting}[language=elixir]
   # your source code
   \end{lstlisting}
   ```
1. optional: select one of the styles `light` or `dark`, e.g.
   ```tex
   \begin{lstlisting}[language=elixir,style=light]
   # your source code
   \end{lstlisting}
   ```

## Documentation
Currently there is only the style-file itself and the example document `example.tex` for documentation.

## Visualization
See [example.pdf](example.pdf)
