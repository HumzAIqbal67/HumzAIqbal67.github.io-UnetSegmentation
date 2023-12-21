# U-NetBioMedSegmentation

The initial stage in quantitatively analyzing microscopy images for biological and biomedical purposes frequently involves the segmentation of cell nuclei. 

Here we solve this problem using Neural Networks in Keras with a tensorflow backend. Specifically, we use a U-Net as invented and explained here; [https://arxiv.org/abs/1505.04597](https://arxiv.org/abs/1505.04597)

Please visit [THIS LINK](https://humzaiqbal67.github.io/HumzAIqbal67.github.io-UnetSegmentation/Unet_Segmentation.pdf) for some discussion, analysis, and exploration of results.

## Implmentation Details

### External Packages
This model utilizes the following external packages:

<div align="center">

| Package                                                                                                | Used for                               |
|--------------------------------------------------------------------------------------------------------|----------------------------------------|
| `numpy`, `pandas`, `tqdm`, `scikit-image`                                                              | For Data Processing                    |
| `matplotlib`                                                                                           | For Data Visualization                 |
| `keras`, `tensorflow`                                                                                  | To build the model                     |


</div>

### Initial Setup

Download `fmodel.ipynb` and the training and testing folders. Update the PATH values in the notebook to the correct locations. Code is documented with other relevant details.

Note the data is down-sampled to keep the model light. You may change this so the model uses the full dataset. If you have problems with downloading the data, you can download it directly from the [KAGGLE DATA SCIENCE BOWL](https://www.kaggle.com/competitions/data-science-bowl-2018/data). 

## References

Allen Goodman, Anne Carpenter, Elizabeth Park, jlefman-nvidia, Josette_BoozAllen, Kyle, Maggie, Nilofer, Peter Sedivec, Will Cukierski. (2018). 2018 Data Science Bowl . Kaggle. https://kaggle.com/competitions/data-science-bowl-2018



