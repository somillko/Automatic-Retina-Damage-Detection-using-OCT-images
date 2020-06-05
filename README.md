# Automatic-Retina-Detection-using-OCT-images
Determining the retina damage using OCT scans.

## What is OCT
Optical Coherence Tomography is a technique developed for non-invasive imaging of biological cells extensively used by Ophthalmologists to study the structure of the retina and related diseases. OCT is analogous to ultrasound where it uses low-coherence interferometry to produce a two-dimensional image of optical scattering. It has longitudinal and latitude spatial resolution which is capable of detecting very small reflected signals from retina approximately 10(-10) of the incident optical power

With millions of people across India reporting CNV, DME and Drusen annually, it has become very crucial to detect these disorders on time to start their treatment as some of these can not be cured after a point of time.Currently, trained ophthalmologists clinically examine the presence of any retinal disease like DME, CNV and Drusen. To enable remote identification of diseases and speed up the diagnostic process, automated analysis of OCT images has remained an active field of research since the early days of OCT imaging.We have developed a new intelligent system based on deep learning to automatically categorize OCT images to aid clinicians and make the process faster and more accurate. The framework has the capability to increment diagnostic efficiency, enable easier access to expert knowledge, facilitate remedial decision-making, and decrease overall healthcare costs.

## 4 Classes
![FourClassesOfImages](https://github.com/somillko/Automatic-Retina-Damage-Detection-using-OCT-images/blob/master/256X256%20images/4%20classes%20of%20diseases.png)

## CNN and CNN layers
* Convolution Layer
* Relu layer
* Pooling Layer
* Flattening Layer
* Fully Connected Layer

## CNN Workflow
![CNNWorkflow](https://miro.medium.com/max/1400/1*XbuW8WuRrAY5pC4t-9DZAQ.jpeg)

## Information about the Dataset
Link to the dataset - https://www.kaggle.com/paultimothymooney/kermany2018

The data was collected from Kaggle.com which was uploaded by Paul Mooney and is licensed by Non Commerical ShareLike 4.0 which gives the permission to Share and Adapt. We have used this particular data set in our project, whose summary is as follows:
* Total Images: 84495
* Final Evaluation: 968 Images
* 242 Images per category in the final evaluation
* There are 84,495 OCT images (JPEG) and 4 categories (NORMAL,CNV,DME,DRUSEN).

## Data Analysis Flowchart
![DataAnalysis](https://github.com/somillko/Automatic-Retina-Damage-Detection-using-OCT-images/blob/master/Flow%20Diagrams/Data%20Analysis.png)

## Baseline 3 Layered Model(95.833%)
![3layer](https://github.com/somillko/Automatic-Retina-Damage-Detection-using-OCT-images/blob/master/Flow%20Diagrams/Model%203%20layer.png)

## 5 Layered Model
![5Layer](https://github.com/somillko/Automatic-Retina-Damage-Detection-using-OCT-images/blob/master/Flow%20Diagrams/Model%205%20Layer.png)

## 7 Layered Model
![7layered](https://github.com/somillko/Automatic-Retina-Damage-Detection-using-OCT-images/blob/master/Flow%20Diagrams/Model%207%20layer.png)

## Results
![table](https://github.com/somillko/Automatic-Retina-Damage-Detection-using-OCT-images/blob/master/Flow%20Diagrams/table.png)

For the individual results I would suggest you see the PPT and the report, since it is not really possible to mention every result in the readme.

## Major Challenges
* Finding of a Cloud GPU resource so as to perform our training and testing part.
* Hyper parameter optimization like optimizing the image size and number of epochs.
* Dealing with overfitting by using dropout regularization.
* Finding out the exact number of dropouts required so that model does not go into underfit and actually fits correctly.

## Transfer Learning models Coming Soon!!
