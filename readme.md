# Awesome Talking Head Generation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ![Last Updated](https://img.shields.io/badge/Last%20Updated-April%202026-blue)

A curated list of papers and resources for **Talking Head Generation**, including face animation, audio-driven synthesis, portrait animation, and related tasks.

> Contributions welcome! Open an issue, pull request, or contact `fatinghong@gmail.com`. Discord: `Fa-Ting Hong#6563`

:fire: **New**: [ACTalker](https://harlanhong.github.io/publications/actalker/index.html) — portrait video generation driven by audio and expression simultaneously. `ICCV 2025`

## Table of Contents

- [Datasets](#datasets)
- [Survey](#survey)
- [Image-driven](#image-driven)
- [Audio-driven](#audio-driven)
- [Nerf & 3D](#nerf--3d)

## Related Groups

- [MMLab@NTU](https://www.mmlab-ntu.com)
- [Alibaba TongYi XR](https://github.com/HumanAIGC)
- [Hedra](https://hedra.com)

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
12. AVSpeech [[`Download link`](https://looking-to-listen.github.io/avspeech/)].

---

## Survey

| Year | Paper | Venue | Links |
|------|-------|-------|-------|
| 2026 | [Talking-Head Generation in Practice: A Longitudinal Analysis 2021–2025](https://openreview.net/forum?id=ns3TgZYQTZ) | OpenReview | |
| 2025 | [Advancing Talking Head Generation: A Comprehensive Survey of Multi-Modal Methodologies, Datasets, Evaluation Metrics, and Loss Functions](https://arxiv.org/abs/2507.02900) | arXiv | |
| 2025 | [Advancements in Talking Head Generation: A Comprehensive Review of Techniques, Metrics, and Challenges](https://link.springer.com/article/10.1007/s00371-025-04232-w) | The Visual Computer | |
| 2024 | [A Survey of Talking Head Synthesis: Portrait Generation, Driving Mechanisms, and Editing](https://dl.acm.org/doi/10.1145/3785656) | ACM CSUR | |
| 2024 | [A Comprehensive Taxonomy and Analysis of Talking Head Synthesis](https://arxiv.org/abs/2406.10553) | arXiv | |
| 2024 | [Audio-Driven Facial Animation with Deep Learning: A Survey](https://www.mdpi.com/2078-2489/15/11/675) | MDPI Information | |
| 2024 | [A Comparative Study of Perceptual Quality Metrics for Audio-driven Talking Head Videos](https://arxiv.org/abs/2403.06421) | arXiv | [Code](https://github.com/zwx8981/ADTH-QA) |
| 2023 | [From Pixels to Portraits: A Comprehensive Survey of Talking Head Generation Techniques and Applications](https://arxiv.org/abs/2308.16041) | arXiv | |
| 2023 | [Talking Human Face Generation: A Survey](https://www.sciencedirect.com/science/article/pii/S0957417423001793) | Expert Systems with Applications | |
| 2022 | [Human-Computer Interaction System: A Survey of Talking-Head Generation](https://www.mdpi.com/2079-9292/12/1/218) | MDPI Electronics | |
| 2020 | [What comprises a good talking-head video generation?: A Survey and Benchmark](https://arxiv.org/pdf/2005.03201v1.pdf) | arXiv | |

---

## Image-driven

### 2026

| Paper | Venue | Links |
|-------|-------|-------|
| [PortraitDirector: A Hierarchical Disentanglement Framework for Controllable and Real-time Facial Reenactment](https://arxiv.org/abs/2604.19129v1) | arXiv 2026 |  |


### 2025

| Paper | Venue | Links |
|-------|-------|-------|
| [HunyuanPortrait: Implicit Condition Control for Enhanced Portrait Animation](https://arxiv.org/abs/2503.18860) | CVPR 2025 | [Code](https://github.com/kkakkkka/HunyuanPortrait) · [Project](https://kkakkkka.github.io/HunyuanPortrait) |
| [Robust Deepfake Detection for Electronic Know Your Customer Systems Using Registered Images](https://arxiv.org/abs/2507.22601v1) | arXiv 2025 |  |
| [Towards Interactive Intelligence for Digital Humans](https://arxiv.org/abs/2512.13674v2) | arXiv 2025 |  |
| [FlashPortrait: 6x Faster Infinite Portrait Animation with Adaptive Latent Prediction](https://arxiv.org/abs/2512.16900v1) | arXiv 2025 |  |


### 2024

| Paper | Venue | Links |
|-------|-------|-------|
| [X-Portrait: Expressive Portrait Animation with Hierarchical Motion Attention](https://arxiv.org/abs/2403.15931) | SIGGRAPH 2024 | [Code](https://github.com/bytedance/X-Portrait) |
| [Follow-Your-Emoji: Fine-Controllable and Expressive Freestyle Portrait Animation](https://arxiv.org/abs/2406.01900) | SIGGRAPH Asia 2024 | [Code](https://github.com/mayuelala/FollowYourEmoji) |
| [LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control](https://arxiv.org/pdf/2407.03168) | arXiv 2024 | [Code](https://github.com/KwaiVGI/LivePortrait) · [Project](https://liveportrait.github.io) |
| [EMOPortraits: Emotion-enhanced Multimodal One-shot Head Avatars](https://arxiv.org/pdf/2404.19110) | CVPR 2024 | [Code](https://github.com/neeek2303/EMOPortraits) · [Project](https://neeek2303.github.io/EMOPortraits/) |
| [Synergizing Motion and Appearance: Multi-Scale Compensatory Codebooks for Talking Head Video Generation](https://arxiv.org/abs/2412.00719) | CVPR 2024 | [Project](https://shaelynz.github.io/synergize-motion-appearance/) |


### 2023

| Paper | Venue | Links |
|-------|-------|-------|
| [Audio-Visual Face Reenactment](https://arxiv.org/pdf/2210.02755.pdf) | WACV 2023 | [Code](https://github.com/mdv3101/AVFR-Gan/) · [Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/avfr) |
| [Cross-identity Video Motion Retargeting with Joint Transformation and Synthesis](https://arxiv.org/pdf/2210.01559.pdf) | WACV 2023 | [Code](https://github.com/nihaomiao/WACV23_TSNet) |
| [Implicit Identity Representation Conditioned Memory Compensation Network for Talking Head Video Generation](https://arxiv.org/abs/2307.09906) | ICCV 2023 | [Project](https://harlanhong.github.io/publications/mcnet.html) · [Code](https://github.com/harlanhong/ICCV2023-MCNET) |
| [StyleLipSync: Style-based Personalized Lip-sync Video Generation](https://arxiv.org/abs/2305.00521) | ICCV 2023 | [Code](https://github.com/TaekyungKi/StyleLipSync) |


### 2022

| Paper | Venue | Links |
|-------|-------|-------|
| [Depth-Aware Generative Adversarial Network for Talking Head Video Generation](https://arxiv.org/abs/2203.06605) | CVPR 2022 | [Code](https://github.com/harlanhong/CVPR2022-DaGAN) · [Project](https://harlanhong.github.io/publications/dagan.html) |
| [Thin-Plate Spline Motion Model for Image Animation](https://arxiv.org/abs/2203.14367) | CVPR 2022 | [Code](https://github.com/yoyo-nb/Thin-Plate-Spline-Motion-Model) |
| [StyleHEAT: One-Shot High-Resolution Editable Talking Face Generation via Pretrained StyleGAN](https://arxiv.org/pdf/2203.04036.pdf) | ECCV 2022 | [Code](https://github.com/FeiiYin/StyleHEAT/) · [Project](https://feiiyin.github.io/StyleHEAT/) |
| [MegaPortraits: One-shot Megapixel Neural Head Avatars](https://arxiv.org/abs/2207.07621) | ACM MM 2022 | [Project](https://samsunglabs.github.io/MegaPortraits/) |
| [Structure-Aware Motion Transfer with Deformable Anchor Model](https://openaccess.thecvf.com/content/CVPR2022/papers/Tao_Structure-Aware_Motion_Transfer_With_Deformable_Anchor_Model_CVPR_2022_paper.pdf) | CVPR 2022 | [Code](https://github.com/JialeTao/DAM) |
| [StyleMask: Disentangling the Style Space of StyleGAN2 for Neural Face Reenactment](https://arxiv.org/pdf/2209.13375.pdf) | FG, 2023 | [Code](https://github.com/StelaBou/StyleMask) |
| [Controllable Radiance Fields for Dynamic Face Synthesis](https://arxiv.org/pdf/2210.06465.pdf) | Arxiv 2022 |  |
| [Animatable 3D-Aware Face Image Generation for Video Avatars](https://arxiv.org/pdf/2210.05825.pdf) | NeurIPS 2022 | [Project](https://yuewuhkust.github.io/AniFaceGAN/) |
| [Implicit Warping for Animation with Image Sets](https://arxiv.org/pdf/2210.01794.pdf) | NeurIPS 2022 | [Project](https://deepimagination.cc/implicit_warping/) |
| [HifiHead: One-Shot High Fidelity Neural Head Synthesis with 3D Control](https://www.ijcai.org/proceedings/2022/0244.pdf) | IJCAI 2022 |  |
| [Face Animation with Multiple Source Images](https://arxiv.org/pdf/2212.00256.pdf?) | Arxiv 2022 |  |
| [MetaPortrait: Identity-Preserving Talking Head Generation with Fast Personalized Adaptation](https://download.arxiv.org/pdf/2212.08062v2) | Arxiv 2022 |  |
| [Compressing Video Calls using Synthetic Talking Heads](https://arxiv.org/pdf/2210.03692.pdf) | BMVC 2022 | [Project](https://cvit.iiit.ac.in/research/projects/cvit-projects/talking-video-compression) |
| [Finding Directions in GAN’s Latent Space for Neural Face Reenactment](https://arxiv.org/pdf/2202.00046.pdf) | BMVC 2022 | [Project](https://stelabou.github.io/stylegan-directions-reenactment/) · [Code](https://github.com/StelaBou/stylegan_directions_face_reenactment) |
| [Latent Image Animator: Learning to Animate Images via Latent Space Navigation](https://arxiv.org/pdf/2203.09043.pdf) | ICLR 2022 | [Project](https://wyhsirius.github.io/LIA-project/) · [Code](https://github.com/wyhsirius/LIA) |


### 2021

| Paper | Venue | Links |
|-------|-------|-------|
| [One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing](https://nvlabs.github.io/face-vid2vid/main.pdf) | CVPR 2021 Oral | [Project](https://nvlabs.github.io/face-vid2vid/) |
| [Sparse to Dense Motion Transfer for Face Image Animation](https://openaccess.thecvf.com/content/ICCV2021W/AIM/papers/Zhao_Sparse_to_Dense_Motion_Transfer_for_Face_Image_Animation_ICCVW_2021_paper.pdf) | ICCV 2021 |  |
| [SAFA: Structure Aware Face Animation](https://arxiv.org/pdf/2111.04928.pdf) | 3DV 2021 | [Code](https://github.com/Qiulin-W/SAFA) |
| [Self-appearance-aided Differential Evolution for Motion Transfer](https://arxiv.org/abs/2110.04658) | arXiv 2021 |  |
| [PIRenderer: Controllable Portrait Image Generation via Semantic Neural Rendering](https://arxiv.org/pdf/2109.08379.pdf) | ICCV 2021 | [Code](https://github.com/RenYurui/PIRender) |
| [FACEGAN: Facial Attribute Controllable rEenactment GAN](https://openaccess.thecvf.com/content/WACV2021/papers/Tripathy_FACEGAN_Facial_Attribute_Controllable_rEenactment_GAN_WACV_2021_paper.pdf) | WACV 2021 |  |
| [F3A-GAN: Facial Flow for Face Animation With Generative Adversarial Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9547053) | IEEE TIP 2021 |  |
| [FACIAL: Synthesizing Dynamic Talking Face with Implicit Attribute Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhang_FACIAL_Synthesizing_Dynamic_Talking_Face_With_Implicit_Attribute_Learning_ICCV_2021_paper.pdf) | ICCV 2021 |  |
| [ Motion Representations for Articulated Animation](https://openaccess.thecvf.com/content/CVPR2021/papers/Siarohin_Motion_Representations_for_Articulated_Animation_CVPR_2021_paper.pdf) | CVPR 2021 | [Code](https://github.com/snap-research/articulated-animation) |
| [HeadGAN: One-shot Neural Head Synthesis and Editing](https://arxiv.org/pdf/2012.08261.pdf) | ICCV 2021 | [Project](https://michaildoukas.github.io/HeadGAN/) |


### 2020

| Paper | Venue | Links |
|-------|-------|-------|
| [Mesh Guided One-shot Face Reenactment Using Graph Convolutional Networks](https://dl.acm.org/doi/pdf/10.1145/3394171.3413865g) | ACM Multimedia 2020 | [Code](https://arxiv.org/abs/2008.07783) |
| [MarioNETte: Few-shot Face Reenactment Preserving Identity of Unseen Targets](https://arxiv.org/abs/1911.08139) | AAAI 2020 | [Project](https://hyperconnect.github.io/MarioNETte/) |
| [Learning Identity-Invariant Motion Representations for Cross-ID Face Reenactment](https://openaccess.thecvf.com/content_CVPR_2020/papers/Huang_Learning_Identity-Invariant_Motion_Representations_for_Cross-ID_Face_Reenactment_CVPR_2020_paper.pdf) | CVPR 2020 |  |


### 2019

| Paper | Venue | Links |
|-------|-------|-------|
| [First order motion model for image animation](http://papers.nips.cc/paper/8935-first-order-motion-model-for-image-animation.pdf) | NeurIPS 2019 | [Code](https://github.com/AliaksandrSiarohin/first-order-model) |
| [Few-Shot Adversarial Learning of Realistic Neural Talking Head Models](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zakharov_Few-Shot_Adversarial_Learning_of_Realistic_Neural_Talking_Head_Models_ICCV_2019_paper.pdf) | ICCV 2019 | [Code](https://github.com/vincent-thevenin/Realistic-Neural-Talking-Head-Models) |
| [Animating Arbitrary Objects via Deep Motion Transfer](https://arxiv.org/abs/1812.08861) | CVPR 2019 Oral | [Code](https://github.com/AliaksandrSiarohin/monkey-net) · [Project](http://www.stulyakov.com/papers/monkey-net.html) |
| [Few-shot Video-to-Video Synthesis](https://nvlabs.github.io/few-shot-vid2vid/main.pdf) | NeurIPS 2019 | [Code](https://github.com/NVlabs/few-shot-vid2vid) · [Project](https://nvlabs.github.io/few-shot-vid2vid/) |


### 2018

| Paper | Venue | Links |
|-------|-------|-------|
| [ReenactGAN: Learning to Reenact Faces via Boundary Transfer](https://wywu.github.io/projects/ReenactGAN/support/ReenactGAN.pdf) | ECCV 2018 | [Code](https://github.com/wywu/ReenactGAN) |
| [X2Face: A network for controlling face generation by using images, audio, and pose codes](http://www.robots.ox.ac.uk/~vgg/publications/2018/Wiles18/wiles18.pdf) | ECCV 2018 | [Code](https://github.com/oawiles/X2Face) · [Project](https://www.robots.ox.ac.uk/~vgg/research/unsup_learn_watch_faces/x2face.html) |


### 2016

| Paper | Venue | Links |
|-------|-------|-------|
| [Face2Face: Real-time face capture and reenactment of RGB videos](http://openaccess.thecvf.com/content_cvpr_2016/html/Thies_Face2Face_Real-Time_Face_CVPR_2016_paper.html) | CVPR 2016 |  |


---

## Audio-driven

### 2026

| Paper | Venue | Links |
|-------|-------|-------|
| [FunCineForge: A Unified Dataset Toolkit and Model for Zero-Shot Movie Dubbing in Diverse Cinematic Scenes](https://arxiv.org/abs/2601.14777v1) | arXiv 2026 |  |
| [TurboTalk: Progressive Distillation for One-Step Audio-Driven Talking Avatar Generation](https://arxiv.org/abs/2604.14580) | arXiv 2026 |  |
| [SEDTalker: Emotion-Aware 3D Facial Animation Using Frame-Level Speech Emotion Diarization](https://arxiv.org/abs/2604.13335) | arXiv 2026 | [Code](https://github.com/FarzanehJafari1987/SEDTalker) |
| [AUHead: Realistic Emotional Talking Head Generation via Action Units Control](https://arxiv.org/abs/2602.09534) | arXiv 2026 |  |


### 2025

| Paper | Venue | Links |
|-------|-------|-------|
| [OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models](https://arxiv.org/abs/2502.01061) | arXiv 2025 | [Project](https://omnihuman-lab.github.io/) |
| [Audio-visual Controlled Video Diffusion with Masked Selective State Spaces Modelling for Natural Talking Head Generation](https://arxiv.org/abs/2504.02542) | ICCV 2025 | [Project](https://harlanhong.github.io/publications/actalker/index.html) |
| [OmniAvatar: Efficient Audio-Driven Avatar Video Generation with Adaptive Body Animation](https://arxiv.org/abs/2506.18866) | arXiv 2025 | [Code](https://github.com/Omni-Avatar/OmniAvatar) · [Project](https://omni-avatar.github.io/) |
| [Teller: Real-Time Streaming Audio-Driven Portrait Animation with Autoregressive Motion Generation](https://arxiv.org/abs/2503.18429) | CVPR 2025 |  |
| [EmotiveTalk: Expressive Talking Head Generation through Audio Information Decoupling and Emotional Video Diffusion](https://arxiv.org/abs/2411.16726) | CVPR 2025 | [Project](https://emotivetalk.github.io/) |
| [INFP: Audio-Driven Interactive Head Generation in Dyadic Conversations](https://arxiv.org/abs/2412.04037) | CVPR 2025 | [Project](https://grisoon.github.io/INFP/) |
| [Hallo2: Long-Duration and High-Resolution Audio-Driven Portrait Image Animation](https://arxiv.org/abs/2410.07718) | ICLR 2025 | [Code](https://github.com/fudan-generative-vision/hallo2) |
| [Loopy: Taming Audio-Driven Portrait Avatar with Long-Term Motion Dependency](https://arxiv.org/pdf/2409.02634) | ICLR 2025 | [Project](https://loopyavatar.github.io) |
| [DAWN: Dynamic Frame Avatar with Non-autoregressive Diffusion Framework for Talking Head Video Generation](https://arxiv.org/abs/2410.13726) | ICLR 2025 | [Project](https://hanbo-cheng.github.io/DAWN/) · [Code](https://github.com/Hanbo-Cheng/DAWN-pytorch) |
| [AnyTalk: Multi-modal Driven Multi-domain Talking Head Generation](https://anytalker.github.io/) | AAAI 2025 |  |
| [Occlusion-Insensitive Talking Head Video Generation via Facelet Compensation](https://ojs.aaai.org/index.php/AAAI/article/view/32277) | AAAI 2025 |  |
| [FixTalk: Taming Identity Leakage for High-Quality Talking Head Generation](https://arxiv.org/abs/2507.01390) | ICCV 2025 |  |
| [FLOAT: Generative Motion Latent Flow Matching for Audio-driven Talking Portrait](https://arxiv.org/abs/2412.01064) | ICCV 2025 | [Project](https://deepbrainai-research.github.io/float/) |
| [MoEE: Mixture of Emotion Experts for Audio-Driven Portrait Animation](https://cvpr.thecvf.com/virtual/2025/poster/32837) | CVPR 2025 |  |
| [Live Avatar: Streaming Real-time Audio-Driven Avatar Generation with Infinite Length](https://arxiv.org/abs/2512.04677) | arXiv 2025 | [Code](https://github.com/Alibaba-Quark/LiveAvatar) |
| [DreamTalk: When Expressive Talking Head Generation Meets Diffusion Probabilistic Models](https://arxiv.org/abs/2312.09767) | arXiv 2025 |  |
| [GAIA: Zero-shot Talking Avatar Generation](https://arxiv.org/abs/2311.15230) | arXiv 2025 |  |


### 2024

| Paper | Venue | Links |
|-------|-------|-------|
| [Real3D-Portrait: One-shot Realistic 3D Talking Portrait Synthesis](https://arxiv.org/pdf/2401.08503.pdf) | ICLR 2024 | [Project](https://real3dportrait.github.io/) · [Code](https://github.com/yerfor/Real3DPortrait) |
| [Emote Portrait Alive - Generating Expressive Portrait Videos with Audio2Video Diffusion Model under Weak Conditions](https://arxiv.org/pdf/2402.17485.pdf) | arXiv 2024 | [Project](https://humanaigc.github.io/emote-portrait-alive/) · [Code](https://github.com/HumanAIGC/EMO) |
| [Style2Talker: High-Resolution Talking Head Generation with Emotion Style and Art Style](https://arxiv.org/pdf/2403.06365.pdf) | AAAI 2024 |  |
| [Say Anything with Any Style](https://arxiv.org/abs/2403.06363) | AAAI 2024 |  |
| [MuseTalk] Real-Time High Quality Lip Synchorization with Latent Space Inpainting, [[Code](https://github.com/TMElyralab/MuseTalk)]. |  | [Code](https://github.com/TMElyralab/MuseTalk) |
| [VASA-1: Lifelike Audio-Driven Talking Faces Generated in Real Time](https://arxiv.org/abs/2404.10667) | NeurIPS 2024 | [Project](https://www.microsoft.com/en-us/research/project/vasa-1/) |
| [THQA: A Perceptual Quality Assessment Database for Talking Heads](https://arxiv.org/abs/2404.09003) | arXiv 2024 | [Code](https://github.com/zyj-2000/THQA) |
| [Talk3D: High-Fidelity Talking Portrait Synthesis via Personalized 3D Generative Prior](https://arxiv.org/abs/2403.20153) | arXiv 2024 | [Code](https://github.com/KU-CVLAB/Talk3D) · [Project](https://ku-cvlab.github.io/Talk3D/) |
| [EDTalk: Efficient Disentanglement for Emotional Talking Head Synthesis](https://arxiv.org/abs/2404.01647) | arXiv 2024 | [Code](https://github.com/tanshuai0219/EDTalk) · [Project](https://tanshuai0219.github.io/EDTalk/) |
| [AniPortrait: Audio-Driven Synthesis of Photorealistic Portrait Animations](https://arxiv.org/abs/2403.17694) | arXiv 2024 | [Code](https://github.com/Zejun-Yang/AniPortrait) |
| [FlowVQTalker: High-Quality Emotional Talking Face Generation through Normalizing Flow and Quantization](https://arxiv.org/abs/2403.06375) | arXiv 2024 |  |
| [FaceChain-ImagineID: Freely Crafting High-Fidelity Diverse Talking Faces from Disentangled Audio](https://arxiv.org/abs/2403.01901) | arXiv 2024 | [Code](https://github.com/modelscope/facechain) |
| [Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation](https://arxiv.org/pdf/2406.08801) | arXiv 2024 | [Code](https://github.com/fudan-generative-vision/hallo) |
| [EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions](https://arxiv.org/abs/2407.08136) | arXiv 2024 | [Code](https://github.com/BadToBest/EchoMimic) · [Project](https://badtobest.github.io/echomimic.html) |
| [RealTalk: Real-time and Realistic Audio-driven Face Generation with 3D Facial Prior-guided Identity Alignment Network](https://arxiv.org/abs/2406.18284) | arXiv 2024 |  |
| [Emotional Conversation: Empowering Talking Faces with Cohesive Expression, Gaze and Pose Generation](https://arxiv.org/abs/2406.07895) | arXiv 2024 |  |
| [Make Your Actor Talk: Generalizable and High-Fidelity Lip Sync with Motion and Appearance Disentanglement](https://arxiv.org/abs/2406.08096) | arXiv 2024 |  |
| [FD2Talk: Towards Generalized Talking Head Generation with Facial Decoupled Diffusion Model](https://arxiv.org/pdf/2408.09384v1) | arXiv 2024 |  |
| [ReSyncer: Rewiring Style-based Generator for Unified Audio-Visually Synced Facial Performer](https://arxiv.org/abs/2408.03284) | arXiv 2024 |  |
| [Style-Preserving Lip Sync via Audio-Aware Style Reference](https://arxiv.org/abs/2408.05412) | arXiv 2024 |  |
| [EchoMimicV2: Towards Striking, Simplified, and Semi-Body Human Animation](https://arxiv.org/abs/2411.10061) | arXiv 2024 | [Code](https://github.com/antgroup/echomimic_v2) · [Project](https://antgroup.github.io/ai/echomimic_v2/) |
| [Latent Diffusion Transformer for Talking Video Synthesis](https://arxiv.org/abs/2411.16748) | arXiv 2024 | [Code](https://github.com/zhang-haojie/letstalk?tab=readme-ov-file) · [Project](https://zhang-haojie.github.io/project-pages/letstalk.html) |
| [IF-MDM: Implicit Face Motion Diffusion Model for High-Fidelity Realtime Talking Head Generation](https://arxiv.org/abs/2412.04000) | arXiv 2024 | [Project](http://ec2-3-25-102-128.ap-southeast-2.compute.amazonaws.com/IF-MDM/ifmdm_supplementary/index.html) |
| [Memory-Guided Diffusion for Expressive Talking Video Generation](https://arxiv.org/abs/2412.04448) | arXiv 2024 | [Project](https://memoavatar.github.io/) · [Code](https://github.com/memoavatar/memo) |
| [Highly Dynamic and Realistic Portrait Image Animation with Diffusion Transformer Networks](https://arxiv.org/abs/2412.00733) | arXiv 2024 |  |
| [VQTalker: Towards Multilingual Talking Avatars through Facial Motion Tokenization](https://arxiv.org/pdf/2412.09892) | arXiv 2024 |  |
| [Towards Customizable One-Shot Audio-to-Talking Face Generation](https://arxiv.org/abs/2412.07754) | arXiv 2024 |  |
| [LatentSync: Audio Conditioned Latent Diffusion Models for Lip Sync](https://arxiv.org/abs/2412.09262) | arXiv 2024 | [Code](https://github.com/bytedance/LatentSync) |
| [Media2Face: Co-speech Facial Animation Generation with Multi-Modality Guidance](https://dl.acm.org/doi/10.1145/3641519.3657413) | SIGGRAPH 2024 |  |
| [PersonaTalk: Bring Attention to Your Persona in Visual Dubbing](https://dl.acm.org/doi/10.1145/3680528.3687618) | SIGGRAPH Asia 2024 |  |
| [StyleTalk++: A Unified Framework for Controlling the Speaking Styles of Talking Heads](https://arxiv.org/abs/2409.09292) | TPAMI 2024 |  |
| [JEAN: Joint Expression and Audio-guided NeRF-based Talking Face Generation](https://arxiv.org/abs/2409.12156) | BMVC 2024 |  |
| [Ditto: Motion-Space Diffusion for Controllable Realtime Talking Head Synthesis](https://arxiv.org/abs/2411.19509) | arXiv 2024 |  |
| [JoyVASA: Portrait and Animal Image Animation with Diffusion-Based Audio-Driven Facial Dynamics](https://arxiv.org/abs/2411.09209) | arXiv 2024 | [Code](https://github.com/jdh-algo/JoyVASA) |
| [HelloMeme: Integrating Spatial Knitting Attentions to Embed High-Level Conditions in Diffusion Models](https://arxiv.org/abs/2410.22901) | arXiv 2024 | [Code](https://github.com/HelloVision/HelloMeme) |
| [LaDTalk: Latent Denoising for Synthesizing Talking Head Videos with High Frequency Details](https://arxiv.org/abs/2410.00990) | arXiv 2024 |  |


### 2023

| Paper | Venue | Links |
|-------|-------|-------|
| [Diffused Heads: Diffusion Models Beat GANs on Talking-Face Generation](https://mstypulkowski.github.io/diffusedheads/diffused_heads.pdf) | Arxiv 2023 | [Project](https://mstypulkowski.github.io/diffusedheads/) |
| [DiffTalk: Crafting Diffusion Models for Generalized Talking Head Synthesis](https://arxiv.org/abs/2301.03786) | Arxiv 2023 | [Project](https://sstzal.github.io/DiffTalk/) · [Code](https://github.com/sstzal/DiffTalk) |
| [READ Avatars: Realistic Emotion-controllable Audio Driven Avatars](READ Avatars: Realistic Emotion-controllable Audio Driven Avatars) | Arxiv 2023 |  |
| [DAE-Talker: High Fidelity Speech-Driven Talking Face Generation with Diffusion Autoencoder](https://arxiv.org/pdf/2303.17550.pdf) | Arxiv 2023 |  |
| [Emotionally Enhanced Talking Face Generation](https://arxiv.org/pdf/2303.11548.pdf) | Arxiv 2023 | [Code](https://github.com/sahilg06/EmoGen) |
| [Seeing What You Said: Talking Face Generation Guided by a Lip Reading Expert](https://arxiv.org/pdf/2303.17480.pdf) | CVPR 2023 | [Code](https://github.com/Sxjdwang/TalkLip) |
| [StyleSync: High-Fidelity Generalized and Personalized Lip Sync in Style-based Generator](https://arxiv.org/pdf/2305.05445.pdf) | CVPR 2023 | [Project](https://hangz-nju-cuhk.github.io/projects/StyleSync) · [Code](https://github.com/guanjz20/StyleSync) |
| [GeneFace++: Generalized and Stable Real-Time Audio-Driven 3D Talking Face Generation](https://arxiv.org/pdf/2305.00787.pdf) | arXiv 2023 | [Project](https://genefaceplusplus.github.io) · [Code](https://github.com/yerfor/GeneFacePlusPlus) |
| [MODA: Mapping-Once Audio-driven Portrait Animation with Dual Attentions](https://arxiv.org/abs/2307.10008) | ICCV 2023 |  |
| [VividTalk: One-Shot Audio-Driven Talking Head Generation Based on 3D Hybrid Prior](https://arxiv.org/pdf/2312.01841.pdf) | Arxiv 2023 | [Project](https://humanaigc.github.io/vivid-talk/) · [Code](https://github.com/HumanAIGC/VividTalk) |
| [IP_LAP: Identity-Preserving Talking Face Generation with Landmark and Appearance Priors](https://arxiv.org/abs/2305.08293) | CVPR 2023 | [Code](https://github.com/Weizhi-Zhong/IP_LAP) |
| [HyperLips: Hyper Control Lips with High Resolution Decoder for Talking Face Generation](https://arxiv.org/abs/2310.05720) | CVPR 2023 | [Code](https://github.com/semchan/HyperLips) |
| [Efficient Emotional Adaptation for Audio-Driven Talking-Head Generation](https://arxiv.org/abs/2309.04946) | ICCV 2023 | [Project](https://yuangan.github.io/eat/) · [Code](https://github.com/yuangan/EAT_code) |
| [SadTalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Talking Head Animation](https://arxiv.org/pdf/2211.12194.pdf) | CVPR 2023 | [Project](https://sadtalker.github.io) · [Code](https://github.com/Winfredy/SadTalker) |
| [DINet: Deformation Inpainting Network for Realistic Face Visually Dubbing on High Resolution Video](https://arxiv.org/abs/2303.03988) | AAAI 2023 | [Code](https://github.com/MRzzm/DINet) |
| [EMMN: Emotional Motion Memory Network for Audio-driven Emotional Talking Face Generation](https://openaccess.thecvf.com/content/ICCV2023/papers/Tan_EMMN_Emotional_Motion_Memory_Network_for_Audio-driven_Emotional_Talking_Face_ICCV_2023_paper.pdf) | ICCV 2023 |  |
| [ToonTalker: Cross-Domain Face Reenactment](https://openaccess.thecvf.com/content/ICCV2023/papers/Gong_ToonTalker_Cross-Domain_Face_Reenactment_ICCV_2023_paper.pdf) | ICCV 2023 |  |
| [High-fidelity Generalized Emotional Talking Face Generation with Multi-modal Emotion Space Learning](https://openaccess.thecvf.com/content/CVPR2023/papers/Xu_High-Fidelity_Generalized_Emotional_Talking_Face_Generation_With_Multi-Modal_Emotion_Space_CVPR_2023_paper.pdf) | CVPR 2023 |  |
| [DisCoHead: Audio-and-Video-Driven Talking Head Generation by Disentangled Control of Head Pose and Facial Expressions](https://arxiv.org/abs/2303.07697) | ICASSP 2023 | [Code](https://github.com/deepbrainai-research/discohead) |


### 2022

| Paper | Venue | Links |
|-------|-------|-------|
| [Expressive Talking Head Generation with Granular Audio-Visual Control ](https://openaccess.thecvf.com/content/CVPR2022/papers/Liang_Expressive_Talking_Head_Generation_With_Granular_Audio-Visual_Control_CVPR_2022_paper.pdf) | CVPR 2022 |  |
| [Talking Face Generation with Multilingual TTS](https://openaccess.thecvf.com/content/CVPR2022/papers/Song_Talking_Face_Generation_With_Multilingual_TTS_CVPR_2022_paper.pdf) | CVPR 2022 | [Demo](https://huggingface.co/spaces/CVPR/ml-talking-face) |
| [EAMM: One-Shot Emotional Talking Face via Audio-Based Emotion-Aware Motion Model](https://arxiv.org/pdf/2205.15278.pdf) | SIGGRAPH 2022 |  |
| [SPACEx 🚀: Speech-driven Portrait Animation with Controllable Expression](https://arxiv.org/pdf/2211.09809.pdf) | arXiv 2022 | [Project](https://deepimagination.cc/SPACEx/) |
| [Masked Lip-Sync Prediction by Audio-Visual Contextual Exploitation in Transformers](https://arxiv.org/pdf/2212.04970.pdf) | SIGGRAPH Asia 2022 |  |
| [Memories are One-to-Many Mapping Alleviators in Talking Face Generation](https://arxiv.org/pdf/2212.05005.pdf) | arXiv 2022 |  |


### 2021

| Paper | Venue | Links |
|-------|-------|-------|
| [Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation](https://arxiv.org/abs/2104.11116) | CVPR 2021 | [Code](https://github.com/Hangz-nju-cuhk/Talking-Face_PC-AVS) · [Project](https://hangz-nju-cuhk.github.io/projects/PC-AVS) |
| [Imitating Arbitrary Talking Style for Realistic Audio-Driven Talking Face Synthesis](https://dl.acm.org/doi/pdf/10.1145/3474085.3475280) | ACM Multimedia 2021 |  |
| [Audio-Driven Emotional Video Portraits](https://openaccess.thecvf.com/content/CVPR2021/papers/Ji_Audio-Driven_Emotional_Video_Portraits_CVPR_2021_paper.pdf) | CVPR 2021 | [Code](https://github.com/jixinya/EVP) |
| [Talking Head Generation with Audio and Speech Related Facial Action Units](https://arxiv.org/pdf/2110.09951.pdf) | arxiv 2021 |  |
| [Speech2Talking-Face: Inferring and Driving a Face with Synchronized Audio-Visual Representation](https://www.ijcai.org/proceedings/2021/0141.pdf) | IJCAI 2021 |  |
| [Imitating Arbitrary Talking Style for Realistic Audio-Driven Talking Face Synthesis](https://arxiv.org/abs/2111.00203) | ACM MM 2021 |  |
| [Live Speech Portraits: Real-Time Photorealistic Talking-Head Animation](https://arxiv.org/abs/2109.10595) | ACM TOG 2021 | [Code](https://github.com/YuanxunLu/LiveSpeechPortraits) |
| [Audio2head: Audio-driven one-shot talking-head generation with natural head motion](https://arxiv.org/pdf/2107.09293) | ArXiv 2021 |  |


### 2020

| Paper | Venue | Links |
|-------|-------|-------|
| [A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild](http://arxiv.org/abs/2008.10010) | ACM Multimedia 2020 | [Code](https://github.com/Rudrabha/Wav2Lip) · [Project](http://cvit.iiit.ac.in/research/projects/cvit-projects/a-lip-sync-expert-is-all-you-need-for-speech-to-lip-generation-in-the-wild/) |
| [Talking-head Generation with Rhythmic Head Motion](https://arxiv.org/pdf/2007.08547v1.pdf) | ECCV 2020 | [Code](https://github.com/lelechen63/Talking-head-Generation-with-Rhythmic-Head-Motion) |
| MakeItTalk: Speaker-Aware Talking-Head Animation | SIGGRAPH Asia 2020 | [Code](https://github.com/yzhou359/MakeItTalk) · [Project](https://people.umass.edu/~yangzhou/MakeItTalk/) |
| [Neural Voice Puppetry: Audio-driven Facial Reenactment](https://arxiv.org/abs/1912.05566) | ECCV 2020 | [Code](https://github.com/keetsky/NeuralVoicePuppetry) · [Project](https://justusthies.github.io/posts/neural-voice-puppetry/) |
| [MEAD: A Large-scale Audio-visual Dataset for Emotional Talking-face Generation](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123660698.pdf) | ECCV 2020 | [Code](https://github.com/uniBruce/Mead) · [Project](https://wywu.github.io/projects/MEAD/MEAD.html) |
| [Realistic Speech-Driven Facial Animation with GANs](https://arxiv.org/pdf/1906.06337.pdf) | IJCV 2020 |  |


### 2019

| Paper | Venue | Links |
|-------|-------|-------|
| [Talking Face Generation by Adversarially Disentangled Audio-Visual Representation](https://arxiv.org/abs/1807.07860) | AAAI 2019 | [Code](https://github.com/Hangz-nju-cuhk/Talking-Face-Generation-DAVS) |
| [Hierarchical Cross-modal Talking Face Generation with Dynamic Pixel-wise Loss](https://www.cs.rochester.edu/~cxu22/p/cvpr2019_facegen_paper.pdf) | CVPR 2019 | [Code](https://github.com/lelechen63/ATVGnet) |


### 2018

| Paper | Venue | Links |
|-------|-------|-------|
| [Lip Movements Generation at a Glance](https://openaccess.thecvf.com/content_ECCV_2018/papers/Lele_Chen_Lip_Movements_Generation_ECCV_2018_paper.pdf) | ECCV 2018 | [Code](https://github.com/lelechen63/3d_gan) |
| [VisemeNet: Audio-Driven Animator-Centric Speech Animation](https://arxiv.org/abs/1805.09488) | SIGGRAPH 2018 |  |


### 2017

| Paper | Venue | Links |
|-------|-------|-------|
| [Synthesizing Obama: Learning Lip Sync From Audio](https://grail.cs.washington.edu/projects/AudioToObama/siggraph17_obama.pdf) | SIGGRAPH 2017 | [Project](https://grail.cs.washington.edu/projects/AudioToObama/) |
| [You Said That?: Synthesising Talking Faces From Audio](https://arxiv.org/abs/1705.02966) | IJCV 2019 | [Code](https://github.com/joonson/yousaidthat) |
| [Audio-Driven Facial Animation by Joint End-to-End Learning of Pose and Emotion](https://users.aalto.fi/~laines9/publications/karras2017siggraph_paper.pdf) | SIGGRAPH 2017 |  |
| [A Deep Learning Approach for Generalized Speech Animation](https://home.ttic.edu/~taehwan/taylor_etal_siggraph2017.pdf) | SIGGRAPH 2017 |  |


### 2016

| Paper | Venue | Links |
|-------|-------|-------|
| [Lip Reading in the Wild](https://www.robots.ox.ac.uk/~vgg/publications/2016/Chung16/chung16.pdf) | ACCV 2016 |  |


---

## Nerf & 3D

### 2026

| Paper | Venue | Links |
|-------|-------|-------|
| [MMTalker: Multiresolution 3D Talking Head Synthesis with Multimodal Feature Fusion](https://arxiv.org/abs/2604.02941v1) | arXiv 2026 |  |
| [FG-Portrait: 3D Flow Guided Editable Portrait Animation](https://arxiv.org/abs/2603.23381v1) | arXiv 2026 |  |
| [Giving Faces Their Feelings Back: Explicit Emotion Control for Feedforward Single-Image 3D Head Avatars](https://arxiv.org/abs/2604.14541v1) | arXiv 2026 |  |
| [3DRealHead: Few-Shot Detailed Head Avatar](https://arxiv.org/abs/2604.13171v1) | arXiv 2026 |  |
| [FHAvatar: Fast and High-Fidelity Reconstruction of Face-and-Hair Composable 3D Head Avatar from Few Casual Captures](https://arxiv.org/abs/2603.23345v1) | arXiv 2026 |  |
| [NBAvatar: Neural Billboards Avatars with Realistic Hand-Face Interaction](https://arxiv.org/abs/2603.12063v1) | arXiv 2026 |  |
| [OMG-Avatar: One-shot Multi-LOD Gaussian Head Avatar](https://arxiv.org/abs/2603.01506v2) | arXiv 2026 |  |
| [OFERA: Blendshape-driven 3D Gaussian Control for Occluded Facial Expression to Realistic Avatars in VR](https://arxiv.org/abs/2602.01748v1) | arXiv 2026 |  |
| [CAG-Avatar: Cross-Attention Guided Gaussian Avatars for High-Fidelity Head Reconstruction](https://arxiv.org/abs/2601.14844v1) | arXiv 2026 |  |
| [Uncertainty-Aware 3D Emotional Talking Face Synthesis with Emotion Prior Distillation](https://arxiv.org/abs/2601.19112v1) | arXiv 2026 |  |
| [3DXTalker: Unifying Identity, Lip Sync, Emotion, and Spatial Dynamics in Expressive 3D Talking Avatars](https://arxiv.org/abs/2602.10516) | arXiv 2026 |  |


### 2025

| Paper | Venue | Links |
|-------|-------|-------|
| [IM-Portrait: Learning 3D-aware Video Diffusion for Photorealistic Talking Heads from Monocular Videos](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_IM-Portrait_Learning_3D-aware_Video_Diffusion_for_Photorealistic_Talking_Heads_from_CVPR_2025_paper.pdf) | CVPR 2025 |  |
| [Perceptually Accurate 3D Talking Head Generation: New Definitions, Speech-Mesh Representation, and Evaluation Metrics](https://perceptual-3d-talking-head.github.io/) | CVPR 2025 |  |
| [GaussianSpeech: Audio-Driven Personalized 3D Gaussian Avatars](https://arxiv.org/abs/2412.04420) | ICCV 2025 | [Code](https://github.com/shivangi-aneja/GaussianSpeech) |
| [MemoryTalker: Personalized Speech-Driven 3D Facial Animation via Audio-Guided Stylization](https://openaccess.thecvf.com/content/ICCV2025/html/Kim_MemoryTalker_Personalized_Speech-Driven_3D_Facial_Animation_via_Audio-Guided_Stylization_ICCV_2025_paper.html) | ICCV 2025 | [Code](https://github.com/kimhyungkyu-1208/MemoryTalker) |
| [CAFE-TALK: Generating 3D Talking Face](https://proceedings.iclr.cc/paper_files/paper/2025/file/2c71b14637802ed08eaa3cf50342b2b9-Paper-Conference.pdf) | ICLR 2025 |  |
| [InsTaG: Learning Personalized 3D Talking Head from Few-Second Video](https://arxiv.org/abs/2304.04790) | CVPR 2025 | [Code](https://github.com/Fictionarry/InsTaG) |
| [Monocular and Generalizable Gaussian Talking Head Animation](https://arxiv.org/abs/2504.00665) | CVPR 2025 | [Project](https://scut-mmpr.github.io/MGGTalk-Homepage/) |
| [DualTalk: Dual-Speaker Interaction for 3D Talking Head Conversations](https://arxiv.org/abs/2504.00545) | CVPR 2025 | [Code](https://github.com/ziqiaopeng/DualTalk) |
| [VASA-3D: Lifelike Audio-Driven Gaussian Head Avatars from a Single Image](https://arxiv.org/abs/2512.14677) | NeurIPS 2025 |  |
| [PointTalk: Audio-Driven Dynamic Lip Point Cloud for 3D Gaussian-based Talking Head Synthesis](https://arxiv.org/abs/2412.08504) | AAAI 2025 |  |
| [PTalker: Personalized Speech-Driven 3D Talking Head Animation via Style Disentanglement](https://arxiv.org/abs/2512.22602) | arXiv 2025 |  |
| [SynergyWarpNet: Attention-Guided Cooperative Warping for Neural Portrait Animation](https://arxiv.org/abs/2512.17331v1) | arXiv 2025 |  |
| [From Autoencoders to CycleGAN: Robust Unpaired Face Manipulation via Adversarial Learning](https://arxiv.org/abs/2509.12176v2) | arXiv 2025 |  |


### 2024

| Paper | Venue | Links |
|-------|-------|-------|
| [CVTHead: One-shot Controllable Head Avatar with Vertex-feature Transformer](https://openaccess.thecvf.com/content/WACV2024/papers/Ma_CVTHead_One-Shot_Controllable_Head_Avatar_With_Vertex-Feature_Transformer_WACV_2024_paper.pdf) | WACV 2024 | [Code](https://github.com/HowieMa/CVTHead) |
| [3D-Aware Talking-Head Video Motion Transfer](https://openaccess.thecvf.com/content/WACV2024/papers/Ni_3D-Aware_Talking-Head_Video_Motion_Transfer_WACV_2024_paper.pdf) | WACV 2024 |  |
| [TalkingGaussian: Structure-Persistent 3D Talking Head Synthesis via Gaussian Splatting](https://arxiv.org/abs/2404.15264) | ECCV 2024 | [Code](https://github.com/Fictionarry/TalkingGaussian) |
| [GaussianTalker: Real-Time High-Fidelity Talking Head Synthesis with Audio-Driven 3D Gaussian Splatting](https://arxiv.org/abs/2404.16012) | ACM MM 2024 | [Code](https://github.com/cvlab-kaist/GaussianTalker) |
| [Generalizable and Animatable Gaussian Head Avatar](https://arxiv.org/abs/2410.07971) | NeurIPS 2024 | [Code](https://github.com/xg-chu/GAGAvatar) |
| [MimicTalk: Mimicking a Personalized and Expressive 3D Talking Face in Minutes](https://arxiv.org/abs/2410.06734) | NeurIPS 2024 |  |
| [EmoTalk3D: High-Fidelity Free-View Synthesis of Emotional 3D Talking Head](https://arxiv.org/abs/2408.00297) | ECCV 2024 |  |
| [Learning Dynamic Tetrahedra for High-Quality Talking Head Synthesis](https://arxiv.org/abs/2402.17364) | CVPR 2024 | [Code](https://github.com/zhangzc21/DynTet) |
| [GPAvatar: Generalizable and Precise Head Avatar from Image(s)](https://arxiv.org/abs/2401.10215) | ICLR 2024 | [Code](https://github.com/xg-chu/GPAvatar) |
| [UniTalker: Scaling up Audio-Driven 3D Facial Animation through A Unified Model](https://arxiv.org/abs/2408.00762) | arXiv 2024 | [Code](https://github.com/X-niper/UniTalker) |


### 2023

| Paper | Venue | Links |
|-------|-------|-------|
| [Efficient Region-Aware Neural Radiance Fields for High-Fidelity Talking Portrait Synthesis](https://arxiv.org/abs/2307.09323) | ICCV 2023 | [Code](https://github.com/Fictionarry/ER-NeRF) |
| [EmoTalk: Speech-Driven Emotional Disentanglement for 3D Face Animation](https://arxiv.org/abs/2303.11866) | ICCV 2023 | [Code](https://github.com/ZiqiaoPeng/EmoTalk) |
| [CodeTalker: Speech-Driven 3D Facial Animation with Discrete Motion Prior](https://arxiv.org/abs/2301.02379) | CVPR 2023 | [Code](https://github.com/Doubiiu/CodeTalker) |
| [GANHead: Towards Generative Animatable Neural Head Avatars](https://arxiv.org/abs/2304.01196) | CVPR 2023 | [Code](https://github.com/wsj-sjtu/GANHead) |
| [OTAvatar: One-shot Talking Face Avatar with Controllable Tri-plane Rendering](https://arxiv.org/abs/2303.14662) | CVPR 2023 | [Code](https://github.com/theEricMa/OTAvatar) |
| [GeneFace: Generalized and High-Fidelity Audio-Driven 3D Talking Face Synthesis](https://arxiv.org/abs/2301.13430) | ICLR 2023 | [Code](https://github.com/yerfor/GeneFace) |
| [SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis](https://arxiv.org/abs/2311.17590) | CVPR 2024 | [Code](https://github.com/ZiqiaoPeng/SyncTalk) |


### 2022

| Paper | Venue | Links |
|-------|-------|-------|
| [Semantic-Aware Implicit Neural Audio-Driven Video Portrait Generation](https://arxiv.org/pdf/2201.07786.pdf) | arxiv, 2022 |  |
| [HeadNeRF: A Real-time NeRF-based Parametric Head Model](https://openaccess.thecvf.com/content/CVPR2022/papers/Grassal_Neural_Head_Avatars_From_Monocular_RGB_Videos_CVPR_2022_paper.pdf) | CVPR 2022 | [Code](https://github.com/CrisHY1995/headnerf) · [Project](https://hy1995.top/HeadNeRF-Project/) |
| [I M Avatar: Implicit Morphable Head Avatars from Videos](https://openaccess.thecvf.com/content/CVPR2022/papers/Zheng_I_M_Avatar_Implicit_Morphable_Head_Avatars_From_Videos_CVPR_2022_paper.pdf) | CVPR 2022 | [Code](https://ait.ethz.ch/projects/2022/IMavatar/) |
| [Realistic One-shot Mesh-based Head Avatars](https://arxiv.org/pdf/2206.08343.pdf) | ECCV 2022 |  |
| [FNeVR: Neural Volume Rendering for Face Animation](https://arxiv.org/abs/2209.10340) | Arxiv 2022 | [Code](https://github.com/zengbohan0217/FNeVR) |
| [3DFaceShop: Explicitly Controllable 3D-Aware Portrait Generation](https://arxiv.org/pdf/2209.05434) | Arxiv 2022 | [Code](https://github.com/junshutang/3DFaceShop) · [Project](https://junshutang.github.io/control/index.html) |
| [Generative Neural Texture Rasterization for 3D-Aware Head Avatars](https://arxiv.org/pdf/2211.11208.pdf) | Arxiv 2022 | [Project](https://mrtornado24.github.io/Next3D/) |
| [NeRFInvertor: High Fidelity NeRF-GAN Inversion for Single-shot Real Image Animation](https://arxiv.org/pdf/2211.17235.pdf?) | Arxiv 2022 |  |
| [Learning Dynamic Facial Radiance Fields for Few-Shot Talking Head Synthesis](https://arxiv.org/abs/2207.11770) | ECCV 2022 | [Code](https://github.com/sstzal/DFRF) |


### 2021

| Paper | Venue | Links |
|-------|-------|-------|
| [DFA-NeRF: Personalized Talking Head Generation via Disentangled Face Attributes Neural Rendering](https://arxiv.org/pdf/2201.00791v1.pdf) | arxiv, 2021 |  |
| [NerFACE: Dynamic Neural Radiance Fields for Monocular 4D Facial Avatar Reconstruction](https://arxiv.org/pdf/2012.03065) | CVPR 2021 Oral | [Code](https://github.com/gafniguy/4D-Facial-Avatars) · [Project](https://gafniguy.github.io/4D-Facial-Avatars/) |
| [AD-NeRF: Audio Driven Neural Radiance Fields for Talking Head Synthesis](https://arxiv.org/abs/2103.11078) | ICCV 2021 | [Code](https://github.com/gafniguy/4D-Facial-Avatars) · [Code](https://github.com/YudongGuo/AD-NeRF) |


### 2020

| Paper | Venue | Links |
|-------|-------|-------|
| [Disentangled and Controllable Face Image Generation via 3D Imitative-Contrastive Learning](https://arxiv.org/abs/2004.01298) | CVPR 2020 Oral | [Code](https://github.com/microsoft/DiscoFaceGAN) |


## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=harlanhong/awesome-talking-head-generation&type=Date)](https://star-history.com/#harlanhong/awesome-talking-head-generation&Date)
