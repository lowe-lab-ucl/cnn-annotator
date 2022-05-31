# Convolutional neural networks 🖥️ for classifying chromatin morphology 🧬 in live cell imaging 🔬
<br/>

<img width="60%" align="right" alt="Protocol" src="assets/napari_annotator.png" />

Welcome to our [CNN Annotator repository](https://github.com/lowe-lab-ucl/cnn-annotator "CNN Annotator repository || Lowe Lab UCL") where you can find our recent *protocol* on how to use a simple convolutional neural network (CNN) to classify time-lapse microscopy single-cell images patches according to live-cell chromatin morphology.

**Wondering what such pipeline could be used for?** Check out our recent publications where we made use of CNNs for classifying cells in live-cell imaging:
- [Ulicna *et al.*, Frontiers in Computer Science, 2021](https://www.frontiersin.org/articles/10.3389/fcomp.2021.734559/full "Automated deep lineage tree analysis using a Bayesian single cell tracking approach") - Automated deep lineage tree analysis using a Bayesian single cell tracking approach
- [Bove *et al.*, Molecular Biology of the Cell, 2017](https://www.molbiolcell.org/doi/10.1091/mbc.E17-06-0368?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed "Local cellular neighbourhood controls proliferation in cell competition") - Local cellular neighbourhood controls proliferation in cell competition


### How to navigate this repository

We provide a detailed walk-through for annotating live-cell microscopy images and training CNN model to infer classification labels on previously unseen images. Here is an overview of the entire process:

![Protocol Pipeline](/assets/protocol_pipeline.png)

For more detailed instructions on how to annotate your microscopy data, train the CNN classifier and infer labels on previously unseen images, please refer to [this step-wise manual](/notebooks/README.md "Protocol Methods").

Please use these links to proceed with the training and inference of your CNN models in the **Google Colab** environment:


| Notebook | Description | Link |
| --- | --- | --- |
| *Training* | Train the CNN using annotated image patches | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lowe-lab-ucl/cnn-annotator/blob/main/notebooks/C_CNN_Training_and_Validation.ipynb) |
| *Inference* | Use the trained CNN to perform predictions and clustering | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lowe-lab-ucl/cnn-annotator/blob/main/notebooks/D_CNN_Inference_and_Embedding.ipynb) |


### Installation Instructions

Clone the repo locally and create a clean `conda` environment with all needed packages to run notebooks A & B on your local machine using the following commands:

```sh
git clone https://github.com/lowe-lab-ucl/cnn-annotator.git
cd cnn-annotator
conda env create -f ./environment.yml
conda activate cnn-annotator
```

---
### Citation

More detailed protocol with step-by-step instructions on how to apply this type of image analysis tool to you own data can be found in the following publication. If you find this protocol useful for your research, please do cite us as follows:

**Convolutional Neural Networks for Classifying Chromatin Morphology in Live-Cell Imaging**  
Ulicna K, Ho LTL, Soelistyo CJ, Day NJ, Lowe AR    
*Chromosome Architecture. Methods in Molecular Biology* (2022)  
[![doi:10.1007/978-1-0716-2221-6_3](https://img.shields.io/static/v1?label=doi&message=10.1007/978-1-0716-2221-6_3&color=blue)](https://doi.org/10.1007/978-1-0716-2221-6_3)


```
@Inbook{Ulicna2022,
    author="Ulicna, Kristina
    and Ho, Laure T. L.
    and Soelistyo, Christopher J.
    and Day, Nathan J.
    and Lowe, Alan R.",
    editor="Leake, Mark C.",
    title="Convolutional Neural Networks for Classifying Chromatin Morphology in Live-Cell Imaging",
    bookTitle="Chromosome Architecture: Methods and Protocols ",
    year="2022",
    publisher="Springer US",
    address="New York, NY",
    pages="17--30",
    abstract="Chromatin is highly structured, and changes in its organization are essential in many cellular processes, including cell division. Recently, advances in machine learning have enabled researchers to automatically classify chromatin morphology in fluorescence microscopy images. In this protocol, we develop user-friendly tools to perform this task. We provide an open-source annotation tool, and a cloud-based computational framework to train and utilize a convolutional neural network to automatically classify chromatin morphology. Using cloud compute enables users without significant resources or computational experience to use a machine learning approach to analyze their own microscopy data.",
    isbn="978-1-0716-2221-6",
    doi="10.1007/978-1-0716-2221-6_3",
    url="https://doi.org/10.1007/978-1-0716-2221-6_3"
}
```

*Happy coding!* <br/>
... **Your [CellX](http://lowe.cs.ucl.ac.uk/cellx.html "Lowe Lab UCL") team**
