# AMD_project
Automatic classification and segmentation of AMD disease from retina scans

This page contain a brief description for my BSc lab project: "Automated Image-Based Analysis of Advanced Macular Degeneration with
Geographic Atrophy using Convolutional Neural Networks".

Age-related macular degeneration (AMD) is a medical condition which may result in blurred or no vision in the center of the visual field, due to the death of nerve cells in the retina. 

Early diagnosis of the condition can lead to preventive treatment which can save the patient's eyesight. 
In this project I implemented a deep learning method for the automatic classification and segmentation of the lesions using two imaging modalities, Infra-Red (IR) and spectral-domain optical coherence tomography (SD-OCT).

The goal is to achieve high segmentation accuracy with limited training data as the ground truth.

Our experimental results on five patients for training and two patients for test set yield a successful segmentation of the lesions. We achieved an 87.4% dice coefficient, a classification recall of 85.65% for the healthy patches and a recall of 87.44% for the pathological patches. We achieved an F1-score of 0.760.
These preliminary results indicate that our method may be a useful tool for assisting clinicians in the diagnosis of AMD. 

An example for the result I've achieved on the test set is displayed below.
![better_result](https://user-images.githubusercontent.com/23454156/45216849-a8254780-b2aa-11e8-8b3d-5afa94ae9958.jpg)

# About This Repo
This page contains only the brief description of the project and visualization of the results. The code is not shared for now.
