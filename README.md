# Template Book Project with LaTeX

This repository contains a LaTeX template for a book discussing the seasonal changes and their impacts, designed for ease of use and modification.

## Project Structure

The project is structured as follows:

```
.
├── Images
│   ├── author-1.jpg
│   ├── author-2.jpg
│   ├── author-3.jpg
│   └── seasons_image.jpg
├── main.tex
├── README.md
├── references.bib
└── TeX_files
    ├── authorbio.tex
    ├── chapter01.tex
    ├── chapter02.tex
    ├── chapter03.tex
    ├── codeblock.tex
    ├── copyright.tex
    ├── foreword.tex
    └── tableofcontents.tex
```

## Getting Started

### Cloning the Repository

To clone this repository and all its sub-modules, use the following command:

```bash
git clone https://github.com/codescient/template-book-latex.git
cd template-book-latex
```

### Pulling Images with Git LFS

This repository uses Git Large File Storage (LFS) to handle large images. Ensure you have Git LFS installed on your system. Check their [official site](https://git-lfs.com/) for how to install. 

Once installed, set up Git LFS for your account by running:

```bash
git lfs install
```

After setting up Git LFS, pull the large files with:

```bash
git lfs pull
```

### Compiling the LaTeX Document

To compile the LaTeX documents, you can use any LaTeX editor of your choice. For instance, using [TexStudio](https://www.texstudio.org/):

1. Open `main.tex` with TexStudio.
2. Configure TexStudio to use XeLaTeX or PDFLaTeX as needed.
3. Press the "Compile" button to build the document.

Alternatively, you can compile the document from the command line:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
bibtex main
pdflatex main.tex
```

Make sure you have all the necessary LaTeX packages installed on your system. Enjoy your editing!
