This is the companion repository to:
"The Magnus expansion in relativistic quantum field theory" 
Authors: Andreas Brandhuber, Graham R. Brown, Paolo Pichini,
Gabriele Travaglini  and Pablo Vives Matasan. 

-The file "Magnus Operator" contains the N-operator itself.
-The file "Magnus Amplitudes" contains matrix elements of the N-
operator.
-The file "Examples.nb" is a Mathematica notebook showing how to load the previous files.

Both the N-operator and the matrix elements are written as lists of graphs and their coefficients. Directed edges correspond to retarded/advanced propagators 
$\Delta^(R/A)$, undirected edges correspond to cuts $\Delta^(1)$. 

The general expansion of the N-operator is given in (6.18) of the paper. 
The coefficients we include in these files are the ratio  $\omega(\tau)/\sigma(\tau)*(Degree factors)$, where $(Degree factors)$ are the n! type terms that appear with external vertices of a graph, see for example (6.19). See "Examples.nb" to see how these $(Degree factors)$ can be easily removed. 

The general expansion of the N-matrix elements is given in (6.20) of the paper. 
The coefficients we include in these files are the ratio   $\omega(\tau)/\sigma(\tau)$
where now g is a graph with external legs which have been labelled "ei" w\here i runs from 1 to n.*) 