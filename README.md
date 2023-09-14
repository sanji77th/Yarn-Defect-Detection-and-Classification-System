# Problem Statement

Problem Statement:
The identification and detection of defects in cotton yarn are of paramount importance in ensuring rigorous quality control within the textile industry. However, the traditional manual inspection processes are not only time-consuming but also prone to a certain degree of human error, thus leading to suboptimal accuracy in defect detection.

Proposed Solution:
In response to the aforementioned problem, a comprehensive solution was devised. A diverse dataset comprising 1250 high-quality images was meticulously curated. This dataset encompassed a wide spectrum of defect categories, including but not limited to thick and thin places, hairiness, snarls, neps, and non-defective yarns. The systematic development of this dataset occurred through several stages to ensure a comprehensive representation of defects prevalent in cotton yarn.
Subsequently, two distinct datasets were created, adhering to an 80:20 ratio for training and testing purposes. This division allowed for an evaluation of the model's ability to generalize effectively to previously unseen data.
To tackle the problem further, a Convolutional Neural Network (CNN) model was meticulously crafted. The model's architecture and hyperparameters underwent rigorous optimization to attain the highest possible accuracy. Moreover, to enhance the model's performance, transfer learning techniques were explored, utilizing pre-trained models such as VGG-16, ResNet50, and InceptionV3, particularly in cases where building a model from scratch proved less effective.
The selection of the most suitable model was contingent upon its performance, with a focus on accurately identifying various defect types present in cotton yarn.


# Code will be available soon!

Project Yarnist aims to tackle the critical issue of yarn quality affecting the final fabric's outcome. By utilizing the Yarnist Inspector, a high-quality capturing device with a faster speed than the running yarn, images of the yarn are automatically captured through a web application with just a single click. These images are then classified based on defects like neps, hairiness, thick and thin places, snarls, and non-defective segments using a trained CNN model. The user-friendly web application facilitates the generation and download of comprehensive quality status reports for the yarn. The system efficiently manages data, allowing for easy clearing of previous images and generating new reports for each new batch of yarn. Going beyond the fundamental approach, Project Yarnist envisions placing the Yarnist Inspector in yarn warehouses with a rewinding mechanism. With cloud-hosted web applications, warehouses worldwide can access the Yarnist system, obtaining valuable reports and contributing data to enhance the CNN model's intelligence. The ultimate vision is to achieve remote certification for yarn quality, revolutionizing the textile industry and ensuring the production of superior fabrics.


https://github.com/sanji77th/yarn-defect-detection-and-classification-system/assets/42697893/f007277c-5d9f-45b1-9ab7-7a253437f62b

