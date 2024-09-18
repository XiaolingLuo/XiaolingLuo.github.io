---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently an assistant professor at Shenzhen University, Shenzhen. In 2023, I received my Doctoral degree from Harbin Institute of Technology, Shenzhen, and my doctoral supervisor was [Yong Xu (徐勇)](http://faculty.hitsz.edu.cn/xuyong). In 2017, I graduated from South China Normal University with a bachelor’s degree in Software Engineering. My research interests include computer vision and medical image processing.

<!--My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).-->


# News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2024.05*: One paper is accepted by BIB!
- *2024.04*: One paper is accepted by JBHI!
- *2023.11*: Two papers are accepted by AAAI 2024!
- *2023.09*: Our paper is accepted by NeurIPS 2023! 
- *2023.06*: Our paper is accepted by TNNLS! 
- *2023.02*: We won the AAAI 2023 distinguished paper award! 
- *2022.11*: Three papers are accepted by AAAI 2023!

# Publications 


## Conference Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/MVCINN.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
(Oral) [MVCINN: Multi-View Diabetic Retinopathy Detection Using a Deep Cross-Interaction Neural Network](https://ojs.aaai.org/index.php/AAAI/article/download/26080/25852), **Xiaoling Luo**, Chengliang Liu, Waikeung Wong, Jie Wen, Xiaopeng Jin, Yong Xu, **AAAI 2023** (CCF-A)
</div>
</div>
- [HACDR-Net: Heterogeneous-Aware Convolutional Network for Diabetic Retinopathy Multi-Lesion Segmentation](https://ojs.aaai.org/index.php/AAAI/article/download/28453/28882), Qihao Xu, **Xiaoling Luo (corresponding author)**, Chao Huang, Chengliang Liu, Jie Wen, Jialei Wang, Yong Xu, **AAAI 2024** (CCF-A)

- (Oral) [DICNet: Deep Instance-Level Contrastive Network for Double Incomplete Multi-View Multi-Label Classification](https://arxiv.org/pdf/2303.08358.pdf), Chengliang Liu, Jie Wen, **Xiaoling Luo**, Chao Huang, Zhihao Wu, Yong Xu, **AAAI 2023** (CCF-A)
  
<!--[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'>
</span></strong>-->
- [AAAI 2023 distinguished paper award](https://aihub.org/2023/02/11/congratulations-to-the-aaai2023-best-paper-winners/)

- (Oral) [Incomplete Multi-View Multi-Label Learning via Label-Guided Masked View-and Category-Aware Transformers](https://arxiv.org/pdf/2303.07180), Chengliang Liu, Jie Wen, **Xiaoling Luo**, Yong Xu, **AAAI 2023** (CCF-A)

- Masked Two-channel Decoupling Framework for Incomplete Multi-view Weak Multi-label Learning, Chengliang Liu, Jie Wen, Yabo Liu, Chao Huang, Zhihao Wu, **Xiaoling Luo**, Yong Xu, **NeurIPS 2023** (CCF-A)


## Journal Papers

- [A Lesion-Fusion Neural Network for Multi-View Diabetic Retinopathy Grading](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10488692), **Xiaoling Luo**, Qihao Xu, Zhihua Wang, et al., IEEE Journal of Biomedical and Health Informatics, Early Access, 1-11, 2024. (JCR Q1, IF-7.7)

- [RV-ESA: A novel computer-aided elastic shape analysis system for retinal vessels in diabetic retinopathy](https://doi.org/10.1016/j.compbiomed.2022.106406), **Xiaoling Luo**, Honggang Zhang, Jingyong Su, Wai Keung Wong, Jinkai L, Yong Xu, Computers in Biology and Medicine, 152: 106406, 2023 (JCR Q1, IF-7.7)

- [A Deep Convolutional Neural Network for Diabetic Retinopathy Detection via Mining Local and Long-Range Dependence](https://doi.org/10.1049/cit2.12155), **Xiaoling Luo**, Wei Wang, Yong Xu, Zhihui Lai, Xiaopeng Jin, Bob Zhang, David Zhang, CAAI Transactions on Intelligence Technology, 2023. (JCR Q2, IF-5.1)

- [Information Recovery-Driven Deep Incomplete Multi-view Clustering Network](https://arxiv.org/abs/2304.00429), Chengliang Liu, Jie Wen, Zhihao Wu, **Xiaoling Luo**, Chao Huang, Yong Xu, IEEE Transactions on Neural Networks and Learning Systems, 2023. (CCF-B, JCR Q1, IF-10.4)

- [PHR-search: a search framework for protein remote homology detection based on the predicted protein hierarchical relationships](https://doi.org/10.1093/bib/bbab609), Xiaopeng Jin, **Xiaoling Luo**, Bin Liu, Briefings in Bioinformatics, 23:2, bbab609, 2022. (JCR Q1, IF-9.5)

- [MVDRNet: Multi-View Diabetic Retinopathy Detection by Combining DCNNs and Attention Mechanisms](https://doi.org/10.1016/j.patcog.2021.108104), **Xiaoling Luo**, Zuhui Pu, Yong Xu, Wai Keung Wong, Jingyong Su, Xiaoyan Dou, Baikang Ye, Jiying Hu, Lisha Mou, Pattern Recognition, 120: 108104, 2021. (CCF-B, JCR Q1, IF-8.0)

- [Multi-resolution Dictionary Learning for Face Recognition](https://doi.org/10.1016/j.patcog.2019.04.027), **Xiaoling Luo**, Yong Xu, Jian Yang, Pattern Recognition, 93: 283-292, 2019. (CCF-B, JCR Q1, IF-14.255)



# Honors and Awards
- *2023.02* [AAAI 2023 distinguished paper award](https://aihub.org/2023/02/11/congratulations-to-the-aaai2023-best-paper-winners/).

# Educations
- *2017.09 - 2023.09*, School of Computer Science of Technology, Harbin Institute of Technology, Shenzhen, China. 
- *2013.09 - 2017.06*, School of Software Engineering, South China Normal University, China. 

# Academic Activities
- Journal Reviewers of IEEE TNNLS, CAAI TRIT
- Program Committee Members of AAAI 
