<img="https://storage.googleapis.com/kaggle-media/competitions/MaxPlanck/Teaser_AnimationwLabels.gif">
# CloudsClassification
Clouds classification analysis from satellite images based on Kaggle Competition. 

All notebooks were initially prepared from publicly shared kernels mentioned in this <a href="https://github.com/TashinAhmed/CloudsClassification/blob/main/EfficientUNet.ipynb">notebook</a>.

paper: https://www.researchgate.net/publication/344410350_Classification_and_understanding_of_cloud_structures_via_satellite_images_with_EfficientUNet

arXiv: https://arxiv.org/pdf/2009.12931.pdf

This paper implements classification of satellite images of
cloud structures into four different classes: Sugar, Gravel, Fish
and Flower. 6 versions of EfficientNet from B0 to B5 were
used as encoder and UNet as decoder has been applied. Dice
coefficient was used as the evaluation metric. The scores used
were compared with both public and private LB scores of
Kaggle competition. By using a segmentation model like UNet
in a classification problem, it was proven that with a good
encoder it is possible to achieve good performance from the
dataset. Although EfficientNet was used in this paper, it could
be replaced with a different model as well but was not tested in
this research. Also, a good segmentation of the images boost the output of the classification drastically, which was also
proven in this paper. In future, estimation of the distribution
of classes and adjustment of the validation set could be
implemented accordingly, although it would only be ideal for
the competition. As the complex architectures of EfficientNet
gave less appreciating results because of default coefficients,
altering these hyperparameters according to the dataset will
hopefully improve the outcome. Exploring gradient weighted
class activation mapping to generate a baseline, which is a
class explainability technique, could be achieved.
