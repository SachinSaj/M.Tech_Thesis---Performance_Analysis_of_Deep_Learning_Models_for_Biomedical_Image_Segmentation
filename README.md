# M.Tech Thesis---Performance Analysis of Deep Learning Models for Biomedical Image Segmentation

### Abstract

Image segmentation is one of the most common task in computer vision, which partition a given digital image into multiple meaningful segments (image) that can be easily analyzed. Since, the cancer rates in the world is increasing at an alarming rate and if it is found at earlier stages, chances of curing the cancer would be very high. Since manual annotation of these cancer regions by doctors is very time consuming and can be prone to human errors, automatic tumor segmentation is of great interest. In recent years, deep learning is progressing in most of the applications and thus motivated us to use this in such important bio-medical task. The cancer that we have considered in this thesis is brain tumor (preprocessed BraTs 2015) and skin tumor (ISIC 2018), as it is dangerous and as well as the rate of people getting affected is also increasing around the world. For our bio-medical image segmentation, we proposed to use three architectures: a) SegAN, b) SegNet, and c) U-Net. Based on evaluation parameters such as jaccard index and dice score, the segmented/predicted outputs are evaluated. The models were able to achieve comparable performances with the existing approaches in the area of bio-medical image segmentation's for these datasets.

- Datasets: a) Preprocessed BraTs 2015 (Brain Tumor Dataset), b) Skin Tumor (ISIC 2018)
- Architecture: a) U-Net, b) SegNet, c) SegAN
- Evaluation Metrics: a) Dice Score, b) Jaccard Index

### Conclusion

- For Skin lesion segmentation ( ISIC 2018): U-Net > SegNet > SegAN ( in terms of Jaccard Index and Dice Score)
- For Brain tumor segmentation ( Preprocessed BraTs 2015 ) : U-Net > SegNet ( in terms of Jaccard Index and Dice Score)
- When compared with state of the results for ISIC 2018 dataset, our proposed work was able to achieve comparable results in terms of jaccard index and in terms of dice score U-Net outperformed them.
- When compared with state of the results for preprocessed BraTs 2015, our U-Net (with addition of 2 convolutional layers at encoder & decoder) and SegNet both outperformed the existing approach.
- Number of Learnable parameters and computation time: SegAN > SegNet > U-Net
- In terms of segmentation output, U-Net gave the sharpest edge output (which is suitable for bio-medical image segmentation), where as SegNet output was smooth edged.



#### The presentation slides is uploaded in this repository. The thesis is not uploaded, as there is plan of publishing the work.
#### The Thesis is submit to  " Book on Deep Learning for Biomedical Application (Aug 2020) ": Publisher - CRC Press (current status - Accepted, waiting to be published online)


#### ** If any idea is used from this work, kindly let me know / cite my work **
