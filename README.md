# Victorian400 Dataset
Victorian400 Dataset for Colorizing Victorian Illustrations | by Hoyeol Kim

---
### Download: [Victorian400 (Kaggle)](https://www.kaggle.com/elibooklover/victorian400/download) (521mb)

##### You can download the Victorain400 dataset directly by using the following URL: 
```
https://github.com/elibooklover/Victorian400/raw/master/Victorian400.tar.gz
```
Here is example code to use on the Victorian400 dataset: 
```
_URL = URL = 'https://github.com/elibooklover/Victorian400/raw/master/Victorian400.tar.gz'
path_to_zip = tf.keras.utils.get_file('Victorian400.tar.gz', origin=_URL, extract=True)
path1 = os.path.join(os.path.dirname(path_to_zip), 'Victorian400/')
```
---

### Dataset
This dataset was originally created to colorize Charles Dickens’ illustrations. Due to a lack of data, however, the scope of this dataset has been expanded to all nineteenth century illustrations. Colorful images from the nineteenth century were selected to be used in the dataset, which were converted to black and white images for training data.

![Victorian400](https://github.com/elibooklover/Victorian400/blob/master/Examples/Victorian400.png)

This dataset contains three different folders: original, resized, and gray. Images in the ‘original’ folder were curated for significant features, such as faces and bodies. In the 'resized' folder, the original images were resized to fit the 256*256 dimensions needed for the process of deep learning. Based on the resized images, I created the 'gray' folder, which contains black and white images converted from the colorful resized images. 

---
The Victorian400 dataset was tested with [pix2pix](https://phillipi.github.io/pix2pix/) developed by Isola et al.

### Test Results 
![Test Results](https://github.com/elibooklover/Victorian400/blob/master/Examples/Example.png)

---

### Citation
Please use the following reference to cite the dataset:
```
@misc{Victorian400,
    author       = {Hoyeol Kim},
    title        = {{Victorian400 Dataset for Colorizing Victorian Illustrations}},
    month        = Dec,
    year         = 2019,
    publisher    = {GitHub},
    url          = {https://github.com/elibooklover/Victorian400}
    }
```

or 

```
Kim, Hoyeol, Victorian400 Dataset for Colorizing Victorian Illustrations, December 2019. GitHub repository: github.com/elibooklover/Victorian400.
```

---

### Funding and Grant
In recognition of my work on the Victorian400 dataset, I received a $563 Project Development Grant from the Center of Digital Humanities Research, as well as Graduate Merit funding for $400 by the Department of English, Texas A&M University.

---
[License](https://creativecommons.org/licenses/by-nc-sa/4.0/)

![License](https://github.com/elibooklover/Victorian400/blob/master/license.png)

