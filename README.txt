The dataset was found on Kaggle, a website that hosts public datasets. 

It contains 90 classes of animals and around 5000 images. 
Github wouldn't allow me to upload the dataset, so here is the link to it
https://drive.google.com/drive/folders/1xiEsnN7lzLSXoR08XUSuMjpx5O1FpBwQ?usp=share_link

I used roboflow to augment the data and tripled the size, using slight rotations and 90 degree flips. 

Because deep learning requires heavy computing power, I was not able to run the model on my computer, but rather provide 
a proof of concept. For our app, this model would be trained in a GPU rich environment to ensure speed and accuracy. 
