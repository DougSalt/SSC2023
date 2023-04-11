This poster describes briefly four extensions to Netlogo. All four extensions
are available in Netlogo's extensions tab, all four run on Windows, OSX and
Linux, and all four have publicly accessible repositories in which there is
extensive documentation and worked examples. The extensions are cbr, an
extension that implements a framework for case-based reasoning; lkt, a table
extension that uses categorical variables to predicate outcomes; math which
provides direct programmatic access to the Java math library in order to
obviate cumulative, transitive mathematical imprecision. 

The case based reasoner, cbr provides a framework to create a case base,
consisting of a series of cases, each containing of a series of conditions, a
decision and an outcome. This case base is then consulted for  the best matches
a given set of conditions and the decision. This is done by a "distance"
function, a default version of which is provided, based on command Netlogo data
types. This function may be overwritten if required. This extension provides
case ageing, collision avoidance, ranking and deletion of individual cases.

The look up extension, lkt which allows the definition of categorical variables
using a "tree" definition file and a data file using these variables to
predicate outcomes in a tabular form. 

The math extension has muliple zero arity functions, single argument and double arity functions 
for precision maths. These include direct callss to Java's math
library for repeated arithmetic operations and trigonometric functions. The
trigonometric correctly orientate zero (not North) and use radians.

Lastly there is the mgr extension which allows access to statistics on thread
and memory usage in the underlying java virtual machine, and allows the
real-time inspection of heap, allocated and total memory, access to statistics
about the number of threads and their state and finally how much CPU time is
being used.



