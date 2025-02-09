# Title of Thesis: "Validation of Meteorological Measurement Results Using Recursive Neural Networks"

This thesis presents a system based on a recursive neural network designed to classify the quality of meteorological measurement data. The dataset used in this study consists of measurements of meteorological parameters collected in the **Biebrza National Park**. These measurements are characterized by significant uncertainty, and they are categorized as either high-quality or low-quality results.

A recursive neural network was developed to classify each measurement into one of these categories. **GRU-based recursive neural networks** were employed in this work. The research focused on examining how classification performance changes depending on factors such as the size of the time window, network architecture, and the hierarchical parameters of the network.

Additionally, the impact of the **graphics processing unit (GPU)** on training speed and the influence of hardware configuration on model performance were explored. The practical part of the project was implemented in **Python** using the **TensorFlow** framework.

The full thesis (in Polish) with detailed research and conclusions can be found in the `EngineeringThesis.pdf` file.

### Neural Network Model Tested on the Following Configurations:

- **MSI KATANA GF66**: Intel i7 11800H, 64GB RAM, Nvidia RTX 3060 6GB, Windows 11 22H2
- **PC**: Xeon X5-2667v2, 32GB RAM, Nvidia RTX 3060 12GB, Windows 10 22H2
- **Dell Wyse 5070**: Intel Pentium J5005, 16GB RAM, Windows 10 22H2
