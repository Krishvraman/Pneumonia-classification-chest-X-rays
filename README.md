# Pneumonia-classification-chest-X-rays

The goal of the project is to classify chest X-rays for Pnuemonia identification

Project Details:

- Using a chest X-Ray is the usual clinical way to diagnose pneumonia
- We are going to apply deep CNN networks to do the same task - custom CNN and DenseNet
- Once the Network is able to classify pnuemonia we are going to understand the hotspots used by the network to identify pnuemonia and correlate its clinial significance
- After that we are going use this data to better understand pnuemonia and apply clustering and neighbor embedding (TSNE) to try and understand if there are any higher   level of information


Sample chest X-ray Images:

![image](https://user-images.githubusercontent.com/117613924/201552465-f0fc50ed-1706-4ff7-bfea-b16e511de28a.png)


Classification results:

![image](https://user-images.githubusercontent.com/117613924/201552911-f45c7bb6-49a6-4768-b93b-577abba9dbb5.png)

GradCam Analysis:

Analysis where the network is looking at for classifying Pneumonia

![image](https://user-images.githubusercontent.com/117613924/201553095-ef58eeb2-dc63-4bba-9bd4-1625c5dfad7c.png)


![image](https://user-images.githubusercontent.com/117613924/201553133-6b5d725d-a6a9-48ff-ac29-5e5c8e0fdea1.png)

T-SNE analysis:

Penultimate layer outputs of both DenseNet was used to create the TSNE plot below

![image](https://user-images.githubusercontent.com/117613924/201553178-ed9ba244-dadb-4a64-8038-01d6e850207f.png)
