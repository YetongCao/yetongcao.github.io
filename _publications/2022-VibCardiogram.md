---
title: "Guard Your Heart Silently: Continuous Electrocardiogram Waveform Monitoring with Wrist-Worn Motion Sensor"
collection: publications
permalink: /publication/2022-VibCardiogram
excerpt: "<img src='/images/teaserVibcardiogram.png'>"
date: 2022-09-07
venue: 'ACM IMWUT'
paperurl: 'http://yetongcao.github.io/files/VibCardiogram.pdf'
citation: #'Yetong Cao, Qian Zhang, Fan Li, Song Yang, Yu Wang. 2020. &quot;EarAce: Empowering Versatile Acoustic Sensing via Earable Active Noise Cancellation Platform.&quot; <i>Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies</i>. 7(2), 1-23.'
---
**Yetong Cao**, Fan Li*, Huijie Chen, Xiaochen liu, Li Zhang, Yu Wang. "Guard Your Heart Silently: Continuous Electrocardiogram Waveform Monitoring with Wrist-Worn Motion Sensor". _Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies_, vol.6, no.3, pp. 1917-1926, 2022.


### Abstract:
In recent years, particular attention has been devoted to continuous electrocardiogram (ECG) waveform monitoring due to its numerous applications. However, existing solutions require users to be confined to particular locations, rely on dedicated and expensive hardware, or require active user participation. The constrained recording conditions prevent them from being deployed in many practical application scenarios. In view of this, we present VibCardiogram, a continuous and reliable design for estimating ECG waveform shape via ubiquitous wrist-worn wearables; it renders a personal ECG waveform shape estimating system with prolonged recording time accessible to a larger sector of the population. Instead of adding auxiliary sensors to wearables, VibCardiogram leverages the widely integrated motion sensor to characterize cardiac activities, and interpret them to generate an alternative signal that has the same waveform shape as the ECG signal. Specifically, VibCardiogram extracts the cardiogenic body vibrations from noisy sensor data. As the waveform variability and inconstant period hinder the segmentation of cardiac cycles, VibCardiogram extracts features and realizes accurate segmentation via machine learning. To parse cardiac activities from vibration signals, we build a deep-learning pipeline associating the encoder-decoder framework and Generative Adversarial Networks. With dedicated construction and training, it can estimate the ECG waveform accurately. Experiments with 20 participants show that VibCardiogram can achieve an average estimation error of 5.989% for waveform amplitude estimation, which is within the 10% margins regulated by the American National Standards Institute. Moreover, the promising results further confirm that VibCardiogram effectively extracts Heart Rate Variability features and supports downstream applications.

[<ins>Download PDF</ins>](../files/VibCardiogram.pdf) 

[<ins>Download slides</ins>](../files/vibcardiogram.pptx)

[<ins>View full paper</ins>](https://dl.acm.org/doi/abs/10.1145/3550307)
