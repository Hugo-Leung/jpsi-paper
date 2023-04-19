# $J/\psi$ paper
To compile, simply use 
```
latexmk 
```
the output files would be written to the `build` directory

The code is also hosted on [Github](https://github.com/Hugo-Leung/jpsi-paper). The git repo can also be found at `/seaquest/users/chleung/paper/jpsi-paper` on the SeaQuet servers
## file struture
Figures should be placed under `figures` directory

## comments
Comments in the tex files are handled by [todonotes](https://tug.ctan.org/macros/latex/contrib/todonotes/todonotes.pdf). To add a comment, please use
```
\todo[author={name}]{comment}
```
The background color can also specified by useing the `color=` option.

To denote a missing figure, one can use the following 
```
\missingfigure{description of the figure}
```
All the comments would be hidden if the option `final` is enabled in the document class
