<div align="center">
  <img src="doc/image/logo.gif" width="300"/>
</div>

<div align="center">- A Photography Portrait Matting Benchmark - </div>



<p align="center">
  <a href="#news">News</a> |
  <a href="#introduction">Introduction</a> |
  <a href="#download">Download</a> | 
  <a href="#license">License</a> | 
  <a href="#citation">Citation</a> | 
  <a href="#contact">Contact</a>
</p>

<img src="doc/image/title.jpg" width="100%">

---

## News
- **[Jul 20 2021] PPM-100 Benchmark is Released!**  
  The benchmark with 100 finly-annotated, high-resolution images (PPM-100) is released. 
  

## Introduction
PPM is a portrait matting benchmark with the following characteristics:
- **Fine Annotation** - All images are labeled and checked carefully.
- **Natural Background** - All images use the original background without replacement.
- **Rich Diversity** - The images cover full/half body and various postures.
- **High Resolution** - The resolution of images is between 1080p and 4k.

Following is an example image:

<img src="doc/image/example.png" width="100%">




## Download
Currently, PPM-100 used in the [MODNet](https://github.com/ZHKKKe/MODNet) paper is available.  
Note that few images used in the MODNet paper are replaced by similar images due to license issues.   
You can download PPM-100 from:  
[Google Drive](https://drive.google.com/file/d/1JUx-EPoV9QAhQgmW0AyOen-xKQUzZia-/view?usp=sharing) | [百度网盘 (提取码: PPMB)](https://pan.baidu.com/s/1iIeowdj6sdKSqW6qGnSb6A)


## License
All original portrait images in PPM are from [Flickr](https://www.flickr.com/) and constrained by [Flickr Creative Commons License (Commercial use & mods allowed)](https://www.flickr.com/creativecommons/).  
All annotated alpha mattes in PPM are released under the [Creative Commons Attribution NonCommercial ShareAlike 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode) license.  


## Citation
If you use this PPM benckmark, please cite:

```bibtex
@article{MODNet,
  author = {Zhanghan Ke and Kaican Li and Yurou Zhou and Qiuhua Wu and Xiangyu Mao and Qiong Yan and Rynson W.H. Lau},
  title = {Is a Green Screen Really Necessary for Real-Time Portrait Matting?},
  journal={ArXiv},
  volume={abs/2011.11961},
  year = {2020},
}
```


## Contact
This repository is currently maintained by Zhanghan Ke ([@ZHKKKe](https://github.com/ZHKKKe)).  
If there is any question, please contact `kezhanghan@outlook.com`.
