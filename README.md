[![Maintenance](https://img.shields.io/badge/Maintained%3F-YES-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![GitHub](https://img.shields.io/badge/License-MIT-lightgrey.svg)

# Awesome Deep Learning for Video Analysis

This repo contains some video analysis, especiall multimodal learning for video analysis, research. I summarize some papers and categorize them by myself. You are kindly invited to pull requests!

I pay more attention on multimodal learning related work and some research like action recognition is not the main scope of this repo.

## Contents

### Video
- [Tutorial](#tutorial)
- [Dataset](#dataset)
- [Tool](#tool)
- [Video Classification](#video-classification-spatiotemporal-features)
- [Multimodal for Video Analysis](#multimodal-for-video-analysis)
- [Video Moment Localization](#video-moment-localization)
- [Video Retrieval](#video-retrieval)
- [Video Advertisement](#video-advertisement-also-include-some-image-advertisement-paper)
- [Visual Commonsense Reasoning](#visual-commonsense-reasoning)
- [Video Highlight](#video-highlight-prediction)
- [Object Tracking](#object-tracking)
- [Audio-Visual Dialog](#audio-visual-dialog)
- [Action Recognition](#action-recognition-spatiotemporal-features-video-classification)





## Tutorial

- CVPR2019:Multi-Modal Learning from Videos [[Project Page]](https://sites.google.com/view/mmlv/home)

- awesome-multimodal-ml: Reading list for research topics in multimodal machine learning [[GitHub]](https://github.com/pliang279/awesome-multimodal-ml)

## Dataset:

I find a very interesting website

#### Sortable and searchable compilation of video dataset [[Video Dataset Overview]](https://www.di.ens.fr/~miech/datasetviz/)

- AVA dataset: AVA is a project that provides audiovisual annotations of video for improving our understanding of human activity. [[Project]](https://research.google.com/ava/index.html)
- PyVideoResearch: A repositsory of common methods, datasets, and tasks for video research [[GitHub]](https://github.com/gsig/PyVideoResearch)
- How2 Dataset: How2: A Large-scale Dataset for Multimodal Language Understanding [[Paper]](https://arxiv.org/pdf/1811.00347.pdf) [[GitHub]](https://github.com/srvk/how2-dataset)
- Moments in Time Dataset A large-scale dataset for recognizing and understanding action in videos [[Dataset]](https://github.com/metalbubble/moments_models) [[Pretrained Model]](http://moments.csail.mit.edu/)
- Pretrained image and video models for Pytorch [[GitHub]](https://github.com/alexandonian/pretorched-x)
- Youtube-8M, new segment task! [[Blog]](https://ai.googleblog.com/2019/06/announcing-youtube-8m-segments-dataset.html)

## Tool

- facebookresearch/ClassyVision: An end-to-end PyTorch framework for image and video classification [[GitHub]](https://github.com/facebookresearch/ClassyVision)
- MediaPipe is a cross-platform framework for building multimodal applied machine learning pipelines [[GitHub]](https://github.com/google/mediapipe)
- This document describes the collection of utilities created for Detection and Classification of Acoustic Scenes and Events (DCASE).  [[GitHub]](https://dcase-repo.github.io/dcase_util/index.html)
- Easy to use video deep features extractor [[GitHub]](https://github.com/antoine77340/video_feature_extractor)
- Video Platform for Action Recognition and Object Detection in Pytorch [[GitHub]](https://github.com/MichiganCOG/ViP)
- FAIR Self-Supervised Learning Integrated Multi-modal Environment (SSLIME) [[GitHub]](https://github.com/facebookresearch/fair-sslime)

## Paper:

### Video Classification (Spatiotemporal Features)

- TSM: Temporal Shift Module for Efficient Video Understanding [[Paper]](https://arxiv.org/pdf/1811.08383.pdf) [[GitHub]](https://github.com/mit-han-lab/temporal-shift-module)
- Long-Term Feature Banks for Detailed Video Understanding (*CVPR2019*) [[Paper]](https://arxiv.org/pdf/1812.05038.pdf)[[GitHub]](https://github.com/facebookresearch/video-long-term-feature-banks)
- Deep Learning for Video Classification and Captioning [[Paper]](https://arxiv.org/pdf/1609.06782.pdf)
- Large-scale Video Classification with Convolutional Neural Networks [[Paper]](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/42455.pdf)
- Learning Spatiotemporal Features with 3D Convolutional Networks [[Paper]](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Tran_Learning_Spatiotemporal_Features_ICCV_2015_paper.pdf)
- Two-Stream Convolutional Networks for Action Recognition in Videos [[Paper]](https://papers.nips.cc/paper/5353-two-stream-convolutional-networks-for-action-recognition-in-videos.pdf)
- Action Recognition with Trajectory-Pooled Deep-Convolutional Descriptors [[Paper]](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wang_Action_Recognition_With_2015_CVPR_paper.pdf)
- Non-local neural networks [[Paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Non-Local_Neural_Networks_CVPR_2018_paper.pdf) [[GitHub]](https://github.com/facebookresearch/video-nonlocal-net)
  - Wang, Xiaolong, Ross Girshick, Abhinav Gupta, and Kaiming He. (*CVPR 2018*)
  - Summary: 
- Learning Correspondence from the Cycle-consistency of Time [[Paper]](https://arxiv.org/pdf/1903.07593.pdf) [[GitHub]](https://github.com/xiaolonw/TimeCycle)
  - Xiaolong Wang and Allan Jabri and Alexei A. Efros (*CVPR2019*)
  - Summary: 
- 3D ConvNets in Pytorch [[GitHub]](https://github.com/Tushar-N/pytorch-resnet3d)

### Multimodal For video Analysis
- Awsome list for multimodal learning [[GitHub]](https://github.com/pliang279/multimodal-ml-reading-list)
- VideoBERT: A Joint Model for Video and Language Representation Learning [[Paper]](https://arxiv.org/abs/1904.01766)
- AENet: Learning Deep Audio Features for Video Analysis [[Paper]](https://arxiv.org/pdf/1701.00599.pdf) [[GitHub]](https://github.com/znaoya/aenet)
- Look, Listen and Learn [[Paper]](https://arxiv.org/pdf/1705.08168.pdf)
- Objects that Sound [[Paper]](https://arxiv.org/pdf/1712.06651)
- Learning to Separate Object Sounds by Watching Unlabeled Video [[Paper]](https://arxiv.org/pdf/1804.01665.pdf)
  - Gao, Ruohan, Rogerio Feris, and Kristen Grauman. *arXiv preprint arXiv:1804.01665 2018*
- Ambient Sound Provides Supervision for Visual Learning [[Paper]](http://www.eccv2016.org/files/posters/O-1B-01.pdf)
  - Owens, Andrew, Jiajun Wu, Josh H. McDermott, William T. Freeman, and Antonio Torralba. *ECCV 2016*
  - Summary: unsupervised learning
- Learning Cross-Modal Temporal Representations from Unlabeled Videos [[Google Blog]](https://ai.googleblog.com/2019/09/learning-cross-modal-temporal.html?m=1)

### Video Moment Localization

- Localizing Moments in Video with Natural Language [[Paper]](https://arxiv.org/pdf/1708.01641.pdf)[[GitHub]](https://github.com/LisaAnne/LocalizingMoments)

### Video Retrieval
- Use What You Have: Video retrieval using representations from collaborative experts [[GitHub]](https://github.com/albanie/collaborative-experts)
- HowTo100M: Learning a Text-Video Embedding by Watching Hundred Million Narrated Video Clips [[Project Website]](https://www.di.ens.fr/willow/research/howto100m/)
  - Miech, Antoine, et al. (arXiv:1906.03327 (2019))
- Learning a Text-Video Embedding from Incomplete and Heterogeneous Data." [[Paper]](https://arxiv.org/pdf/1804.02516.pdf)[[GitHub]](https://github.com/antoine77340/Mixture-of-Embedding-Experts)
  - Miech, Antoine, Ivan Laptev, and Josef Sivic. *ECCV 2018*
  - Summary: combine multi-modality information, calculate similarities and weight different similarities
- Cross-Modal and Hierarchical Modeling of Video and Text [[Paper]](https://arxiv.org/pdf/1810.07212.pdf)
  - B. Zhang * , H. Hu * , F. Sha *ECCV 2018*
  - Summary: learning the intrinsic hierarchical structures of both videos and texts. (Make video and text closer, make videos closer and make text closer)
- A dataset for movie description. [[Paper]](https://arxiv.org/pdf/1501.02530.pdf)
  - Rohrbach, Anna, Marcus Rohrbach, Niket Tandon, and Bernt Schiele. *CVPR 2015*
  - Summary: dataset paper
- Web-scale Multimedia Search for Internet Video Content. [[Thesis]](http://www.lujiang.info/resources/Thesis.pdf)
  - Lu Jiang
  - Summary: amazing thesis
  
### Video Advertisement (Also include some image advertisement paper)

- Automatic understanding of image and video advertisements [[Paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Hussain_Automatic_Understanding_of_CVPR_2017_paper.pdf) [[Project]](http://people.cs.pitt.edu/~kovashka/ads/)
  - Hussain, Zaeem, Mingda Zhang, Xiaozhong Zhang, Keren Ye, Christopher Thomas, Zuha Agha, Nathan Ong, and Adriana Kovashka. *CVPR 2017*
  - Summary: Image and video advertisement datasets and baselines.
- Multimodal Representation of Advertisements Using Segment-level Autoencoders [[Paper]](https://sail.usc.edu/publications/files/p418-somandepalli.pdf) [[GitHub]](https://github.com/usc-sail/mica-multimodal-ads)
  - Somandepalli, Krishna, Victor Martinez, Naveen Kumar, and Shrikanth Narayanan. *ICMI 2018*
  - Summary: video and audio features to understand whether video is funny or not.
- Story Understanding in Video Advertisements. [[Paper]](http://people.cs.pitt.edu/~kovashka/ye_buettner_kovashka_bmvc2018.pdf) [[GitHub]](https://github.com/yekeren/Story-Video_ads_understanding)
  - Keren Ye, Kyle Buettner, Adriana Kovashka *BMVC 2018*
  - Summary: Combine multiple features including climax, audio and so on to analyze video ads. 
- ADVISE: Symbolism and External Knowledge for Decoding Advertisements. [[Paper]](http://people.cs.pitt.edu/~kovashka/ye_kovashka_advise_eccv2018.pdf) [[GitHub]](https://github.com/yekeren/ADVISE)
  - Keren Ye and Adriana Kovashka. (*ECCV2018*)
  - Summary: action-reason statement for advertisement. Many pre-trained models are as prior knowledge. SSD, DenseCAP and GloVe.

### Visual Commonsense Reasoning 

- From Recognition to Cognition: Visual Commonsense Reasoning [[Paper]](https://arxiv.org/pdf/1811.10830.pdf) [[Project Website]](https://visualcommonsense.com/)
  - Rowan Zellers, Yonatan Bisk, Ali Farhadi, Yejin Choi (*CVPR2019*)
  - Summary: First dataset paper. Use BERT and fastrcnn as the baseline

### Video Highlight Prediction

- Video highlight prediction using audience chat reactions
  - Fu, Cheng-Yang, Joon Lee, Mohit Bansal, and Alexander C. Berg. (*EMNLP 2017*)
  
### Object Tracking

- SenseTime's research platform for single object tracking research, implementing algorithms like SiamRPN and SiamMask. [[GitHub]](https://github.com/STVIR/pysot)

### Audio-Visual Dialog

- Audio-Visual Scene-Aware Dialog [[GitHub]](https://github.com/batra-mlp-lab/avsd)
  - Alamri, Huda, Vincent Cartillier, Abhishek Das, Jue Wang, Stefan Lee, Peter Anderson, Irfan Essa et al.
  - arXiv preprint arXiv:1901.09107 (2019) 


