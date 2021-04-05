# MRI based Diagnosis of Rotator Cuff Tears using Deep Learning and Weighted Linear Combinations

![RCT_description](images/RCT_description.png?raw=true "RCT_description")


## Introduction 

Rotator Cuff Tears (RCTs) are a common injury among people who are middle-aged or older. For effective diagnosis of RCTs, orthopedic surgeons typically need to have access to both shoulder Magnetic Resonance Imaging (MRI) and proton density-weighted imaging. However, the generation and interpretation of such comprehensive image information is labor intensive, and thus time consuming and costly. Although computer-aided diagnosis can help in mitigating the aforementioned issues, not much computational tools are currently available for diagnosing RCTs. Furthermore, it is hard to find the shoulder MRI dataset publicly available for research purposes. By releasing our shoulder MRI dataset of 2,447 T2-weighted coronal scans, we hope to facilitate further research efforts and ease of benchmarks.


## About dataset

The number of total data is 2,447 and is classified into 3 imbalanced classes. Each class name, number, and rate information are as follows.

<ul>
  <li>Normal (1,628, 67%)</li>
  <li>Partial-thickness tear (157, 6%)</li>
  <li>Full-thickness tear (662, 27%)</li>
</ul>


Each data contains 16 image files of 512x512 size. Those are the (coronally) sliced images of a 3-D T2 MRI. The physical gap between each image is known to be about 2mm. Sample image stream for each class is as follows. (Normal, Partial-thickness tear, followed by Full-thickness tear)

![RCT_description](images/normal.png?raw=true "RCT_description")
![RCT_description](images/partial.png?raw=true "RCT_description")
![RCT_description](images/full.png?raw=true "RCT_description")



## Download dataset

Readers who want to contribute to the MRI based Computer Aided Rotator Cuff Tears Diagnosis can get the download link at the following address.

https://forms.gle/52MK9wJVokmrKb8z5



## Citation 

Readers may use the following information to cite our research and the datasets used in it.

Kim, M., Park, H., Kim, J.Y., Kim, S.H., Hoeke, S. & De Neve, W.. (2020). MRI-based Diagnosis of Rotator Cuff Tears using Deep Learning and Weighted Linear Combinations. Proceedings of the 5th Machine Learning for Healthcare Conference, in PMLR 126:292-308
