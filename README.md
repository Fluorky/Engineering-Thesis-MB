Title of Thesis: "Validation of meteorological measurement results using recursive neural networks"

My Thesis discusses a system based on a recursive neural network that classifies the quality of measurement data. 
For the purposes of the work, was used a set of data related to the measurements of meteorological parameters in the Biebrza National Park.
These mentioned measurements are subject to significant uncertainty and are categorized as high or low quality results. 
A recursive neural network was built and discussed, allowing for the classification to which of the above-mentioned categories a specific measurement belongs.
Recursive neural networks of the GRU type were used. It was researched how the efficiency of classification changes depending on the size of the time window, network architecture or its hierarchical parameters.
The impact of the graphics card on the learning speed and the impact of the hardware configuration on the results were also reasearched. 
The practical part of the work was prepared in Python using the tensorflow library.


Neural network model was tested on this configurations:

*MSI KATANA GF66 with Intel i7 11800H, 64GB RAM, Nvidia RTX 3060 6GB Windows 11 22H2

*PC with Xeon X5-2667v2, 32GB RAM, RTX 3060 12GB Windows 10 22H2

*Dell Wyse 5070 with Intel Pentium J5005 and 16GB RAM Windows 10 22H2

