# awesome-NDT
A collection of AWESOME things about ML for non-destructive testing
# Contents

- [awesome-NDT](#awesome-ndt)
- [Contents](#contents)
- [Papers](#papers)
  - [Survey](#survey)
  - [Supervised Learning](#supervised-learning)
    - [Classification](#classification)
    - [Regression](#regression)
    - [Object Detection](#object-detection)
    - [Segmentation](#segmentation)
  - [Unsupervised Learning](#unsupervised-learning)
    - [Self-Supervised Learning](#self-supervised-learning)
    - [Anomaly Detection](#anomaly-detection)
    - [Metric Learning](#metric-learning)
    - [Dimension Reduction](#dimension-reduction)
  - [Image Generation](#image-generation)
  - [Domain Adaptation](#domain-adaptation)
  - [Data Augmentation](#data-augmentation)
  - [Federated Learning](#federated-learning)
  - [Bayesian inference](#bayesian-inference)
  - [Simulation](#simulation)
  - [Super Resolution](#super-resolution)
  - [denoising technique](#denoising-technique)
  - [Physics Informed Neural Network](#physics-informed-neural-network)
- [Others](#others)

# Papers
## Survey
- Machine learning for ultrasonic nondestructive examination of welding defects: A systematic review [[January 2023]](https://www.sciencedirect.com/science/article/pii/S0041624X22001603)
- Deep learning in automated ultrasonic NDE – Developments, axioms and opportunities [[October 2022]](https://www.sciencedirect.com/science/article/pii/S0963869522001025?via%3Dihub)
- A review of ultrasonic sensing and machine learning methods to monitor industrial processes [[August 2022]](https://www.sciencedirect.com/science/article/pii/S0041624X2200083X)
- Artificial Intelligence, Machine Learning and Smart Technologies for Nondestructive Evaluation [[May 2022]](https://www.mdpi.com/1424-8220/22/11/4055)
- Recent Advances in Machine Learning Applied to Ultrasound Imaging [[March 2022]](https://www.mdpi.com/2079-9292/11/11/1800)
- A Survey on Artificial Intelligence Research and Its Applications to Non-destructive Evaluation [[April 2018]](https://unit.aist.go.jp/nmij/public/report/bulletin/Vol10/2/V10N2P263.pdf)
## Supervised Learning
### Classification
- Machine Learning and 3D Reconstruction of Materials Surface for Nondestructive Inspection [[August 2022]](https://www.mdpi.com/1424-8220/22/16/6201?type=check_update&version=1)
- Automated detection and characterisation of defects from multiview ultrasonic imaging [[June 2022]](https://www.sciencedirect.com/science/article/pii/S0963869522000275?via%3Dihub)
- CNN-LSTM network-based damage detection approach for copper pipeline using laser ultrasonic scanning [[April 2022]](https://www.sciencedirect.com/science/article/pii/S0041624X22000038)
- TAF2-Net: Triple-Branch Attentive Feature Fusion Network for Ultrasonic Flaw Detection [[February 2022]](https://ieeexplore.ieee.org/document/9709291)
- A deep learning automatic classification method for clogging pervious pavement [[November 2021]](https://www.sciencedirect.com/science/article/pii/S0950061821029391)
- Automated Flaw Detection in Multi-channel Phased Array Ultrasonic Data Using Machine Learning [[August 2021]](https://link.springer.com/article/10.1007/s10921-021-00796-4)
- Porosity Evaluation of Additively Manufactured Components Using Deep Learning-based Ultrasonic Nondestructive Testing [[April 2021]](https://link.springer.com/article/10.1007/s40684-021-00319-6)
- Machine Learning-Based Detection Technique for NDT in Industrial Manufacturing [[April 2021]](https://www.mdpi.com/2227-7390/9/11/1251)
- Deconvolution of ultrasonic signals using a convolutional neural network [[March 2021]](https://www.sciencedirect.com/science/article/pii/S0041624X2030247X?via%3Dihub)
- Identification of Grout Sleeve Joint Defect in Prefabricated Structures Using Deep Learning [[October 2020]](https://www.frontiersin.org/articles/10.3389/fmats.2020.00298/full)
- Performance enhancement of convolutional neural network for ultrasonic flaw classification by adopting autoencoder [[April 2020]](https://www.sciencedirect.com/science/article/pii/S0963869519306243)
- Machine Learning in Pipeline Inspection: Applications of supervised learning in non-destructive evaluation [[June 2019]](https://www.ndt.net/search/docs.php3?id=24701)
- Convolutional neural network for ultrasonic weldment flaw classification in noisy conditions [[April 2019]](https://www.sciencedirect.com/science/article/pii/S0041624X18305754?via%3Dihub)
- Computerized Ultrasonic Imaging Inspection: From Shallow to Deep Learning [[October 2018]](https://www.mdpi.com/1424-8220/18/11/3820)
- Deep learning based classification of breast tumors with shear-wave elastography [[December 2016]](https://www.sciencedirect.com/science/article/pii/S0041624X16301378)
- Automatic Defect Classification in Ultrasonic NDT Using Artificial Intelligence [[December 2010]](https://link.springer.com/article/10.1007/s10921-010-0086-0)
### Regression
- Non-destructive evaluating the density and mechanical properties of ancient timber members based on machine learning approach [[July 2022]](https://www.sciencedirect.com/science/article/pii/S0950061822015288)
- Defect sizing in guided wave imaging structural health monitoring using convolutional neural networks [[September 2021]](https://www.sciencedirect.com/science/article/pii/S0963869521000797)
### Object Detection
- Defects detection in weld joints based on visual attention and deep learning [[January 2023]](https://www.sciencedirect.com/science/article/pii/S0963869522001633)
- DefectDet: A deep learning architecture for detection of defects with extreme aspect ratios in ultrasonic images [[February 2022]](https://www.sciencedirect.com/science/article/pii/S0925231221018464)
- Towards using convolutional neural network to locate, identify and size defects in phased array ultrasonic testing [[August 2021]](https://www.sciencedirect.com/science/article/pii/S0041624X21000731)
- Flaw Detection from Ultrasonic Images using YOLO and SSD [[September 2019]](https://ieeexplore.ieee.org/document/8868929)
- Generative adversarial network with object detector discriminator for enhanced defect detection on ultrasonic B-scan [[Jun 2021]](https://arxiv.org/pdf/2106.04281.pdf)
- Internal Damage Identification of Sandwich Panels With Truss Core Through Dynamic Properties and Deep Learning [[September 2020]](https://www.frontiersin.org/articles/10.3389/fmats.2020.00301/full)
- Concrete crack detection and quantification using deep learning and structured light [[August 2020]](https://www.sciencedirect.com/science/article/pii/S0950061820311016)
### Segmentation
- Predicting local material thickness from steady-state ultrasonic wavefield measurements using a convolutional neural network [[July 2022]](https://www.sciencedirect.com/science/article/pii/S0041624X2100278X?via%3Dihub)
- Two-stage ultrasound image segmentation using U-Net and test time augmentation [[April 2020]](https://link.springer.com/article/10.1007/s11548-020-02158-3)
- Fine tuning U-Net for ultrasound image segmentation: which layers? [[Feb 2020]](https://arxiv.org/abs/2002.08438)
- Breast lesion segmentation in ultrasound images with limited annotated data [[Jan 2020]](https://arxiv.org/abs/2001.07322)
## Unsupervised Learning
### Self-Supervised Learning
### Anomaly Detection
- Deep anomaly detection model for composite inspection in quadratic frequency modulated thermal wave imaging [[December 2022]](https://www.sciencedirect.com/science/article/pii/S0963869522001098)
- Deep learning-based anomaly detection from ultrasonic images [[August 2022]](https://www.sciencedirect.com/science/article/pii/S0041624X2200049X)
- Autoencoder-based detection of near-surface defects in ultrasonic testing [[February 2022]](https://www.sciencedirect.com/science/article/pii/S0041624X21002547)
### Metric Learning
- Unsupervised deep learning based approach to temperature monitoring in focused ultrasound treatment [[May 2022]](https://www.sciencedirect.com/science/article/pii/S0041624X22000063)
### Dimension Reduction
- Convolutional feature extraction for process monitoring using ultrasonic sensors [[December 2021]](https://www.sciencedirect.com/science/article/pii/S0098135421002866?via%3Dihub)
- Application of Deep Learning in Infrared Non-Destructive Testing [[May 2019]](https://www.ndt.net/search/docs.php3?id=24222)
## Image Generation
- Generating ultrasonic images indistinguishable from real images using Generative Adversarial Networks [[February 2022]](https://www.sciencedirect.com/science/article/pii/S0041624X21002298)
## Domain Adaptation
- Machine learning and domain adaptation to monitor yoghurt fermentation using ultrasonic measurements [[May 2023]](https://www.sciencedirect.com/science/article/pii/S0956713523000221?via%3Dihub)
- Transfer learning for process monitoring using reflection-mode ultrasonic sensing [[Aug 2021]](https://www.sciencedirect.com/science/article/pii/S0041624X21001025?via%3Dihub)
## Data Augmentation
- Augmented Ultrasonic Data for Machine Learning [[March 2019]](https://arxiv.org/abs/1903.11399)
- Flaw Detection in Ultrasonic Data Using Deep Learning [[January 2019]](https://core.ac.uk/download/pdf/292602691.pdf3)
## Federated Learning
- Domain Adaptation and Federated Learning for Ultrasonic Monitoring of Beer Fermentation [[October 2021]](https://www.mdpi.com/2311-5637/7/4/253)
## Bayesian inference
- The use of full-skip ultrasonic data and Bayesian inference for improved characterisation of crack-like defects [[July 2021]](https://www.sciencedirect.com/science/article/pii/S0963869521000669?via%3Dihub)
## Simulation
- Optimizing hyperparameters of Data-driven simulation-assisted-Physics learned AI (DPAI) model to reduce compounding error [[February 2023]](https://www.sciencedirect.com/science/article/pii/S0041624X2200169X?ref=cra_js_challenge&fr=RR-1)
- Simulation trained CNN for accurate embedded crack length, location, and orientation prediction from ultrasound measurements [[May 2022]](https://www.sciencedirect.com/science/article/pii/S0020768322000786?via%3Dihub)
- Deep Learning for Ultrasonic Crack Characterization in NDE [[May 2021]](https://research-information.bris.ac.uk/ws/files/286790774/clean_file_for_Xplore.pdf)
## Super Resolution
- Uncertainty quantification in super-resolution guided wave array imaging using a variational Bayesian deep learning approach [[January 2023]](https://www.sciencedirect.com/science/article/pii/S0963869522001529)
- Real-time super-resolution mapping of locally anisotropic grain orientations for ultrasonic non-destructive evaluation of crystalline material [[May 2021]](https://arxiv.org/abs/2105.09466)
## denoising technique
- Ultrasonic signal enhancement for coarse grain materials by machine learning analysis [[December 2021]](https://www.sciencedirect.com/science/article/pii/S0041624X21001773)
- Ultrasonic signal denoising based on autoencoder [[April 2020]](https://aip.scitation.org/doi/10.1063/1.5136269) 
## Physics Informed Neural Network
- Physics-informed neural network for ultrasound nondestructive quantification of surface breaking cracks [[May 2020]](https://arxiv.org/abs/2005.03596)
# Others
- Improvement Possibilities for Nuclear Power Plants Inspections by Adding Deep Learning-based Assistance Algorithms Into a Classic Ultrasound NDE Acquisition and Analysis Software [[February 2023]](http://www.journalofenergy.com/index.php/joe/article/view/410/378)
- Non-destructive testing (NDT) in industry 4.0: A brief review [[June 2021]](https://procceding.unram.ac.id/index.php/icst/article/view/71/pdf)
- Manufacturing Industry DX through Deep Learning Application Technologies —From Non-Destructive Testing to Quality Control— [[February 2020]](https://www.fujitsu.com/global/documents/about/resources/publications/technicalreview/2020-02/article03.pdf)
- A human-centric approach to AI in aviation [[February 2020]](https://www.easa.europa.eu/en/downloads/109668/en)
- Advanced methods in NDE using machine learning approaches [[April 2018]](https://aip.scitation.org/doi/abs/10.1063/1.5031519)
- Guidebook on non-destructive testing of concrete structures [[September 2002]](https://www-pub.iaea.org/mtcd/publications/pdf/tcs-17_web.pdf)