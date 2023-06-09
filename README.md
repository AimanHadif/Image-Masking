# Image-Masking
Creating a black circle boarder in the images in a folder. This technique is also known as Alpha Mask that is available using OpenCV
- Performing image masking helps transformers and autoencoders to learn easily using only required information from the images. Masking can speed up the transformer to perform classification tasks using images.
- Make sure the set of images is in a folder
- An option to mask only 1 image is also available

## Example of Original Image Before Masking
- Let say you are doing face recognition but you dont want to capture the whole image as an input. Therefore, masking the image may help depending on your model in recognizing the face

<img src="images/face.png" alt="face1" width="300"> <img src="images/manface.webp" alt="face2" width="300">

## After Masking

<img src="images/masked_face.png" alt="face1" width="300"> <img src="images/masked_manface.webp" alt="face2" width="300">

