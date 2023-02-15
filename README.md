# Pneumonia-Classification
Determining whether or not a patient has pneumonia based on image classification


# What is Pneumonia? 
-An infection that inflames the air sacs in the lungs, and the fluid accumulation in the lungs can cause a lack of oxygen
-The patient struggles to breathe and, without treatment, can succumb to asphyxiation

Bacteria, viruses, fungi, and mold can cause pneumonia 

Aspergillus: 
![Organism](https://imgur.com/a/7JNPQxc)

# The Dataset: 
Mendeley Dataset with 256 pictures of chest x-rays  
It contains normal x-rays, x-rays of patients with bacterial pneumonia, and x-rays of patients with viral pneumonia ​​
The viral and bacterial x-ray pictures are split into two classes: normal and pneumonia
I used binary classification to determine if a patient has pneumonia or not. 

# The Model: 
-I used a convolutional neural network (preferred for image classification)
-The diffuse X-ray scattering of the image shows up as fuzziness and the more fuzzy the picture is, that's how the algorithm determines if the patient has pneumonia 
-Baseline accuracy score of 96-98%

Agar Art: 
![Agar Art](https://imgur.com/a/iTv7naf)

# Future Improvements: 
Multi-class algorithm with 3 or 4 nodes, for viral, bacterial, or fungal pneumonia, along with normal lungs (differentiate between all 4 classes)
Adapting the technology to help monitor pneumonia, not just diagnosing it 

![X-ray](https://i.imgur.com/RB34kxW.png) 

# Future Improvements not related to data science: 
X-rays are not a good tool to monitor the patient’s condition. (It’s too much radiation exposure for the patient.) 
Consistent lab results and vital signs are how we monitor patients with severe pneumonia 
Nurses have to count the respiration rate of the patient, but we could set up a camera to do this automatically. 
The camera could also detect the color of the patient’s skin to see if it turns blue. 

# Potential impact of this technology: 
Automatic data collection could allow the workers to act more quickly
Prevent further exposure of nurses and staff to Covid-19 and other serious diseases, saving more lives overall
Patients with level 4 pathogens like Ebola would be well-contained in their room, with very little intervention needed from nurses
With the help of data science algorithms, cameras, and robots to physically assist the patients, we could save the lives of more healthcare workers

