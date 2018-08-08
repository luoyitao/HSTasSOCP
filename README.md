# HSTasSOCP
Homogeneous shear turbulence as a second-order cone program

The source codes and data files in this repository provide supporting materials for the paper titled
    *Homogeneous shear turbulence as a second-order cone program. II*
submitted to
     \"Proceedings of the Royal Society of London A: Mathematical, Physical and Engineering Sciences\". 

We have written the codes to solve numerically the second-order model proposed in Part I,
    *Homogeneous shear turbulence as a second-order cone program. I*
submitted to
     \"Proceedings of the Royal Society of London A: Mathematical, Physical and Engineering Sciences\".
Since the second-order model, in its discretized form, is a second-order cone program (SOCP), 
we resort to the widely used and tested open-source package, SCS, to find its optimal solutions 
in the steady asymptotic state for various discretized versions 
 (of different combinations of candidate objective functions and constraints under two mesh sizes). 
One set of the codes, stored in Folder \`01MathematicaCubaCodeData\',
produces coefficients to be used either to construct standard forms of the discretized versions
   or to compute certain global quantities.
Another set of the codes,  stored in Folders \`02PythonModulesImportToSFCode\',
 \`03StandardFormGeneratingCodeDataI\'
 and \`04StandardFormGeneratingCodeDataII\',
constructs the standard forms.
Stored in Folder \`05ParallelComputingCodeData\',
the third set solves the standard forms in parallel computing to obtain optimal solutions.
With the help of the optimal solutions, the fourth set of the codes,
stored in Folder \`06GlobalQuantitiesCodeData\',
computes certain global
quantities that can be compared with experimental data.
 
The codes and data files are grouped and stored in the six folders aforementioned, 
according to their functions.
The text file, \`README-00.txt\', outlines the contents contained in the folders. 
Inside each folder, there is an associated text file, such as \`README-01MathematicaCubaCodeData.txt\' and so on,
presenting more details on the codes and data files stored in that folder.
For convenience, all these associated text files are stored in  Folder \`00CommentFiles\'.
