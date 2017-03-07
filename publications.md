---
layout: page
permalink: /publications/
---

----------------------------------------------------------------

## Publications in 2017

----------------------------------------------------------------

### Improving Open Source Face Detection by Combining an Adapted Cascade Classification Pipeline and Active Learning

![]({{ site.url }}/images/face_detection.png)

*Presented at VISAPP2017, Porto, Portugal.*

<p style='text-align: justify;'>
Recent advances in computer vision have almost solved the problem of in the wild face detection, using complex techniques like convolutional neural networks. On the contrary many open source computer vision frameworks like OpenCV have not yet made the switch to these complex techniques and tend to depend on well established algorithms for face detection, like the cascade classification pipeline suggested by Viola and Jones. However the accuracy of these open source face detection models on public datasets like FDDB stays rather low, mainly due to the relatively high number of false positive detections produced. We propose several adaptations to the current existing LBP/AdaBoost cascade classification pipeline of OpenCV. This is done by improving the training sample generation and annotation procedure, and by applying an active learning strategy. This boosts the accuracy of in the wild face detection on the FDDB dataset quite drastically, closing the gap towards the accuracy levels gained by state-of-the-art CNN-based face detectors. The proposed changes allow us to provide a new face detection model to the OpenCV framework, achieving a remarkably high precision at an acceptable recall rate, offering a model that ensures detected faces are actually faces, a critical requirement for further processing pipelines like person identification, etc.
</p>

*The associated detection model (IterativeHardPositives+ model in paper) for this publication can be found [here](https://github.com/StevenPuttemans/opencv/blob/master/data/lbpcascades/lbpcascade_frontalface_improved.xml).*

*Download the paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/560283/2/VISAPP2017.pdf).*

*Download the poster presentation by clicking [here]({{ site.url }}/presentations/VISIGRAPP2017poster.pdf).*

----------------------------------------------------------------

## Publications in 2016

----------------------------------------------------------------

### How to reach top accuracy for a visual pedestrian detection warning system from a car?

![]({{ site.url }}/images/LWIR.png)

*Presented at IPTA2016, Oulu, Finland.*

<p style='text-align: justify;'>
Due to the wide applicability of pedestrian detection
in surveillance and safety, this research topic has received much attention in computer vision literature. However, the focus of this research mainly lies in detecting and locating pedestrians individually as accurate as possible. In recent years, a number of datasets are captured using a forward looking camera from a car, which imposes the application of warning the driver when pedestrians are in front of the car. For such applications, it is not required to detect each pedestrian independently, but to generate an alarm when necessary. In this paper we explore techniques to boost the accuracy of recent channel-based algorithms in this application: algorithmic refinements as well as the inclusion of an LWIR image channel. We use the KAIST dataset which is constructed from image-pairs of both the visual and the LWIR spectrum, in day and night conditions. We study the influence of techniques that have shown success in literature.
</p>

*Download the paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/562021/1/40_paper_fds.pdf).*

*Download the 15 min oral presentation by clicking [here]({{ site.url }}/presentations/IPTA2016FDS.pdf).*

### Automated Visual Fruit Detection for Harvest Estimation and Robotic Harvesting

![]({{ site.url }}/images/fruit_detection.png)

*Presented at IPTA2016, Oulu, Finland.*

<p style='text-align: justify;'>
A fully automated detection and localisation of fruit in orchards is a key component of automatic robotic harvesting
systems, still a dream of many farmers around the world to cope with large production and personnel costs. In the past years
a lot of research on this topic has been performed, using very basic computer vision techniques, like colour based segmentation,
as a possible solution. When not using standard RGB cameras, research tends to resort to other sensors, like hyper spectral or
3D. However more recent advances in computer vision got a broad range of more advanced object detection techniques that
could improve the quality of fruit detection from RGB images drastically. We suggest to use a object categorisation technique
based on a boosted cascade of weak classifiers to implement a fully automated semi-supervised fruit detector and demonstrate it
on strawberries and apples. Compared to existing techniques we improve single object instance detection in fruit clusters, using a supervised machine learning instead of hand crafting image filters specific to the application. Moreover we integrate application specific colour information to ensure a more stable output of our fully automated detection algorithm. The developed technique is validated on strawberries and apples and is proven to have large benefits in the field of automated harvest and crop estimation.
</p>

*Download the paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/546316/3/IPTA2016_submission_camera_ready.pdf).*

*Download the 15 min oral presentation by clicking [here]({{ site.url }}/presentations/IPTA2016SPU.pdf).*

### Detection of Photovoltaic Installations in RGB Aerial Imaging: a Comparative Study.

![]({{ site.url }}/images/solar_panels.png)

*Presented at GEOBIA2016, Enschede, The Netherlands.*

