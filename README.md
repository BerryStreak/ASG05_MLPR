# ASG05_MLPR
Assignment 5 in the Machine Learning and Pattern Recognition course
## Aim:
- detect multiple faces in a group photograph 
- extract features(hue and saturation) for colour from detected faces
- cluster detected faces using K-means
- classify an additional template image into an existing cluster
- visualize results

## Methodology:
- face detection using opencv's Haar Cascade Classifier
- feature extraction(hue and saturation) using hsv
- clustering using k-means (number of clusters=2)
- template detection and classification by extracting features and predicting cluster label (using trained K-means model)

## Key Findings:
# successfully detected all faces in the group photograph (accuracy dependent on minsize and maxsize parameters, lighting etc)
![Plaksha_Faculty](https://github.com/user-attachments/assets/43c12de4-ea89-48db-aa34-2da99b5aaaca)

# two clusters successfully identified based on hue and saturation of the detected faces (skin tone) with centroids clearly separated
<img width="1087" height="557" alt="Screenshot 2026-02-15 171253" src="https://github.com/user-attachments/assets/a766eb4e-71cb-49a0-b74c-c5702ba762bb" />
<img width="1111" height="558" alt="Screenshot 2026-02-15 171405" src="https://github.com/user-attachments/assets/7221983d-5e93-45ea-aaef-0c742ef811d8" />

# template image successfully detected and classfied into an appropriate cluster
<img width="1101" height="565" alt="Screenshot 2026-02-15 171552" src="https://github.com/user-attachments/assets/a154a325-5817-46d6-94ab-6d6d2b5758e3" />
<img width="1098" height="562" alt="Screenshot 2026-02-15 171526" src="https://github.com/user-attachments/assets/327b65ba-5892-4418-aa2b-5b80237cd07c" />
<img width="492" height="503" alt="Screenshot 2026-02-15 171441" src="https://github.com/user-attachments/assets/9e96992b-9b2d-4822-a048-4e44e82bc6b3" />



## Conclusions:
- effective face detection using Haar Cascade classifier
- effective clustering using K-means
- effective hsv feature selection
- effective template detection and classification

visualizations provided above
