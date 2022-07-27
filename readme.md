# awesome-talking-head-generation  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Papers for Talking Head Generation, released codes collections.

This repo mainly focus on the image-driven talking head generation task, but any addition or bug about other domain talking head generation,please open an issue, pull requests or e-mail me by `fhongac@cse.ust.hk` 

## Related Group
0. [MMLab@NTU](https://www.mmlab-ntu.com)

## Datasets
0. VoxCeleb1 [[`Download link`](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html)].
1. VoxCeleb2 [[`Download link`](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)].
2. Faceforensics++ [[`Download link`](https://github.com/ondyari/FaceForensics)].
3. CelebV [[`Download link`](https://drive.google.com/file/d/1jQ6d76T5GQuvQH4dq8_Wq1T0cxvN0_xp/view)].
4. TalkingHead-1KH [[`Download link`](https://github.com/deepimagination/TalkingHead-1KH)].
5. LRW (Lip Reading in the Wild) [[`Download link`](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html)].
-----
## Image-driven
### 2016
1. <span id = "16001">[Face2face]</span> [Face2face: Real-time face capture and reenactment of RGB videos](http://openaccess.thecvf.com/content_cvpr_2016/html/Thies_Face2Face_Real-Time_Face_CVPR_2016_paper.html), `CVPR 2016`. 
### 2018
1. <span id = "18001">[ReenactGAN]</span> [ReenactGAN: Learning to Reenact Faces via Boundary Transfer](https://wywu.github.io/projects/ReenactGAN/support/ReenactGAN.pdf), `ECCV 2018`. [[Code](https://github.com/wywu/ReenactGAN)].
2. <span id = "18002">[X2Face]</span> [X2Face: A network for controlling face generation by using images, audio, and pose codes](http://www.robots.ox.ac.uk/~vgg/publications/2018/Wiles18/wiles18.pdf), `ECCV 2018`. [[Code](https://github.com/oawiles/X2Face)], [[Project](https://www.robots.ox.ac.uk/~vgg/research/unsup_learn_watch_faces/x2face.html)].

### 2019
1. <span id = "19001">[FOMM]</span> [First order motion model for image animation](http://papers.nips.cc/paper/8935-first-order-motion-model-for-image-animation.pdf), `NeurIPS 2019`. [[Code](https://github.com/AliaksandrSiarohin/first-order-model)].
2. <span id = "19002">[NeuralHead]</span>[Few-Shot Adversarial Learning of 
Realistic Neural Talking Head models](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwif8Y6R_Mb1AhVjH0QIHcQZDpwQFnoECDQQAQ&url=https%3A%2F%2Fopenaccess.thecvf.com%2Fcontent_ICCV_2019%2Fpapers%2FZakharov_Few-Shot_Adversarial_Learning_of_Realistic_Neural_Talking_Head_Models_ICCV_2019_paper.pdf&usg=AOvVaw1oKgCYySpv2cFHZ2mNI5A9), `ICCV 2019`. [[Code](https://github.com/vincent-thevenin/Realistic-Neural-Talking-Head-Models)].
3. <span id="19003">[Monkey-Net]</span>[Animating Arbitrary Objects via Deep Motion Transfer](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjnoOTYgsf1AhXsJ0QIHSF3A-sQFnoECAUQAQ&url=https%3A%2F%2Farxiv.org%2Fabs%2F1812.08861&usg=AOvVaw2fzcaa6nXcI9MiH8uIFNfJ), `CVPR 2019 Oral`. [[Code](https://github.com/AliaksandrSiarohin/monkey-net)], [[Project](http://www.stulyakov.com/papers/monkey-net.html)].
3. <span id = "19003">[fs-vid2vid]</span>[Few-shot Video-to-Video Synthesis](https://nvlabs.github.io/few-shot-vid2vid/main.pdf), `NeurIPS 2019`. [[Code](https://github.com/NVlabs/few-shot-vid2vid)], [[Project](https://nvlabs.github.io/few-shot-vid2vid/)].

### 2020
1. <span id = "20001">[MeshG]</span> [Mesh Guided One-shot Face Reenactment Using Graph Convolutional Networks](https://dl.acm.org/doi/pdf/10.1145/3394171.3413865g), `ACM Multimedia 2020`. [[Code](https://arxiv.org/abs/2008.07783)].
2. <span id = "20002">[MarioNETte]</span> [MarioNETte: Few-shot Face Reenactment 
Preserving Identity of Unseen Targets](https://arxiv.org/abs/1911.08139), `AAAI 2020`. [[Project](https://hyperconnect.github.io/MarioNETte/)].

### 2021
1. <span id = "21001">[face-vid2vid]</span> [One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://nvlabs.github.io/face-vid2vid/main.pdf), `CVPR 2021 Oral`. [[Project](https://nvlabs.github.io/face-vid2vid/)].
2. <span id="21002">[S2D]</span> [Sparse to Dense Motion Transfer for Face Image Animation](https://openaccess.thecvf.com/content/ICCV2021W/AIM/papers/Zhao_Sparse_to_Dense_Motion_Transfer_for_Face_Image_Animation_ICCVW_2021_paper.pdf), `ICCV 2021`.
3. <span id="21003">[SAFA]</span> [SAFA: Structure Aware Face Animation](https://arxiv.org/pdf/2111.04928.pdf), `3DV 2021`. [[Code](https://github.com/Qiulin-W/SAFA)]
4. <span id="21004">[SAA]</span> [Self-appearance-aided Differential Evolution for Motion Transfer](https://arxiv.org/abs/2110.04658), `arXiv 2021`.
5. <span id="21005">[PIRenderer]</span>[PIRenderer: Controllable Portrait Image Generation via Semantic Neural Rendering](https://arxiv.org/pdf/2109.08379.pdf), `ICCV 2021`. [[Code](https://github.com/RenYurui/PIRender)]

6. <span id="21006">[FaceGAN]</span>[FACEGAN: Facial Attribute Controllable rEenactment GAN](https://openaccess.thecvf.com/content/WACV2021/papers/Tripathy_FACEGAN_Facial_Attribute_Controllable_rEenactment_GAN_WACV_2021_paper.pdf), `WACV 2021`.

7. <span id="21007">[F^3A-GAN]</span>[F3A-GAN: Facial Flow for Face Animation With Generative Adversarial Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9547053), `IEEE TIP 2021`.

### 2022
1. <span id="22001">[DaGAN]</span>[Depth-Aware Generative Adversarial Network for Talking Head Video Generation](https://arxiv.org/abs/2203.06605), `CVPR 2022`. [[Code](https://github.com/harlanhong/CVPR2022-DaGAN)], [[Project](https://harlanhong.github.io/publications/dagan.html)]

2. <span id="22002">[TPSM]</span>[Thin-Plate Spline Motion Model for Image Animation](https://arxiv.org/abs/2203.06605), `CVPR 2022`. [[Code](https://github.com/yoyo-nb/Thin-Plate-Spline-Motion-Model)]

3. <span id="22003">[StyleHEAT]</span>[StyleHEAT: One-Shot High-Resolution Editable Talking Face Generation via Pretrained StyleGAN](https://arxiv.org/pdf/2203.04036.pdf), `ECCV 2022`. [[Code](https://github.com/FeiiYin/StyleHEAT/)], [[Project](https://feiiyin.github.io/StyleHEAT/)]

4. <span id="22004">[MegaPortraits]</span>[MegaPortraits: One-shot Megapixel Neural Head Avatars](https://arxiv.org/abs/2207.07621), `ACM MM 2022`. [[Project](https://samsunglabs.github.io/MegaPortraits/)]
----
## Audio-driven
### 2016
1. <span id="a16001">[LRW]</span> [Lip Reading in the Wild](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16/chung16.pdf), `ACCV 2016`. 
### 2019
1. <span id="a19001">[DAVS]</span> [Talking Face Generation by Adversarially Disentangled Audio-Visual Representation](https://arxiv.org/abs/1807.07860), `AAAI 2019`. [[Code](https://github.com/Hangz-nju-cuhk/Talking-Face-Generation-DAVS)].
2. <span id="a19002">[ATVGnet]</span> [Hierarchical Cross-modal Talking Face Generation with Dynamic Pixel-wise Loss](https://www.cs.rochester.edu/~cxu22/p/cvpr2019_facegen_paper.pdf), `CVPR 2019`. [[Code](https://github.com/lelechen63/ATVGnet)]
### 2020
1. <span id= "a20001">[Wav2Lip]</span> [A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild](http://arxiv.org/abs/2008.10010), `ACM Multimedia 2020`. [[Code](https://github.com/Rudrabha/Wav2Lip)], [[Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/a-lip-sync-expert-is-all-you-need-for-speech-to-lip-generation-in-the-wild/)].
2. <span id="a20002">[RhythmicHead]</span>[Talking-head Generation with Rhythmic Head Motion](https://arxiv.org/pdf/2007.08547v1.pdf), `ECCV 2020`. [[Code](https://github.com/lelechen63/Talking-head-Generation-with-Rhythmic-Head-Motion)].
3. <span id="a20003">[MakeItTalk]</span> [MakeItTalk: Speaker-Aware Talking-Head Animation](), `SIGGRAPH Asia 2020`. [[Code](https://github.com/yzhou359/MakeItTalk)], [[Project](https://people.umass.edu/~yangzhou/MakeItTalk/)].
### 2021
1. <span id="a21001">[PC-AVS]</span> [Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://arxiv.org/abs/2104.11116), `CVPR 2021`. [[Code](https://github.com/Hangz-nju-cuhk/Talking-Face_PC-AVS)], [[Project](https://hangz-nju-cuhk.github.io/projects/PC-AVS)].
2. <span id="a21002">[IATS]</span>[Imitating Arbitrary Talking Style for Realistic Audio-Driven Talking Face Synthesis](https://dl.acm.org/doi/pdf/10.1145/3474085.3475280),`ACM Multimedia 2021`..
3. <span id="a21003">[EVP]</span> [Audio-Driven Emotional Video Portraits](https://openaccess.thecvf.com/content/CVPR2021/papers/Ji_Audio-Driven_Emotional_Video_Portraits_CVPR_2021_paper.pdf), `CVPR 2021`. [[Code](https://github.com/jixinya/EVP)]
4. <span id="a21004">[FAU]</span> [Talking Head Generation with Audio and Speech Related Facial Action Units](https://arxiv.org/pdf/2110.09951.pdf), `arxiv 2021`.
5. <span id="a21005">[Speech2Talking-Face]</span> [Speech2Talking-Face: Inferring and Driving a Face with Synchronized Audio-Visual Representation](https://www.ijcai.org/proceedings/2021/0141.pdf), `IJCAI 2021`.
6. <span id="a21006">[IATS]</span> [Imitating Arbitrary Talking Style for Realistic Audio-Driven Talking Face Synthesis](https://arxiv.org/abs/2111.00203), `ACM MM 2021`.
7. <span id="a21007">[LSP]</span> [Live Speech Portraits: Real-Time Photorealistic Talking-Head Animation](https://arxiv.org/abs/2109.10595), `ACM TOG 2021`.
8. <span id="a21008">[Audio2head]</span> [Audio2head: Audio-driven one-shot talking-head generation with natural head motion](https://arxiv.org/pdf/2107.09293), `ArXiv 2021`.


### 2022
1. <span id="a22001">[GC-AVT]</span> [Expressive Talking Head Generation with Granular Audio-Visual Control ](https://openaccess.thecvf.com/content/CVPR2022/papers/Liang_Expressive_Talking_Head_Generation_With_Granular_Audio-Visual_Control_CVPR_2022_paper.pdf), `CVPR 2022`.

----
## Nerf-Head
### 2021
1. <span id="n21001">[DFA-NeRF]</span> [DFA-NeRF: Personalized Talking Head Generation via Disentangled Face Attributes Neural Rendering](https://arxiv.org/pdf/2201.00791v1.pdf), `arxiv, 2021`.
2. <span id="n21002">[NerFACE]</span> [NerFACE: Dynamic Neural Radiance Fields for Monocular 4D Facial Avatar Reconstruction](https://arxiv.org/pdf/2012.03065), `CVPR 2021 Oral`. [[Code](https://github.com/gafniguy/4D-Facial-Avatars)], [[Project](https://gafniguy.github.io/4D-Facial-Avatars/)]
### 2022
1. <span id="n22001">[SSP-NeRFF]</span> [Semantic-Aware Implicit Neural Audio-Driven Video Portrait Generation](https://arxiv.org/pdf/2201.07786.pdf), `arxiv, 2022`.
2. <span id="n22002">[HeadNeRF]</span> [HeadNeRF: A Real-time NeRF-based Parametric Head Model](https://openaccess.thecvf.com/content/CVPR2022/papers/Grassal_Neural_Head_Avatars_From_Monocular_RGB_Videos_CVPR_2022_paper.pdf), `CVPR 2022`. [[Code](https://github.com/CrisHY1995/headnerf)], [[Project](https://hy1995.top/HeadNeRF-Project/)]
3. <span id="n22003">[IMavatar]</span> [I M Avatar: Implicit Morphable Head Avatars from Videos
](https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_I_M_Avatar_Implicit_Morphable_Head_Avatars_From_Videos_CVPR_2022_paper.pdf), `CVPR 2022`. [[Code](https://ait.ethz.ch/projects/2022/IMavatar/)]
4. <span id="n22004">[ROME]</span> [Realistic One-shot Mesh-based Head Avatars
](https://arxiv.org/pdf/2206.08343.pdf), `ECCV 2022`.

----
## Parameter-Based
### 2020
1. <span id="p20001">[DiscoFaceGAN
]</span> [Disentangled and Controllable Face Image Generation via 3D Imitative-Contrastive Learning
](), `CVPR 2020 Oral`. [[Code](https://github.com/microsoft/DiscoFaceGAN)].

## Survey

### 2020
1. <span id="s20001">[What comprises a good talking-head video generation?: A Survey and Benchmark](https://arxiv.org/pdf/2005.03201v1.pdf).

