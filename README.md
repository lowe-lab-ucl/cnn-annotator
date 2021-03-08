# CNN Annotator

### Convolutional neural networks for classifying chromatin morphology in live cell imaging



| Notebook | Description | Link |
| --- | --- | --- |
| *Training* | Train the CNN using annotated image patches | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lowe-lab-ucl/cnn-annotator/blob/main/notebooks/C_CNN_Training_and_Validation.ipynb) |
| *Inference* | Use the trained CNN to perform predictions and clustering | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lowe-lab-ucl/cnn-annotator/blob/main/notebooks/D_CNN_Inference_and_Embedding.ipynb) |

### Installation

Clone the repo locally and create a clean `conda` environment with all needed packages to run notebooks A & B on your local machine using the following commands:

```sh
git clone https://github.com/lowe-lab-ucl/cnn-annotator.git
cd cnn-annotator
conda env create -f ./environment.yml
conda activate cnn-annotator
```

Happy coding!

... Your CellX team


#### TODOs:

- [x] Order notebooks.
- [x] Image patch extractor.
- [x] Add notebook with data stats pre-training
- [x] Test napari annotator.  
- [x] Add napari screenshot to ntbk A
- [ ] Write a proper readme!
- [x] Provide Colab link for training model.  
- [ ] Add label statistic to napari annotator widget.
- [x] Export image patches from napari annotator as tif files/zip file.    
- [x] Allow loading of zip training data in Colab notebook.   
- [x] Add confusion matrix final output in colab notebook.
- [x] Model evaluation + predictions on unseen data
---

Kristina's TODOs:

- [ ] Relative contrib of zipfiles to patch counts
- [ ] Class patch count figure to Colab
- [ ] Record video how to annotate in napari
- [x] Colab notebook link to Lowe-Lab-UCL
---


