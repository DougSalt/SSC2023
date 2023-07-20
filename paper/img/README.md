# PURPOSE

The image pre-processing and instructions for the paper sourced above this directory.

# Notes

To produce schema.png

Took the overall schema from the SSREPI interface document. Take the picture of
the global schema,  open it in Paint, then open the workflow shema in another
instance of Paint. Draw a box around it and then add it and an arrow to the
global schema.

To produce workflow.png

dot -Tpng -o worflow.minor.png workflow.minor.dot
dot -Tpng -o worflow.png workflow.dot

and then impose the workflow.minor.png over the workflow.png, suitably resized and round boxed to show the detail.

To produce provenance.pdf 

dot -Tpdf -o provenance.pdf provenance.dot

# MANIFEST

+ `README.md` - 
+ `broken-application.dot` - 
+ `broken-application.pdf` - 
+ `fine-grain-vs-coarse-grain.jpeg` - 
+ `high-lit-proveance-trace-large.pdf` - 
+ `high-lit-provenance-trace-large.dot` - 
+ `high-lit-provenance-trace-large.pdf` - 
+ `high-lit-provenance-trace.pdf` - 
+ `provenance.dot` - 
+ `provenance.pdf` - 
+ `schema.jpeg.2023-07-20` - 
+ `schema.png` - 
+ `subsection-of-provenance.png` - 
+ `trace.dot` - 
+ `trace.pdf` - 
+ `unmodified` - 
+ `workflow.dot` - 
+ `workflow.minor.dot` - 
+ `workflow.minor.png` - 
+ `workflow.pdf` - 
+ `workflow.png` - 
