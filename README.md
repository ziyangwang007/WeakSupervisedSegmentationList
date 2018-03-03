# WeakSupervisedSegmentation
This repository contains lists of state-or-art weak supervised semantic segmentation works. Papers and resources are listed below according to supervision types.
(on progress)

- [ ] Paper list
	- [x] instance
	- [ ] box
	- [ ] one-shot
	- [ ] others 
- [ ] Resources
- [ ] Survey


#### Typical weak supervised segmentation problems 


| No | Supervision | Difficulty | Domain | Core issues |
| -- | ----------- | ---------- | ------ | ----------- |
| 1 | [Bounding box](#1) | middle | annotated classes | transfer learning |
| 2 | [One-shot segment](#2) | middle | similar objects | one-shot learning |
| 3 | [Image/video label](#3) | hard | annotated classes | transfer learning |
| 4 | [Others](#4) | n/a | n/a | n/a |

Instance semantic segmentation
----

<img src="img/instance.PNG" alt="git" title="instance segmentation" width="450" height="350" />

* [Learning to Segment Every Thing](https://arxiv.org/abs/1711.10370), CVPR 2018
* [Simple Does It: Weakly Supervised Instance and Semantic Segmentation](https://arxiv.org/abs/1603.07485), CVPR 2017

<h2 id="1">1.Bounding box supervision</h2>

* [Weakly- and Semi-Supervised Learning of a DCNN for Semantic Image Segmentation](https://arxiv.org/abs/1502.02734), ICCV 2015
* [BoxSup: Exploiting Bounding Boxes to Supervise Convolutional Networks for Semantic Segmentation](https://arxiv.org/abs/1503.01640), ICCV 2015


<h2 id="2">2.One-Shot segmentation supervision</h2>

DAVIS Challenge: <http://davischallenge.org/>

<img src="img/davis.PNG" alt="git2" title="davis" width="700" height="350" />

* [OSVOS: One-Shot Video Object Segmentation](http://www.vision.ee.ethz.ch/~cvlsegmentation/osvos/), CVPR 2017

<h2 id="3">3.Image/video label supervision</h2>

* [Weakly Supervised Semantic Segmentation using Web-Crawled Videos](https://arxiv.org/abs/1701.00352), CVPR 2017
* [Learning from Weak and Noisy Labels for Semantic Segmentation](http://ieeexplore.ieee.org/document/7450177/), PAMI 2017
* [Learning to Segment Human by Watching YouTube](https://arxiv.org/abs/1710.01457), PAMI 2017

<h2 id="4">4.Other supervision</h2>

* [Deep Extreme Cut: From Extreme Points to Object Segmentation](https://arxiv.org/abs/1711.09081), Arxiv1711
* [ScribbleSup: Scribble-Supervised Convolutional Networks for Semantic Segmentation](https://arxiv.org/abs/1604.05144), CVPR 2016

