# Dreamscape Motion : Creating Dynamic Visuals with DeepDream

This project focuses on leveraging AI to create blended images and generate Deep Dream effects. The primary objective is to blend two images and apply the Deep Dream technique to enhance and visualize patterns within the blended image.

## Project Structure

1. **Image Blending**
    - Loading images
    - Blending images using a specified alpha value
    - Saving the blended image

2. **Deep Dream Implementation**
    - Loading the pre-trained InceptionV3 model
    - Applying the Deep Dream algorithm to the blended image
    - Saving the processed images

3. **Video Creation**
    - Generating a video from the processed images
    - Saving the video

## Image Blending

### Loading and Blending Images

Here, we load two images (`mars.jpg` and `eiffel.jpg`), blend them using a specified alpha value, and save the resulting image.Below is the result of blended image.

![Blend](https://github.com/QHaider4622/Dreamscape-Motion-Creating-Dynamic-Visuals-with-DeepDream/assets/79516393/46bf278b-ae77-4228-a1c3-494bd20bd9f5)

### Saving the Blended Image

The blended image is saved to a specified directory.

## Deep Dream Implementation

### Loading the Model

We load the pre-trained InceptionV3 model from TensorFlow.

### Applying Deep Dream

We apply the Deep Dream technique to the blended image, enhancing specific features and saving the processed images.

###  Deep Dream Processed Image After Certain Amount of Steps

##### After 200 Steps
![After200](https://github.com/QHaider4622/Dreamscape-Motion-Creating-Dynamic-Visuals-with-DeepDream/assets/79516393/f203ceb0-8ff9-4b54-a067-f17145c0594f)

##### After 800 Steps
![After 800](https://github.com/QHaider4622/Dreamscape-Motion-Creating-Dynamic-Visuals-with-DeepDream/assets/79516393/202e1f77-2616-430b-8bf3-40cd9aa96e5f)

##### After 2600 Steps
![After2600](https://github.com/QHaider4622/Dreamscape-Motion-Creating-Dynamic-Visuals-with-DeepDream/assets/79516393/4b14dc47-9f84-4cd4-bd2a-38d576c64e42)

##### After 4800 Steps
![After4800](https://github.com/QHaider4622/Dreamscape-Motion-Creating-Dynamic-Visuals-with-DeepDream/assets/79516393/8c7544fa-6c54-4955-9df4-1f94c8a920c0)


### Saving the Processed Images

The processed images are saved to a specified directory.

## Video Creation

### Generating Video from Frames

We create a video from the processed images using OpenCV's `VideoWriter`.

### Deep Dream Video

### Saving the Video

The generated video is saved to a specified directory.

## Credits

- **Deep Dream Code**: This project uses the Deep Dream code from TensorFlow's tutorial, which can be found [here](https://www.tensorflow.org/tutorials/generative/deepdream).
- **Images**: The images used in this project (`mars.jpg` and `eiffel.jpg`) were taken from [Source Image 1](https://www.pxfuel.com/en/free-photo-xxgfs) and [Source Image 1](https://commons.wikimedia.org/wiki/File:Georges_Garen_embrasement_tour_Eiffel.jpg) respectively.
  

## References
- [TensorFlow Deep Dream Tutorial](https://www.tensorflow.org/tutorials/generative/deepdream)
