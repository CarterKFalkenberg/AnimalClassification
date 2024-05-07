The dataset was found on Kaggle, a website that hosts public datasets. 

It contains 90 classes of animals and around 5000 images. 
Github wouldn't allow me to upload the dataset, so here is the link to it
https://www.kaggle.com/datasets/iamsouravbanerjee/animal-image-dataset-90-different-animals 

I used roboflow to augment the data and tripled the size, using slight rotations and 90 degree flips. 

Here is a link to the roboflow page: https://universe.roboflow.com/chess-ynmuj/animal-detection-3deg6 

Because deep learning requires heavy computing power, I was not able to run the model on my computer, but rather provide 
a proof of concept of the code that would be used. For our app, this model would be trained in a GPU rich environment to ensure speed and accuracy. 

While I was not able to run my code locally, I was able to use free credits on Roboflow to use their ML algorithms to train for classifications. 
See results in "Classification_Summary.pdf"
