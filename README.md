
<div align="center">
<p align="center"> <img src="asset/unipose_logo.png" width="250px"> </p>
<h2> UniPose: Detecting Any Keypoints  </h2> 
  
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/unipose-detecting-any-keypoints/2d-human-pose-estimation-on-human-art)](https://paperswithcode.com/sota/2d-human-pose-estimation-on-human-art?p=unipose-detecting-any-keypoints)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/unipose-detecting-any-keypoints/2d-pose-estimation-on-animal-kingdom)](https://paperswithcode.com/sota/2d-pose-estimation-on-animal-kingdom?p=unipose-detecting-any-keypoints)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/unipose-detecting-any-keypoints/2d-pose-estimation-on-300w)](https://paperswithcode.com/sota/2d-pose-estimation-on-300w?p=unipose-detecting-any-keypoints)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/unipose-detecting-any-keypoints/2d-pose-estimation-on-macaquepose)](https://paperswithcode.com/sota/2d-pose-estimation-on-macaquepose?p=unipose-detecting-any-keypoints)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/unipose-detecting-any-keypoints/2d-pose-estimation-on-desert-locust)](https://paperswithcode.com/sota/2d-pose-estimation-on-desert-locust?p=unipose-detecting-any-keypoints)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/unipose-detecting-any-keypoints/2d-pose-estimation-on-vinegar-fly)](https://paperswithcode.com/sota/2d-pose-estimation-on-vinegar-fly?p=unipose-detecting-any-keypoints)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/unipose-detecting-any-keypoints/multi-person-pose-estimation-on-coco)](https://paperswithcode.com/sota/multi-person-pose-estimation-on-coco?p=unipose-detecting-any-keypoints)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/unipose-detecting-any-keypoints/animal-pose-estimation-on-ap-10k)](https://paperswithcode.com/sota/animal-pose-estimation-on-ap-10k?p=unipose-detecting-any-keypoints)
#### [<code>Project Page</code>](https://yangjie-cv.github.io/UniPose/) | [<code>Paper</code>](http://arxiv.org/abs/2310.08530) | [<code>ReadPaper</code>](https://readpaper.com/paper/2002445839294507520)  | UniKPT data(coming soon)  |[<code>Video</code>](https://github.com/IDEA-Research/UniPose)

[Jie Yang<sup>1,2</sup>](https://yangjie-cv.github.io/), [Ailing Zeng<sup>1</sup>](https://ailingzeng.site/), [Ruimao Zhang<sup>2</sup>](http://www.zhangruimao.site/), [Lei Zhang<sup>1</sup>](https://www.leizhang.org/)

<sup>1</sup>[International Digital Economy Academy](https://www.idea.edu.cn/research/cvr.html) <sup>2</sup>[The Chinese University of Hong Kong, Shenzhen](https://www.cuhk.edu.cn/en)
</div>

## 🤩 News
- **2023.10.13 :** We release the [arxiv](http://arxiv.org/abs/2310.08530) version.
  
### In-the-wild Test via UniPose
UniPose has strong fine-grained localization and generalization abilities across image styles, categories, and poses.
<p align="middle">
<img src="asset/in-the-wild.jpg" width="2000">
<br>
</p>


## 🗒 TODO 

- [ ] Release inference code and demo [Expected on October 30th].
- [ ] Release checkpoints [Expected on October 30th].
- [ ] Release UniKPT dataloader and annotations[Expected on October 30th].
- [ ] Release training codes.

## 💡 Overview

 • UniPose is the first end-to-end prompt-based keypoint detection framework.
 

<p align="middle">
<img src="asset/framework.png" width="2000">
<br>
</p>


• It supports multi-modality prompts, including textual and visual prompts to detect arbitrary keypoints (e.g., from articulated, rigid, and soft objects).


#### Visual Prompts as Inputs
<p align="middle">
<img src="asset/task1.png" width="2000">
<br>
</p>


#### Textual Prompts as Inputs
<p align="middle">
<img src="asset/task2.png" width="2000">
<br>
</p>





### Citing UniPose
If you find this repository useful for your work, please consider citing it as follows:

```
@article{yang2023unipose,
  title={UniPose: Detection Any Keypoints},
  author={Yang, Jie and Zeng, Ailing and Zhang, Ruimao and Zhang, Lei},
  journal={arXiv preprint arXiv:2310.08530},
  year={2023}
}
```
```
@inproceedings{yang2023neural,
  title={Neural Interactive Keypoint Detection},
  author={Yang, Jie and Zeng, Ailing and Li, Feng and Liu, Shilong and Zhang, Ruimao and Zhang, Lei},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={15122--15132},
  year={2023}
}
```

```
@inproceedings{yang2022explicit,
  title={Explicit Box Detection Unifies End-to-End Multi-Person Pose Estimation},
  author={Yang, Jie and Zeng, Ailing and Liu, Shilong and Li, Feng and Zhang, Ruimao and Zhang, Lei},
  booktitle={The Eleventh International Conference on Learning Representations},
  year={2022}
}
```


