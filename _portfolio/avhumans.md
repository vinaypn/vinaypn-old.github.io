---
title: "Audio - Visual Humans"
excerpt: "Project page for Audio Visual Humans"
collection: portfolio
---

## Audio-Visual Digital Humans

We have been pursuing research on a number of aspects related to audio-visual digital humans. On this page we present the works that we have been involved with

### Wav2Lip: Accurately Lip-syncing Videos In The Wild (ACM Multimedia 2020)
In this work, we investigate the problem of lip-syncing a talking face video of an arbitrary identity to match a target speech segment. Current works excel at producing accurate lip movements on a static image or on videos of specific people seen during the training phase. However, they fail to accurately morph the actual lip movements of arbitrary identities in dynamic, unconstrained talking face videos, resulting in significant parts of the video being out-of-sync with the newly chosen audio. We identify key reasons pertaining to this and hence resolve them by learning from a powerful lip-sync discriminator. Next, we propose new, rigorous evaluation benchmarks and metrics to specifically measure the accuracy of lip synchronization in unconstrained videos. Extensive quantitative and human evaluations on our challenging benchmarks show that the lip-sync accuracy of the videos generated using our Wav2Lip model is almost as good as real synced videos. We clearly demonstrate the substantial impact of our Wav2Lip model in our publicly available demo video. We also open-source our code, models, and evaluation benchmarks to promote future research efforts in this space.

