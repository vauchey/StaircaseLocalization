
## Industrial Staircase location (IROS2020)
The project ARGOS Viking, one of the objectives of which was to cross a staircase whose position and characteristics were designed, allowed us to have a reliable crossing algorithm. After this project, the objectify was to detect and rally one staircase unknown. The staircase detection is used to help elderly people move around, to prevent them from falling down the stairs. Or in robotic, it is using for crossing stairs as well as for humanoid robots as for robots equipped with tracks. Most of these methods use a lengthwise camera, but the angle camera using was height, but the height of the camera does not allow to have such an angle since it is at the height of the step. The proposed solution was used an RGB-D camera, mainly the depth. This choice was made rather than a LIDAR, because of the stairs without risers. Indeed, the steps of this type of staircase can pass between two layers of the LIDAR. We will first expose the algorithm used, we will then see the qualification method, to finally finish on the results obtained.

[![](https://img.youtube.com/vi/wie3POxmbGI/1.jpg)](https://www.youtube.com/watch?v=wie3POxmbGI)


Jérémy FOURRE¹, Yohan DUPUIS¹, Vincent VAUCHEY¹, Xavier SAVATIER¹.  
¹[ESIGELEC](http://www.esigelec.fr/) , IRSEEM, Rouen, France, Normandie Univ, UNIROUEN,   

fourre@esigelec.fr
dupuis@esigelec.fr
vauchey@esigelec.fr
savatier@esigelec.fr


# Datasets
Dataset RGBD Camera done by [ESIGELEC](http://www.esigelec.fr/)


List of sensors and software used :
* D435 trigged on IMU ([intelrealsense](https://www.intelrealsense.com/depth-camera-d435))
* RTMAPS ([Intempora](https://intempora.com/)) Realtime acquisition software (can also be used to replay datasets)
* [VICON](https://www.vicon.com/) positionning system use as reference
![](images/20200213_175111.jpg )

Result obtained on industrial staircase with no riser and drilled tread :
![](images/3dESCFER.png )

