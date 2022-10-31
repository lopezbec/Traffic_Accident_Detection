# Machine Learning method for real-time accident detection in the Dominican Republic

## Abstract

The objective of this project is to develop a method based on Machine Learning algorithms to detect traffic accidents in real-time with the use of traffic cameras. Early accident detection systems can save lives because, after an accident, a quick medical response can mean the difference between life and death. In addition, these systems could mitigate the economic impact of accidents by reducing bottlenecks and possible secondary incidents. 

Although the existing 9-1-1 System allows detecting accidents and providing medical assistance faster than ever before, accident detection technologies could help the system improve its response time and reduce its costs. Unfortunately, existing accident detection methods tend to have low accuracy and high levels of false alarm in complex urban environments, such as those prevailing in the Dominican Republic. Given these limitations and the impact that accident detection systems will have on the Dominican society, this project aims to develop a hybrid multistage method based on Machine Learning and Deep Neural Network algorithms. This method will help detect accidents in real-time, helping save lives, reduce bottlenecks, and reduce the economic impact of accidents. In addition, this proposal will help develop talent in the area of Artificial Intelligence, which is scarce in the Dominican Republic, despite the fact that it has been postulated as an essential area for technological innovation.

The slides that provide an overview of the project and its objectives can be found [HERE](https://sites.lafayette.edu/lopezbec/files/2020/04/20191208-Propuesta-de-Deteccion-de-Accidentes-FONDOCYT-CL-AA-VC-RV_v1.pdf)

You can watch a video of the implementation of an object detection algorithm on video footage of accidents from the Dominican Republic: **Viewer discretion is advised!**( [videos](https://www.youtube.com/watch?v=MZTDC0jko1E&feature=youtu.be)) 


___________________________________________________

# Algorithms and Models implementation
___________________________________________________
## Object Detection and Object Tracking

### Yolov3 with Deepsort: 
Click the link bellow to run the [Yolov3]( https://github.com/ultralytics/yolov3) Object detection with [DeepSort]( https://github.com/nwojke/deep_sort)  Object Tracking directly in Google Collab (no coding needed, just clicking and runing) 

<table align="left">
  <td>
    <a target="_blank" href="https://colab.research.google.com/github/lopezbec/Traffic_Accident_Detection/blob/master/Yolov3_DeepSort/GPU/Implementation_Object_tracker.ipynb"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run Yolov3 + DeepSort in Google Colab</a>
  </td>
</table>
<br></br>

### MaskRCNN: 
Click the link bellow to run the [MaskRCNN](https://github.com/matterport/Mask_RCNN) Object detection directly in Google Collab (no coding needed, just clicking and runing) 

<table align="left">
  <td>
    <a target="_blank" href="https://colab.research.google.com/github/lopezbec/Traffic_Accident_Detection/blob/master/MaskRCNN-ODS/video_detection_run.ipynb"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run MaskRCNN in Google Colab</a>
  </td>
</table>
<br></br>

___________________________________________________

## Anomaly Detection

### Fast Unsupervised Anomaly Detection for Traffic Videos Implementation (2nd Place AI City Challenge 2020)
Click the link bellow to run the [Fast Unsupervised Anomaly Detection for Traffic Videos Implementation](https://github.com/kevaldoshi17/NVIDIA_AICITY) for anomaly detectiondirectly in Google Collab (no coding needed, just clicking and runing) 

<table align="left">
  <td>
    <a target="_blank" href="https://colab.research.google.com/github/lopezbec/Traffic_Accident_Detection/blob/master/Anomaly_Detection_Models/Fast_Unsupervised_Anomaly_Detection_Traffic_Videos_Implementation.ipynb"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run Fast Unsupervised Anomaly Detection for Traffic Videos in Google Colab</a>
  </td>
</table>
<br></br>

### Fractional Data Distillation Model for Anomaly Detection Traffic Videos (3rd Place AI City Challenge 2020)
Click the link bellow to see the code implementation for the [Fractional Data Distillation Model for Anomaly Detection Traffic Videos](https://github.com/cetcvlab/AICity-2020-CETCVLAB) for anomaly detection directly. Due to the computational complexity of this model, it cannot be fully run in free version of Google Colab (see notes)

<table align="left">
  <td>
    <a target="_blank" href="https://colab.research.google.com/github/lopezbec/Traffic_Accident_Detection/blob/master/Anomaly_Detection_Models/Fractional_Data_Distillation_Model_for_Anomaly_Detection_Traffic_Videos.ipynb"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run Fractional Data Distillation Model for Anomaly Detection Traffic Videos in Google Colab</a>
  </td>
</table>
<br></br>



### iTASK - Intelligent Traffic Analysis Software Kit-Anomaly Detections  (AI City Challenge 2020)
Click the link bellow to see the code implementation for the [iTASK - Intelligent Traffic Analysis Software Kit](https://github.com/selab-hcmus/AI_City_2020) for anomaly detection directly. Due to the models code limitations, it cannot be used with videos that are not part of the AI City Challenge (see notes)

<table align="left">
  <td>
    <a target="_blank" href="https://colab.research.google.com/github/lopezbec/Traffic_Accident_Detection/blob/master/Anomaly_Detection_Models/iTASK_Intelligent_Traffic_Analysis_Software_Kit_Anomaly_Detection.ipynb#scrollTo=eRdy5zbjJVtD"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run iTASK - Intelligent Traffic Analysis Software Kit-Anomaly Detections in Google Colab</a>
  </td>
</table>
<br></br>

___________________________________________________


# Traffic accident simulator for generating synthetic traffic video data
___________________________________________________

Given the limited available of traffic footage of complex urban environment that contain traffic accidents, the team is exporting the use of a traffic accident simulator to generate a large synthetic dataset of video that contain traffic accidents. This idea still in development as you can see from the video below. The team is working on making the simulation more realistic, by improving the physics and adding more object to the simulations. 


<div class="figure">
<img src="https://github.com/lopezbec/Traffic_Accident_Detection/blob/master/Traffic_Simulation.jpg" width="90%" />
</div>

## Latest version 


<div class="figure">
<img src="https://github.com/lopezbec/Traffic_Accident_Detection/blob/master/Traffic_Simulation.jpg" width="90%" />
</div>


#### https://youtu.be/TMOxRQqsbgA
#### https://youtu.be/U1jcL2GEOYQ


___________________________________________________
## References of Project Publications

1.	Naphade, M., Wang, S., Anastasiu, D.C., Tang, Z., Chang, M.C., Yang, X., Yao, Y., Zheng, L., Chakraborty, P., Lopez, C.E. and Sharma, A., “The 5th AI City Challenge”. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition, Virtual Conference, June 19-25, ([PDF](https://openaccess.thecvf.com/content/CVPR2021W/AICity/html/Naphade_The_5th_AI_City_Challenge_CVPRW_2021_paper.html))

2.	Vasu, M.,  Lopez, C. E.,  “Vehicle-counting with automatic Region-of-Interest and Driving-Trajectory detection” LatinXAI Workshops at Int. Conference on Machine Learning, 2021.(see [PDF](https://research.latinxinai.org/papers/icml/2021/pdf/paper_33.pdf) and [presentation](https://slideslive.com/38962858/vehiclecounting-with-automatic-regionofinterest-and-drivingtrajectory-detection?ref=account-folder-87716-folders))
	
## Support and collaboration

This project is supported by the National Fund for Innovation and Scientific and Technological Development (FONDOCyT for its acronym in Spanish) from the  Ministry of Higher Education, Science and Technology of the Dominican Republic (FONDOCYT 2018-19-3A1-107). The project is in collaboration with the Universidad Autonoma de Santo Domingo (UASD).

