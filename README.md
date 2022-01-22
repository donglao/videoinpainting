# Flow-guided Video Inpainting With Scene Template

This is the demo code for 'Flow-guided Video Inpainting With Scene Template (ICCV 2021)'. We propose a flow-based solution to video inpainting by introducing the scene template, a 2D representation of the scene based on a layered formulation. This reduces geometric distortions in flow-based inpainting, creating consistent and crisp inpaintings results.

[![Demo Video](pics/thumbnail.png)](https://youtu.be/v8YZ7X6NChQ)
  
Now a [Matlab demo](https://drive.google.com/file/d/1sj1ef5BzlSKK9qwFE37l89Hsgw2ZI1yt/view?usp=sharing) can be downloaded from Google Drive. The code is configured for Matlab + Ubuntu due to its dependency of SobolevFlow (Mex/C++ on Linux). You may also play around by using pre-computed flow as initialization, or disable SobolevFlow (which will significantly reduce performance). I am working on migrating the code into python + pytorch.

An [evaluation toolbox](https://drive.google.com/file/d/1Z_vrebbz23E6URknGG-sWjiDFs7vTa7M/view?usp=sharing) can be downloaded to measuring temporal consistency of inpainted regions.


## Fun Stuff
![Fun stuff](pics/fun.gif)
