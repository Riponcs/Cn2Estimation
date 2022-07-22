# Cn2 Estimation
## Turbulence Strenght Estimation from Video/Image Sequence


We have used two datasets to train/test the model(the July dataset and October Dataset). Each dataset contains around 30k images. All those images were taken with the Nikon P100 DSLR camera at 60fps at a distance of 750m~1500m from the camera. We used a scintillometer to measure the turbulence strength.


* Two Models are used here:
   - Naive Deep Learning Model
   - Physics-Based Deep Learning

The naive Deep learning model tends to overfit the data and is suited for single-point consistent measurement. 
<figure>
<img src="https://github.com/Riponcs/Cn2Estimation/blob/main/Img/NaiveCNN.jpg?raw=true" alt="Naive CNN" style="width:100%">
<figcaption align = "center"><b>Naive Deep Learning Model</b></figcaption>
</figure>

However, the Physics-Based Deep Learning model can generalize well over multiple datasets. 
<figure>
<img src="https://github.com/Riponcs/Cn2Estimation/blob/main/Img/PhysicsBasedCNN.jpg?raw=true" alt="Naive CNN" style="width:100%">
<figcaption align = "center"><b>Physics based Deep Learning. </b></figcaption>
</figure>

Overall, the Physics-Based Deep Learning model is more accurate than the Naive Deep Learning Model as well as conventional image gradient-based methods.
<figure>
<img src="https://github.com/Riponcs/Cn2Estimation/blob/main/Img//PhysicsBasedCNN-Result.png?raw=true" alt="Naive CNN" style="width:100%">
<figcaption align = "center"><b>Performance of Physics based Deep Learning. </b></figcaption>
</figure>
