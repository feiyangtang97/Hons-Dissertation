For each chapter, create a folder with a .tex file of the same name.
This folder should also contain all the other files (e.g. figures) for this chapter.
The main file, dissertation.tex, should include the .tex file of each chapter.

Example:
Chapter "Introduction" is written in the file Introduction.tex in folder Introduction.
This folder should also contain all other files for this chapter.
Introduction.tex is included in dissertation.tex:
\include{Introduction/Introduction}
