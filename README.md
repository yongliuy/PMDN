# Revitalizing Image Dehazing in the Real World: A High-Quality Dataset and A Customized Method
[Yong Liu](https://scholar.google.com/citations?user=DT0LPIEAAAAJ&hl=en&oi=sra), 
Qingji Dong, 
Chao Zhu, 
[Yu Guo](https://scholar.google.com/citations?user=OemeiSIAAAAJ&hl=zh-TW), 
[Fei Wang](http://www.aiar.xjtu.edu.cn/info/1046/1242.htm)<br/>


[Paper]() | [BibTeX](#bibtex) 


:sparkling_heart: If our PMDN is helpful to your researches or projects, please help star this repository. Thanks! :hugs: 

![visitors](https://visitor-badge.laobi.icu/badge?page_id=yongliuy/PMDN) 
<img alt="GitHub" src="https://img.shields.io/badge/license-Apache_2.0-brightgreen">
[![GitHub Stars](https://img.shields.io/github/stars/yongliuy/PMDN?style=social)](https://github.com/yongliuy/PMDN/)


>Existing dehazing methods face challenges in generalization due to the lack of paired real-world training data and tailored models.
Recently, some semi-supervised/unsupervised schemes have been explored and achieve impressive performance.
However, their performance still depends heavily on synthetic training data and the introduced prior-based strong constraints do not always hold.
In this paper, we first introduce RealHQ-HAZE, a new dataset with 200 collected real-world hazy images, corresponding 200 carefully rendered haze-free images, and additional 1000 varicolored hazy images transferred from the collected images.
We also  propose a Prior-compensated Multi-stage Dehazing Network (PMDN), which can learn different levels of real-world haze distribution through multi-stage progressive learning.
To utilize prior knowledge effectively, we introduce a Prior-based Feature Compensation Module (PFCM), guiding intermediate results with an adaptive weight. 
Additionally, we propose a MixCut Consistent Dehazing (MCCD) strategy to mix paired and derived images using a cross-cutting scheme, reinforcing dehazing through consistency principles.
Extensive experiments demonstrate the effectiveness of our dataset and the superior performance of PMDN over existing state-of-the-art dehazing methods.


## Update
- **2025.07.15**: Create this repository.
