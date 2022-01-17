# Image-Colorization
This is an ongoing project and is to be updated.

# Baseline Architecture
We have made a simple U-Net architecture employing first two layers of ResNet50 network(pre-trained on imagenet) as Encoder.
</br>
In the decoder section we have used Upsampling layers to avoid checkerboard artifacts.
</br>
</br>
<img src="figures/Color_Model.png">

# BASELINE Results
These are the results we have obtained from our basline model on the Flicker Faces Dataset. As it is evident the architecture is capable of modeling decent color aesthetics while witholding quality of image.
</br>
</br>

<h3 align="center"> Predicted Colors </h3>
<img src="figures/color_output.png">
<h3 align="center"> True Colors </h3>
<img src="figures/true_color.png">
