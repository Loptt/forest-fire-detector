# Forest Fire Detector

There are three Jupyter Notebooks, one for each classifier created

- The classifier with the VGG19 model is in classifier_vgg19.ipynb
- The classifier with the ResNet50 model is in classifier_resnet50.ipynb
- The classifier with the InceptionV3 model is in classifier_inceptionv3.ipynb

Run each individual notebook from start to finish to see the training and evaluation process for each model.

The exploratory analysis for the images can be found in image_analysis.ipynb. Please note that running the analysis on all images might take a while to execute...

The data set is too large to be uploaded to Github. Please download the data from [here](https://ieee-dataport.org/open-access/flame-dataset-aerial-imagery-pile-burn-detection-using-drones-uavs).
Once downloaded, it must be placed in a directory called data/ at the root of the project. This step is crucial for the training to work.

Finally, models are saved in the models/ directory. Previously saved models are, however not on this repository as they are too large to by uploaded as dictated by GitHub guidelines.
