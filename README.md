# Victorian400 Dataset
Colorizing Victorian Illustrations with the Victorian400 Dataset | by Hoyeol Kim

---
### Download: [Victorian400](https://drive.google.com/file/d/1yKp2flysO9paKIUlEG4TQ7ne4obC1EdF/view?usp=sharing) (521mb)
---

### Dataset
This dataset was originally created to colorize Charles Dickens’ illustrations. Due to a lack of data, however, the scope of this dataset has been expanded to all nineteenth century illustrations. Colorful images from the nineteenth century were selected to be used in the dataset, which were converted to black and white images for training data.

![Victorian400](https://github.com/elibooklover/Victorian400/blob/master/Examples/Victorian400.png)

This dataset contains three different folders: original, resized, and gray. Images in the ‘original’ folder were curated for significant features, such as faces and bodies. In the 'resized' folder, the original images were resized to fit the 256*256 dimensions needed for the process of deep learning. Based on the resized images, I created the 'gray' folder, which contains black and white images converted from the colorful resized images. 

---
The Victorian400 dataset was tested with [pix2pix](https://phillipi.github.io/pix2pix/) developed by Isola et al.

### ![Validation Results](https://github.com/elibooklover/Victorian400/blob/master/Examples/Example.png)

---

### Citation
Please use the following reference to cite the dataset:
```
@misc{Victorian400,
    author       = {Hoyeol Kim},
    title        = {{Colorizing Victorian Illustrations with the Victorian400 Dataset}},
    month        = Dec,
    year         = 2019,
    publisher    = {GitHub},
    url          = {https://github.com/elibooklover/Victorian400}
    }
```

or 

```
Kim, Hoyeol, Colorizing Victorian Illustrations with the Victorian400 Dataset, December 2019. GitHub repository: github.com/elibooklover/Victorian400.
```
