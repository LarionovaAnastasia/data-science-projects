# Automatic Classification of handwritten letters in Russian

**Project Summary** :   

This is a personal data science project launched to try out : 
- Keras Sequential model for classification tasks
- OpenCV library for image preprocessing and removal of background noise

The goal of this project is to create an engine capable of automatically classifying an image of a handwritten letter into one of the 33 categories/letters of the Russian alphabet using deep learning technologies.

**Repo structure**

This repo includes the following files:

- The Jupyter notebook used for this project (notebook.ipynb);
- 'Models' directory containing trained models

**Data source** :    

The dataset is publicly available on Kaggle : 
https://www.kaggle.com/tatianasnwrt/russian-handwritten-letters

The dataset includes a folder with a total of 14190 PNG-formatted images. It also has a CSV file describing each image. This information file contains 4 columns:

- letter (in cyrillic);
- file (the name of a file with this image);
- label (a number corresponding to that letter, see below);

        а=>1, б=>2, в=>3, г=>4, д=>5, е=>6, ё=>7, ж=>8, з=>9, и=>10, й=>11, к=>12, л=>13, м=>14, н=>15, о=>16, п=>17, р=>18, с=>19, т=>20, у=>21, ф=>22, х=>23, ц=>24, ч=>25, ш=>26, щ=>27, ъ=>28, ы=>29, ь=>30, э=>31, ю=>32, я=>33

- background (a label corresponding to the background of an image, see below).

        striped=>0
        gridded=>1
        no background=>2
        graph paper=>3
