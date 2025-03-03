---
title: "UAVM 2025"
collection: pages
permalink: /ACMMM2025Workshop-UAV
author_profile: false
---



 <div align='center' > 
  <h2> ACM Multimedia </h2>
 </div>

 <div align='center' style = "vertical-align:middle"> 
  <h2> <img src="https://acmmm2025.org/wp-content/uploads/2024/10/ACM-MM-2025-LinkedIn-Banner-scaled.jpg" margin-right="20px" alt="ACM Multimedia conference 2025" ><a href="https://acmmm2025.org/"> ACM MM 2025 </a><a href="https://acmmm2025.org/">(https://acmmm2025.org/)</a>  </h2>
 </div>
 
 <div align='center' > 
  <h2> Workshop on </h2>
  <h2> UAVs in Multimedia: Capturing the World from a New Perspective (UAVM 2025)
</h2>
 <img src="https://github.com/layumi/ACMMM2023Workshop/blob/main/picture/logo.png?raw=true" alt="workshop logo">
</div>

<meta name="og:image" content="https://github.com/layumi/ACMMM2023Workshop/blob/main/picture/logo.png?raw=true">
<meta name="og:description" content="UAVs in Multimedia: Capturing the World from a New Perspective (UAVM 2025)"> 
<meta name='description' content='ACMMM2024 Workshop UAVs in Multimedia: Capturing the World from a New Perspective (UAVM 2025) '>

The accept papers will be published at ACM Multimedia Workshop (top 50%), and go through the same peer review process as the regular papers. Several authors will be invited to do a oral presentation. 

## Workshop Schedule

**TBD**

## Invited Speakers

**TBD**

## Important Dates

**Submission of papers:**
* Workshop Papers Submission: 13 June 2025
* Workshop Papers Notification: 24 July 2025
* Student Travel Grants Application Deadline: 7 August 2025
* Camera-ready Submission: 3 August 2025
* Conference Dates: 27 October 2025 – 31 October 2025

Please note: The submission deadline is at 11:59 p.m. of the stated deadline date [Anywhere on Earth](https://time.is/Anywhere_on_Earth)

## Abstract
Unmanned Aerial Vehicles (UAVs), also known as drones, have become increasingly popular in recent years due to their ability to capture high-quality multimedia data from the sky. With the rise of multimedia applications, such as aerial photography, cinematography, and mapping, UAVs have emerged as a powerful tool for gathering rich and diverse multimedia content. This workshop aims to bring together researchers, practitioners, and enthusiasts interested in UAV multimedia to explore the latest advancements, challenges, and opportunities in this exciting field. The workshop will cover various topics related to UAV multimedia, including aerial image and video processing, machine learning for UAV data analysis, UAV swarm technology, and UAV-based multimedia applications. In the context of the ACM Multimedia conference, this workshop is highly relevant as multimedia data from UAVs is becoming an increasingly important source of content for many multimedia applications. The workshop will provide a platform for researchers to share their work and discuss potential collaborations, as well as an opportunity for practitioners to learn about the latest developments in UAV multimedia technology. Overall, this workshop will provide a unique opportunity to explore the exciting and rapidly evolving field of UAV multimedia and its potential impact on the wider multimedia community.


**The list of possible topics includes, but is not limited to:**

*  Video-based UAV Navigation
    + Satellite-guided & Ground-guided Navigation
    + Path Planning and Obstacle Avoidance
    + Visual SLAM (Simultaneous Localization and Mapping)
    + Sensor Fusion and Reinforcement Learning for Navigation
* UAV Swarm Coordination
    + Multiple Platform Collaboration
    + Multi-agent Cooperation and Communication
    + Decentralized Control and Optimization
    + Distributed Perception and Mapping
* UAV-based Object Detection and Tracking
    + Aerial-view Object Detection, Tracking and Re-identification
    + Aerial-view Action Recognition
* UAV-based Sensing and Mapping
    + 3D Mapping and Reconstruction
    + Remote Sensing and Image Analysis
    + Disaster Response and Relief
* UAV-based Delivery and Transportation
    + Package Delivery and Logistics
    + Safety and Regulations for UAV-based Transportation


## Submission Types

Paper can be submitted on [[Open Review]](https://openreview.net/group?id=acmmm.org/ACMMM/2025/Workshop/UAVM).

Submission template can be found at [ACM](https://www.acm.org/publications/proceedings-template) or you may directly follow the [overleaf template](https://www.overleaf.com/read/yfpxtyngmzjn).

**We recommend the single-blind (showing your name and affilliation) for fast processing, but double-blind papers are also acceptable. We will ensure the fairness.**

In this workshop, we welcome four types of submissions, all of which should relate to the topics and themes as listed in Section 3: 

- (1). Challenge papers (**up to 4 pages in length, plus unlimited pages for references**): original solution to the Challenge data, University160k, in terms of effectiveness and efficiency. 

- (2). Original papers (**up to 4 pages in length, plus unlimited pages for references**): original ideas, perspectives, research vision, and open challenges in the area of evaluation approaches for UAVs in Multimedia; Page limits include diagrams and appendices.

Page limits include diagrams and appendices. Submissions should be single-blind, written in English, and formatted according to the current ACM two-column conference format. Suitable LaTeX, Word, and Overleaf templates are available from the ACM Website (use “sigconf” proceedings template for LaTeX and the Interim Template for Word).

**Tips:**
- For privacy protection, please blur faces in the published materials (such as paper, video, poster, etc.) 
- For social good, please do not contain any misleading words, such as ``surveillance`` and  ``secret``.


## Challenge

**Challenge Platform is at https://codalab.lisn.upsaclay.fr/competitions/18770 .**

This year’s focus is specifically on matching partial street images to corresponding satellite images (illustrated in Figure 3). By concentrating on partial views, our aim is to more accurately reflect real-world scenarios where obstructions or limited sensor angles may restrict the field of view, such as during low-altitude UAV operations for navigation, search-and-rescue missions, and autonomous flight. We harness University-1652 [40] as the challenge dataset, which provides 2,579 street images as query and 951 gallery satellite images. To encourage broader participation and innovation, we will make University-1652 training set available through our website with name-masked test set, along with a public leaderboard. 

Check challenge details at Section 5 in [proposal](https://github.com/spyflying/ACMMM2025Workshop-UAV/blob/main/proposal.pdf)

The challenge dataset contains two part.
1. The basic dataset (training set) can be download by [Request](https://github.com/layumi/University1652-Baseline/blob/master/Request.md). Usually I will reply the download link in 5 minutes. 

2. The name-masked test-160k-WX dataset (query & gallery+distractor) can be downloaded from [Onedrive](https://hdueducn-my.sharepoint.com/:f:/g/personal/wongtyu_hdu_edu_cn/EoP7u9rymIxMrv_s3Im-vvQBX8PQ_4v1xzXolMfyKmINkw?e=N8vpum).
Since only drone will meet weather conditions, we only simulate weather on drone-view queries. 

The submission example can be found at [Baseline Submission](https://github.com/wtyhub/ACMMM2024Workshop/blob/main/answer.txt). Please zip it as `answer.zip` to submit the result.

Please return the top-10 satellite names. For example, the first query is `Q3JI2tUwDkhcfip.jpeg`. Therefore, the first line of returned result in `answer.txt` should be the format as follows:
```
e6kXgz36E8nOY2n       ioqKwvSIYYhiW2v       y4VmQPUYOMD8AH4       kpZ2QJlNBHMnbRA       xffJQs2n9DP17fg       IejrFHLQYBfce2y       cH79t5WJMEMZ3VA       W9u0j4N1nlFbI97       zDurtAW4FTJfNJ3       MuvIMNVdofmaRqG
```
Please return the result following the order of query at [Query TXT](https://github.com/wtyhub/ACMMM2024Workshop/blob/main/query_drone_name.txt)
It will be 37855 lines.

## Related Papers 
- Wang, T., Zheng, Z., Sun, Y., Yan, C., Yang, Y., & Chua, T. S. (2024). [Multiple-environment Self-adaptive Network for Aerial-view Geo-localization](https://zdzheng.xyz/files/PR2024-Wang.pdf). Pattern Recognition, 152, 110363.
- Zheng, Z., Wei, Y., & Yang, Y. (2020, October). [University-1652: A multi-view multi-source benchmark for drone-based geo-localization](https://zdzheng.xyz/files/ACMMM20.pdf). In Proceedings of the 28th ACM international conference on Multimedia (pp. 1395-1403).
- Wang, C., Zheng, Z., Quan, R., Sun, Y., & Yang, Y. (2023). [Context-aware pretraining for efficient blind image decomposition](https://zdzheng.xyz/files/CVPR2023-Wang.pdf). In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 18186-18195).
- Chu, M., Zheng, Z., Ji, W., & Chua, T. S. (2024). [Towards Natural Language-Guided Drones: GeoText-1652 Benchmark with Spatially Relation Matching](https://arxiv.org/abs/2311.12751). ECCV.

## Organizing Team

| <img src="https://github.com/wtyhub/Photo/blob/a713229943f0628ffb82556bc9e396bbfabe8567/1%20inch.jpg?raw=true" width="160"> |<img src="https://yujiaoshi.github.io/images/YujiaoShiCircle.jpg" width="160"> | <img src="https://skyy93.github.io/assets/img/avatar.jpeg" width="160"> | <img src="https://spyflying.github.io/images/android-chrome-512x512.png" width=160> |
| :-: | :-: | :-: | :-: |
| [Tingyu Wang](https://scholar.google.com/citations?user=wv3H-F4AAAAJ), Hangzhou Dianzi University, China | [Yujiao Shi](https://yujiaoshi.github.io/), ShanghaiTech University, China | [Fabian Deuser](https://skyy93.github.io/), University of the Bundeswehr Munich, Germany | [Shaofei Huang](https://spyflying.github.io/), Institute of Information Engineering, Chinese Academy of Sciences, China |
| <img src="https://huguosheng.github.io/authors/admin/avatar_hu9cdb3e56f445519b0cfb017d5ee8dc29_1315845_270x270_fill_q75_lanczos_center.jpg" width="160"> | <img src="https://iai.buaa.edu.cn/__local/8/B3/D8/4ECB804DFB2D885A57A1586F536_32659FCA_15A1A.jpg" width="160"> | <img src="https://github.com/layumi/ICME2022SS/blob/main/picture/1.png?raw=true" width="160"> | <img src="https://www.comp.nus.edu.sg/~sochr/www/stfphotos/rogerz.jpg" width="160">
[Guosheng Hu](https://huguosheng.github.io/), University of Bristol, United Kingdom | [Si Liu](https://colalab.net/), Beihang University, China | [Zhedong Zheng](https://zdzheng.xyz), University of Macau, China | [Roger Zimmermann](https://www.comp.nus.edu.sg/cs/people/rogerz/), National University of Singapore, Singapore |


## Conference and Journal Papers

All papers presented at ACMMM 2025 will be included in ACM proceeding. All papers submitted to this workshop will go through the same review process as the regular papers submitted to the main conference to ensure that the contributions are of high quality. 


## Student Traval Funding

Please check https://acmmm2025.org/

## Workshop Citation
```bibtex
@inproceedings{zheng2025UVA,
  title={The 3rd Workshop on UAVs in Multimedia: Capturing the World from a New Perspective},
  author={Wang, Tingyu and Shi, Yujiao and Deuser, Fabian and Huang, Shaofei and Hu, Guosheng and Liu, Si and Zheng, Zhedong and Zimmermann, Roger},
  booktitle={Proceedings of the 33rd ACM International Conference on Multimedia Workshop},
  year={2025}
}  
```