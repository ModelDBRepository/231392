This is the readme for the models associated with the paper:

 Urdapilleta E, Si B, Treves A (2017) Self-organization of modular
 activity of grid cells. Hippocampus

These files were contributed by E. Urdapilleta.

To run the model, standard gcc package is required. Parameters are
defined in grid.h. Compile as:
gcc grid.cpp -o grid -lm
and execute
./grid
In case you use a compiler under Windows, you should replace
"47" by "92" in grid.cpp for a proper folder management.

The folder "Simulation" contains part of the data of the final step
(the complete simulation with the parameters defined here lasts for
days), which are the basis of the analysis done in the referenced
paper.
