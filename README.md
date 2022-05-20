# Hyperspectral Change Detection Dataset Irrigated Agricultural Area
A hyperspectral data set can be used for testing binary and multi-class change detection techniques.

## File Description
All the files are in .mat format that can be loaded in Matlab.

**_PreImg_2004_:** Pre-processed Hyperion image acquired on May 1, 2004;

**_PostImg_2007_:** Pre-processed Hyperion image acquired on May 8, 2007;

**_Reference_Map_Binary_:** A binary reference map for evaluting the binary change detection performance (Two classes: change and no-change).

**_Reference_Map_Multiclass_:** A multiclass reference map for evaluting the multiclass change detection performance (Seven classes: six change classes and no-change).

## Data Set Description
This dataset is made up of a pair of bitemporal hyperspectral images acquired by the Hyperion sensor mounted on board the EO-1 satellite on May 1, 2004 and May 8, 2007. The study area is an irrigated agricultural land of Benton County, Oregon, USA, which has a size of 180 ×225 pixels.

**Preprocessing operations** were made (i.e., repairing bad stripes, removal of uncalibrated and noisiest bands, atmospheric correction, co-registration) on two images, where **159 bands** (i.e., bands 8–57, 82–119, 131–164, 182–184, and 187–220) out of original 242 bands were selected.

The major land-cover changes in this scenario are due to the transitions among different kinds of crops, soil and other land-cover types.

![2004](https://user-images.githubusercontent.com/102267920/169201916-50334b2a-3068-445a-a8f0-afd01395013b.jpg)
![2007](https://user-images.githubusercontent.com/102267920/169201946-5a60f9df-7667-44d4-a830-f1c22fffe32c.jpg)
![Reference_map_binary](https://user-images.githubusercontent.com/102267920/169202966-05cca785-ea75-4fcc-8a37-5d35c1891ed0.jpg)
![Reference_map](https://user-images.githubusercontent.com/102267920/169202979-fe3a6dd0-0cd1-4d2b-86b7-1bd1877032de.jpg)
![微信图片_20220519123039](https://user-images.githubusercontent.com/102267920/169206215-038458cc-8b4b-438a-a4fa-837f8563d73e.jpg)

 (a) May 1, 2004; (b) May 8, 2007; (c) Binary CD Reference Map; (d) Multiclass CD Reference Map

## Class Information

**_Change Class 1 (C1)_**: 1034 pixels

**_Change Class 2 (C2)_**: 1048 pixels

**_Change Class 3 (C3)_**: 5111 pixels

**_Change Class 4 (C4)_**: 1261 pixels

**_Change Class 5 (C5)_**: 479 pixels

**_Change Class 6 (C6)_**: 988 pixels

**_No-change Class (NC)_**: 30579 pixels

**_Total_**: 40500 pixels


## Citation

If you use this data set for your research, please cite the following papers.

[1] S. Liu, D. Marinelli, L. Bruzzone and F. Bovolo, "A Review of Change Detection in Multitemporal Hyperspectral Images: Current Techniques, Applications, and Challenges," IEEE Geoscience and Remote Sensing Magazine, vol. 7, no. 2, pp:140-158, 2019. [DOI: 10.1109/MGRS.2019.2898520](https://ieeexplore.ieee.org/document/8738052)

[2] S. Liu, Q. Du, X. Tong, A. Samat, H. Pan , X. Ma, “Band Selection based Dimensionality Reduction for Change Detection in Multitemporal Hyperspectral Images,”Remote Sensing, vol. 9, no.10, pp:1008, 2017. [DOI: 10.3390/rs9101008](https://www.mdpi.com/2072-4292/9/10/1008)

[3] S. Liu, L. Bruzzone, F. Bovolo, P. Du., “Unsupervised Multitemporal Spectral Unmixing for Detecting Multiple Changes in Hyperspectral Images,”IEEE Transactions on Geoscience and Remote Sensing, vol.54, no. 5, pp:2733-2748, 2016. [DOI: 10.1109/TGRS.2015.2505183](https://ieeexplore.ieee.org/document/7378967)

