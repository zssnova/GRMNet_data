# GRMNet_data
This repository provides a heterogeneous railway scene perception dataset for research on railway track-geometry reconstruction and foreign-object detection.

## Dataset composition

The dataset contains 2,449 images:

- 2,072 synthetic images
- 377 real-world images
- 2,105 training images
- 264 validation images
- 80 test images

The detailed split is as follows:

| Split | Synthetic | Real-world | Total |
|---|---:|---:|---:|
| Train | 1,809 | 296 | 2,105 |
| Validation | 226 | 38 | 264 |
| Test | 37 | 43 | 80 |
| Total | 2,072 | 377 | 2,449 |

## Real-world data

The real-world images were extracted from six high-definition railway video segments recorded by a low-altitude unmanned aerial vehicle. The camera was oriented along the railway track to approximate the forward-looking viewpoint of an on-board railway inspection system. The images were therefore acquired from an UAV-based platform under an on-board-like viewing configuration.

## Annotations

The dataset supports two tasks:

1. Foreign-object detection using bounding-box annotations.
2. Railway track-geometry reconstruction using paired left and right rail polylines.

The foreign-object categories are:

- UAVs
- Animals
- Falling rocks
- Pedestrians
- Plastic bags
- Tree trunks
- Traffic lights

The release package contains:

- Images
- Object-detection annotations
- Rail-polyline annotations
- Training, validation, and test split files
- Camera parameters required for geometry-aware processing

## Intended use

The dataset is intended for academic research on:

- Railway visual perception
- Track-geometry reconstruction
- Foreign-object detection
- Geometric scene understanding
- Topology-aware visual modeling
- Railway inspection and maintenance

Access to the dataset is available upon request. Please contact \texttt{zhaozhihao@stu.qut.edu.cn} to submit an access request.

通过网盘分享的文件：VOC2007.zip
链接: https://pan.baidu.com/s/10_fBtjl-FGsIPmbjlvARSw?pwd=bec4 提取码: bec4 
--来自百度网盘超级会员v1的分享
