Disaster Classification Research Documentation  


1. Project Overview 

Disaster Classification Exploration a project in which we used machine learning to explore if we could classify natural disasters and implement authentication of whether the image was real or fake (AI-Generated, Human-Manipulated, etc.). This project's purpose was to make a tool in which first responders can use to identify the disaster and make sure it's real. The reason for the authentication is because first responders could depend on social media images to identify the situation of a disaster, but with current advancement of AI technology, they risk obtaining fake images. In this project, I've collaborated with Allisson, and together we took a step towards this proof of concept.  


2. Timeline 

March 2024: 

During this month, we kept exploring and reading articles that could point us in a direction with how we want to do this project (and overall find a project idea). Some of the articles we have read include:  

- Deep Learning Benchmarks and Datasets for Social Media Image Classification for Disaster Response 
- Damage Assessment from Social Media Imagery Data During Disasters 
- Detecting Fake Images on social media using Machine Learning 
- Application of Artificial Intelligence in Predicting Earthquakes: State-of-the-Art and Future Challenges 
- Rapid Damage Assessment Using Social Media Images by Combining Human and Machine Intelligence 
- EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks 
- Deep Learning for Image Authentication: A Comparative Study on Real and AI-Generated Image Classification 

We were exploring a lot of articles involving identification of fake images, efficient pre-trained models for such tasks, and overall research on disaster classification. With this we were able to head in a direction that satisfied all of us.  

April 2024: 

During April is when a lot of coding occurred (Using TensorFlow) and gathering of data for our set model. Scouring through the internet and following threads through the previously mentioned articles, we found the following datasets: 

- MEDIC Datasets (https://crisisnlp.qcri.org/medic/#data_format_and_dir)
- CIFAKE (https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images)
- Real vs Fake - Turkey Earthquake (https://www.kaggle.com/datasets/merveakdogan/real-vs-fake-turkey-earthquake?rvi=1)

With these good datasets, we implemented transfer learning and used pre-trained models that have been efficient for other researchers. Two in particular were VGG16 and EffecientNet (ironic). During this process we took guidance of previous work in GitHub to work with the dataset and implemented. A few GitHub we have used were:  

- https://github.com/Natsu6767/VGG16-Tensorflow/blob/master/VGG16%20Train.ipynb 
- https://github.com/qubvel/efficientnet?tab=readme-ov-file#about-efficientnet-models 
- https://github.com/2spi/ai-v-real/blob/master/.ipynb_checkpoints/ai_real-checkpoint.ipynb 
- https://github.com/yjwong1999/MobileNetV2-for-Disaster-Classification 

Overall, throughout the month it was a lot of development and steps towards building and replicating models with the same accuracy. All while continuing to complete Coursera. Towards the end of the month, we were encouraged to participate in a poster celebration event which pushed us to produce a poster talking about our project. 

#Add poster image

Unfortunately, we couldn’t produce good results but were able to present proof of concept.  

May 2024:  

During May we continue to work on the project and Allisson is exploring ways in which we can create our dataset using an API that collects images through the internet. During the beginning of this month, I took a different route to explore how AI, or fake images are detected, and so I used CIFAKE (which I previously mentioned.) to explore if it’s able to detect images of fake disasters. It proved to be promising and so I thought of implementing this AI Detection to my original Model of Disaster Detection. This continues.  


3. Code 

Throughout this project our best friend was TensorFlow, and with TensorFlow, we were able to create a lot of models that had a lot of potential with Classifying Disaster images while authenticating if it's real. Also, TensorFlow helped us organize data and be able to curate it for our use. Further, we used Collab as our project's IDE because it already had TensorFlow Implemented into it and was useful. The following list is the many collabs we created: 

- https://colab.research.google.com/drive/149VS6Ov2zSwyTJaXU8g75qb0L6GJ4tQ4?usp=sharing
- https://colab.research.google.com/drive/1YtsfefGepkYVoukK6ndukrbHa2L7stO3?usp=sharing
- https://colab.research.google.com/drive/1u2VTRf5O2ciSaAYeiLjEj6EfRTTde_CN?usp=sharing
  
A lot of these collabs have not yet been given comments, there are prototypes of different pre-trained models and models I’ve made. Most of the code is accessing the data and preparing it, the MEDIC dataset was difficult to access and the only having data involving disasters. I want to profusely comment now that the models are not complete. There is still a lot to work on and most of these builds have not successfully produced high accurate classification and a lot of bugs are occurring, especially when it comes to testing the model.  


4. Lessons Learned 

Throughout this whole project, there have continuously been challenges. The following being: 

- We had a limited amount of data when it comes to Disaster Images and specifically AI Generated Disaster Images.  
- MEDIC Dataset (which previously mentioned) was difficult to use due to its complex organization which made trying to implement other datasets with it difficult. 
- Transfer Learning (Pre-train Models) were a new concept and spent almost a whole week not realizing that I was retraining the model instead of using its weights pre-installed.  (Thank goodness I was taking COURSERA) 
- Training with these sorts of models took a lot of time and computational power (which we didn't have). It made training difficult and progressing hard.  
- Currently, there are problems with testing the model when given a specific image, it might be an issue with how I submit the image.  

There were plenty more challenges with this project, but all eventually have been found a solution. Overall, these challenges have pushed us and helped grow our experience with Machine Learning and Datasets overall.  


5. Conclusion 

As I continue working on this project, it's becoming clear that it will serve as more of a proof of concept rather than delivering outstanding accuracies or groundbreaking results. Nonetheless, the journey has been immensely educational, providing valuable insights into the complexities of machine learning. Through this process, my skills have grown, and I've gained valuable experience in navigating various challenges. A special acknowledgment goes to Allisson for her invaluable partnership and contributions to the project. 