<p style='text-align: justify;'>
In this work, we compare four different approaches for detecting photovoltaic installations from RGB aerial images. Our client, an electricity grid administrator, wants to hunt down fraud with unregistered illegal solar panel installations by detecting installations in aerial imagery and checking these against their database of registered installations. The detection of solar panels in these RGB images is a difficult task. Reasons are the relatively low resolution (at 25 cm/pixel an individual solar panel only measures about 9 × 7 pixels), the undiscriminating colour properties of the object (due to in-class variance and specular effects) and the apparent shape variability (rotation and skew due to the different roofs slant angles). Therefore, straightforward object segmentation techniques do not yield a satisfying solution, as proven in this paper. We compared four state-of-the-art object detection approaches for this task. First we experimented with a machine learning object detection technique based on pixel-based support vector machine classification. Secondly we developed an approach using MSER based colour segmentation and shape analysis. Finally a dual approach based on object categorization using the boosted cascade classifier technique of Viola & Jones and the aggregate channel features technique of Dollar et al., is introduced, learning a combination of colour and gradient feature based classifiers from a given training set. We successfully evaluate these four different approaches on a fully labelled test set of a 8000 × 8000 pixel, 4 square km zone containing 315 solar panel installations with in total more than 10.000 individual panels.
</p>

*Download the paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/546313/1/submission_final2.pdf).*

*Download the 20 min oral presentation by clicking [here]({{ site.url }}/presentations/GEOBIA2016.pdf).*

*The publicly made available training dataset can be found [here](http://eavise.be/SolarPanelDataset/).*

### Safeguarding Privacy by Reliable Automatic Blurring of Faces in Mobile Mapping Images

![]({{ site.url }}/images/masking.png)

*Presented at VISIGRAPP2016, Rome, Italy.*

<p style='text-align: justify;'>
When capturing images in the wild containing pedestrians, privacy issues remain a concern for industrial applications. Our application, collecting cycloramic mobile mapping data in crowded environments, is an example of this. If the data is processed and accessed by third parties, privacy of individuals inside the data must be ensured. This is where pedestrian detectors come into play, used to detect individuals and make them privacy safe through blurring. However the problem of undesired false positive detections, typical for pedestrian detectors and unavoidable, still leaves undesired areas of the images being blurred. We tackled this problem by using application specific scene constraints, under the form of a scale-space mapping based on the pedestrian detector’s training data, combined with reducing the field of interest and a specific false positive elimination classifier. Furthermore we applied a technique called soft blurring to avoid the artificial look of simply applying a Gaussian blur to the found detections, which resulted in an effective full-automatic masking pipeline for privacy safeguarding in mobile mapping images. We prove that we can use pre-trained pedestrian detection models, but, based on a limited amount of application-specific annotations, we can boost the detection accuracy enormously by exploiting scene specific constraints.
</p>

*Download the paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/516446/2/VISAPP2016.pdf).*

*Download the 20 min oral presentation by clicking [here]({{ site.url }}/presentations/VISIGRAPP2016.pdf).*

*The publicly made available dataset can be found [here](http://eavise.be/MobileMappingDataset/).*

----------------------------------------------------------------

## Publications in 2015

----------------------------------------------------------------

### Automated Walking Aid Detector Based on Indoor Video Recordings

![]({{ site.url }}/images/walker.png)

*Presented at EMBC2015, Milan, Italy.*

<p style='text-align: justify;'>
Due to the rapidly aging population, developing automated home care systems is a very important step in taking care of elderly people. This will enable us to automatically monitor the health of senior citizens in their own living environment and prevent problems before they happen. One of the challenging tasks is to actively monitor walking habits of elderlies, who alternate between the use of different walking aids, and to combine this with automated fall risk assessment systems. We propose a camera based system that uses object categorization techniques to robustly detect walking aids, like a walker, in order to improve the classification of the fall risk. By automatically integrating the application specific scenery knowledge like camera position and used walker type, we succeed in detecting walking aids within a single frame with an accuracy of 68% for trajectory A and 38% for trajectory B. Furthermore, compared to current state of the art detection systems, we use a rather limited set of training data to achieve this accuracy and thus create a system that is easily adaptable for other applications. Moreover, we applied spatial constraints between detections to optimize the object detection output and to limit the amount of false positive detections. Finally, we evaluate the output on a walking sequence base, leading up to a 92.3% correct classification rate of walking sequences. It can be noted that adapting this approach to other walking aids, like a walking cane, is quite straightforward and opens up the door for many future applications.
</p>

*Download the paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/499873/1/EMBC2015.pdf).*

*Download the poster presentation by clicking [here]({{ site.url }}/presentations/EMBC2015poster.pdf).*

### Visual Detection and Species Classification of Orchid Flowers

![]({{ site.url }}/images/orchid.png)

*Presented at MVA2015, Tokyo, Japan.*

