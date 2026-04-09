<div align="center">
  <img src="figures/LeavesBank.png" alt="Train Images and Labels" width="1000" height="500"/>
</div>


<div align="center">

## LeavesBank Dataset: An Instance Leaf Segmentation Dataset with 220K Instances Across Different Plant Types and Task

</div>


<p align="center">
  <a href="https://www.kaggle.com/datasets/aslhanyldrm/leavesbank-dataset"><img src="https://img.shields.io/badge/Kaagle Dataset-blue.svg"></a>
  <a href="https://www.python.org/downloads/release/python-3106/"><img src="https://img.shields.io/badge/Python-3.10.6-red.svg"></a>
  <a href="https://pytorch.org/get-started/previous-versions/"><img src="https://img.shields.io/badge/Pytorch-2.0.1-red.svg"></a>
  <a href="https://developer.nvidia.com/cuda-11-8-0-download-archive/"><img src="https://img.shields.io/badge/Cuda-11.8-red.svg"></a>
  <a href="https://github.com/ultralytics/ultralytics"><img src="https://img.shields.io/badge/Ultralytics-green.svg"></a>
  <a href="https://github.com/facebookresearch/sam2"><img src="https://img.shields.io/badge/SAM2-purple.svg"></a>
  </p>



## 👋 Welcome

Hi! Welcome to "The Leaves Bank Dataset" official repository. Leafbank dataset was created by labeling 13 different publicly available datasets using a semi-automated active learning pipeline.During dataset development, care was taken to include not only plant diversity but also various plant tasks such as growth monitoring, disease classification, and phenotyping, as well as image quality. Detailed explanations are below 👇.

------------------


## 🌱 Datasets Used In This Study

This study utilized open-source datasets predominantly consisting of academic outputs. The research was conducted using datasets encompassing various leaf morphologies (e.g., compound, simple) and more than 13 distinct plant species. Specifically, the following datasets were incorporated into the study: [Plant Pathology 2021](https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8), [PlantNet 300K](https://zenodo.org/records/4726653), [Betel Leaf Dataset](https://data.mendeley.com/datasets/g7fpgj57wc/2), [icassava2019](https://sites.google.com/view/fgvc6/competitions/icassava-2019), [Cinnamoum Tamala (Indian Bay Tree Leaf)](https://data.mendeley.com/datasets/s9t7sr52wg/1), [GroundNut Leaf Dataset](https://data.mendeley.com/datasets/x6x5jkk873/2), [Lemon Leaf Dataset](https://data.mendeley.com/datasets/rcyyf5j9zg/1), [OkraDiseaseNet](https://data.mendeley.com/datasets/nh7zk4hv8z/1), [Peach Dataset](https://data.mendeley.com/datasets/3pmj85snvw/1), [Diamos Dataset](https://zenodo.org/records/5557313), [Pumpkin Leaf Dataset](https://data.mendeley.com/datasets/wtxcw8wpxb/1), [Sunflower Dataset](https://data.mendeley.com/datasets/b83hmrzth8/1), and [CVPPP2017 Dataset](https://www.plant-phenotyping.org/datasets-home) .


------------------------------


## 🗃️ Annotation Process and Hierarchical File Structure

An analysis of the datasets mentioned in Section 2.1 revealed several artifacts suboptimal for a high-quality dataset, such as low image resolution, motion blur or shifts caused by environmental conditions during acquisition, and the presence of weeds rather than the target foliage. Furthermore, some datasets exhibited potential data imbalance due to a high density of leaves per image. To mitigate the labor-intensive nature of labeling these instances, a representative sampling strategy was adopted instead of utilizing the entire collection. Following a rigorous multi-criteria evaluation, the annotation process was initiated. Two distinct classes were defined: the 'leaf' label was assigned to centrally located and clearly distinguishable leaves, while the 'leaf_secondary' label was used for the remaining instances. After the annotation process, a hierarchical file structure was established. Comprehensive details regarding the class definitions and the organizational directory structure are presented in Figure A.


------------------------------


## 🧪 Test Results 
To demonstrate how LeafBank's rich data repository contributes to classical architectures, we trained YOLOv11 variants. The test results are shown in the video.


https://github.com/user-attachments/assets/06e4ea6c-3b15-42a9-8b5e-b377b31e2906


We also used Leafbank to compare the zero-shot performance of various YOLO features from the literature with the state-of-the-art SAM3 model and extensive studies.

---------

## 📥 How to Download Dataset and Trained Models
The dataset was published on Kaagle because it contains high-resolution images and a massive number of polygon points. You can access the main link by clicking [https://www.kaggle.com/datasets/aslhanyldrm/leavesbank-dataset](https://www.kaggle.com/datasets/aslhanyldrm/leavesbank-dataset). Also you can access the published models from [here](https://github.com/aaslihanyildirim/LeavesBank-Dataset/releases/tag/models).

-----------
## 📖 Citation (to be added)
If you are conducting a study using this dataset or published models, please remember to tag this repository and the research paper will be published under [license](https://github.com/aaslihanyildirim/LeafBank-Dataset?tab=CC-BY-4.0-1-ov-file).
