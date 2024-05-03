# RiverSnap - estimation of river hydraulic parameters using machine learning/AI models
# The page is in the process of being created or updated.


## Overviwe
RiverSnap is a local citizen science project that records and estimates some hydrological parameters such as water level (water level), river course (erosion/subsidence of the river), and vegetation.
![Test Image 1](https://github.com/ArminMoghimi/RiverSnap/blob/RiverSnap/RiverSnap.jpg)
In the RiverSnap research project, which is part of the Zukunftslabor Wasser initiative, data from smartphones and other close-range image sources like unmanned aerial vehicles capturing river scenes or videos shared voluntarily by citizens, scientists, and community members are combined with in-situ data (e.g., official gauge stations data). These data are analyzed to extract water-related, hydraulic, and structural parameters pertinent to river systems. The project RiverSnap is focused on further developing and investigating novel methods to determine hydraulic parameters, which are shared on this platform. To achieve this, cutting-edge machine learning and AI methods are employed, developed, further developed, and investigated, enabling the accurate determination of critical indices.



The first paper was published in IEEE Access (codes and dataset): 

A. Moghimi, M. Welzel, T. Celik, and T. Schlurmann, "A Comparative Performance Analysis of Popular Deep Learning Models and Segment Anything Model (SAM) for River Water Segmentation in Close-Range Remote Sensing Imagery," in IEEE Access, doi: 10.1109/ACCESS.2024.3385425. 

https://ieeexplore.ieee.org/document/10493013

## Our paper presents the Python code for fine-tuning [SAM](https://segment-anything.com/) for water segmentation from close-range remote sensing images, which is under development. 
Try it in Colab:</br></br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/169TpQs74YkzF1Dffb_SHddCdOJX6fDdE?usp=drive_link)

https://colab.research.google.com/drive/169TpQs74YkzF1Dffb_SHddCdOJX6fDdE?usp=drive_link

This code is developed based on the original code of SAM (https://github.com/facebookresearch/segment-anything) and a nice tutorial presented by Alexandre Bonnet regarding fine-tuning of SAM available at https://encord.com/blog/learn-how-to-fine-tune-the-segment-anything-model-sam/

https://github.com/facebookresearch/segment-anything


## The LuFI-RiverSNAP.v1 dataset for water segmentation is available in the following links:  

[https://1drv.ms/u/s!AvQPxeTMtP1HbTnvKmGI3PD4g68?e=kPJhZm](https://drive.google.com/drive/folders/1fA78HOktI98PTKfhxxzPCijTodlBaf_r?usp=sharing)

 ## Kaggle
This dataset is also available at # Kaggle:
https://www.kaggle.com/datasets/arminmoghimi/lufi-riversnap

## ISPRS ICWG III/IVa "Disaster Management
This dataset is also available in the "Datasets & Opensources" section of # ISPRS ICWG III/IVa "Disaster Management" of ISPRS: 

https://www2.isprs.org/commissions/comm3/icwg-3-4a/datasets/

## Cite
Please cite the following papers if they help your research. You can use the following BibTeX entry:
```
@article{moghimi2024comparative,
  title={A Comparative Performance Analysis of Popular Deep Learning Models and Segment Anything Model (SAM) for River Water Segmentation in Close-Range Remote Sensing Imagery},
  author={Moghimi, Armin and Welzel, Mario and Celik, Turgay and Schlurmann, Torsten},
  journal={IEEE Access},
  year={2024},
  doi={https://doi.org/10.48550/arXiv.2304.02643},
  publisher={IEEE}
}
```
A. Moghimi, M. Welzel, T. Celik, and T. Schlurmann, "A Comparative Performance Analysis of Popular Deep Learning Models and Segment Anything Model (SAM) for River Water Segmentation in Close-Range Remote Sensing Imagery," in IEEE Access, doi: 10.1109/ACCESS.2024.3385425. https://ieeexplore.ieee.org/document/10493013
```
@inproceedings{kirillov2023segment,
  title={Segment anything},
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C and Lo, Wan-Yen and others},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={4015--4026},
  doi={https://doi.org/10.48550/arXiv.2304.02643},
  year={2023}
}
```
Kirillov, A., Mintun, E., Ravi, N., Mao, H., Rolland, C., Gustafson, L., ... & Girshick, R. (2023). Segment anything. In Proceedings of the IEEE/CVF International Conference on Computer Vision (pp. 4015-4026).
https://doi.org/10.48550/arXiv.2304.02643


# The page is in the process of being created or updated.
