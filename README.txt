The MMOTU dataset is a significant resource designed to support research and applications in the field of medical image analysis, specifically in the classification and segmentation of ovarian tumors from ultrasound images. Automatic image segmentation of ovarian tumors is crucial for improving diagnostic accuracy, reducing errors by clinicians, saving time, and minimizing costs in medical examination processes. Additionally, this dataset can aid in the development of advanced machine learning and deep learning algorithms to assist medical professionals in diagnosing ovarian tumors more efficiently.

The MMOTU dataset contains images of different types of ovarian tumors, including chocolate cysts, mucinous cystadenomas, high-grade serous cystadenomas, normal ovaries, and more. The diversity of tumor types in the dataset makes it an invaluable resource for training models that are capable of handling a variety of clinical cases.

A Multi-Modality Ovarian Tumor Ultrasound Image Dataset for Unsupervised Cross-Domain Semantic Segmentation
Authors: Qi Zhao, Shuchang Lyu, Wenpei Bai, Linghan Cai, Binghao Liu, Meijing Wu, Xiubo Sang, Min Yang, and Lijiang Chen.
Link github: https://github.com/cv516Buaa/MMOTU_DS2Netx

TABLET 1:  THE DATA DISTRIBUTION OF MMOTU IMAGE DATASET.
-------------------------------------------------------------
  Data type  | Training set | Testing set | Category number
-------------------------------------------------------------
    OTU_2D   |	   1000	    |      469    |         8		
   OTU_CEUS  |      70      |	     100    |         8
-------------------------------------------------------------

As shown in TABLE 1, the MMOTU image dataset includes two sub-databases: OTU_2D and OTU_CEUS, which contain 1469 2D ultrasound images and 170 CEUS images, respectively. The authors have divided the two sub-databases into TRAINING-SET and TESTING-SET. Notably, the TESTING-SET for OTU_CEUS contains more images than the TRAINING-SET because the authors wanted to ensure the quality of the evaluation. Here, we are focusing on the OTU_2D dataset.

TABLET 2: OTU2D Dataset
-----------------------------------------------------------------------------------------------------
  Total number of images | Num of Training images | Num of Testing images | Num of Validation images
-----------------------------------------------------------------------------------------------------
           1469          |          1177          |         147           |             147
-----------------------------------------------------------------------------------------------------

TABLET 3: IMAGE COUNT IN EACH CLASS OF OTU_2D
-------------------------------------------------------------------------
 No. |      Type of Ovarian Tumor     | Total image | Train | Validation
-------------------------------------------------------------------------
  1  | Chocolate cyst                 |     336     |  226  |    110 
  2  | Mucinous cystadenoma           |     104     |  71   |    33  
  3  | High-grade serous cystadenoma  |     53      |  38   |    15
  4  | Ovary normal                   |     267     |  180  |    87
  5  | Simple cyst                    |     66      |  47   |    19
  6  | Theca cell tumor               |     88      |  57   |    31
  7  | Teratoma                       |     336     |  228  |    108
  8  | Serous cystadenoma             |     219     |  153  |    66
-------------------------------------------------------------------------
                  Total               |     1469    |  1000 |    469
-------------------------------------------------------------------------

The OTU_2D dataset contains 216 Doppler Flow Images (CDFI - Color Doppler Flow Images), with the remaining 1253 images being traditional 2D ultrasound images. As described in TABLE 2, the OTU_2D dataset includes 1469 images across 8 categories, with the corresponding image counts shown in TABLE 3. The annotated JSON files for the 1469 images can be found at the following paths:
          1. OTU_2D dataset                     :    '.../OTU_2D/OTU_2D_annotation.json'
          2. OTU_2D dataset devied to 8 classes :    '.../OTU_2D/8_layers/OTU_2D_8-layers.json'

Here is the citation for the MMOTU Dataset paper:
```
@article{Zhao2022AMO,
  title={A Multi-Modality Ovarian Tumor Ultrasound Image Dataset for Unsupervised Cross-Domain Semantic Segmentation},
  author={Qi Zhao and Shuchang Lyu and Wenpei Bai and Linghan Cai and Binghao Liu and Mei-Hsuan Wu and Xiubo Sang and Min Yang and Lijiang Chen},
  journal={ArXiv},
  year={2022},
  volume={abs/2207.06799},
  url={https://api.semanticscholar.org/CorpusID:250526625}
}
```
