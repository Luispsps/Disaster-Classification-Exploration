Disaster Image Classification & Authentication

Machine Learning Research | Computer Vision | Proof of Concept

Overview

This project explores whether machine learning models can be used to classify natural disasters from images while also detecting AI-generated or manipulated images. The motivation behind this work is to address the growing risk of misinformation in emergency response, where first responders may rely on social media images to assess disaster situations.

With recent advances in AI image generation, fake or altered images can appear highly realistic. This project investigates the feasibility of combining disaster classification with image authenticity detection as a potential decision-support tool for emergency response teams.

This work was conducted in collaboration with Allisson as an exploratory research project and proof of concept.

Project Goals

Explore deep learning approaches for disaster image classification

Investigate detection of AI-generated vs real disaster-related images

Evaluate the feasibility of combining both tasks into a single pipeline

Gain hands-on experience with real-world datasets and transfer learning

Technologies Used

Python

TensorFlow / Keras

Convolutional Neural Networks (CNNs)

Transfer Learning

VGG16

EfficientNet

Google Colab

Datasets

The project uses a combination of disaster-related and AI-authentication datasets:

MEDIC Dataset
https://crisisnlp.qcri.org/medic/#data_format_and_dir

CIFAKE: Real and AI-Generated Images
https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images

Real vs Fake Turkey Earthquake Images
https://www.kaggle.com/datasets/merveakdogan/real-vs-fake-turkey-earthquake

Approach

The project follows an experimental, research-driven workflow:

Conducted a literature review on disaster response image classification and AI image authentication

Collected and curated datasets from multiple public sources

Implemented transfer learning using pre-trained CNN architectures

Experimented with multiple model configurations and preprocessing pipelines

Evaluated feasibility and limitations under real-world constraints

Several existing open-source implementations were referenced to guide model design and dataset handling.

Code & Notebooks

Development was conducted primarily in Google Colab due to its built-in TensorFlow support. The repository includes multiple notebooks exploring different model architectures and dataset configurations.

Colab notebooks:

https://colab.research.google.com/drive/149VS6Ov2zSwyTJaXU8g75qb0L6GJ4tQ4

https://colab.research.google.com/drive/1YtsfefGepkYVoukK6ndukrbHa2L7stO3

https://colab.research.google.com/drive/1u2VTRf5O2ciSaAYeiLjEj6EfRTTde_CN

These notebooks represent experimental prototypes. Some models are incomplete and were created to explore architecture behavior, data preprocessing, and feasibility rather than final accuracy.

Results

Due to limited data availability, dataset complexity, and computational constraints, the models did not achieve production-level accuracy. However, the experiments demonstrated promising signals for both disaster classification and AI-generated image detection, validating the project as a proof of concept.

The project and findings were presented at a poster celebration event.

<!-- Add poster image here -->
Challenges & Lessons Learned

Limited availability of AI-generated disaster imagery

Complex dataset structures, particularly within the MEDIC dataset

Learning correct transfer learning workflows and avoiding retraining pre-trained weights

High computational cost of deep CNN models

Debugging inference and image input pipelines

These challenges provided valuable experience working with real-world data and highlighted the gap between academic models and practical deployment.

Current Status

This project is ongoing and remains a research-focused proof of concept. Future work includes improving dataset quality, refining model architectures, and exploring automated data collection methods.

Acknowledgments

Special thanks to Allisson for her collaboration and contributions throughout this project.
