Download Link: https://assignmentchef.com/product/solved-ee5175-lab4-shape-from-focus
<br>
The amount of blur due to optical defocussing depends on the distance between camera and scene. Hence it is possible to use blur as a cue to determine the depth of a particular point in the scene.

In this experiment, you are given a set of images which are captured using different camera lens settings, thus resulting in different degrees of optical blur. Use these images to determine the depth of each pixel in the image using the shape from focus (SFF) algorithm discussed in class. Display the 3D structure of the scene using the calculated depth values.

Use sum-modified Laplacian (SML) operator as focus measure and ∆<em>d</em><em>=</em>50.50. Observe the output 3D structure for <em>q</em><em>=</em>0,1 and 2, where <em>q </em>is the size of the neighbourhood for the SML window as defined in class. Comment on your observations.

<strong>Files</strong>: stack.mat contains 100 images with variable names from ‘frame001’ to ‘frame100’.

<strong>Matlab usage</strong>:   <strong>Scilab usage</strong>: To load mat file:   To load mat file: load ‘stack.mat’; loadmatfile(‘stack.mat’);

To read 15th image:                                            To read 15th image:

img = eval([‘frame’ sprintf(‘%.3d’,15)]); img = evstr(‘frame’ + msprintf(‘%.3d’,15));

–end–