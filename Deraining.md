# A Collection of Papers and Codes for Deraining

**整理汇总了下近年各顶级会议或期刊图像去雨/雨滴去除任务(Deraining/Raindrop removal)相关的一些论文和代码，主要target在数据集的整理上。**

**欢迎star，fork和PR~**

**Please feel free to star, fork or PR if helpful~**
  
# **参考或转载请注明出处**

**【Contents】**

- [1.图像去雨(Image Deraining)](#1.图像去雨)


<a name="1.图像去雨"></a>
# Synthetic datasets

### Joint Rain Detection and Removal from a Single Image (CVPR 2017, TPAMI 2019)

- Dataset Name: Rain200H、Rain200L
- Scale: 2000 pairs
- Rain Category: rain streak
- Resolution: 
- Paper: [Deep joint rain detection and removal from a single image](https://openaccess.thecvf.com/content/CVPR2021/html/Quan_Removing_Raindrops_and_Rain_Streaks_in_One_Go_CVPR_2021_paper.html)
- Code: [https://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html](https://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html)
- 备注：最早的去雨数据集

### Density-aware Single Image De-raining using a Multi-stream Dense Network (CVPR 2018)

- Dataset Name: Rain1200
- Scale: 12000 pairs
- Rain Category: rain streak
- Resolution: 586×586
- Paper: [Density-aware Single Image De-raining using a Multi-stream Dense Network](https://arxiv.org/abs/1802.07412)
- Code: [https://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html](https://github.com/hezhangsprinter/DID-MDN)
- 备注：3 rain-density labels


### Image de-raining using a conditional generative adversarial network (TCSVT 2019)

- Dataset Name: Rain800
- Scale: 800 pairs
- Rain Category: rain streak
- Resolution: 
- Paper: [Image De-Raining Using a Conditional Generative Adversarial Network](https://arxiv.org/abs/1701.05957)
- Code: [https://github.com/hezhangsprinter/ID-CGAN](https://github.com/hezhangsprinter/ID-CGAN)
- 备注：Randomly selected from BSD and UCID dataset


### Image de-raining using a conditional generative adversarial network (CVPR 2018)

- Dataset Name: RainDrop
- Scale: 1119 pairs
- Rain Category: raindrop
- Resolution: 
- Paper: [Image De-Raining Using a Conditional Generative Adversarial Network](https://arxiv.org/abs/1711.10098)
- Code: [https://github.com/hezhangsprinter/ID-CGAN](https://github.com/rui1996/DeRaindrop)
- 备注：两块lens，一块喷水一块干净，第一个raindrop数据集





### Single Image Deraining: A Comprehensive Benchmark Analysis (CVPR 2019)

- Dataset Name: MPID
- Scale: 4380 pairs
- Rain Category: rain streak & raindrop & rain mist
- Resolution: 
- Paper: [Single Image Deraining: A Comprehensive Benchmark Analysis](https://arxiv.org/abs/1903.08558)
- Code: [https://github.com/panda-lab/Single-Image-Deraining](https://github.com/panda-lab/Single-Image-Deraining)
- 备注：large-scale, 3种类型的雨(雨线，雨滴，雨雾), 有bounding box标注



### Depth-Attentional Features for Single-Image Rain Removal and RainCityscapes Dataset (CVPR 2019, TIP 2021)

- Dataset Name: RainCityscapes
- Scale: 4380 pairs
- Rain Category: rain streak & raindrop & rain mist
- Resolution: 
- Paper: [Depth-Attentional Features for Single-Image Rain Removal and RainCityscapes Dataset](https://openaccess.thecvf.com/content_CVPR_2019/html/Hu_Depth-Attentional_Features_for_Single-Image_Rain_Removal_CVPR_2019_paper.html)
- Code: [https://github.com/xw-hu/DAF-Net](https://github.com/xw-hu/DAF-Net)
- 备注：





### Depth-Attentional Features for Single-Image Rain Removal and RainCityscapes Dataset (CVPR 2019)

- Dataset Name: Outdoor-Rain
- Scale: 10,500 pairs
- Rain Category: rain streak
- Resolution: 
- Paper: [Heavy Rain Image Restoration: Integrating Physics Model and Conditional Adversarial Learning](https://arxiv.org/abs/1904.05050)
- Code: [https://github.com/liruoteng/HeavyRainRemoval](https://github.com/liruoteng/HeavyRainRemoval)
- 备注：考虑了深度信息，有积雨效应，整体合成的雨很大



### Depth-Attentional Features for Single-Image Rain Removal and RainCityscapes Dataset (CVPR 2020)

- Dataset Name: Outdoor-Rain
- Scale: 10,500 pairs
- Rain Category: rain streak
- Resolution: 
- Paper: [Heavy Rain Image Restoration: Integrating Physics Model and Conditional Adversarial Learning](https://arxiv.org/abs/1904.05050)
- Code: [https://github.com/liruoteng/HeavyRainRemoval](https://github.com/liruoteng/HeavyRainRemoval)
- 备注：考虑了深度信息，有积雨效应，整体合成的雨很大
























### Removing Raindrops and Rain Streaks in One Go (CVPR 2021)

- Dataset Name: RainDS
- Scale: 4800 pairs
- Rain Category: rain streak & raindrop
- Resolution: 1296*728
- Paper: [Removing Raindrops and Rain Streaks in One Go](https://ieeexplore.ieee.org/document/8099666)
- Code: [https://github.com/Songforrr/RainDS_CCN](https://github.com/Songforrr/RainDS_CCN)





# Real-world datasets



### Spatial Attentive Single-Image Deraining with a High Quality Real Rain Dataset (CVPR 2019)

- Dataset Name: SPA-Data
- Scale: 170 rainy videos (86 from Youtube) --> 29,500 pairs
- Rain Category: rain streak
- Resolution: 
- Paper: [Spatial Attentive Single-Image Deraining with a High Quality Real Rain Dataset](https://arxiv.org/abs/1904.01538)
- Code: [https://github.com/stevewongv/SPANet](https://github.com/stevewongv/SPANet)
- 备注：人工对齐视频,从一个sequence的多张图像中计算intensity change，用均值图像作为GT





### Removing Raindrops and Rain Streaks in One Go

- Dataset Name: RainDS
- Scale: 1000 pairs
- Rain Category: rain streak & raindrop
- Resolution: 1296*728
- Paper: [Removing Raindrops and Rain Streaks in One Go, CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/html/Quan_Removing_Raindrops_and_Rain_Streaks_in_One_Go_CVPR_2021_paper.html)
- Code: [https://github.com/Songforrr/RainDS_CCN](https://github.com/Songforrr/RainDS_CCN)




<font color=red size=5>持续更新~</font>



