# Visual_Anomaly_Detection
Contains Codes for visual anomaly detection

Part 1) Uses MVtec_AD dataset and using Anomalib from the OpenVino toolkit, trains it on specifically transistor images for detecting anomalies, using EfficientAD from Anomalib.

Further plans:
1) Evaluate it on custom data of good apple vs bad.
2)  Implement it on Tensorflow lite, and use it o generate portable files on Android.
3)  Custom model on Jetson Nano using Efficient net architecture for faster inference times.



PS: Made for learning purposes only and not for commercial use.

code reference:
1) [https://www.kaggle.com/code/skrmanglam/mvtec-ad-anomaly-detection-with-anomalib-library/edit](https://www.kaggle.com/code/ipythonx/mvtec-ad-anomaly-detection-with-anomalib-library/notebook)https://www.kaggle.com/code/ipythonx/mvtec-ad-anomaly-detection-with-anomalib-library/notebook
2) https://github.com/openvinotoolkit/anomalib

Anomalib Documentation:
1) https://openvinotoolkit.github.io/anomalib/

Paper References:
1) https://arxiv.org/abs/2202.08341 -> Anomalib
2) https://arxiv.org/pdf/2303.14535.pdf -> EfficientAD
---Other papers can be found at Anomalib's github page---

Dataset reference: 
1) https://www.mvtec.com/company/research/datasets/mvtec-ad
