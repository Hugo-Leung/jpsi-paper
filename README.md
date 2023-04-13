# J/psi paper
To compile, simple type 
```
latexmk 
```
the output files would be in the `build` directory

## file struture
The figures should be placed under `figures` directory

## comments
Comments in the tex files are handled by [todonotes]{https://tug.ctan.org/macros/latex/contrib/todonotes/todonotes.pdf}. To add a comment, please use
```
\todo[author={name}]{comment}
```
To denote a missing figure, one can use the following 
```
\missingfigure{description of the figure}
```
All the comments would be hidden if the option `final` is enabled in the document class
