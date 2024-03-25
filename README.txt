Bộ cơ sở dữ liệu hình ảnh Multi-Modality Ovarian Tumor Ultrasound (MMOTU) bao gồm hai tập cơ sở dữ liệu con là OTU_2D và OTU_CEUS tương ứng bao gồm 1469 hình ảnh siêu âm 2D và 170 hình ảnh CEUS. Và cơ sở dữ liệu MMOTU đã được công bố xuất bản trong bài báo:

A Multi-Modality Ovarian Tumor Ultrasound Image Dataset for Unsupervised Cross-Domain Semantic Segmentation
Authors: Qi Zhao, Shuchang Lyu, Wenpei Bai, Linghan Cai, Binghao Liu, Meijing Wu, Xiubo Sang, Min Yang, and Lijiang Chen.
Link github: https://github.com/cv516Buaa/MMOTU_DS2Net

TABLET 1:  THE DATA DISTRIBUTION OF MMOTU IMAGE DATASET.
-------------------------------------------------------------
  Data type  | Training set | Testing set | Category number
-------------------------------------------------------------
    OTU_2D   |	   1000	    |      70     |         8		
   OTU_CEUS  |      70      |	    100    |         8
-------------------------------------------------------------

Như được hiển thị trong TABLET.I, tập dữ liệu hình ảnh MMOTU chứa hai tập cơ sở dữ liệu con, trong đó OTU_2D và OTU_CEUS tương ứng bao gồm 1469 hình ảnh siêu âm 2D và 170 hình ảnh CEUS. Trên hai tập con, tác giả chia chúng thành TRAINING-SET và TESTING-SET. Điều đáng chú ý là tập TESTING chứa nhiều hình ảnh hơn tập huấn luyện trong OTU CEUS vì trước tiên tác giả hy vọng đảm bảo chất lượng đánh giá. Và trong đây, chúng tôi đang tập trung vào tập dữ liệu OUT_2D.

TABLET 2: Cơ sở dữ liệu OTU_2D
-----------------------------------------------------------------------------------------------------
  Total number of images | Num of Training images | Num of Testing images | Num of Validation images
-----------------------------------------------------------------------------------------------------
           1469          |          1177          |         147           |             147
-----------------------------------------------------------------------------------------------------

TABLET 3: Số lượng ảnh trong từng lớp của CSDLCSDL
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

Cơ sở dữ liệu OTU-2D có 216 hình ảnh Doppler Flow (CDFI - Color Doppler Flow Images), và trong đó có 1253 ảnh còn lại là ảnh siêu âm 2D truyền thống. Trong TABLET 2, đã mô tả cơ sở dữ liệu OTU_2D bao gồmgồm 1469 ảnh, bao gồm 8 loại và số lượng tương ứng trong TABLET. Và đường dẫn file JSON gán nhãn của 1469 ảnh nằm theo đường dẫn 
          1. Cơ sở dữ liệu OTU_2D             :    '.../OTU_2D/OTU_2D_annotation.json'
          2. Cơ sở dữ liệu OTU_2D đã chia lớp :    '.../OTU_2D/8_layers/OTU_2D_8-layers.json'

