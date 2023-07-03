# AUTOMATIC-CAPTIONING-OF-BLURRY-IMAGES-WITH-CNN

(FINAL YEAR MAJOR PROJECT)

UNDER SUPERVISION OF-Ms. P. Venkateshwari

TEAM- ROHIT KANDARI(05120902819) & SAKSHI(01720902819)

(ECE 8TH SEM)

G.B. PANT GOVT. ENGINEERING COLLEGE, OKHLA, DELHI

DEPARTMENT OF ELECTRONICS & COMMUNICATION ENGINEERING


Blur image captioning is a challenging task that involves generating accurate and meaningful descriptions for blurry or low-quality images affected by factors like camera shake, motion blur, or out-of-focus captures. This abstract provides an overview of recent advancements in deep learning-based approaches for blur image captioning. These methods utilize convolutional neural networks (CNNs) and recurrent neural networks (RNNs) in an encoder-decoder architecture. The encoder extracts visual features from the blurry image, while the decoder generates captions based on these features. Techniques like pre-processing algorithms for image enhancement and attention mechanisms for improved alignment between image regions and generated captions are also discussed.



Dataset :

https://www.kaggle.com/datasets/sayanf/flickr8k/download?datasetVersionNumber=5

The Flickr_8K dataset is used for the model training of image caption generators.8092 images are stored inside the Flicker8k_Dataset folder and the text files with captions of images are stored in the Flickr_8k_text folder.

There are also some text files related to the images. One of the files is “Flickr8k.token.txt” which has each image along with its 5 captions. Every line contains the <image name>#i <caption>, where 0≤i≤4 i.e. the name of the image, caption number (0 to 4) and the actual caption.


Model Development will have the following blocks:

1. Read Captions File 

2. Data Cleaning 

3. Loading Training Testing Data 

4. Data Preprocessing - Images 

5. Data Preprocessing - Captions 

6. Data Preparation using Generator Function 

7. Word Embedding 

8. Model Architecture 

9. Train Our Model 

10. Predictions 


conclusion:

In conclusion, Convolutional Neural Networks (CNNs) offer a promising solution for automatically captioning blurry images, addressing the challenge of accurately describing their content. These images often lack fine details and sharpness, posing difficulties for traditional captioning algorithms. However, CNN-based approaches have demonstrated the ability to extract meaningful features from blurry images, enabling the generation of valuable insights through captions. In our study, we initially employed the ResNet50 and LSTM models to generate captions for normal images in the flickr_8k dataset. We then applied data augmentation techniques to blur the images and utilized the transformer model to generate captions for the blurred images. Both models exhibited good accuracy for their respective datasets. To achieve state-of-the-art results, we suggest hyperparameter tuning and conducting experiments on larger datasets to expand the model's vocabulary. Additionally, incorporating more recent architectures, such as GoogleNet, could further enhance the accuracy of the captioning task and reduce language generation errors
