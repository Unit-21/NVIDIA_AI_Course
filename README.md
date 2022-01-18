# NVIDIA AI Course

This model is created based on the "Episode 3 - Training Image Classification Models" under the "Hello AI World Course" (https://developer.nvidia.com/embedded/learn/jetson-ai-certification-programs)

The idea comes from my daily life. Since I am a university student and I am in remote instruction mode nowadays, the sitting position is critical to my physical health, especially my spine and eyesight. I reckon sitting up straight is the proper body position, whereas leaning forward is wrong.

This model is developed to use the input of a live camera to tell if the sitting position of the people in the camera is proper or not. This model is trained based on 127 images of proper position and 127 wrong position. In each dataset, you can see me sitting in different positions. Following the course content, I trained my model for 35 epochs to improve accuracy.

In the video (https://drive.google.com/file/d/1ZAkCejln8QYhoJEnTzSchxD5o-_KtFsC/view?usp=sharing), you can see me sitting in different positions and the camera is in a fixed position to test the result of my model. The accuracy of my model after 35 epochs is not bad. The confidence level is usually above 60% and it is correct in most scenarios. In addition, when I took off my jacket in the video, the model still worked properly, since I trained my model with different clothes.

This model can be easily reproduced by anyone, as long as he/she follows the Jetson Nano setup video and learns the basic knowledge of Python, Linux, and machine learning in Nvidia tutorials. Then the person needs to put the camera in a fixed position, take pictures of his/her body position, categorize them in correct or wrong position, and train the resnet18 model using these pictures. 

Moreover, this model can be improved by: 1. Taking more pictures under different lighting conditions; 2. Taking pictures of different people; 3. Taking pictures of people wearing different clothes.

