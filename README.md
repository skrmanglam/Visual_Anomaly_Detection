# Visual_Anomaly_Detection
Contains Codes for visual anomaly detection

**Part 1**: Uses the MVtec_AD dataset and, using Anomalib from the OpenVino toolkit, trains it on specifically transistor images for detecting anomalies, using EfficientAD from Anomalib.

Further plans:
1) Test all the network architectures available in Anomalib for their latency.
2) Evaluate it on custom data on good apples vs. bad apples.
3) Implement it on Tensorflow Lite and use it to generate portable files on Android.
4) Custom model on Jetson Nano using Efficient net architecture for faster inference times.



PS: Made for learning purposes only and not for commercial use.

code reference:
1) [https://www.kaggle.com/code/skrmanglam/mvtec-ad-anomaly-detection-with-anomalib-library/edit](https://www.kaggle.com/code/ipythonx/mvtec-ad-anomaly-detection-with-anomalib-library/notebook)https://www.kaggle.com/code/ipythonx/mvtec-ad-anomaly-detection-with-anomalib-library/notebook
2) https://github.com/openvinotoolkit/anomalib

Anomalib Documentation:
1) https://openvinotoolkit.github.io/anomalib/

Paper References:
1) https://arxiv.org/abs/2202.08341 -> Anomalib
2) https://arxiv.org/pdf/2303.14535.pdf -> EfficientAD
---Other papers can be found on Anomalib's GitHub page---

Dataset reference: 
1) https://www.mvtec.com/company/research/datasets/mvtec-ad


**Part 2**: Uses Alibi_detect

Outlier detection using alibi-detect:
Alibi Detect is an open-source Python library focused on outlier, adversarial, and drift detection. 
The package aims to cover both online and offline detectors for tabular data, text, 
images, and time series. The outlier detection methods should allow the user to 
identify global, contextual, and collective outliers.

Video Tutorial References:
1) https://www.youtube.com/watch?v=2K3ScZp1dXQ
2) https://www.youtube.com/watch?v=Pql6ShORpNU&t=433s

Code References:
1) https://github.com/bnsreenu/python_for_microscopists/blob/master/264%20-%20Image%20outlier%20detection%20using%20alibi-detect/264_alibinet_outlier_detection.py


