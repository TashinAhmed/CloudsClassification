![alt text](https://storage.googleapis.com/kaggle-media/competitions/MaxPlanck/Teaser_AnimationwLabels.gif)


[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/classification-and-understanding-of-cloud/satellite-image-classification-on-nasa)](https://paperswithcode.com/sota/satellite-image-classification-on-nasa?p=classification-and-understanding-of-cloud)
![alt text](https://img.shields.io/badge/version-1.0-f39f37)
# Clouds Classification

Clouds classification analysis from satellite images based on Kaggle Competition. 

All notebooks were initially prepared from publicly shared kernels mentioned in this <a href="https://github.com/TashinAhmed/CloudsClassification/blob/main/EfficientUNet.ipynb">notebook</a>.

RG: https://www.researchgate.net/publication/344410350_Classification_and_understanding_of_cloud_structures_via_satellite_images_with_EfficientUNet

arXiv: https://arxiv.org/pdf/2009.12931.pdf



<strong>Kaggle LB score on final experimental setting (EfficientUNet):</strong>

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky" rowspan="2">EfficientNet<br>Version</th>
    <th class="tg-0pky" rowspan="2">Cross<br>Validation</th>
    <th class="tg-0pky" colspan="2">LB score</th>
  </tr>
  <tr>
    <td class="tg-0pky">Private</td>
    <td class="tg-0pky">Public</td>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">B0</td>
    <td class="tg-0pky">0.6654</td>
    <td class="tg-0pky">0.6602</td>
    <td class="tg-0pky">0.6626</td>
  </tr>
  <tr>
    <td class="tg-0pky">B1</td>
    <td class="tg-0pky">0.6601</td>
    <td class="tg-0pky">0.6553</td>
    <td class="tg-0pky">0.6598</td>
  </tr>
  <tr>
    <td class="tg-0pky">B2</td>
    <td class="tg-0pky">0.6589</td>
    <td class="tg-0pky">0.6570</td>
    <td class="tg-0pky">0.6578</td>
  </tr>
  <tr>
    <td class="tg-0pky">B3</td>
    <td class="tg-0pky">0.6588</td>
    <td class="tg-0pky">0.6500</td>
    <td class="tg-0pky">0.6582</td>
  </tr>
  <tr>
    <td class="tg-0pky">B4</td>
    <td class="tg-0pky">0.6425</td>
    <td class="tg-0pky">0.6417</td>
    <td class="tg-0pky">0.6421</td>
  </tr>
  <tr>
    <td class="tg-0pky">B5</td>
    <td class="tg-0pky">0.6322</td>
    <td class="tg-0pky">0.6319</td>
    <td class="tg-0pky">0.6333</td>
  </tr>
</tbody>
</table>


<strong>Cite the work:</strong>
```
@article{ahmed2020classification,
  title={Classification and understanding of cloud structures via satellite images with EfficientUNet},
  author={Ahmed, Tashin and Sabab, Noor Hossain Nuri},
  journal={arXiv preprint arXiv:2009.12931},
  year={2020}
}
```
