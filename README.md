# MARL for Autonomous Driving

Hi there, welcome to our repository.  
Here is all you need to learn the **Multi-Agent Reinforcement Learning (MARL) for Autonomous Driving**.  
For a more comprehensive survey, please look at:
> [**Multi-Agent Reinforcement Learning for Autonomous Driving: A Survey**](https://arxiv.org/abs/2408.09675)  
> [Ruiqi Zhang<sup>1,2</sup>](https://ruiqizhang99.github.io), [Jing Hou<sup>1</sup>](https://scholar.google.com/citations?user=8mO6YIMAAAAJ), [Florian Walter<sup>3</sup>](https://scholar.google.com/citations?user=Z3QCbaUAAAAJ), [Shangding Gu<sup>2,4</sup>](https://scholar.google.com/citations?user=E1GCDXUAAAAJ), [Jiayi Guan<sup>1</sup>](https://scholar.google.com/citations?user=PbNNo9cAAAAJ), [Florian Röhrbein<sup>5</sup>](https://scholar.google.com/citations?user=IEOJBbAAAAAJ), [Yali Du<sup>6</sup>](https://scholar.google.com/citations?user=WMlPkOoAAAAJ), [Panpan Cai<sup>7</sup>](https://cindycia.github.io/), [Guang Chen<sup>1,4,*</sup>](https://ispc-group.github.io/), [Alois Knoll<sup>4</sup>](https://scholar.google.com/citations?user=-CA8QgwAAAAJ)  
> <sup>1</sup>Tongji University; <sup>2</sup>University of California, Berkeley; <sup>3</sup>University of Technology Nuremberg; <sup>4</sup>Technical University of Munich; <sup>5</sup>Chemnitz University of Technology; <sup>6</sup>King's College London; <sup>7</sup>Shanghai Jiao Tong University


## 0 Glance at the History

## 1 Open-Access Learning Materials
**Books**
> [Reinforcement Learning: An Introduction](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf) (by Richard Sutton et. al, MIT press)  
> [Reinforcement Learning for Sequential Decision and Optimal Control](https://link.springer.com/book/10.1007/978-981-19-7784-8) (by Shengbo Eben Li, Springer)  
> [Autonomous Driving (Technical, Legal and Social Aspects)](https://link.springer.com/book/10.1007/978-3-662-48847-8) (by Markus Maurer et. al, Springer)  


**Courses** 
> [UC Berkeley, CS285: Introduction to Reinforcement Learning](https://www.youtube.com/watch?v=SupFHGbytvA&list=PL_iWQOsE6TfVYGEGiAOMaOzzv41Jfm_Ps) (by Sergey Levine)  
> [Stanford, CS 234: Reinforcement Learning](https://www.youtube.com/watch?v=FgzM3zpZ55o&list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u) (by Emma Brunskill)  
> [Introduction to Reinforcement Learning (Chinese Version)](https://www.youtube.com/watch?v=IkEF4LpH5Ys&list=PLySQw_vQ73PyDY68KF0HdCzcILBoHVTvD) (by Bolei Zhou)  
> [Multi-Agent Artificial Intelligence [Bilibili]](https://www.bilibili.com/video/BV1fz4y1S72S?p=1&vd_source=cd04812e2c6ae50416c20981d08acf0a) (by Jun Wang)  
> [Self-Driving Cars [Course Syllabus]](https://uni-tuebingen.de/en/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/autonomous-vision/lectures/self-driving-cars/) [[Video]](https://www.youtube.com/watch?v=_q4WUxgwDeg&list=PL05umP7R6ij321zzKXK6XCQXAaaYjQbzr) (by Andreas Geiger)  

**Talks**
> [MicroSoft Reinforcement Learning Day: Multi-Agent Reinforcement Learning](https://www.youtube.com/watch?v=Yd6HNZnqjis&list=PLNZMKGYv14qLCMfRuOJOrvgcKrqyPk6eB)  
> [Berkeley Simons Institute: Multi-Agent Reinforcement Learning [Part I]](https://www.youtube.com/watch?v=RCu-nU4_TQM&t=5s)[[Part II]](https://www.youtube.com/watch?v=RWBF9gG2uz0&t=30s)  
> [Safe Reinforcement Learning via Statistical Model Predictive Shielding, RSS 2021](https://www.youtube.com/watch?v=_czP3eqTjaY)  
> [Safety in Reinforcement Learning by Leveraging Offline Data, IEEE MFI 2022](https://www.youtube.com/watch?v=uvXb0P1knRw)  
> [Learning Robust Policies for Self-Driving, ECCV 2022](https://www.youtube.com/watch?v=rm-1sPQV4zg)  


## 2 Benchmarks
### 2.1 Simulators

**TrafficFlow Oriented**
| Simulator | Released Time | Paper | Other Supplyments | Affiliation |
|-----------|---------------|-------|-------------------|-------------|
|[**SUMO**](https://eclipse.dev/sumo/)| 2001 | [Preprint](https://elib.dlr.de/6661/2/dkrajzew_MESM2002.pdf) | - | openMobility
|[**Flow**](https://flow-project.github.io) | 2018 |[T-RO](https://ieeexplore.ieee.org/document/9489303)|[Documentation](https://flow-project.github.io/tutorial.html)| UC Berkeley
|[**Highway-env**](https://github.com/Farama-Foundation/HighwayEnv)| 2018 | - |[Documentation](https://highway-env.farama.org/) |Farama FD. 
|[**CityFlow**](https://github.com/cityflow-project/CityFlow/)| 2019 | [WWW](https://arxiv.org/abs/1905.05217) |[Documentation](https://cityflow-project.github.io/index.html)| UC Berkeley
|[**BARK**](https://github.com/bark-simulator/bark)| 2020 | [IROS](https://ieeexplore.ieee.org/abstract/document/9341222)|[Documentation](https://bark-simulator.github.io/tutorials/) | fortiss
|[**MADRaS**](https://github.com/madras-simulator/MADRaS) | 2020 | - |[Documentation](https://github.com/madras-simulator/MADRaS/wiki) | - |
|[**SMARTS**](https://github.com/huawei-noah/SMARTS)| 2020 | [CoRL](https://proceedings.mlr.press/v155/zhou21a.html) | [Documentation](https://smarts.readthedocs.io/en/latest/) | Noah's Ark Lab |
|[**MetaDrive**](https://github.com/metadriverse/metadrive)| 2021 |[T-PAMI](https://ieeexplore.ieee.org/abstract/document/9829243) | [Documentation](https://metadrive-simulator.readthedocs.io/en/latest/) | UCLA 
|[**TBSim**](https://github.com/NVlabs/traffic-behavior-simulation) | 2021 | [ICRA](https://ieeexplore.ieee.org/abstract/document/10161167) | [Pretrained Model](https://drive.google.com/drive/folders/1y3_HO1c721pFrFOYeGGjORV58g6zNEds) | NVIDIA Research
|[**TorchDriveSim**](https://github.com/inverted-ai/torchdrivesim)|  2021 | [ITSC](https://ieeexplore.ieee.org/document/9565113) | - | Inverted AI
|[**InterSim**](https://github.com/Tsinghua-MARS-Lab/InterSim) | 2022 | [IROS](https://ieeexplore.ieee.org/abstract/document/9982008) | - | Tsinghua University
|[**Nocturne**](https://github.com/facebookresearch/nocturne) | 2022 | [NeurIPS](https://papers.nips.cc/paper_files/paper/2022/hash/191e9e721a2748a860714fb23aaf7c5d-Abstract-Datasets_and_Benchmarks.html) | - | Meta
|[**ScenarioNet**](https://github.com/metadriverse/scenarionet)| 2024 | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/0c26a501df8fb919a0350e2df06b5d39-Abstract-Datasets_and_Benchmarks.html) | [Documentation](https://scenarionet.readthedocs.io/en/latest/operations.html) |UCLA
|[**Waymax**](https://github.com/waymo-research/waymax)| 2024 | [NeurIPS](https://openreview.net/pdf?id=7VSBaP2OXN) | [Documentation](https://waymo-research.github.io/waymax/docs/) | Waymo Research

**Fidelity Oriented**
| Simulator | Released Time | Paper | Other Supplyments | Affiliation |
|-----------|---------------|-------|-------------------|-------------|
|[**TORCS**](https://sourceforge.net/projects/torcs/)| 2000 | - | - | SourceForge
|[**Gym-TORCS**](https://github.com/ugo-nama-kun/gym_torcs)| 2017 | [Preprint](https://arxiv.org/pdf/1304.1672) | - | UTokyo
|[**CARLA**](https://github.com/carla-simulator/carla)| 2017 | [CoRL](https://proceedings.mlr.press/v78/dosovitskiy17a.html) | [Documentation](https://carla.readthedocs.io/en/latest/)| Intel Lab
|[**MACAD**](https://github.com/praveen-palanisamy/macad-gym)| 2020 | [IJCNN](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9207663)| - | MicroSoft Research
|[**ISAAC Sim**](https://developer.nvidia.com/isaac/sim) | 2020 | - | [Documentation](https://docs.omniverse.nvidia.com/isaacsim/latest/installation/index.html) | NVIDIA Research
|[**ISAAC Lab**](https://github.com/isaac-sim/IsaacLab) | 2024 | [RA-L](https://ieeexplore.ieee.org/abstract/document/10107764) | [Documentation](https://isaac-sim.github.io/IsaacLab/index.html)| NVIDIA Research
|[**Vista**](https://github.com/vista-simulator/vista) | 2020 |  [RA-L](https://ieeexplore.ieee.org/abstract/document/8957584) /[ICRA](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9812276) | [Documentation](https://vista.csail.mit.edu/) | MIT CSAIL


### 2.2 Datasets
> [**KITTI**](https://www.cvlibs.net/datasets/kitti/) (by KIT, etc., 2013)  
> [**KITTI 360**](https://www.cvlibs.net/datasets/kitti-360/) (by KIT, etc., 2021)  
> [**Visual KITTI**](https://europe.naverlabs.com/research/computer-vision/proxy-virtual-worlds-vkitti-1/) (by Naver Lab, 2016)  
> [**Visual KITTI 2**](https://europe.naverlabs.com/research/computer-vision/proxy-virtual-worlds-vkitti-2/) (by Naver Lab, 2020)  
> [**nuScenes**](https://www.nuscenes.org/) (by Motional)
> [**nuPlan**](https://www.nuscenes.org/nuplan) (by Motional)  
> [**Waymo Open Dataset**](https://waymo.com/open/) (by Waymo)  
> [**Lyft LV5**](https://github.com/cognitive-robots/lyft_prediction_dataset_tools) (by Lyft)  
> [**INTERACTION Dataset**](https://interaction-dataset.com/) (by UC Berkeley, 2019) 

-----------
*(UPDATE STILL ON THE WAY)*

### 2.3 Competitions


## 3. Methodologies
### 3.1 Fundamental Algorithm
**Single-Agent RL**

**Multi-Agent RL**

### 3.2 CTDE MARL for Autonomous Driving


### 3.3 Decentralied MARL for Autonomous Driving


### 3.4 MARL with Social Preference


### 3.5 Trust-worthy and Safe MARL

## Citation
If this repository or our paper is useful for your research and would like to cite it, here is our bibtex.
```
@article{zhang2024multi,
  title={Multi-Agent Reinforcement Learning for Autonomous Driving: A Survey},
  author={Zhang, Ruiqi and Hou, Jing and Walter, Florian and Gu, Shangding and Guan, Jiayi and R{\"o}hrbein, Florian and Du, Yali and Cai, Panpan and Chen, Guang and Knoll, Alois},
  journal={arXiv preprint arXiv:2408.09675},
  year={2024}
}
```

## Contact
If you have any questions or good supplyments for the advanced research, talk, or any form of relevant materials, please contact us and we appreciate for your contribute.
- **Email** ``1854136@tongji.edu.cn``(primary), and cc to ``richzhang@berkeley.edu``, ``guangchen@tongji.edu.cn``, ``guang@in.tum.de``
- **Github issues** We would appreciate it if you reported any factual, technical and copyright issue you found in this repository.
