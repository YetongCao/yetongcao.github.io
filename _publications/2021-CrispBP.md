---
title: "Crisp-BP: Continuous Wrist Ppg-Based Blood Pressure Measurement"
collection: publications
permalink: /publication/2021-CrispBP
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-10-25
venue: 'ACM MOBICOM'
paperurl: 'http://yetongcao.github.io/files/PPGPass.pdf'
citation: #'Yetong Cao, Qian Zhang, Fan Li, Song Yang, Yu Wang. 2020. &quot;EarAce: Empowering Versatile Acoustic Sensing via Earable Active Noise Cancellation Platform.&quot; <i>Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies</i>. 7(2), 1-23.'
---
Yetong Cao, Qian Zhang, Fan Li, Song Yang, Yu Wang. "Crisp-BP: Continuous Wrist Ppg-Based Blood Pressure Measurement". _Proceedings of the 27th Annual International Conference on Mobile Computing and Networking_, 2021, pp. 378–391.


### Abstract:
Arterial blood pressure (ABP) monitoring using wearables has emerged as a promising approach to empower users with self-monitoring for effective diagnosis and control of hypertension. However, existing schemes mainly monitor ABP at discrete time intervals, involve some form of user effort, have insufficient accuracy, and require collecting sufficient training data for model development. To tackle these problems, we propose Crisp-BP, a novel ABP monitoring system leveraging the PPG sensor available in commercial wrist-worn devices (e.g., smartwatches or fitness trackers). It enables continuous, accurate, user-independent ABP monitoring and requires no behavior changes during collecting PPG data. The basic idea is to illuminate a skin/tissue, measure the light absorption, and characterize ABP-related blood volume change in the artery. To obtain accurate measurements and relieve the pain of training data collection, we use an arterial pulse extraction method that removes interference caused by capillary pulses. Moreover, we design a contact pressure estimation method to combat the deficiency of PPG waveform being sensitive to the contact pressure between the sensor and the skin. In addition, we leverage the great power of Bidirectional Long Short Term Memory and design a hybrid neural network model to enable user-independent ABP monitoring, so that users do not have to provide training data for model development. Furthermore, we propose a transfer learning method that first extracts general knowledge from online PPG data, then use it to improve the learning of a new model on our target problem. Extensive experiments with 35 participants demonstrate that Crisp-BP obtains the average estimation error of 0.86 mmHg and 1.67 mmHg and the standard deviation error of 6.55 mmHg and 7.31 mmHg for diastolic pressure and systolic pressure, respectively. These errors are within the acceptable range regulated by the FDA's AAMI protocol, which allows average errors of up to 5 mmHg and a standard deviation of up to 8 mmHg. Our results demonstrate that Crisp-BP is promising for improving the diagnosis and control of hypertension as it provides continuousness, comfort, convenience, and accuracy.

[<ins>Download PDF</ins>](../files/Crisp-BP.pdf)

[<ins>Download slides</ins>](../files/Mobicom-15min.pptx)

[<ins>View full paper</ins>](https://dl.acm.org/doi/abs/10.1145/3447993.3483241)
