
# Industrial Staircase location (IROS2020)

![](images/gifFer.gif )



### Abstract
This paper presents an industrial staircase localization algorithm based on RGBD data from a tracked robot. This situation is really challenging as the camera is placed close to the ground. Moreover, RGBD can be really noisy on sparse staircases. Contrary to existing works, our evaluation relies on ground truth data provided by a motion capture system. Our experiments suggest that our algorithm can robustly locate industrial staircase. We also propose a new framework to evaluate stair localization performance from RGBD data. The overall performance allows to safety control a robot to rally the staircase.


[![](https://img.youtube.com/vi/wie3POxmbGI/1.jpg)](https://www.youtube.com/watch?v=wie3POxmbGI)




Jérémy FOURRE¹, Yohan DUPUIS¹, Vincent VAUCHEY¹, Xavier SAVATIER¹.  
¹[ESIGELEC](http://www.esigelec.fr/) , IRSEEM, Rouen, France, Normandie Univ, UNIROUEN,   

fourre@esigelec.fr
dupuis@esigelec.fr
vauchey@esigelec.fr
savatier@esigelec.fr


### Datasets
Dataset RGBD Camera done by [ESIGELEC](http://www.esigelec.fr/)


List of sensors and software used :
* D415 trigged on IMU ([intelrealsense](https://www.intelrealsense.com/depth-camera-d435))
* RTMAPS ([Intempora](https://intempora.com/)) Realtime acquisition software (can also be used to replay datasets)
* [VICON](https://www.vicon.com/) positionning system use as reference
![](images/20200213_175111.jpg )

Result obtained on industrial staircase with no riser and drilled tread :
![](images/3dESCFER.png )