[Detailed Project page](http://cvit.iiit.ac.in/research/projects/cvit-projects/a-lip-sync-expert-is-all-you-need-for-speech-to-lip-generation-in-the-wild/)

[![Watch the video](https://img.youtube.com/vi/0fXaDCZNOJc/maxresdefault.jpg)]( https://www.youtube.com/watch?v=0fXaDCZNOJc)


### Lip2Wav: Audio generation based on lip movements (CVPR 2020)
Humans involuntarily tend to infer parts of the conversation from lip movements when the speech is absent or corrupted by external noise. In this work, we explore the task of lip to speech synthesis, i.e., learning to generate natural speech given only the lip movements of a speaker. Acknowledging the importance of contextual and speaker-specific cues for accurate lip reading, we take a different path from existing works. We focus on learning accurate lip sequences to speech mappings for individual speakers in unconstrained, large vocabulary settings. To this end, we collect and release a large-scale benchmark dataset, the first of its kind, specifically to train and evaluate the single-speaker lip to speech task in natural settings. We propose an approach to achieve accurate, natural lip to speech synthesis in such unconstrained scenarios for the first time. Extensive evaluation using quantitative, qualitative metrics and human evaluation shows that our method is almost twice as intelligible as previous works in this space.

[Detailed Project page](https://cvit.iiit.ac.in/research/projects/cvit-projects/speaking-by-observing-lip-movements)

[![Watch the video](https://img.youtube.com/vi/HziA-jmlk_4/maxresdefault.jpg)]( https://www.youtube.com/watch?v=HziA-jmlk_4)

### Towards Automatic Face-to-Face Translation (ACM Multimedia 2019)
In light of the recent breakthroughs in automatic machine translation systems, we propose a novel approach of what we term as "Face-to-Face Translation". As today's digital communication becomes increasingly visual, we argue that there is the need for systems that can automatically translate a video of a person speaking in language A into a target language B with realistic lip synchronization. In this work, we create an automatic pipeline for this problem and demonstrate its impact in multiple real-world applications. First, we build a working speech-to-speech translation system by bringing together multiple existing modules from speech and language. We then move towards "Face-to-Face Translation" by incorporating a novel visual module, LipGAN for generating realistic talking faces from the translated audio. Quantitative evaluation of LipGAN on the standard LRW test set, shows that it significantly outperforms existing approaches across all standard metrics. We also subject our Face-to-Face Translation pipeline, to multiple human evaluations and show that it can significantly improve the overall user experience for consuming and interacting with multimodal content across languages.

[Detailed Project page](https://cvit.iiit.ac.in/research/projects/cvit-projects/facetoface-translation)

[![Watch the video](https://img.youtube.com/vi/aHG6Oei8jF0/maxresdefault.jpg)](https://www.youtube.com/watch?v=aHG6Oei8jF0)

### Visual Speech Enhancement Without a Real Visual Stream (WACV 2021)
In this work, we re-think the task of speech enhancement in unconstrained real-world environments. Current state-of-the-art methods use only the audio stream and are limited in their performance in a wide range of real-world noises. Recent works using lip movements as additional cues improve the quality of generated speech over ``audio-only" methods. But, these methods cannot be used for several applications where the visual stream is unreliable or completely absent. We propose a new paradigm for speech enhancement by exploiting recent breakthroughs in speech-driven lip synthesis. Using one such model as a teacher network, we train a robust student network to produce accurate lip movements that mask away the noise, thus acting as a ``visual noise filter". The intelligibility of the speech enhanced by our pseudo-lip approach is almost close (< 3\% difference) to the case of using real lips. This implies that we can exploit the advantages of using lip movements even in the absence of a real video stream. We rigorously evaluate our model using quantitative metrics as well as qualitative human evaluations. Additional ablation studies and a demo video in the supplementary material containing qualitative comparisons and results clearly illustrate the effectiveness of our approach.

[Detailed Project page]( https://cvit.iiit.ac.in/research/projects/cvit-projects/visual-speech-enhancement-without-a-real-visual-stream)

[![Watch the video](https://img.youtube.com/vi/y_oP9t7WEn4/maxresdefault.jpg)](https://www.youtube.com/watch?v=y_oP9t7WEn4)


### Extreme-scale Talking-Face Video Upsampling with Audio-Visual Priors (ACM Multimedia 2022)
In this paper, we explore an interesting question of what can be obtained from an 8×8 pixel video sequence. Surprisingly, it turns out to be quite a lot. We show that when we process this 8×8 video with the right set of audio and image priors, we can obtain a full-length, 256×256 video. We achieve this 32× scaling of an extremely low-resolution input using our novel audio-visual upsampling network. The audio prior helps to recover the elemental facial details and precise lip shapes and a single high-resolution target identity image prior provides us with rich appearance details. Our approach is an end-to-end multi-stage framework. The first stage produces a coarse intermediate output video that can be then used to animate single target identity image and generate realistic, accurate and high-quality outputs. Our approach is simple and performs exceedingly well (an 8× improvement in FID score) compared to previous super-resolution methods. We also extend our model to talking-face video compression, and show that we obtain a 3.5× improvement in terms of bits/pixel over the previous state-of-the-art. The results from our network are thoroughly analyzed through extensive ablation experiments (in the paper and supplementary material). We also provide the demo video along with code and models on our website


[Detailed Project page]( https://cvit.iiit.ac.in/research/projects/cvit-projects/talking-face-video-upsampling)

Video and demo coming soon


### Personalized One-Shot Lipreading for an ALS Patient (BMVC 2021)
     Lipreading or visually recognizing speech from the mouth movements of a speaker is a challenging and mentally taxing task. Unfortunately, multiple medical conditions force people to depend on this skill in their day-to-day lives for essential communication. Patients suffering from Amyotrophic Lateral Sclerosis (ALS) often lose muscle control, consequently their ability to generate speech and communicate via lip movements. Existing large datasets do not focus on medical patients or curate personalized vocabulary relevant to an individual. Collecting a large-scale dataset of a patient, needed to train mod-ern data-hungry deep learning models is, however, extremely challenging. In this work, we propose a personalized network to lipread an ALS patient using only one-shot examples. We depend on synthetically generated lip movements to augment the one-shot scenario. A Variational Encoder based domain adaptation technique is used to bridge the real-synthetic domain gap. Our approach significantly improves and achieves high top-5accuracy with 83.2% accuracy compared to 62.6% achieved by comparable methods for the patient. Apart from evaluating our approach on the ALS patient, we also extend it to people with hearing impairment relying extensively on lip movements to communicate. 


[![Watch the video](https://img.youtube.com/vi/_famGVaem-8/maxresdefault.jpg)](https://www.youtube.com/watch?v=_famGVaem-8)

### FaceOff: A Video-to-Video Face Swapping System (WACV 2023)
     Doubles play an indispensable role in the movie industry. They take the place of the actors in dangerous stunt scenes or in scenes where the same actor plays multiple characters. The double's face is later replaced with the actor's face and expressions manually using expensive CGI technology, costing millions of dollars and taking months to complete. An automated, inexpensive, and fast way can be to use face-swapping techniques that aim to swap an identity from a source face video (or an image) to a target face video. However, such methods can not preserve the source expressions of the actor important for the scene's context. % essential for the scene. % that are essential in cinemas. To tackle this challenge, we introduce video-to-video (V2V) face-swapping, a novel task of face-swapping that can preserve (1) the identity and expressions of the source (actor) face video and (2) the background and pose of the target (double) video. We propose FaceOff, a V2V face-swapping system that operates by learning a robust blending operation to merge two face videos following the constraints above. It first reduces the videos to a quantized latent space and then blends them in the reduced space. FaceOff is trained in a self-supervised manner and robustly tackles the non-trivial challenges of V2V face-swapping. As shown in the experimental section, FaceOff significantly outperforms alternate approaches qualitatively and quantitatively. 


[![Watch the video](https://img.youtube.com/vi/3TCugwmMjzo/maxresdefault.jpg)](https://www.youtube.com/watch?v=3TCugwmMjzo)
