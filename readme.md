# awesome-talking-head-generation  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Papers for Talking Head Generation, released codes collections.

Any addition or bug about talking head generation,please open an issue, pull requests or e-mail me by `fhongac@cse.ust.hk`. If you are researching in talking head generation task, you can add my discord account: Fa-Ting Hong#6563 for better communication and cooperations.

 :fire:I am currently seeking a job or postdoctoral position. If you are interested in my qualifications and experience, please feel free to contact me. :fire: 

 :fire: We released a new work: ACTalker, which can generate portrait videos driven by both audio and expression simultaneously. Please view [HERE](https://harlanhong.github.io/publications/actalker/index.html) :fire: 

## Related Group

0. [MMLab@NTU](https://www.mmlab-ntu.com)
1. [Alibaba TongYi XR](https://github.com/HumanAIGC)

## Datasets

0. VoxCeleb1 [[`Download link`](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox1.html)].
1. VoxCeleb2 [[`Download link`](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/vox2.html)].
2. Faceforensics++ [[`Download link`](https://github.com/ondyari/FaceForensics)].
3. CelebV [[`Download link`](https://drive.google.com/file/d/1jQ6d76T5GQuvQH4dq8_Wq1T0cxvN0_xp/view)].
4. TalkingHead-1KH [[`Download link`](https://github.com/tcwang0509/TalkingHead-1KH)].
5. LRW (Lip Reading in the Wild) [[`Download link`](https://www.robots.ox.ac.uk/~vgg/data/lip_reading/lrw1.html)].
6. MEAD [[`Download link`](https://github.com/uniBruce/Mead)].
7. CelebV-HQ [[`Download link`](https://github.com/CelebV-HQ/CelebV-HQ)].
8. CHDTF [[`Download link`](https://medialab.sjtu.edu.cn/post/chdtf/)].
9. MultiTalk [[`Download link`](https://github.com/postech-ami/MultiTalk/tree/main/MultiTalk_dataset)].
10. VFHQ [[`Download link`](https://github.com/anjieyang/VFHQ-downloader)].
11. Hallo3 [[`Download link`](https://huggingface.co/datasets/fudan-generative-ai/hallo3_training_data)].

---

## Image-driven

### 2025

1. [HunyuanPortrait] [HunyuanPortrait: Implicit Condition Control for Enhanced Portrait Animation](https://arxiv.org/abs/2503.18860), `CVPR 2025`. [[Code](https://github.com/kkakkkka/HunyuanPortrait)] [[Project](https://kkakkkka.github.io/HunyuanPortrait)]

### 2024

1. [X-Portrait] [X-Portrait: Expressive Portrait Animation with Hierarchical Motion Attention](https://arxiv.org/abs/2403.15931), `arXiv 2024`.
2. [LivePortrait] [LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control](https://arxiv.org/pdf/2407.03168)  [[Code](https://github.com/KwaiVGI/LivePortrait)] [[Project](https://liveportrait.github.io)]
3. [EMOPortraits] [EMOPortraits: Emotion-enhanced Multimodal One-shot Head Avatars](https://arxiv.org/pdf/2404.19110),  `CVPR 2024`. [[Code](https://github.com/neeek2303/EMOPortraits)], [[Project](https://neeek2303.github.io/EMOPortraits/)]
4. [SMA] [Synergizing Motion and Appearance: Multi-Scale Compensatory Codebooks for Talking Head Video Generation](https://arxiv.org/abs/2412.00719),  `CVPR 2024`. [[Project](https://shaelynz.github.io/synergize-motion-appearance/)]

### 2023

1. [AVFR-GAN][Audio-Visual Face Reenactment](https://arxiv.org/pdf/2210.02755.pdf), `WACV 2023`. [[Code](https://github.com/mdv3101/AVFR-Gan/)], [[Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/avfr)]
2. [TS-Net][Cross-identity Video Motion Retargeting with Joint Transformation and Synthesis](https://arxiv.org/pdf/2210.01559.pdf), `WACV 2023`. [[Code](https://github.com/nihaomiao/WACV23_TSNet)]
2. [MCNET][Implicit Identity Representation Conditioned Memory Compensation Network for Talking Head Video Generation](https://arxiv.org/abs/2307.09906), `ICCV 2023`. [[Project](https://harlanhong.github.io/publications/mcnet.html)] [[Code](https://github.com/harlanhong/ICCV2023-MCNET)]

### 2022

1. [DaGAN][Depth-Aware Generative Adversarial Network for Talking Head Video Generation](https://arxiv.org/abs/2203.06605), `CVPR 2022`. [[Code](https://github.com/harlanhong/CVPR2022-DaGAN)], [[Project](https://harlanhong.github.io/publications/dagan.html)]
2. [TPSM][Thin-Plate Spline Motion Model for Image Animation](https://arxiv.org/abs/2203.14367), `CVPR 2022`. [[Code](https://github.com/yoyo-nb/Thin-Plate-Spline-Motion-Model)]
3. [StyleHEAT][StyleHEAT: One-Shot High-Resolution Editable Talking Face Generation via Pretrained StyleGAN](https://arxiv.org/pdf/2203.04036.pdf), `ECCV 2022`. [[Code](https://github.com/FeiiYin/StyleHEAT/)], [[Project](https://feiiyin.github.io/StyleHEAT/)]
4. [MegaPortraits][MegaPortraits: One-shot Megapixel Neural Head Avatars](https://arxiv.org/abs/2207.07621), `ACM MM 2022`. [[Project](https://samsunglabs.github.io/MegaPortraits/)]
5. [DAM][Structure-Aware Motion Transfer with Deformable Anchor Model](https://openaccess.thecvf.com/content/CVPR2022/papers/Tao_Structure-Aware_Motion_Transfer_With_Deformable_Anchor_Model_CVPR_2022_paper.pdf), `CVPR 2022`. [[Code](https://github.com/JialeTao/DAM)]
6. [StyleMask][StyleMask: Disentangling the Style Space of StyleGAN2 for Neural Face Reenactment](https://arxiv.org/pdf/2209.13375.pdf), `FG, 2023`. [[Code](https://github.com/StelaBou/StyleMask)]
7. [CoRF][Controllable Radiance Fields for Dynamic Face Synthesis](https://arxiv.org/pdf/2210.06465.pdf), `Arxiv 2022`. 
8. [AniFaceGAN][Animatable 3D-Aware Face Image Generation 
for Video Avatars](https://arxiv.org/pdf/2210.05825.pdf), `NeurIPS 2022`. [[Project](https://yuewuhkust.github.io/AniFaceGAN/)] 
9. [IW][Implicit Warping for Animation with Image Sets](https://arxiv.org/pdf/2210.01794.pdf), `NeurIPS 2022`. [[Project](https://deepimagination.cc/implicit_warping/)] 
10. [HifiHead][HifiHead: One-Shot High Fidelity Neural Head Synthesis with 3D Control](https://www.ijcai.org/proceedings/2022/0244.pdf), `IJCAI 2022`.
10. [Face Animation with Multiple Source Images](https://arxiv.org/pdf/2212.00256.pdf?), `Arxiv 2022`.
10. [MetaPortrait][MetaPortrait: Identity-Preserving Talking Head Generation with Fast Personalized Adaptation](https://download.arxiv.org/pdf/2212.08062v2), `Arxiv 2022`.
11. [Compressing Video Calls using Synthetic Talking Heads](https://arxiv.org/pdf/2210.03692.pdf), `BMVC 2022`. [[Project](https://cvit.iiit.ac.in/research/projects/cvit-projects/talking-video-compression)] 
12. [Finding Directions in GAN’s Latent Space for Neural Face Reenactment](https://arxiv.org/pdf/2202.00046.pdf), `BMVC 2022`. [[Project](https://stelabou.github.io/stylegan-directions-reenactment/)] [[Code](https://github.com/StelaBou/stylegan_directions_face_reenactment)] 
13. [LIA][Latent Image Animator: Learning to Animate Images via Latent Space Navigation](https://arxiv.org/pdf/2203.09043.pdf), `ICLR 2022`. [[Project](https://wyhsirius.github.io/LIA-project/)] [[Code](https://github.com/wyhsirius/LIA)] 

### 2021

1. [face-vid2vid] [One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://nvlabs.github.io/face-vid2vid/main.pdf), `CVPR 2021 Oral`. [[Project](https://nvlabs.github.io/face-vid2vid/)]
2. [S2D] [Sparse to Dense Motion Transfer for Face Image Animation](https://openaccess.thecvf.com/content/ICCV2021W/AIM/papers/Zhao_Sparse_to_Dense_Motion_Transfer_for_Face_Image_Animation_ICCVW_2021_paper.pdf), `ICCV 2021`.
3. [SAFA] [SAFA: Structure Aware Face Animation](https://arxiv.org/pdf/2111.04928.pdf), `3DV 2021`. [[Code](https://github.com/Qiulin-W/SAFA)]
4. [SAA] [Self-appearance-aided Differential Evolution for Motion Transfer](https://arxiv.org/abs/2110.04658), `arXiv 2021`.
5. [PIRenderer][PIRenderer: Controllable Portrait Image Generation via Semantic Neural Rendering](https://arxiv.org/pdf/2109.08379.pdf), `ICCV 2021`. [[Code](https://github.com/RenYurui/PIRender)]
6. [FaceGAN][FACEGAN: Facial Attribute Controllable rEenactment GAN](https://openaccess.thecvf.com/content/WACV2021/papers/Tripathy_FACEGAN_Facial_Attribute_Controllable_rEenactment_GAN_WACV_2021_paper.pdf), `WACV 2021`.
7. [F^3A-GAN][F3A-GAN: Facial Flow for Face Animation With Generative Adversarial Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9547053), `IEEE TIP 2021`.
8. [FACIAL][FACIAL: Synthesizing Dynamic Talking Face with Implicit Attribute Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_FACIAL_Synthesizing_Dynamic_Talking_Face_With_Implicit_Attribute_Learning_ICCV_2021_paper.pdf), `ICCV 2021`.
9. [MRAA][ Motion Representations for Articulated Animation](https://openaccess.thecvf.com/content/CVPR2021/papers/Siarohin_Motion_Representations_for_Articulated_Animation_CVPR_2021_paper.pdf), `CVPR 2021`. [[Code](https://github.com/snap-research/articulated-animation)]
10. [HeadGAN][HeadGAN: One-shot Neural Head Synthesis and Editing](https://arxiv.org/pdf/2012.08261.pdf), `ICCV 2021`. [[Project](https://michaildoukas.github.io/HeadGAN/)]

### 2020

1. [MeshG] [Mesh Guided One-shot Face Reenactment Using Graph Convolutional Networks](https://dl.acm.org/doi/pdf/10.1145/3394171.3413865g), `ACM Multimedia 2020`. [[Code](https://arxiv.org/abs/2008.07783)]
2. [MarioNETte] [MarioNETte: Few-shot Face Reenactment Preserving Identity of Unseen Targets](https://arxiv.org/abs/1911.08139), `AAAI 2020`. [[Project](https://hyperconnect.github.io/MarioNETte/)]
3. [CrossID-GAN] [Learning Identity-Invariant Motion Representations for Cross-ID Face Reenactment](https://openaccess.thecvf.com/content_CVPR_2020/papers/Huang_Learning_Identity-Invariant_Motion_Representations_for_Cross-ID_Face_Reenactment_CVPR_2020_paper.pdf), `CVPR 2020`.

### 2019

1. [FOMM] [First order motion model for image animation](http://papers.nips.cc/paper/8935-first-order-motion-model-for-image-animation.pdf), `NeurIPS 2019`. [[Code](https://github.com/AliaksandrSiarohin/first-order-model)]
2. [NeuralHead][Few-Shot Adversarial Learning of
   Realistic Neural Talking Head models](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwif8Y6R_Mb1AhVjH0QIHcQZDpwQFnoECDQQAQ&url=https%3A%2F%2Fopenaccess.thecvf.com%2Fcontent_ICCV_2019%2Fpapers%2FZakharov_Few-Shot_Adversarial_Learning_of_Realistic_Neural_Talking_Head_Models_ICCV_2019_paper.pdf&usg=AOvVaw1oKgCYySpv2cFHZ2mNI5A9), `ICCV 2019`. [[Code](https://github.com/vincent-thevenin/Realistic-Neural-Talking-Head-Models)]
3. [Monkey-Net][Animating Arbitrary Objects via Deep Motion Transfer](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjnoOTYgsf1AhXsJ0QIHSF3A-sQFnoECAUQAQ&url=https%3A%2F%2Farxiv.org%2Fabs%2F1812.08861&usg=AOvVaw2fzcaa6nXcI9MiH8uIFNfJ), `CVPR 2019 Oral`. [[Code](https://github.com/AliaksandrSiarohin/monkey-net)], [[Project](http://www.stulyakov.com/papers/monkey-net.html)]
4. [fs-vid2vid][Few-shot Video-to-Video Synthesis](https://nvlabs.github.io/few-shot-vid2vid/main.pdf), `NeurIPS 2019`. [[Code](https://github.com/NVlabs/few-shot-vid2vid)], [[Project](https://nvlabs.github.io/few-shot-vid2vid/)]

### 2018

1. [ReenactGAN] [ReenactGAN: Learning to Reenact Faces via Boundary Transfer](https://wywu.github.io/projects/ReenactGAN/support/ReenactGAN.pdf), `ECCV 2018`. [[Code](https://github.com/wywu/ReenactGAN)]
2. [X2Face] [X2Face: A network for controlling face generation by using images, audio, and pose codes](http://www.robots.ox.ac.uk/~vgg/publications/2018/Wiles18/wiles18.pdf), `ECCV 2018`. [[Code](https://github.com/oawiles/X2Face)], [[Project](https://www.robots.ox.ac.uk/~vgg/research/unsup_learn_watch_faces/x2face.html)]

### 2016

1. [Face2face] [Face2Face: Real-time face capture and reenactment of RGB videos](http://openaccess.thecvf.com/content_cvpr_2016/html/Thies_Face2Face_Real-Time_Face_CVPR_2016_paper.html), `CVPR 2016`.

---

## Audio-driven

### 2025

1. [OmniHuman-1][OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models](https://arxiv.org/abs/2502.01061),  `arXiv 2025`. [[Project](https://omnihuman-lab.github.io/)]
2. [ACTalker][Audio-visual Controlled Video Diffusion with Masked Selective State Spaces Modelling for Natural Talking Head Generation](https://arxiv.org/abs/2504.02542),  `arXiv 2025`. [[Project](https://harlanhong.github.io/publications/actalker/index.html)]

### 2024

1. [Real3DPortrait] [Real3D-Portrait: One-shot Realistic 3D Talking Portrait Synthesis](https://arxiv.org/pdf/2401.08503.pdf), `ICLR 2024`. [[Project](https://real3dportrait.github.io/)] [[Code](https://github.com/yerfor/Real3DPortrait)]
2. [EMO] [Emote Portrait Alive - Generating Expressive Portrait Videos with Audio2Video Diffusion Model under Weak Conditions](https://arxiv.org/pdf/2402.17485.pdf), `arXiv 2024`.  [[Project](https://humanaigc.github.io/emote-portrait-alive/)] [[Code](https://github.com/HumanAIGC/EMO)]
3. [Style2Talker] [Style2Talker: High-Resolution Talking Head Generation with Emotion Style and Art Style](https://arxiv.org/pdf/2403.06365.pdf), `AAAI 2024`.
4. [SaaS] [Say Anything with Any Style](https://arxiv.org/abs/2403.06363), `AAAI 2024`.
5. [MuseTalk] Real-Time High Quality Lip Synchorization with Latent Space Inpainting, [[Code](https://github.com/TMElyralab/MuseTalk)].
6. [VASA-1] [VASA-1: Lifelike Audio-Driven Talking Faces Generated in Real Time]((https://arxiv.org/abs/2404.10667)), `arXiv 2024`. [[Project](https://www.microsoft.com/en-us/research/project/vasa-1/)]
7. [THQA] [THQA: A Perceptual Quality Assessment Database for Talking Heads](https://arxiv.org/abs/2404.09003), `arXiv 2024`. [[Code](https://github.com/zyj-2000/THQA)]
8. [Talk3D] [Talk3D: High-Fidelity Talking Portrait Synthesis via Personalized 3D Generative Prior](https://arxiv.org/abs/2403.20153), `arXiv 2024`. [[Code](https://github.com/KU-CVLAB/Talk3D)] [[Project](https://ku-cvlab.github.io/Talk3D/)]
9. [EDTalk] [EDTalk: Efficient Disentanglement for Emotional Talking Head Synthesis](https://arxiv.org/abs/2404.01647), `arXiv 2024`. [[Code](https://github.com/tanshuai0219/EDTalk)] [[Project](https://tanshuai0219.github.io/EDTalk/)]
10. [AniPortrait] [AniPortrait: Audio-Driven Synthesis of Photorealistic Portrait Animations](https://arxiv.org/abs/2403.17694), `arXiv 2024`. [[Code](https://github.com/Zejun-Yang/AniPortrait)]
11. [FlowVQTalker] [FlowVQTalker: High-Quality Emotional Talking Face Generation through Normalizing Flow and Quantization](https://arxiv.org/abs/2403.06375), `arXiv 2024`.
12. [FaceChain-ImagineID] [FaceChain-ImagineID: Freely Crafting High-Fidelity Diverse Talking Faces from Disentangled Audio](https://arxiv.org/abs/2403.01901), `arXiv 2024`. [[Code](https://github.com/modelscope/facechain)]
13. [Hallo] [Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation](https://arxiv.org/pdf/2406.08801), `arXiv 2024`. [[Code](https://github.com/fudan-generative-vision/hallo)]
14. [EchoMimic][EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions](https://arxiv.org/abs/2407.08136),  `arXiv 2024`. [[Code](https://github.com/BadToBest/EchoMimic)], [[Project](https://badtobest.github.io/echomimic.html)]
15. [RealTalk][RealTalk: Real-time and Realistic Audio-driven Face Generation with 3D Facial Prior-guided Identity Alignment Network](https://arxiv.org/abs/2406.18284),  `arXiv 2024`.
16. [Emotional Conversation][Emotional Conversation: Empowering Talking Faces with Cohesive Expression, Gaze and Pose Generation](https://arxiv.org/abs/2406.07895),  `arXiv 2024`.
17. [Make Your Actor Talk][Make Your Actor Talk: Generalizable and High-Fidelity Lip Sync with Motion and Appearance Disentanglement](https://arxiv.org/abs/2406.08096),  `arXiv 2024`.
18. [FD2Talk][FD2Talk: Towards Generalized Talking Head Generation with Facial Decoupled Diffusion Model](https://arxiv.org/pdf/2408.09384v1),  `arXiv 2024`.
19. [ReSyncer][ReSyncer: Rewiring Style-based Generator for Unified Audio-Visually Synced Facial Performer](https://arxiv.org/abs/2408.03284),  `arXiv 2024`.
20. [StyleSync][Style-Preserving Lip Sync via Audio-Aware Style Reference](https://arxiv.org/abs/2408.05412),  `arXiv 2024`.
21. [Loopy][Loopy: Taming Audio-Driven Portrait Avatar with Long-Term Motion Dependency](https://arxiv.org/pdf/2409.02634),  `arXiv 2024`. [[Project](https://loopyavatar.github.io)]
22. [DAWN][DAWN: Dynamic Frame Avatar with Non-autoregressive Diffusion Framework for Talking Head Video Generation](https://arxiv.org/abs/2410.13726),  `arXiv 2024`. [[Project](https://hanbo-cheng.github.io/DAWN/)], [[Code](https://github.com/Hanbo-Cheng/DAWN-pytorch)]
23. [EchoMimicV2][EchoMimicV2: Towards Striking, Simplified, and Semi-Body Human Animation](https://arxiv.org/abs/2411.10061),  `arXiv 2024`. [[Code](https://github.com/antgroup/echomimic_v2)], [[Project](https://antgroup.github.io/ai/echomimic_v2/)]
24. [LetsTalk][Latent Diffusion Transformer for Talking Video Synthesis](https://arxiv.org/abs/2411.16748),  `arXiv 2024`. [[Code](https://github.com/zhang-haojie/letstalk?tab=readme-ov-file)], [[Project](https://zhang-haojie.github.io/project-pages/letstalk.html)]
25. [IF-MDM][Implicit Face Motion Diffusion Model for High-Fidelity Realtime Talking Head Generation](https://arxiv.org/abs/2412.04000),  `arXiv 2024`. [[Project](http://ec2-3-25-102-128.ap-southeast-2.compute.amazonaws.com/IF-MDM/ifmdm_supplementary/index.html)]
26. [INFP][Audio-Driven Interactive Head Generation in Dyadic Conversations](https://arxiv.org/abs/2412.04037),  `arXiv 2024`. [[Project](https://grisoon.github.io/INFP/)]
27. [MEMO][Memory-Guided Diffusion for Expressive Talking Video Generation](https://arxiv.org/abs/2412.04448),  `arXiv 2024`. [[Project](https://memoavatar.github.io/)], [[Code](https://github.com/memoavatar/memo)]
28. [FLOAT][ Generative Motion Latent Flow Matching for Audio-driven Talking Portrait](https://arxiv.org/abs/2412.01064),  `arXiv 2024`. [[Project](https://deepbrainai-research.github.io/float/)]
29. [Hallo3][Highly Dynamic and Realistic Portrait Image Animation with Diffusion Transformer Networks](https://arxiv.org/abs/2412.00733),  `arXiv 2024`.
30. [VQTalker][VQTalker: Towards Multilingual Talking Avatars through Facial Motion Tokenization](https://arxiv.org/pdf/2412.09892),  `arXiv 2024`.
31. [PortraitTalk][Towards Customizable One-Shot Audio-to-Talking Face Generation](https://arxiv.org/abs/2412.07754),  `arXiv 2024`.
32. [IF-MDM][IF-MDM: Implicit Face Motion Diffusion Model for High-Fidelity Realtime Talking Head Generation](https://arxiv.org/abs/2412.04000),  `arXiv 2024`.
33. [LatentSync][LatentSync: Audio Conditioned Latent Diffusion Models for Lip Sync](https://arxiv.org/abs/2412.09262),  `arXiv 2024`. [[Code](https://github.com/bytedance/LatentSync)]

### 2023

1. [Diffused Heads] [Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation](https://mstypulkowski.github.io/diffusedheads/diffused_heads.pdf), `Arxiv 2023`. [[Project](https://mstypulkowski.github.io/diffusedheads/)] :fire:Diffusion:fire: 
2. [DiffTalk] [DiffTalk: Crafting Diffusion Models for Generalized Talking Head Synthesis](https://arxiv.org/abs/2301.03786), `Arxiv 2023`. [[Project](https://sstzal.github.io/DiffTalk/)] [[Code](https://github.com/sstzal/DiffTalk)] :fire:Diffusion:fire: 
3. [READ] [READ Avatars: Realistic Emotion-controllable Audio Driven Avatars](READ Avatars: Realistic Emotion-controllable Audio Driven Avatars), `Arxiv 2023`. 
4. [DAE-Talker] [DAE-Talker: High Fidelity Speech-Driven Talking Face Generation with Diffusion Autoencoder](https://arxiv.org/pdf/2303.17550.pdf), `Arxiv 2023`. :fire:Diffusion:fire: 
5. [EmoGen] [Emotionally Enhanced Talking Face Generation](https://arxiv.org/pdf/2303.11548.pdf), `Arxiv 2023`. [[Code](https://github.com/sahilg06/EmoGen)] 
6. [TalkLip] [Seeing What You Said: Talking Face Generation Guided by a Lip Reading Expert](https://arxiv.org/pdf/2303.17480.pdf), `CVPR 2023`. [[Code](https://github.com/Sxjdwang/TalkLip)] 
7. [StyleSync] [StyleSync: High-Fidelity Generalized and Personalized Lip Sync in Style-based Generator](https://arxiv.org/pdf/2305.05445.pdf), `CVPR 2023`. [[Project](https://hangz-nju-cuhk.github.io/projects/StyleSync)] [[Code](https://github.com/guanjz20/StyleSync)]
8. [GeneFace++] [GeneFace++: Generalized and Stable Real-Time Audio-Driven 3D Talking Face Generation](https://arxiv.org/pdf/2305.00787.pdf), `arXiv 2023`. [[Project](https://genefaceplusplus.github.io)] [[Code](https://github.com/yerfor/GeneFacePlusPlus)]
9. [MODA] [MODA: Mapping-Once Audio-driven Portrait Animation with Dual Attentions](https://arxiv.org/abs/2307.10008), `ICCV 2023`.
10. [VividTalk] [VividTalk: One-Shot Audio-Driven Talking Head Generation Based on 3D Hybrid Prior](https://arxiv.org/pdf/2312.01841.pdf), `Arxiv 2023`. [[Project](https://humanaigc.github.io/vivid-talk/)] [[Code](https://github.com/HumanAIGC/VividTalk)]
11. [IP_LAP] [IP_LAP: Identity-Preserving Talking Face Generation with Landmark and Appearance Priors](https://arxiv.org/abs/2305.08293), `CVPR 2023`. [[Code](https://github.com/Weizhi-Zhong/IP_LAP)]
12. [HyperLips] [HyperLips: Hyper Control Lips with High Resolution Decoder for Talking Face Generation](https://arxiv.org/abs/2310.05720), `CVPR 2023`. [[Code](https://github.com/semchan/HyperLips)]
13. [EAT] [Efficient Emotional Adaptation for Audio-Driven Talking-Head Generation](https://arxiv.org/abs/2309.04946), `ICCV 2023`. [[Project](https://yuangan.github.io/eat/)] [[Code](https://github.com/yuangan/EAT_code)]
14. [SadTalker] [SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Talking Head Animation](https://arxiv.org/pdf/2211.12194.pdf), `CVPR 2023`. [[Project](https://sadtalker.github.io)] [[Code](https://github.com/Winfredy/SadTalker)]

### 2022

1. [GC-AVT] [Expressive Talking Head Generation with Granular Audio-Visual Control ](https://openaccess.thecvf.com/content/CVPR2022/papers/Liang_Expressive_Talking_Head_Generation_With_Granular_Audio-Visual_Control_CVPR_2022_paper.pdf), `CVPR 2022`.
2. [Talking Face Generation with Multilingual TTS](https://openaccess.thecvf.com/content/CVPR2022/papers/Song_Talking_Face_Generation_With_Multilingual_TTS_CVPR_2022_paper.pdf), `CVPR 2022`. [[Demo Track](https://huggingface.co/spaces/CVPR/ml-talking-face)]
3. [EAMM] [EAMM: One-Shot Emotional Talking Face via Audio-Based Emotion-Aware Motion Model](https://arxiv.org/pdf/2205.15278.pdf), `SIGGRAPH 2022`.
4. [SPACEx] [SPACEx 🚀: Speech-driven Portrait Animation with Controllable Expression](https://arxiv.org/pdf/2211.09809.pdf), `arXiv 2022`. [[Project](https://deepimagination.cc/SPACEx/)] `CVPR 2023`
5. [AV-CAT] [Masked Lip-Sync Prediction by Audio-Visual Contextual Exploitation in Transformers](https://arxiv.org/pdf/2212.04970.pdf), `SIGGRAPH Asia 2022`. 
6. [MemFace] [Memories are One-to-Many Mapping Alleviators in Talking Face Generation](https://arxiv.org/pdf/2212.05005.pdf), `arXiv 2022`. 

### 2021

1. [PC-AVS] [Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://arxiv.org/abs/2104.11116), `CVPR 2021`. [[Code](https://github.com/Hangz-nju-cuhk/Talking-Face_PC-AVS)], [[Project](https://hangz-nju-cuhk.github.io/projects/PC-AVS)]
2. [IATS][Imitating Arbitrary Talking Style for Realistic Audio-Driven Talking Face Synthesis](https://dl.acm.org/doi/pdf/10.1145/3474085.3475280),`ACM Multimedia 2021`.
3. [EVP] [Audio-Driven Emotional Video Portraits](https://openaccess.thecvf.com/content/CVPR2021/papers/Ji_Audio-Driven_Emotional_Video_Portraits_CVPR_2021_paper.pdf), `CVPR 2021`. [[Code](https://github.com/jixinya/EVP)]
4. [FAU] [Talking Head Generation with Audio and Speech Related Facial Action Units](https://arxiv.org/pdf/2110.09951.pdf), `arxiv 2021`.
5. [Speech2Talking-Face] [Speech2Talking-Face: Inferring and Driving a Face with Synchronized Audio-Visual Representation](https://www.ijcai.org/proceedings/2021/0141.pdf), `IJCAI 2021`.
6. [IATS] [Imitating Arbitrary Talking Style for Realistic Audio-Driven Talking Face Synthesis](https://arxiv.org/abs/2111.00203), `ACM MM 2021`.
7. [LSP] [Live Speech Portraits: Real-Time Photorealistic Talking-Head Animation](https://arxiv.org/abs/2109.10595), `ACM TOG 2021`. [[Code](https://github.com/YuanxunLu/LiveSpeechPortraits)]
8. [Audio2head] [Audio2head: Audio-driven one-shot talking-head generation with natural head motion](https://arxiv.org/pdf/2107.09293), `ArXiv 2021`.

### 2020

1. [Wav2Lip] [A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild](http://arxiv.org/abs/2008.10010), `ACM Multimedia 2020`. [[Code](https://github.com/Rudrabha/Wav2Lip)], [[Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/a-lip-sync-expert-is-all-you-need-for-speech-to-lip-generation-in-the-wild/)]
2. [RhythmicHead] [Talking-head Generation with Rhythmic Head Motion](https://arxiv.org/pdf/2007.08547v1.pdf), `ECCV 2020`. [[Code](https://github.com/lelechen63/Talking-head-Generation-with-Rhythmic-Head-Motion)]
3. [MakeItTalk] [MakeItTalk: Speaker-Aware Talking-Head Animation](), `SIGGRAPH Asia 2020`. [[Code](https://github.com/yzhou359/MakeItTalk)], [[Project](https://people.umass.edu/~yangzhou/MakeItTalk/)]
4. [Neural Voice Puppetry] [Neural Voice Puppetry: Audio-driven Facial Reenactment](https://arxiv.org/abs/1912.05566), `ECCV 2020`. [[Code](https://github.com/keetsky/NeuralVoicePuppetry)], [[Project](https://justusthies.github.io/posts/neural-voice-puppetry/)]
5. [MEAD] [MEAD: A Large-scale Audio-visual Dataset for Emotional Talking-face Generation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660698.pdf), `ECCV 2020`. [[Code](https://github.com/uniBruce/Mead)], [[Project](https://wywu.github.io/projects/MEAD/MEAD.html)]
6. [Realistic Speech-Driven Facial Animation with GANs](https://arxiv.org/pdf/1906.06337.pdf), `IJCV 2020`.

### 2019

1. [DAVS] [Talking Face Generation by Adversarially Disentangled Audio-Visual Representation](https://arxiv.org/abs/1807.07860), `AAAI 2019`. [[Code](https://github.com/Hangz-nju-cuhk/Talking-Face-Generation-DAVS)]
2. [ATVGnet] [Hierarchical Cross-modal Talking Face Generation with Dynamic Pixel-wise Loss](https://www.cs.rochester.edu/~cxu22/p/cvpr2019_facegen_paper.pdf), `CVPR 2019`. [[Code](https://github.com/lelechen63/ATVGnet)]

### 2018

1. [Lip Movements Generation at a Glance](https://openaccess.thecvf.com/content_ECCV_2018/papers/Lele_Chen_Lip_Movements_Generation_ECCV_2018_paper.pdf), `ECCV 2018`. [[Code](https://github.com/lelechen63/3d_gan)]
2. [VisemeNet] [VisemeNet: Audio-Driven Animator-Centric Speech Animation](https://arxiv.org/abs/1805.09488), `SIGGRAPH 2018`.

### 2017

1. [Synthesizing-Obama] [Synthesizing Obama: Learning Lip Sync From Audio](https://grail.cs.washington.edu/projects/AudioToObama/siggraph17_obama.pdf), `SIGGRAPH 2017`. [[Project](https://grail.cs.washington.edu/projects/AudioToObama/)]
2. [You-Said-That?] [You Said That?: Synthesising Talking Faces From Audio](https://arxiv.org/abs/1705.02966), `IJCV 2019`. [[Code](https://github.com/joonson/yousaidthat)]
3. [Audio-Driven Facial Animation by Joint End-to-End Learning of Pose and Emotion](https://users.aalto.fi/~laines9/publications/karras2017siggraph_paper.pdf), `SIGGRAPH 2017`.
4. [A Deep Learning Approach for Generalized Speech Animation](https://home.ttic.edu/~taehwan/taylor_etal_siggraph2017.pdf), `SIGGRAPH 2017`.

### 2016

1. [LRW] [Lip Reading in the Wild](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16/chung16.pdf), `ACCV 2016`.

---

## Nerf & 3D

### 2024

1. [CVTHead] [CVTHead: One-shot Controllable Head Avatar with Vertex-feature Transformer](https://openaccess.thecvf.com/content/WACV2024/papers/Ma_CVTHead_One-Shot_Controllable_Head_Avatar_With_Vertex-Feature_Transformer_WACV_2024_paper.pdf), `WACV 2024`. [[Code](https://github.com/HowieMa/CVTHead)].  
2. [Head3D] [3D-Aware Talking-Head Video Motion Transfer](https://openaccess.thecvf.com/content/WACV2024/papers/Ni_3D-Aware_Talking-Head_Video_Motion_Transfer_WACV_2024_paper.pdf), `WACV 2024`.

### 2022

1. [SSP-NeRFF] [Semantic-Aware Implicit Neural Audio-Driven Video Portrait Generation](https://arxiv.org/pdf/2201.07786.pdf), `arxiv, 2022`.
2. [HeadNeRF] [HeadNeRF: A Real-time NeRF-based Parametric Head Model](https://openaccess.thecvf.com/content/CVPR2022/papers/Grassal_Neural_Head_Avatars_From_Monocular_RGB_Videos_CVPR_2022_paper.pdf), `CVPR 2022`. [[Code](https://github.com/CrisHY1995/headnerf)], [[Project](https://hy1995.top/HeadNeRF-Project/)]
3. [IMavatar] [I M Avatar: Implicit Morphable Head Avatars from Videos](https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_I_M_Avatar_Implicit_Morphable_Head_Avatars_From_Videos_CVPR_2022_paper.pdf), `CVPR 2022`. [[Code](https://ait.ethz.ch/projects/2022/IMavatar/)]
4. [ROME] [Realistic One-shot Mesh-based Head Avatars](https://arxiv.org/pdf/2206.08343.pdf), `ECCV 2022`.
5. [FNeVR] [FNeVR: Neural Volume Rendering for Face Animation](https://arxiv.org/abs/2209.10340), `Arxiv 2022`. [[Code](https://github.com/zengbohan0217/FNeVR)]
6. [3DFaceShop] [3DFaceShop: Explicitly Controllable 3D-Aware Portrait Generation](https://arxiv.org/pdf/2209.05434), `Arxiv 2022`. [[Code](https://github.com/junshutang/3DFaceShop)], [[Project](https://junshutang.github.io/control/index.html)]
7. [Next3D] [Generative Neural Texture Rasterization for 3D-Aware Head Avatars](https://arxiv.org/pdf/2211.11208.pdf), `Arxiv 2022`. [[Project](https://mrtornado24.github.io/Next3D/)]
8. [NeRFInvertor] [NeRFInvertor: High Fidelity NeRF-GAN Inversion for Single-shot Real Image Animation](https://arxiv.org/pdf/2211.17235.pdf?), `Arxiv 2022`.
9. [DFRF] [Learning Dynamic Facial Radiance Fields for Few-Shot Talking Head Synthesis](https://arxiv.org/abs/2207.11770), `ECCV 2022`. [[Code](https://github.com/sstzal/DFRF)]

### 2021

1. [DFA-NeRF] [DFA-NeRF: Personalized Talking Head Generation via Disentangled Face Attributes Neural Rendering](https://arxiv.org/pdf/2201.00791v1.pdf), `arxiv, 2021`.
2. [NerFACE] [NerFACE: Dynamic Neural Radiance Fields for Monocular 4D Facial Avatar Reconstruction](https://arxiv.org/pdf/2012.03065), `CVPR 2021 Oral`. [[Code](https://github.com/gafniguy/4D-Facial-Avatars)], [[Project](https://gafniguy.github.io/4D-Facial-Avatars/)]
3. [AD-NeRF] [AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis](https://arxiv.org/abs/2103.11078), `ICCV 2021`. [[Code](https://github.com/gafniguy/4D-Facial-Avatars)], [[Code](https://github.com/YudongGuo/AD-NeRF)]

### 2020

1. [DiscoFaceGAN
   ] [Disentangled and Controllable Face Image Generation via 3D Imitative-Contrastive Learning
   ](), `CVPR 2020 Oral`. [[Code](https://github.com/microsoft/DiscoFaceGAN)]

## Survey

### 2024

1. [A Comparative Study of Perceptual Quality Metrics for Audio-driven Talking Head Videos](https://arxiv.org/abs/2403.06421) [[Code](https://github.com/zwx8981/ADTH-QA)]

### 2020

1. [What comprises a good talking-head video generation?: A Survey and Benchmark](https://arxiv.org/pdf/2005.03201v1.pdf)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=harlanhong/awesome-talking-head-generation&type=Date)](https://star-history.com/#harlanhong/awesome-talking-head-generation&Date)
