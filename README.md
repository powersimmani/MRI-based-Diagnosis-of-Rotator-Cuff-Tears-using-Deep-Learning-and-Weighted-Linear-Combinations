!!!!! Sorry this git is not activated. the git is only used for testing at the moment. We will open the form after June. !!!!!


# MRI-based Diagnosis of Rotator Cuff Tears using Deep Learning and Weighted Linear Combinations

![RCT_description](images/RCT_description.png?raw=true "RCT_description")


## Introduction 

Rotator Cuff Tears (RCTs) are a common injury among people who are middle-aged or older. For effective diagnosis of RCTs, orthopedic surgeons typically need to have access to both shoulder Magnetic Resonance Imaging (MRI) and proton density-weighted imaging. However, the generation and interpretation of such comprehensive image information is labor intensive, and thus time consuming and costly. Although computer-aided diagnosis can help in mitigating the aforementioned issues, not many computational tools are currently available for diagnosing RCTs. Furthermore, it is hard to find a publicly available shoulder MRI dataset for research purposes. By releasing our shoulder MRI dataset of 2,447 T2-weighted coronal scans, we hope to facilitate further research efforts and ease of benchmarking.

## Dataset information

The total number of MRI scans is 2,447. These MRI scans have been classified into three imbalanced classes:

<ul>
  <li>Normal: 1,628 MRI scans (fraction: 67%)</li>
  <li>Partial-thickness tear: 157 MRI scans (fraction: 6%)</li>
  <li>Full-thickness tear: 662 MRI scans (fraction: 27%)</li>
</ul>

 Each MRI scan contains 16 images (slices) with a spatial resolution 512x512. These images denote the (coronally) sliced images of a 3-D T2 MRI scan. The physical gap between two such images is about 2mm. The sample image stream for each class is as follows: normal, partial-thickness tear, and full-thickness tear.

![RCT_description](images/normal.png?raw=true "RCT_description")
![RCT_description](images/partial.png?raw=true "RCT_description")
![RCT_description](images/full.png?raw=true "RCT_description")



## Download information 

Readers who want to contribute to MRI-based computer-aided diagnosis of rotator cuff tears can get the download link using the following URL:

https://forms.gle/52MK9wJVokmrKb8z5

Note that the dataset comes with a size of 7.96 GB.



## Citation 

Readers may use the following information to cite our research and the dataset.

Kim, M., Park, H., Kim, J.Y., Kim, S.H., Hoecke, S. & De Neve, W. (2020). MRI-based Diagnosis of Rotator Cuff Tears using Deep Learning and Weighted Linear Combinations. Proceedings of the 5th Machine Learning for Healthcare Conference, in PMLR 126:292-308


##### The original paper can be found in the following URL

http://proceedings.mlr.press/v126/kim20a.html
