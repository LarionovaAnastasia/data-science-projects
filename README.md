# Russian Hadwritten Letters Classification 

**Project Summary** :   
The gola of this project is to create an engine capable to automatically classify an image of a handwritten letter into one of 33 categories/letters of Russian alphabet using the deep learning technologies.

**Repo structure**

This project's repo includes the following files:

- The project's final jupyter notebook (notebook.ipynb);
- The final pretrained models (best_res_model.h5, best_gray_model.h5, best_full_model.h5)
- 'Data' directory with the used dataset

**Data source** :    

The dataset from 'data' directory is publicy available on Kaggle here : 
https://www.kaggle.com/tatianasnwrt/russian-handwritten-letters

The dataset includes a folder with the total of 14190 PNG format images. It also has a csv file describing each image. This information file contains 4 columns:

- letter (in cyrillic);
- file (the name of a file with this image);
- label (a number corresponding to that letter, see below);

        а=>1, б=>2, в=>3, г=>4, д=>5, е=>6, ё=>7, ж=>8, з=>9, и=>10, й=>11, к=>12, л=>13, м=>14, н=>15, о=>16, п=>17, р=>18, с=>19, т=>20, у=>21, ф=>22, х=>23, ц=>24, ч=>25, ш=>26, щ=>27, ъ=>28, ы=>29, ь=>30, э=>31, ю=>32, я=>33

- background (a label corresponding to the background of an image, see below).

        striped=>0
        gridded=>1
        no background=>2
        graph paper=>3
