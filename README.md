# Nighttime Segmentation 

* Datasets 
* Models 
* Experiments conducted 
* Inferences 
* Modifications

## Datasets 

* **[Dark Zurich](https://www.trace.ethz.ch/publications/2019/GCMA_UIoU/)** 
    * 50 Annot. Val. images
    * 2416 unlabelled night
    * 151 test: part of competition.
* **[BDD 100k](https://bdd-data.berkeley.edu/)**
    * 395 Annot. Val. images
    * 39k unlabelled night 
* **[Nighttime Driving (only test)](http://people.ee.ethz.ch/~daid/NightDriving/)**
    * 50 Annot test images
* **[Mapillary Vistas](https://www.mapillary.com/dataset/vistas?pKey=2ix3yvnjy9fwqdzwum3t9g)**
    * At least 250 test images 
* **[NightCity](https://www.cs.cityu.edu.hk/~rynson/projects/lowlight/Low-lightImaging.html)**
    * 4297 Labelled Night Segmentation (Not Published yet)

## Models

### Unsuperivsed Domain Adaptation
* Map-Guided Curriculum Domain Adaptation and Uncertainty-Aware Evaluation for Semantic Nighttime Image Segmentation **[TPAMI 21 code](https://github.com/sakaridis/MGCDA)** 
* Guided Curriculum Model Adaptation and Uncertainty-Aware Evaluation for Semantic Nighttime Image Segmentation **[ICCV 19](https://openaccess.thecvf.com/content_ICCV_2019/papers/Sakaridis_Guided_Curriculum_Model_Adaptation_and_Uncertainty-Aware_Evaluation_for_Semantic_Nighttime_ICCV_2019_paper.pdf)**
* ForkGAN: Seeing into the rainy night **[ECCV 20 code](https://github.com/zhengziqiang/ForkGAN)**
* Dark model adaptation: Semantic image segmentation from daytime to nighttime **[ITSC 18](https://arxiv.org/abs/1810.02575)**
* See Clearer at Night: Towards Robust Nighttime Semantic Segmentation through Day-Night Image Conversion **[IEEE 19](https://arxiv.org/abs/1908.05868#:~:text=16%20Aug%202019%5D-,See%20Clearer%20at%20Night%3A%20Towards%20Robust%20Nighttime%20Semantic,through%20Day%2DNight%20Image%20Conversion&text=Currently%2C%20semantic%20segmentation%20shows%20remarkable,scenes%20with%20favorable%20illumination%20conditions.)**
* Bridging the Day and Night Domain Gap for Semantic Segmentation **[IEEE 19](https://arxiv.org/abs/2003.04645)**
* What's there in the dark **[ICIP 19 code](https://github.com/sauradip/night_image_semantic_segmentation)**
* Semantic Segmentation With Low Light Images by Modified CycleGAN-Based Image Enhancement **[IEEE 20](https://ieeexplore.ieee.org/abstract/document/9094229)**
* Rainy Night Scene Understanding With Near Scene Semantic Adaptation **[ITSC 21](https://ieeexplore.ieee.org/document/9000933)**
* Modified Perceptual Cycle Generative Adversarial Network-Based Image Enhancement for Improving Accuracy of Low Light Image Segmentation **[IEEE 20](https://ieeexplore.ieee.org/abstract/document/9311609)**

### Supervised 

* Night-time Semantic Segmentation with a Large Real Dataset **[arxiv 20](https://arxiv.org/abs/2003.06883)** 
* Hybrid Feature based Pyramid Network for Nighttime Semantic Segmentation **[visigrapp 20](https://www.insticc.org/node/TechnicalProgram/visigrapp/2021/presentationDetails/102485)**

### Thermal Modality

* HeatNet: Bridging the Day-Night Domain Gap in Semantic Segmentation with Thermal Images **[arxiv 20](https://arxiv.org/abs/2003.04645)**
* Segmenting Objects in Day and Night:Edge-Conditioned CNN for Thermal Image Semantic Segmentation **[arxiv 19](https://arxiv.org/abs/1907.10303)** 



