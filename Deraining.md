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
- Scale: 2000
- Rain Category: rain streak
- Resolution: 
- Paper: [Deep joint rain detection and removal from a single image](https://openaccess.thecvf.com/content/CVPR2021/html/Quan_Removing_Raindrops_and_Rain_Streaks_in_One_Go_CVPR_2021_paper.html)
- Code: [https://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html](https://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html)
- 备注：最早的去雨数据集

### Density-aware Single Image De-raining using a Multi-stream Dense Network (CVPR 2018)

- Dataset Name: Rain1200
- Scale: 12000
- Rain Category: rain streak
- Resolution: 586×586
- Paper: [Density-aware Single Image De-raining using a Multi-stream Dense Network](https://arxiv.org/abs/1802.07412)
- Code: [https://www.icst.pku.edu.cn/struct/Projects/joint_rain_removal.html](https://github.com/hezhangsprinter/DID-MDN)
- 备注：3 rain-density labels


### Image de-raining using a conditional generative adversarial network (TCSVT 2019)

- Dataset Name: Rain800
- Scale: 800
- Rain Category: rain streak
- Resolution: 
- Paper: [Image De-Raining Using a Conditional Generative Adversarial Network](https://arxiv.org/abs/1701.05957)
- Code: [https://github.com/hezhangsprinter/ID-CGAN](https://github.com/hezhangsprinter/ID-CGAN)
- 备注：Randomly selected from BSD and UCID dataset


### Image de-raining using a conditional generative adversarial network (CVPR 2018)

- Dataset Name: RainDrop
- Scale: 1119
- Rain Category: raindrop
- Resolution: 
- Paper: [Image De-Raining Using a Conditional Generative Adversarial Network](https://arxiv.org/abs/1711.10098)
- Code: [https://github.com/hezhangsprinter/ID-CGAN](https://github.com/rui1996/DeRaindrop)
- 备注：两块lens，一块喷水一块干净，第一个raindrop数据集




### Spatial Attentive Single-Image Deraining with a High Quality Real Rain Dataset (CVPR 2019)

- Dataset Name: RainDrop
- Scale: 1119
- Rain Category: raindrop
- Resolution: 
- Paper: [Spatial Attentive Single-Image Deraining with a High Quality Real Rain Dataset](https://arxiv.org/abs/1904.01538)
- Code: [https://github.com/stevewongv/SPANet](https://github.com/stevewongv/SPANet)
- 备注：两块lens，一块喷水一块干净，第一个raindrop数据集






### Removing Raindrops and Rain Streaks in One Go

- Dataset Name: RainDS
- Scale: 4800 pairs
- Rain Category: rain streak & raindrop
- Resolution: 1296*728
- Paper: [Removing Raindrops and Rain Streaks in One Go, CVPR2021](https://ieeexplore.ieee.org/document/8099666)
- Code: [https://github.com/Songforrr/RainDS_CCN](https://github.com/Songforrr/RainDS_CCN)





# Real-world datasets

### Removing Raindrops and Rain Streaks in One Go

- Dataset Name: RainDS
- Scale: 1000 pairs
- Rain Category: rain streak & raindrop
- Resolution: 1296*728
- Paper: [Removing Raindrops and Rain Streaks in One Go, CVPR2021](https://openaccess.thecvf.com/content/CVPR2021/html/Quan_Removing_Raindrops_and_Rain_Streaks_in_One_Go_CVPR_2021_paper.html)
- Code: [https://github.com/Songforrr/RainDS_CCN](https://github.com/Songforrr/RainDS_CCN)




<font color=red size=5>持续更新~</font>



