---
layout: page
permalink: /publications/
---

----------------------------------------------------------------

## Publications in 2015

----------------------------------------------------------------

### Automated Walking Aid Detector Based on Indoor Video Recordings

![]({{ site.url }}/images/walker.png)

*Presented at EMBC2015, Milan, Italy.*

Due to the rapidly aging population, developing automated home care systems is a very important step in taking care of elderly people. This will enable us to automatically monitor the health of senior citizens in their own living environment and prevent problems before they happen. One of the challenging tasks is to actively monitor walking habits of elderlies, who alternate between the use of different walking aids, and to combine this with automated fall risk assessment systems. We propose a camera based system that uses object categorization techniques to robustly detect walking aids, like a walker, in order to improve the classification of the fall risk. By automatically integrating the application specific scenery knowledge like camera position and used walker type, we succeed in detecting walking aids within a single frame with an accuracy of 68% for trajectory A and 38% for trajectory B. Furthermore, compared to current state of the art detection systems, we use a rather limited set of training data to achieve this accuracy and thus create a system that is easily adaptable for other applications. Moreover, we applied spatial constraints between detections to optimize the object detection output and to limit the amount of false positive detections. Finally, we evaluate the output on a walking sequence base, leading up to a 92.3% correct classification rate of walking sequences. It can be noted that adapting this approach to other walking aids, like a walking cane, is quite straightforward and opens up the door for many future applications.

*Download paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/499873/1/EMBC2015.pdf).*

### Visual Detection and Species Classification of Orchid Flowers

![]({{ site.url }}/images/orchid.png)

*Presented at MVA2015, Tokyo, Japan.*

The goal of this research is to investigate the possibility of using object categorization and object classification techniques in an industrial context with a very limited set of training data. As an industrial application of the proposed techniques we investigate the case of orchid flower detection and orchid species classification in an orchid packaging plant. Due to their large variety of colors and patterns, these orchid flowers are very hard to detect with classic segmentation based techniques but form an ideal test case for object categorization techniques. Due to the limited amount of training data available, we aim at building a system with close to no false positive detections but guaranteeing that each orchid plant still returns a single flower detection. Subsequently the detected flowers are passed towards a classification system of linear binary SVM classifiers trained on visual characteristics of the flowers. To increase the classification success rate, we combined results of single flowers, using majority voting, to reach an orchid plant based classification. The complete pipeline is optimized by effectively using the industrial application specific knowledge of the setup. By implementing this approach we prove that industrial object categorization and classification with high accuracy is possible, even if only a small training dataset is available.

*Download paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/499870/1/14-22.pdf).*

----------------------------------------------------------------

## Publications in 2014

----------------------------------------------------------------

### Optimal object categorization under application specific conditions + Extended Journal Version

![]({{ site.url }}/images/optimal.png)

*Presented at VISAPP2014, Lissabon, Portugal.*

*Published in Journal of Communication and Computer, edition 10, pages 1484-1496.*

Day-to-day industrial computer vision applications focusing on object detection have the need of robust, fast and accurate object detection techniques. However, current state-of-the-art object categorization techniques only reach about 85% detection rate when performing in the wild detections who try to cope with as much scene and object variation as possible. However several industrial applications show many known characteristics like constant lighting, known camera position, constant background, … giving lead to several constraints on the actual algorithms. With a complete new universal object categorization framework, we want to prove the detection rate of these object categorization algorithms by exploiting the application specific knowledge which can help to reach a robust detector with detection rates of 99.9% or higher. We will use the same constraints to effectively reduce the number of false positive detections. Furthermore we will introduce an innovative active learning system based on this application specific knowledge that will drastically reduce the amount of positive and negative training samples, leading to a shorter and more effective annotation and training phase.

*Download paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/435081/2/paper+doctoral+consortium.pdf).*

*Download extended paper by clicking [here](http://www.davidpublishing.com/DownLoad/?id=16291).*

----------------------------------------------------------------

## Publications in 2013

----------------------------------------------------------------

### How to exploit scene constraints to improve object categorization algorithms for industrial applications?

![]({{ site.url }}/images/constraints.png)

*Presented at VISAPP2013, Barcelona, Spain.*

State-of-the-art object categorization algorithms are designed to be heavily robust against scene variations like illumination changes, occlusions, scale changes, orientation and location differences, background clutter and object intra-class variability. However, in industrial machine vision applications where objects with variable appearance have to be detected, many of these variations are in fact constant and can be seen as constraints on the scene, which in turn can reduce the enormous search space for object instances. In this position paper we explore the possibility to fixate certain of these variations according to the application specific scene constraints and investigate the influence of these adaptations on three main aspects of object categorization algorithms: the amount of training data needed, the speed of the detection and the amount of false detections. Moreover, we propose steps to simplify the training process under such scene constraints.

*Download paper by clicking [here](http://eavise.be/papers/VISAPP2013.pdf).*

----------------------------------------------------------------

## Publications in 2011

----------------------------------------------------------------

### Weighted multi-method user identification in gaming applications

![]({{ site.url }}/images/identification.png)

In this paper, considerations and methodology for user identification in gaming applications is discussed. Typical user identification processes operate through input devices that yield qualitative audio and video data in a controlled environment. In gaming applications, low cost hardware and uncontrolled environmental conditions pose a serious obstacle towards efficient user identification. Through a combination of several methods, including speaker recognition, facial feature extraction and the eigenface recognition approach for face recognition, a robust algorithm can be developed. Weighing the relative importance of each method leads to more robust recognition, despite the limitations associated with the application.

*Download paper by clicking [here](https://lirias.kuleuven.be/bitstream/123456789/390669/1/Weighted+multi-method+user+identification+in+gaming+applications.pdf).*

----------------------------------------------------------------