# Awesome ACG Machine Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/dimpurr/awesome-acg-machine-learning/tree/master)

A curated list of awesome machine learning resources related to anime, manga and so on.

Sharing, suggestions and contributions are always welcome. Please take a look at the [Contribution Guidelines](https://github.com/dimpurr/awesome-acg-machine-learning/tree/master#contribution-guidelines) first.

Also you can take a look at some realted [news reports & blog posts](https://github.com/dimpurr/awesome-acg-machine-learning/blob/master/README.md) for reference.

## Commissions & Groups

- MANPU - International Workshop on coMics ANalysis, Processing and Understanding
	- [MANPU 2016](http://manpu2016.imlab.jp/)
		- Publications: [Proceedings of the 1st International Workshop on coMics ANalysis, Processing and Understanding](https://dl.acm.org/citation.cfm?id=3011549&preflayout=flat)
	- [MANPU 2017](http://manpu2017.imlab.jp/)
- [SIG2D](http://sig2d.org/) - SIG2D (Special Interest Group on 2D Information Processing; しぐつーでぃー) は，二次元情報処理に強い興味を持つ研究者・技術者によるグループである
	- Publications: [Publications - SIG2D](http://sig2d.org/publications/)

## Datasets

### Image Processing & Recognization & Tagging

- [anime_faces (scrapy)](https://github.com/shaform/GirlsManifold/tree/master/anime_faces) - The scrapy script for processing anime characters faces
- [DANBOORU2017](https://www.gwern.net/Danbooru2017) - A Large-scale crowsourced and tagged anime illustration dataset

### Comics

- [eBDtheque](http://ebdtheque.univ-lr.fr/) - 100 images with ground truth for panels, speech balloons, tails, text lines, leading characters
- [Manga109](http://www.manga109.org/index_en.php) - Over 20 thousand images of 109 volumes (21,142 images)

## Projects

- [Awesome ACG/Image Processing](https://github.com/soruly/awesome-acg/blob/master/README.md#image-processing)
- [Awesome ACG/Image Recognition](https://github.com/soruly/awesome-acg/blob/master/README.md#image-recognition)

## Network Implementations

### TensorFlow

- [IllustrationGAN](https://github.com/tdrussell/IllustrationGAN) - A simple, clean TensorFlow implementation of Generative Adversarial Networks with a focus on modeling illustrations
- [Tensorflow-ACGAN-Anime-Generation](https://github.com/ctwxdd/Tensorflow-ACGAN-Anime-Generation) - Tensorflow implementation of "Towards the Automatic Anime Characters Creation with Generative Adversarial Networks" which related to [make.girls.moe](http://make.girls.moe)

### PyTorch

- [animeGAN](https://github.com/jayleicn/animeGAN) - A simple PyTorch Implementation of Generative Adversarial Networks, focusing on anime face drawing
- [GirlsManifold](https://github.com/shaform/GirlsManifold) - An attempt to replicate [make.girls.moe](http://make.girls.moe) using PyTorch

## Papers

### Image Recognization

- [Face Detection and Face Recognition of Cartoon Characters Using Feature Extraction](http://www.iieej.org/trans/IEVC/IEVC2012/PDF/4B-1.pdf) *Proceedings of IIEEJ Image Electronics and Visual Computing Workshop*
- [Manga FaceNet: Face Detection in Manga based on Deep Neural Network](https://www.cs.ccu.edu.tw/~wtchu/papers/2017ICMR-chu2.pdf) *ICMR '17 Proceedings of the 2017 ACM on International Conference on Multimedia Retrieva*
- [Pose estimation of anime/manga characters: a case for synthetic data](https://dl.acm.org/citation.cfm?id=3011552) *MANPU '16 Workshop*

### Image Processing

- [A sustainable practice method of hand-drawing by merging user's stroke and model's stroke](https://dl.acm.org/citation.cfm?id=3011559) *MANPU '16 Workshop*
- [Closure-aware Sketch Simplification](http://www.cse.cuhk.edu.hk/~ttwong/papers/sketch/sketch.html) *ACM Transactions on Graphics (SIGGRAPH Asia 2015 issue), Vol. 34, No. 6, November 2015, pp. 168:1-168:10.*
- [Towards the Automatic Anime Characters Creation with Generative Adversarial Networks](https://arxiv.org/abs/1708.05509) *Doujinshi in Comiket 92, summer 2017, with the booth number 05a, East-U, Third Day* - Related to [make.girls.moe](http://make.girls.moe)

### Multi-page Manga & Comic Analyze

- [A Study on Object Detection Method from Manga Images using CNN](http://www.iwait2018.org/Paper%20IWAIT2018/IWAIT2018_paper_016.pdf) *International Workshop on Advanced Image Technology 2018 (IWAIT 2018)*
- [Comics image processing: learning to segment text](https://dl.acm.org/citation.cfm?id=3011560) *MANPU '16 Workshop*
- [Comic visualization on smartphones based on eye tracking](https://dl.acm.org/citation.cfm?id=3011553) *MANPU '16 Workshop*
- [Designing a question-answering system for comic contents](https://dl.acm.org/citation.cfm?id=3011554) *MANPU '16 Workshop*
- [Detection of comic books twin pages with a non-overlapping stitching method](https://dl.acm.org/citation.cfm?id=3011550) *MANPU '16 Workshop*
- [Emotional arousal estimation while reading comics based on physiological signal analysis](https://dl.acm.org/citation.cfm?id=3011556) *MANPU '16 Workshop*
- [Estimation of structure of four-scene comics by convolutional neural networks](https://dl.acm.org/citation.cfm?id=3011558) *MANPU '16 Workshop*
- [Face Detection for Comic Images with Deformable Part Model](https://www.ams.giti.waseda.ac.jp/data/pdf-files/2014IEVC_yanagisawa.pdf) *The Fourth IIEEJ International Workshop on Image Electronics and Visual Computing*
- [Manga content analysis using physiological signals](https://dl.acm.org/citation.cfm?id=3011555) *MANPU '16 Workshop*
- [Manga generator, a future of interactive manga media: invited talk paper](https://dl.acm.org/citation.cfm?id=3015156) *MANPU '16 Workshop*
- [Manga109 dataset and creation of metadata](https://dl.acm.org/citation.cfm?id=3011551) *MANPU '16 Workshop*
- [Line-Based Drawing Style Description for Manga Classification](https://www.cs.ccu.edu.tw/~wtchu/papers/2014MM-chu.pdf) *Proceedings of ACM International Conference on Multimedia. 781–784*
- [Object Detection for Comics using Manga109 Annotations](https://arxiv.org/abs/1803.08670) *Arxiv*
- [Retrieval of comic book images using context relevance information](https://dl.acm.org/citation.cfm?id=3011561) *MANPU '16 Workshop*
- [Segmentation and indexation of complex objects in comic book images](https://tel.archives-ouvertes.fr/tel-01221308/document) *Université de La Rochelle*
- [Sketch-based manga retrieval using manga109 dataset](https://link.springer.com/article/10.1007/s11042-016-4020-z) *Multimedia Tools and Applications October 2017, Volume 76, Issue 20, pp 21811–21838*
- [Text-aware balloon extraction from manga](https://dl.acm.org/citation.cfm?id=2913253) *The Visual Computer: International Journal of Computer Graphics archive, Volume 32 Issue 4, April 2016, Pages 501-511* - Related to [moeka.me/mangaEditor](https://moeka.me/mangaEditor/)
- [Toward speech text recognition for comic books](https://dl.acm.org/citation.cfm?id=3011557) *MANPU '16 Workshop*

### Anime & Animation

- [Stereoscopizing Cel Animations](http://www.cse.cuhk.edu.hk/~ttwong/papers/3dcel/3dcel.html) *ACM Transactions on Graphics (SIGGRAPH Asia 2013 issue), Vol. 32, No. 6, November 2013, pp. 223:1-223:10.*

### Recommender System

- [Using Posters to Recommend Anime and Mangas in a Cold-Start Scenario](https://arxiv.org/pdf/1709.01584.pdf) *MANPU '17 Workshop*

## Contribution Guidelines

- For `Network Implementations` , use the following format:  `- [project-name](http://github-or-project-homepage.com) - Description` .
- For `Papers` , use the following format: `- [paper-title](http://paper-pdf-direct-link-(perferred)-or-library-page) *published-in-(optional)* - Description & project related (optional)` .
- `Datasets`, `Networks Implementations` and `Papers` sorted by alphabetical.
- Follow the original capitalization of the name of the project (no need to covert letter case).
- Item descriptions begin with a capital letter, and no need to end with a period.
