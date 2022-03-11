# Introduction

This code presents the database construction of the RSVQAxBEN dataset, and the model both presented in [1]. This database leverages BigEarthNet, a large-scale dataset on landcover classification presented in [2]. Please cite [1] if you use this code.

# How to use

The code is mainly organized in two jupyter notebooks:
* BigEarthNetVQA.ipynb presents the database construction procedure and allow you to modify the database if needed;
* Model.ipynb presents the model training procedure (including dataloader).

# References

[1] Lobry, Sylvain, Begüm Demir, and Devis Tuia. "RSVQA Meets Bigearthnet: A New, Large-Scale, Visual Question Answering Dataset for Remote Sensing." 2021 IEEE International Geoscience and Remote Sensing Symposium IGARSS. IEEE, 2021.
[2] Sumbul, Gencer, et al. "Bigearthnet: A large-scale benchmark archive for remote sensing image understanding." IGARSS 2019-2019 IEEE International Geoscience and Remote Sensing Symposium. IEEE, 2019.