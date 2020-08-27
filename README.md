# Awesome Diabetic-Retinopathy-Detection

If you have any problems, suggestions or improvements, please submit the issue or PR.

## Contents
* [Datasets](#datasets)
* [Papers](#papers)
* [Codes](#codes)

## Datasets

| Dataset                   | Time     | Images |  Format   |  Camera  |  Resolution |  FOV  | Institudes | Tasks |
|---------------------------|----------|--------|-----------|----------|-------------|-------|------------| ----- |
| [Kaggle](https://www.kaggle.com/c/diabetic-retinopathy-detection/) | 2015 | 88k | jpeg | / | / | 50° | EyePACS | DR grading |
| [Messidor](http://www.adcis.net/en/third-party/messidor/) | 2014 | 1200 | tiff | Topcpn TRC NW6 | 1440x960,<br>2240x1488,<br>2304x1536 | 45° | ADCIS | DR & DME grading |
| [IDRiD](https://ieee-dataport.org/open-access/indian-diabetic-retinopathy-image-dataset-idrid) | 2018 | 516/81 | jpg | Kowa VX-10α | 4288x2848 | 50° | CESIP | DR & DME grading / Typical DR lesions & optic disc detection / Optic disc and fovea center location |
| [DIARETDB0](https://www.it.lut.fi/project/imageret/diaretdb0/index.html) | 2007 | 130 | jpg | / | 1500x1152 | 50° | / | DR lesions finding |
| [DIARETDB1](https://www.it.lut.fi/project/imageret/diaretdb1/index.html) | 2007 | 89 | jpg | / | 1500x1152 | 50° | / | DR lesions detection |
| [ROC](http://webeye.ophth.uiowa.edu/ROC/) | 2007 | 100 | jpg | / | 768×576,<br>1058x1061,<br>1386×1391 | 45° | / | Microaneurysms detection  |
| [E-ophtha-EX](http://www.adcis.net/en/third-party/e-ophtha/) | 2013 | 82 | jpeg | / | 2533x1696 | 45° | ADCIS | Exudates detection |
| [E-ophtha-MA](http://www.adcis.net/en/third-party/e-ophtha/) | 2013 | 381 | jpeg | / | 2533x1696 | 45° | ADCIS | Microaneurysms detection |

## Papers
<!-- 
- Unsupervised Visual Representation Learning by Context Prediction.
  [[pdf]](https://arxiv.org/abs/1505.05192)
  [[code]](http://graphics.cs.cmu.edu/projects/deepContext/)
  - Doersch, Carl and Gupta, Abhinav and Efros, Alexei A. *ICCV 2015*
-->

### Survey
- IDRiD: Diabetic Retinopathy – Segmentation and Grading Challenge
  [[pdf]](https://www.sciencedirect.com/science/article/pii/S1361841519301033)
  [[code]](https://idrid.grand-challenge.org/Challenge_Proceedings/)
  - Prasanna Porwal, Samiksha Pachade, Manesh Kokare. *MIA 2015*
  
- Computerised approaches for the detection of diabetic retinopathy using retinal fundus images: a survey
  [[pdf]](https://link.springer.com/content/pdf/10.1007%2Fs10044-017-0630-y.pdf)
  - Toufique Ahmed Soomro, Junbin Gao, Tariq Khan. *Pattern Anal Applic 2017*
  
- Computer-aided diagnosis of diabetic retinopathy: A review
  [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S0010482513002862)
  - Muthu Rama Krishnan Mookiah, U. Rajendra Acharya, Chua Kuang Chua. *Computers in Biology and Medicine 2013*


### DR Grading
- <a name=""></a> Collaborative learning of semi-supervised segmentation and classification for medical images **(CVPR2019)** [[paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhou_Collaborative_Learning_of_Semi-Supervised_Segmentation_and_Classification_for_Medical_Images_CVPR_2019_paper.pdf)]
- <a name="CANet"></a> **[CANet]** CANet: Cross-disease Attention Network for Joint Diabetic Retinopathy and Diabetic Macular Edema Grading **(TMI2019)** [[paper](https://arxiv.org/abs/1911.01376)]

- <a name="Zoom-in-Net"></a> **[Zoom-in-Net]** Zoom-in-Net: Deep Mining Lesions for Diabetic Retinopathy Detection **(MICCAI2018)** [[paper](https://arxiv.org/abs/1706.04372)]
- <a name=""></a> A Framework for Identifying Diabetic Retinopathy Based on Anti-noise Detection and Attention-Based Fusion **(MICCAI2018)** [[paper](https://link.springer.com/chapter/10.1007/978-3-030-00934-2_9)]

- <a name="Google"></a> **[Google 1]** Development and Validation of a Deep Learning Algorithm for Detection of Diabetic Retinopathy in Retinal Fundus Photographs **(JAMA2016)** [[paper](https://jamanetwork.com/journals/jama/fullarticle/2588763)]
- <a name="Google"></a> **[Google 2]** Grader Variability and the Importance of Reference Standards for Evaluating Machine Learning Models for Diabetic Retinopathy **(Ophthalmology2018)** [[paper](https://www.aaojournal.org/article/S0161-6420(17)32698-2/fulltext)]
- <a name="Google"></a> **[Google 3]** Using a Deep Learning Algorithm and Integrated Gradients Explanation to Assist Grading for Diabetic Retinopathy **(Ophthalmology2018)** [[paper](https://www.aaojournal.org/article/S0161-6420(18)31575-6/fulltext)]


## Codes
- [[Team o_O](https://github.com/sveitser/kaggle_diabetic)] Team o_O solution for the Kaggle Diabetic Retinopathy Detection Challenge
- [[EyeNet](https://github.com/gregwchase/eyenet)] Identifying diabetic retinopathy using convolutional neural networks


