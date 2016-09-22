---
layout: page
permalink: /datasets/
---

----------------------------------------------------------------
<h2>Solar Panel Dataset</h2>
----------------------------------------------------------------

<div style="text-align: center">
<img src="http://eavise.be/SolarPanelDataset/VJ.png" height="200" /> <img src="http://eavise.be/SolarPanelDataset/ACF.png" height="200" />
</div>

<p style='text-align: justify;'>
The EAVISE Solar Panel Dataset consists a solar panel training set, containing 2500 solar panel annotations and a larger image 16000x16000 aerial image with solar panels blacked out, containing the 150000 negatives random samples collected for model training. We also provide a test image of a single 2x2km urban area (Sint-Truiden, Belgium) with a resolution of 25cm/pixel combined with solar panel installation annotations. The image has an original resolution of 8000x8000 pixels but was upscaled using bicubic interpolation to a resolution of 16000x16000 pixels to provide enough pixel information per individual solar panel (19x14 pixels).
</p>

<p style='text-align: justify;'>
<i>The data was originally supplied by <a href="http://www.agiv.be/">AGIV</a>, as part of the publicly available medium-scale aerial footage of Flanders.</i>
</p>

<p style='text-align: justify;'>
Positive training dataset can be downloaded <a href="http://eavise.be/SolarPanelDataset/positives.zip">here</a>.<br>
Negative training image can be downloaded <a href="http://eavise.be/SolarPanelDataset/negative.zip">here</a>.<br>
Annotations can be downloaded <a href="http://eavise.be/SolarPanelDataset/ground_truth_positives.txt">here</a>.
</p>

<p style='text-align: justify;'>
If you plan to use this dataset, we require you to cite the following publication: 2016; <i>Detection of solar panel installations in RGB aerial imaging: a comparative study.</i>; <b>Puttemans S, Van Ranst W, Goedem&#233; T</b>; Proceedings of GEOBIA2016; published; Enschede, The Netherlands; 14-16 September 2016.
</p>


----------------------------------------------------------------
<h2>Mobile Mapping Dataset</h2>
----------------------------------------------------------------

<div>
<img src="http://eavise.be/MobileMappingDataset/sets.png" />
</div>

<p style='text-align: justify;'>
The EAVISE Mobile Mapping Dataset consists of two mobile mapping datasets, which are made publicly available, to encourage further research in this area.
</p>

<h3>Dataset 1: Urban area in the Netherlands.</h3>

<p style='text-align: justify;'>
The first dataset is a series of mobile mapping cycloramic images, captured using a <b>LadyBug 1 camera setup</b> , in a quiet and calm urban area in the Netherlands. The captured images give a full 360 degree view from the surroundings of the car at any given position. The camera itself is fixed and mounted on the top of the roof of the car. The set has <b>450</b> images under daylight conditions with a resolution of <b>4800x2400</b> pixels with a total size of <b>1.4GB</b>. The dataset is used to develop and fine-tune the suggested approach.
</p>

<p style='text-align: justify;'>
Dataset 1 can be downloaded <a href="http://eavise.be/MobileMappingDataset/dataset1.zip">here</a>.<br>
Annotations can be downloaded <a href="http://eavise.be/MobileMappingDataset/ground_truth_dataset1.txt">here</a>.
</p>

<p style='text-align: justify;'>
<i>This dataset was supplied by <a href="http://www.vansteelandt.be/">Vansteelandt BVBA</a>.</i>
</p>

<h3>Dataset 2: Belgian train and bus station.</h3>

<p style='text-align: justify;'>
The second dataset was captured using a </b> LadyBug 2 camera</b> , having a resolution of <b> 8000x4000</b>  pixels, again mounted on top of the roof of the car, containing <b>45</b> images of a train and bus station in Belgium with a total size of <b>110MB</b>. We used this dataset to prove that the developed approach is independent of the application-specific settings like camera setup and application environment, except for defining the actual height-position relation used to improve the detection success rate.
</p>

<p style='text-align: justify;'>
Dataset 2 can be downloaded <a href="http://eavise.be/MobileMappingDataset/dataset2.zip">here</a>.<br>
Annotations can be downloaded <a href="http://eavise.be/MobileMappingDataset/ground_truth_dataset2.txt">here</a>.
</p>

<p style='text-align: justify;'>
<i>This dataset was supplied by <a href="http://www.grontmij.be/EN/Pages/default.aspx">Grontmij Belgium</a>.</i>
</p>

<p style='text-align: justify;'>
If you plan to use this dataset, we require you to cite the following publication: 2016; <i>Safeguarding Privacy by Reliable Automatic Blurring of Faces in Mobile Mapping Images</i>; <b>Puttemans S, Goedem&#233; T, Vanwolputte S</b>; Proceedings of VISAPP2016; published; VISAPP; 11; Rome, Italy; 27-29 February 2016.
</p>

----------------------------------------------------------------
