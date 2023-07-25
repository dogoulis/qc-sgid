# qc-sgid
This is the official code implementation of the paper **Improving Synthetically Generated Image Detection in Cross-Concept Settings** accepted in the MAD Workshop of ICMR 2023.

The first step is to use the GIQA implementation from the paper [GIQA: Generated Image Quality Assessment](https://link.springer.com/chapter/10.1007/978-3-030-58621-8_22), in order to rank the images in the dataset based on their quality. The model that we use and the implementation details are precisely described in the section **Implementation Details** of our paper.

After the selection of the k-best generated images based on the quality, the models can be trained and evaluated based on the scripts provided in the **src** folder.