<p style='text-align: justify;'>
The goal of this research is to investigate the possibility of using object categorization and object classification techniques in an industrial context with a very limited set of training data. As an industrial application of the proposed techniques we investigate the case of orchid flower detection and orchid species classification in an orchid packaging plant. Due to their large variety of colors and patterns, these orchid flowers are very hard to detect with classic segmentation based techniques but form an ideal test case for object categorization techniques. Due to the limited amount of training data available, we aim at building a system with close to no false positive detections but guaranteeing that each orchid plant still returns a single flower detection. Subsequently the detected flowers are passed towards a classification system of linear binary SVM classifiers trained on visual characteristics of the flowers. To increase the classification success rate, we combined results of single flowers, using majority voting, to reach an orchid plant based classification. The complete pipeline is optimized by effectively using the industrial application specific knowledge of the setup. By implementing this approach we prove that industrial object categorization and classification with high accuracy is possible, even if only a small training dataset is available.
</p>

*Download the paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/499870/1/14-22.pdf).*

*Download the poster presentation by clicking [here]({{ site.url }}/presentations/MVA2015poster.pdf).*

----------------------------------------------------------------

## Publications in 2014

----------------------------------------------------------------

### Optimal object categorization under application specific conditions + Extended Journal Version

![]({{ site.url }}/images/optimal.png)

*Presented at VISAPP2014, Lissabon, Portugal.*

*Published in Journal of Communication and Computer, edition 10, pages 1484-1496.*

<p style='text-align: justify;'>
Day-to-day industrial computer vision applications focusing on object detection have the need of robust, fast and accurate object detection techniques. However, current state-of-the-art object categorization techniques only reach about 85% detection rate when performing in the wild detections who try to cope with as much scene and object variation as possible. However several industrial applications show many known characteristics like constant lighting, known camera position, constant background, … giving lead to several constraints on the actual algorithms. With a complete new universal object categorization framework, we want to prove the detection rate of these object categorization algorithms by exploiting the application specific knowledge which can help to reach a robust detector with detection rates of 99.9% or higher. We will use the same constraints to effectively reduce the number of false positive detections. Furthermore we will introduce an innovative active learning system based on this application specific knowledge that will drastically reduce the amount of positive and negative training samples, leading to a shorter and more effective annotation and training phase.
</p>

*Download the paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/435081/2/paper+doctoral+consortium.pdf).*

*Download the 20 min oral presentation of the doctoral consortium by clicking [here]({{ site.url }}/presentations/VISIGRAPP2014.pdf).*

*Download the poster presentation by clicking [here]({{ site.url }}/presentations/VISIGRAPP2014poster.pdf).*

*Download the extended journal paper by clicking [here](http://www.davidpublishing.com/DownLoad/?id=16291).*

----------------------------------------------------------------

## Publications in 2013

----------------------------------------------------------------

### How to exploit scene constraints to improve object categorization algorithms for industrial applications?

![]({{ site.url }}/images/constraints.png)

*Presented at VISAPP2013, Barcelona, Spain.*

<p style='text-align: justify;'>
State-of-the-art object categorization algorithms are designed to be heavily robust against scene variations like illumination changes, occlusions, scale changes, orientation and location differences, background clutter and object intra-class variability. However, in industrial machine vision applications where objects with variable appearance have to be detected, many of these variations are in fact constant and can be seen as constraints on the scene, which in turn can reduce the enormous search space for object instances. In this position paper we explore the possibility to fixate certain of these variations according to the application specific scene constraints and investigate the influence of these adaptations on three main aspects of object categorization algorithms: the amount of training data needed, the speed of the detection and the amount of false detections. Moreover, we propose steps to simplify the training process under such scene constraints.
</p>

*Download paper by clicking [here](http://eavise.be/papers/VISAPP2013.pdf).*

*Download the poster presentation by clicking [here]({{ site.url }}/presentations/VISIGRAPP2013poster.pdf).*

----------------------------------------------------------------

## Publications in 2011

----------------------------------------------------------------

### Weighted multi-method user identification in gaming applications

![]({{ site.url }}/images/identification.png)

<p style='text-align: justify;'>
In this paper, considerations and methodology for user identification in gaming applications is discussed. Typical user identification processes operate through input devices that yield qualitative audio and video data in a controlled environment. In gaming applications, low cost hardware and uncontrolled environmental conditions pose a serious obstacle towards efficient user identification. Through a combination of several methods, including speaker recognition, facial feature extraction and the eigenface recognition approach for face recognition, a robust algorithm can be developed. Weighing the relative importance of each method leads to more robust recognition, despite the limitations associated with the application.
</p>

*Download paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/390669/1/Weighted+multi-method+user+identification+in+gaming+applications.pdf).*

----------------------------------------------------------------
