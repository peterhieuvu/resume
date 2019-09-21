# Resume
My personal live resume, with personal information removed.

## Usage
The project is written in LaTeX and so it requires a LaTeX distribution to build the document. A number of packages are also required and so requires more than a minimal install. A full installation of TeX Live should work. As an example if you are on a debian derivate (like Ubuntu), this command will install what you need:

    sudo apt-get install texlive-full

With that installed, you can build the TeX files with:

    pdflatex resume.tex

Otherwise, it may be easier to use software such as TeXWorks to edit and compile your LaTeX documents.

## The Project

The project consists of a main file (`resume.txt`), a package file (`resume.sty`), and optional private files (none of which are present in the repository since they are private :)).