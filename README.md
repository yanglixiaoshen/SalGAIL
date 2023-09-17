# SalGAIL

Saliency Prediction on Omnidirectional Image with Generative Adversarial Imitation Learning (IEEE TIP 2021)

Attention Research on Omnidirectional images (AOI) dataset release.

==========================================================================================================

-----------COPYRIGHT NOTICE STARTS WITH THIS LINE------------

Copyright (c) 2021, The Beihang University, China.

All rights reserved.

## License

Permission to use, copy, or modify this dataset and its documentation
for educational and research purposes only and without fee is hereby
granted, provided that this copyright notice and the original authors'
names appear on all copies and supporting documentation. This program
shall not be used, rewritten, or adapted as the basis of a commercial
software or hardware product without first obtaining permission of the
authors. The authors make no representations about the suitability of
this software for any purpose. It is provided "as is" without explicit
or implied warranty.

## Citation

This is an implementation of the large-scale ODI dataset which contains the head fixations of 30 subjects viewing 600 ODIs.
You can use this dataset for human visual attention behaviour analysis on ODIs, attention/saliency map prediction modeling, and etc.

Please refer to the following paper and readme.txt with suggested usage.


Note: You must cite our paper in the following BibTex format !!!

```latex
@article{xu2021saliency,
  title={Saliency prediction on omnidirectional image with generative adversarial imitation learning},
  author={Xu, Mai and Yang, Li and Tao, Xiaoming and Duan, Yiping and Wang, Zulin},
  journal={IEEE Transactions on Image Processing},
  volume={30},
  pages={2087--2102},
  year={2021},
  publisher={IEEE}
}
```

The final citation format in the reference of your paper should be:

1. M. Xu, L. Yang, X. Tao, Y. Duan and Z. Wang, "Saliency Prediction on Omnidirectional Image With 
Generative Adversarial Imitation Learning," in IEEE Transactions on Image Processing, vol. 30, pp. 2087-2102, 
2021, doi: 10.1109/TIP.2021.3050861.

----------------------------------------------------------------------------------------------------------

## Dataset

The dataset has been uploaded to Beihang Yunpan (LINK:https://bhpan.buaa.edu.cn/link/AA25AF73AE70B143ACABB96F6274EB63EA).
You should ask for the PASSWORD to download it by sending emails to 13021041@buaa.edu.cn.
The emial should contain your university/company, your grade (undergraduate, master or doctor) and the purpose of pursuing this dataset.
The act of spreading our dataset freely on the Internet is forbidden.

1. IMG_600
	
   The original format of ERP-projection, high-quality, high-resolution omnidirectional images.
   The number of all ODIs is 600, containing 4 categories of human, cityscapes, indoor and nature.

   Resolution: 8000*4000

2. AOI_salmap&fixation

   (1) AOI_salmap:

   The ground-truth saliency maps of the corresponding 600 ODIs with resized size.

   The saliency map is generated from the collected human head fixations, and the

   details of collecting the AOI dataset and generating saliency maps can be found 

   in our paper. (https://ieeexplore.ieee.org/document/9328187)

   Resolution: 1333*667

   (2) Fixation:

   For each ODI in AOI dataset, we offer the original head fixations of 30 subjects
   
   in ODI_name.txt, which are collected from the experiment introduced in paper. 

   The format of ODI_name.txt is as follows:

   =================================================================================================================================================

      0                      1                         2                             3                                           4

   Subject_ID          Fixation_number            Time stamp               Head_fixation_longitude                     Head_fixation_latitude

   1-30                     1-*                    unit: ms              -180--180 (degree) [Left to Right]         -90--90 (degree) [Bottom to Top] 

   =================================================================================================================================================
    

## Tips

 Kindly report any suggestions or corrections to 13021041@buaa.edu.cn, or contact with me if you have any problem of datasets in our paper.
