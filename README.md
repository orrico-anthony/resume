# resume
Repo for personal resume

## Prerequisites (from jwest https://github.com/jwestfromtheeast/resume/blob/master/README.md)

Install BasicTeX via Homebrew:

```bash
brew install --cask basictex
```

Restart your terminal (or run `eval "$(/usr/libexec/path_helper)"`), then install required packages:

```bash
sudo tlmgr install titlesec enumitem fancyhdr helvetic tex-gyre
```

## Compile

```bash
pdflatex resume.tex
```

Output: `resume.pdf`
