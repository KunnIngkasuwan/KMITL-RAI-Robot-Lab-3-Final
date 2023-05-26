# KMITL-RAI-Robot-Lab-3-Final
KMITL RAI Robot Lab 3 Final Assignment

Task 1 - Data Acquisition 
Although our project may appear simple, creating a high-quality dataset for it requires significant effort. To ensure accuracy in detecting the different hand gestures (rock, paper, and scissors), we need to generate a substantial amount of diverse rock-paper-scissors photos. It's important to avoid separating the fingers too much during image capture, as it could potentially lead to misclassifications, particularly as scissors. By amassing a large and varied dataset, we can enhance the accuracy of our model and improve its ability to distinguish between different hand gestures effectively. 

Task 2 - Data Preparation 
Loading data: For dataset creation, we utilized Roboflow as our chosen tool. Roboflow provided the necessary functionality to effectively generate our dataset for the project. 
Labeling and annotation: The data needs to be meticulously labeled and annotated to indicate the corresponding hand gestures (rock, paper, or scissors) in each image or frame. 
Data splitting: The dataset should be divided into appropriate subsets, such as training 70%, validation 20%, and testing sets 10%, to evaluate and optimize the model's performance effectively. 
Data augmentation: To enhance the diversity of our dataset and mitigate overfitting, we employed various data augmentation techniques. These techniques encompassed image rotations, flips, hue adjustments, 90-degree rotations, blurring, and color manipulations. By applying these augmentation techniques, we effectively expanded the dataset, ensuring a more robust and generalized training experience for our model. 

Task 3 - Model Training and Deploy 
In this task, the objective is to train a computer vision model for the Rock Paper Scissors task and deploy it on Jetson Nano. For this project, we have the flexibility to select our own model for training the data, allowing us to choose the most suitable architecture and approach for the task. Once the model is trained, it needs to be deployed on the chosen hardware, ensuring that it can efficiently process and classify Rock Paper Scissors gestures in real time. By successfully completing this task, we can demonstrate the effectiveness of our computer vision model and its deployment on Jetson, enabling real-time Rock Paper Scissors detection for various applications. 

Task 4 – Model Inference  
https://m.youtube.com/watch?v=v2ZVSA9yt5Q&feature=youtu.be 
https://www.tiktok.com/@kmitlphurich/video/7237395703868165378?is_from_webapp=1&sender_device=pc&web_id=7237394789250319873 
