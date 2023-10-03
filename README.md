# Applied-AI-Model-of-ASL-Interpretation
Our initial machine-learning model was trained on a homogenous dataset of 78,000 images depicting a hand, showing a letter from the ASL alphabet, against a white background. The original training dataset is too large to include, but the testing dataset is avaailable for comparison purposes. 

Working in a team of 5 to enhance this pre-existing model with a three-pronged approach: 
1. Diversifying the photo dataset with colorful backgrounds
2. Modifying transforms to account for varying image clarity or color
3. Using edge detection to highlight hand shape.

My partner and I, focusing on dataset diversification, incorporated over 1500 photos from Kaggle datasets and original photos we took ourselves. Data splits and organization were used to follow the structure from the original homogenous dataset. This difference in data proportions was due to the computing power available to us. With training on the mixed dataset and testing it only on the new images, with diverse backgrounds, we reported a 7% accuracy increase in ASL recognition. 

# A visual comparison
Below are some photos highlighting the quality and photo diversification between the original and new datasets. This is included due to the density of the training files containing all of the images. 

Old dataset:
<div style= ""width:60px ; height:60px">
![image](https://github.com/gleverette/Applied-AI-Model-of-ASL-Interpretation/assets/108033707/99d67e78-ad23-4c14-a610-c5c7c9aa341b)
![image](https://github.com/gleverette/Applied-AI-Model-of-ASL-Interpretation/assets/108033707/eb2819cb-6356-4b6c-8447-644a96d6e354)
![image](https://github.com/gleverette/Applied-AI-Model-of-ASL-Interpretation/assets/108033707/95403d25-c812-4f97-b654-b4aee7a94b9d)
</div>

New dataset: 
<br>
<div style= ""width:60px ; height:60px">
  ![image](https://github.com/gleverette/Applied-AI-Model-of-ASL-Interpretation/assets/108033707/2e7965d5-0af3-4c3d-9b23-ddf3a355f3df)<br>
  ![image](https://github.com/gleverette/Applied-AI-Model-of-ASL-Interpretation/assets/108033707/745dadc0-54b4-4903-b5d0-c1cb7876787d)<br>
  ![image](https://github.com/gleverette/Applied-AI-Model-of-ASL-Interpretation/assets/108033707/c2676705-3dbb-429b-a1f4-46b8cfe5bbe3)<br>
</div>












