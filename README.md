# Extracts the answers(options) from a tex file

### Install using pip
```
pip install extract-answer-key
```

### Usage
```
Usage: extract-answer-key [OPTIONS]

Options:
  -i, --inputfile PATH   Input file path  [default: ./main.tex]
  -c, --columns INTEGER  Number of columns in answer key  [default: 5]
  -h, --help             Show this message and exit.
```

### Creates a seperate file answer.tex

```
\begin{center}
\texttt{Answer Key}
  \begin{multicols}{5}
    \begin{enumerate}
      \item (b)
      \item (b)
      \item (a), (b)
    \end{enumerate}
    \begin{enumerate}\addtocounter{enumi}{3}
      \item 2
      \item 2
      \item 2
    \end{enumerate}
  \end{multicols}
\end{center}
```


