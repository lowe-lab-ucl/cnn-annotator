# Convolutional neural networks 🖥️ for classifying chromatin morphology 🧬 in live cell imaging 🔬
<br/>

<img width="50%" align="right" alt="LIDo_Int" src="assets/napari_annotator.png" />

Welcome to our [CNN Annotator repository](https://github.com/lowe-lab-ucl/cnn-annotator "CNN Annotator repository || Lowe Lab UCL") where you can find our recent *Methods to Molecular Biology (MiMB) protocol* on how to use a convolutional neural network (CNN) to classify time-lapse microscopy single-cell images patches according to live-cell chromatin morphology.

**Wondering what such pipeline could be used for?** Check out our recent publications where we made use of CNNs for classifying cells in live-cell imaging:
- [Ulicna *et al.*, bioRxiv, 2020](https://www.biorxiv.org/content/10.1101/2020.09.10.276980v1.full "Automated deep lineage tree analysis using a Bayesian single cell tracking approach") - Automated deep lineage tree analysis using a Bayesian single cell tracking approach
- [Bove *et al.*, MBoC, 2017](https://www.molbiolcell.org/doi/10.1091/mbc.E17-06-0368?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed "Local cellular neighbourhood controls proliferation in cell competition") - Local cellular neighbourhood controls proliferation in cell competition


### How to navigate this repository

We provide a detailed walk-through for annotating live-cell microscopy images and training CNN model to infer classification labels on previously unseen images. Here is an overview of the entire process:

![Protocol Pipeline](/assets/protocol_pipeline.png)

For more detailed instructions on how to use annotate your microscopy data, train the CNN classifier and infer labels on previously unseen images, please refer to [this step-wise manual](/notebooks/README.md "Protocol Methods").

Please use these links to proceed with the training and inference of your CNN models in the Google Colab environment:

+ Training: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lowe-lab-ucl/cnn-annotator/blob/main/notebooks/C_CNN_Training_and_Validation.ipynb)

+ Inference: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lowe-lab-ucl/cnn-annotator/blob/main/notebooks/D_CNN_Prediction_and_Testing.ipynb)

Train the CNN on Colab: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/KristinaUlicna/cnn-annotator/blob/napari/notebooks/C_CNN_Training_and_Validation.ipynb)

<!---Test the CNN on Colab: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chris-soelistyo/cnn-annotator/blob/Chris_Branch/notebooks/D_CNN_Prediction_and_Testing.ipynb) -->

### Installation Instructions

`$ git clone https://github.com/lowe-lab-ucl/cnn-annotator.git`

...etc...

---

*Happy coding!* <br/>
... **Your [CellX](http://lowe.cs.ucl.ac.uk/cellx.html "Lowe Lab UCL") team**
