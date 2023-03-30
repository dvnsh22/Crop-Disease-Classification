# Crop-Disease-Classification
<p> Plants' health can be diagnosed effectively by analysing their leaves and hence, they can be helpful in recognising a disease that the plant is suffering from. Accurate diagnosis of health of crops is a critical issue for farmers. To help them in the best management practices and to prevent future losses, Machine Learning can prove to be beneficent for them. </p>
<p> In this project, a Machine Learning model has been created for the prediction of health of apple crop by the means of its leaves. The model classifies the plant into one of the 4 categories namely, <i>healthy</i>, <i>scab</i>, <i>rust</i>, or <i>multiple diseases</i>. </p>

## Methodology
Dataset used: https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data <br /><br />
Steps involved during implementation of the project are as follows:
<ol>
<li> Using the <i>train.csv</i> file provided with dataset, the images have been categorized into the 4 different classes (<i>healthy</i>, <i>scab</i>, <i>rust</i>, <i>multiple diseases</i>), and further divided into training, testing and validation sets. </li>
<li> Transfer Learning approach has been used to train the model where pre-trained weights of ImageNet have been used and then, five neural network layers have been added to it. </li>
<li> The trained model has been saved with the name <i>crop_disease.h5</i> after performing 10 epochs. </li>
<li> The model has been tested against 10 random images from the testing set and its class predictions have been displayed. </li>
</ol>
