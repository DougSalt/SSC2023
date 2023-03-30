Authors: Doug Salt, Gary Polhill, Ben Mccormick

Title: Three Netlogo extensions: publicly available Netlogo extensions that provide a case-base reasoning framework, tables look up with categorical variables and data encryption using GnuPG, Gnu's implementation of Pretty Good Privacy.

Abstract: 

This poster describes briefly three extensions to Netlogo. All three extensions
are available in Netlogo's extensions tab, all three run on Windows, OSX and
Linux, and all three have publicly accessible repositories in which there is
extensive documentation and worked examples. The three extensions are gpg: an
extension that using Gnu's Pretty Good Privacy suite to decrypt asymmetrically
encrypted data; cbr, an extension that implements a framework for case-based
reasoning, and lkt and table extension that uses categorical variables to
predicate outcomes. 

The encryption extension, gpg can be make data accessible to specific
individuals or groups using specific and unique keys. This may mean that
sensitive data, commercial, sensitive or otherwise can be reliably and legally
be stored in the cloud for use by NetLogo models. It requires the presence of
Gnu's Pretty Good Privacy suite in the command path.  In an era of cloud
computing the destruction of such keys may be the only way to ensure the true
deletion of replicated, geographically distributed data.

The case based reasoner, cbr provides a framework to create a case base,
consisting of a series of cases, each containing of a series of conditions, a
decision and an outcome. This case base is then consulted for  the best matches
a given set of conditions and the decision. This is done by a "distance"
function, a default version of which is provided, based on command Netlogo data
types. This function may be overwritten if required. This extension provides
case ageing, collision avoidance, ranking and deletion of individual cases.

Lastly, the look up extension, lkt which allows the definition of categorical
variables using a "tree" definition file and a data file using these variables
to predicate outcomes in a tabular form. 



