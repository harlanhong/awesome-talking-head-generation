# awesome-talking-head-generation  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
Papers for Talking Head Generation, released codes collections.

Any addition or bug please open an issue, pull requests or e-mail me by `fhongac@cse.ust.hk` 

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
1. <span id = "16001">[Face2face]</span> [Face2face: Real-time face capture and reenactment of RGB videos](http://openaccess.thecvf.com/content_cvpr_2016/html/Thies_Face2Face_Real-Time_Face_CVPR_2016_paper.html), `CVPR 16`. 
### 2018
1. <span id = "18001">[ReenactGAN]</span> [ReenactGAN: Learning to Reenact Faces via Boundary Transfer](https://wywu.github.io/projects/ReenactGAN/support/ReenactGAN.pdf), `ECCV 18`. [[Code](https://github.com/wywu/ReenactGAN)].
2. <span id = "18002">[X2Face]</span> [X2Face: A network for controlling face generation by using images, audio, and pose codes](http://www.robots.ox.ac.uk/~vgg/publications/2018/Wiles18/wiles18.pdf), `ECCV 18`. [[Code](https://github.com/oawiles/X2Face)], [[Project](https://www.robots.ox.ac.uk/~vgg/research/unsup_learn_watch_faces/x2face.html)].

### 2019
1. <span id = "19001">[FOMM]</span> [First order motion model for image animation](http://papers.nips.cc/paper/8935-first-order-motion-model-for-image-animation.pdf), `NeurIPS 19`. [[Code](https://github.com/AliaksandrSiarohin/first-order-model)].
2. <span id = "19002">[NeuralHead]</span>[Few-Shot Adversarial Learning of 
Realistic Neural Talking Head models](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwif8Y6R_Mb1AhVjH0QIHcQZDpwQFnoECDQQAQ&url=https%3A%2F%2Fopenaccess.thecvf.com%2Fcontent_ICCV_2019%2Fpapers%2FZakharov_Few-Shot_Adversarial_Learning_of_Realistic_Neural_Talking_Head_Models_ICCV_2019_paper.pdf&usg=AOvVaw1oKgCYySpv2cFHZ2mNI5A9), `ICCV 19`. [[Code](https://github.com/vincent-thevenin/Realistic-Neural-Talking-Head-Models)].
3. <span id="19003">[Monkey-Net]</span>[Animating Arbitrary Objects via Deep Motion Transfer](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjnoOTYgsf1AhXsJ0QIHSF3A-sQFnoECAUQAQ&url=https%3A%2F%2Farxiv.org%2Fabs%2F1812.08861&usg=AOvVaw2fzcaa6nXcI9MiH8uIFNfJ), `CVPR 19 Oral`. [[Code](https://github.com/AliaksandrSiarohin/monkey-net)], [[Project](http://www.stulyakov.com/papers/monkey-net.html)].
3. <span id = "19003">[fs-vid2vid]</span>[Few-shot Video-to-Video Synthesis](https://nvlabs.github.io/few-shot-vid2vid/main.pdf), `NeurIPS 19`. [[Code](https://github.com/NVlabs/few-shot-vid2vid)], [[Project](https://nvlabs.github.io/few-shot-vid2vid/)].

### 2020
1. <span id = "20001">[MeshG]</span> [Mesh Guided One-shot Face Reenactment Using Graph Convolutional Networks](http://papers.nips.cc/paper/8935-first-order-motion-model-for-image-animation.pdf), `ACM Multimedia 20`. [[Code](https://arxiv.org/abs/2008.07783)].
2. <span id = "20002">[MarioNETte]</span> [MarioNETte: Few-shot Face Reenactment 
Preserving Identity of Unseen Targets](https://arxiv.org/abs/1911.08139), `AAAI 20`. [[Project](https://hyperconnect.github.io/MarioNETte/)].

### 2021
1. <span id = "21001" >[face-vid2vid]</span> [One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://nvlabs.github.io/face-vid2vid/main.pdf), `CVPR 21 Oral`. [[Project](https://nvlabs.github.io/face-vid2vid/)].
----
## Audio-driven
### 2019
1. <span id="a19001">[DAVS]</span> [Talking Face Generation by Adversarially Disentangled Audio-Visual Representation](https://arxiv.org/abs/1807.07860), `AAAI 19`. [[Code](https://github.com/Hangz-nju-cuhk/Talking-Face-Generation-DAVS)].
2. <span id="a19002">[ATVGnet]</span> [Hierarchical Cross-modal Talking Face Generation with Dynamic Pixel-wise Loss](https://www.cs.rochester.edu/~cxu22/p/cvpr2019_facegen_paper.pdf), ``. [[Code](https://github.com/lelechen63/ATVGnet)]
### 2020
1. <span id= "a20001">[Wav2Lip]</span> [A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild](http://arxiv.org/abs/2008.10010), `ACM Multimedia 20`. [[Code](https://github.com/Rudrabha/Wav2Lip)], [[Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/a-lip-sync-expert-is-all-you-need-for-speech-to-lip-generation-in-the-wild/)].
2. <span id="a20002">[RhythmicHead]</span>[Talking-head Generation with Rhythmic Head Motion](https://arxiv.org/pdf/2007.08547v1.pdf), `ECCV 20`. [[Code](https://github.com/lelechen63/Talking-head-Generation-with-Rhythmic-Head-Motion)].
3. <span id="a20003">[MakeItTalk]</span> [MakeItTalk: Speaker-Aware Talking-Head Animation](), `SIGGRAPH Asia 2020`. [[Code](https://github.com/yzhou359/MakeItTalk)], [[Project](https://people.umass.edu/~yangzhou/MakeItTalk/)].
### 2021
1. <span id="a21001">[PC-AVS]</span> [Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://arxiv.org/abs/2104.11116), `CVPR 21`. [[Code](https://github.com/Hangz-nju-cuhk/Talking-Face_PC-AVS)], [[Project](https://hangz-nju-cuhk.github.io/projects/PC-AVS)].

----
## Nerf-Head
### 2021
1. <span id="n21001">[DFA-NeRF]</span> [DFA-NeRF: Personalized Talking Head Generation via Disentangled Face Attributes Neural Rendering](https://arxiv.org/pdf/2201.00791v1.pdf), `arxiv, 2021`.
----
## Parameter-Based
### 2020
1. <span id="p20001">[DiscoFaceGAN
]</span> [Disentangled and Controllable Face Image Generation via 3D Imitative-Contrastive Learning
](), `CVPR 20 Oral`. [[Code](https://github.com/microsoft/DiscoFaceGAN)].

## Survey

### 2020
1. <span id="s20001">[What comprises a good talking-head video generation?: A Survey and Benchmark](https://arxiv.org/pdf/2005.03201v1.pdf).