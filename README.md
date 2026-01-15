<div align="center">
  <img src="leafbank.png" alt="Train Images and Labels" width="500" height="500"/>
</div>


<div align="center">

## LeafBank: A Leaf Segmentation Dataset with 220K Instances Across Different Plant Types and Tasks

</div>


<p align="center">
  <a href="https://www.python.org/downloads/release/python-3106/"><img src="https://img.shields.io/badge/Python-3.10.6-red.svg"></a>
  <a href="https://pytorch.org/get-started/previous-versions/"><img src="https://img.shields.io/badge/Pytorch-2.0.1-red.svg"></a>
  <a href="https://developer.nvidia.com/cuda-11-8-0-download-archive/"><img src="https://img.shields.io/badge/Cuda-11.8-red.svg"></a>
  <a href="https://github.com/ultralytics/ultralytics"><img src="https://img.shields.io/badge/Ultralytics-green.svg"></a>
  <a href="https://huggingface.co/"><img src="https://img.shields.io/badge/Hugginface-yellow.svg"></a>
  <a href="https://www.gradio.app/"><img src="https://img.shields.io/badge/Gradio-orange.svg"></a>
  <a href="https://huggingface.co/spaces/aslihanyildirim/genyolo-leaf"><img src="https://img.shields.io/badge/GenYOLOLeaf Gradio Space-purple.svg"></a>
</p>



## 👋 Welcome

The LeafBank dataset was created by labeling 13 different publicly available datasets using a semi-automated active learning pipeline.  
Detailed information about the dataset and download instructions are provided in the following sections 👇.


 ## 🗃️ Datasets Used For This Study

| Dataset | Plant Type | Leaf Form | Image Count | Task | Region | Camera | Background | Excluding Criteria | 
|--------|------------|-----------|-------------|------|--------|--------|------------|--------------------|
| [Plant Pathology (2021)](https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8)| Apple | Basic | 18,632 | Phenotyping | Europe, USA | Various | N | All |
| [PlantNet](https://zenodo.org/records/4726653) | Various | Mixed | 2,859 | Phenotyping | Various | Various | M | Sample |
| [Betel Leaf Dataset](https://zenodo.org/records/4726653) | Pepper | Basic | 750 | Disease C. | Asia | Smartphone | N | Sample |
| [icassava2019](https://www.kaggle.com/competitions/cassava-disease/data) | Cassava | Compound | 996 | Disease C. | Africa | Smartphone | N | Sample |
| [Cinnamomum Tamala](https://data.mendeley.com/datasets/s9t7sr52wg/2)| Bay Leaves | Basic | 5,696 | Disease C. | Asia | Smartphone | C | All |
| [Ground Nut Leaf Dataset](https://data.mendeley.com/datasets/x6x5jkk873/2) | Ground Nut | Compound | 1,263 | Disease C. | Asia | Smartphone | N | All |
| [Lemon Leaf Dataset](https://data.mendeley.com/datasets/rcyyf5j9zg/1) | Lemon | Basic | 2,094 | Disease C. | Asia | Not Applicable | N | All |
| [Okra DiseaseNet](https://data.mendeley.com/datasets/nh7zk4hv8z/1) | Okra | Compound | 1,500 | Disease C. | Asia | Digital Cam. | N | All |
| [Peach Dataset](https://data.mendeley.com/datasets/3pmj85snvw/1) | Peach | Basic | 285 | Disease C. | Asia | Smartphone | N | Sample |
| [Diamos Dataset](https://zenodo.org/records/5557313) | Pear | Basic | 2,964 | Disease C. | Europe | Various | N | Sample |
| [Pumpkin Leaf Dataset](https://data.mendeley.com/datasets/wtxcw8wpxb/1) | Pumpkin | Compound | 2,000 | Disease C. | Asia | Smartphone | N | All |
| [Sunflower Dataset](https://data.mendeley.com/datasets/b83hmrzth8/1) | Sunflower | Basic | 389 | Disease C. | Asia | Digital Cam. | N | Sample |
| [CVPPP 2017](https://www.plant-phenotyping.org/datasets-home) | Tobacco, Arabidopsis | Compound | 804 | Phenotyping | Asia | Various | C | All |
