# Agentic Agri-Robotic Phenotyping: Curated Literature & Reference Hub

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Curated References](https://img.shields.io/badge/Curated%20References-114%20Papers-brightgreen.svg)](#-curated-literature-matrix)
[![Data Formats](https://img.shields.io/badge/Data%20Formats-BibTeX%20%7C%20CSV%20%7C%20JSON-orange.svg)](#-data-assets)

Official companion resource and literature taxonomy repository for the perspective review paper:

> **"Recent Advances in Agentic Agri-Robotic Phenotyping: A Perspective Review from Fragmented Multimodal Sensing to Unified PhenoAgent Intelligence"**  
> *Muhammad Owais, Ehtesham Iqbal, Samee Ullah Khan, Muhammad Umraiz, Yusra Abdulrahman, and Irfan Hussain*  
> Khalifa University Center for Autonomous Robotic Systems (KU-CARS) & Chung-Ang University.

---

## 📖 Overview

Plant phenotyping serves as the critical operational bridge linking genotype, environmental dynamics, crop management, and biological performance. While high-throughput sensing, robotics, and deep learning have advanced rapidly, conventional phenotyping workflows remain fragmented across sensing modalities, crop stages, environments, and management objectives.

This repository hosts the **structured literature database, search methodology, and curated taxonomy of 114 key studies** analyzed in the review, establishing the foundation for next-generation **PhenoAgent** intelligence—advancing phenotyping from passive trait extraction to closed-loop, uncertainty-aware crop decision support.

---

## 🔍 Systematic Search & Screening Strategy

The literature surveyed in this perspective review followed a systematic screening framework focused on papers bridging sensing, automated platforms, biological modeling, and agentic decision support:

| Item | Description |
| :--- | :--- |
| **Databases** | Scopus, Web of Science, PubMed, IEEE Xplore, ScienceDirect, SpringerLink, MDPI, Google Scholar, and arXiv. |
| **Search Period** | Primary focus from 2011 to present, incorporating foundational studies where necessary for historical and conceptual framing. |
| **Core Search Strings** | `"plant phenotyping AND deep learning"`, `"high throughput plant phenotyping AND artificial intelligence"`, `"seed phenotyping AND deep learning"`, `"plant phenotyping AND UAV OR UGV OR robotics"`, `"greenhouse phenotyping AND IoT AND AI"`, `"plant phenotyping AND digital twin"`, `"foundation models AND agriculture"`, `"retrieval augmented generation AND agriculture"`, and `"agentic AI AND smart farming"`. |
| **Inclusion Criteria** | Peer-reviewed reviews, perspective articles, benchmarks, and representative experimental studies directly related to plant/seed phenotyping, multimodal sensing, automated platforms, deep learning, digital twins, or high-TRL AgriTech deployment. |
| **Exclusion Criteria** | Papers focused only on general smart farming without phenotyping relevance; non-crop domains (livestock, aquaculture); purely economic/policy papers lacking sensing/AI depth; and studies without methodological rigor. |
| **Screening Logic** | Dual-stage title/abstract and full-text screening, synthesizing eligible literature into the **Seed-Soil-Plant-Environment-Management (SSPEM)** continuum and PhenoAgent roadmap. |

---

## 📁 Repository Structure

```text
.
├── LICENSE                    # MIT License
├── README.md                  # Comprehensive documentation, search strategy, and literature tables
├── data/
│   ├── references.bib         # Complete BibTeX database (114 citations)
│   ├── references.csv         # Tabular dataset for Excel, Google Sheets, or Notion
│   └── references.json        # Machine-readable JSON array for programmatic use
└── scripts/
    └── parse_references.py    # Zero-dependency Python script to validate and export metadata
```

---

## 📊 Summary of Curated Literature by Category

| Thematic Category | Number of Curated Papers | Focus & Relevance |
| :--- | :---: | :--- |
| **High-Throughput Phenotyping & Strategy** | 34 | Field and greenhouse HTP platforms, phenotypic bottlenecks, standards (MIAPPE), and breeding pipelines. |
| **AI & Deep Learning Perception** | 27 | Object detection (YOLO), semantic/instance segmentation, vision transformers, and disease classification. |
| **Digital Twins & Smart CEA** | 15 | Greenhouse IoT monitoring, microclimate simulation, functional-structural plant models (FSPM), and digital twins. |
| **Seed & Root Phenotyping** | 15 | Seed vigor assessment, germination dynamics, X-ray CT/rhizotron root imaging, and subterranean trait capture. |
| **Robotics & Autonomous Platforms** | 10 | Field robots, UGVs, UAV-based multispectral aerial imaging, autonomous navigation, and robotic arm manipulation. |
| **Agentic AI & Reasoning** | 7 | LLM agents, Retrieval-Augmented Generation (RAG), multimodal reasoning, and closed-loop decision engines. |
| **Multimodal Sensing & Imaging** | 6 | Hyperspectral imaging, thermal cameras, LiDAR/3D point clouds, and multimodal data fusion. |
| **Total** | **114** | **Curated research papers, benchmark datasets, and perspective reviews.** |

---

## 📚 Curated Literature Matrix

Below is the complete catalog of curated literature organized chronologically. Each entry includes direct DOI or publisher links.

| Year | Title | Authors | Venue / Source | Topic | Link |
| :---: | :--- | :--- | :--- | :--- | :---: |
| 2026 | Towards an AI-Based Knowledge Assistant for Goat Farmers Based on Retrieval-Augmented Generation | Han, Nana and Liu, Dong and Norton, Tomas | Computers and Electronics in Agriculture | Agentic AI & Reasoning | [Link](https://doi.org/10.1016/j.compag.2026.111542) |
| 2026 | Leveraging Explainable AI for Sustainable Agriculture: A Comprehensive Review of Recent Advances | Rajbongshi, Aditya et al. | Artificial Intelligence Review | Agentic AI & Reasoning | [Link](https://doi.org/10.1007/s10462-025-11459-5) |
| 2026 | Ground Mobile Robots for High-Throughput Plant Phenotyping: A Review from the Closed-Loop Perspective of Perception, Decision, and Action | Zhang, Heng-Wei et al. | Plants | Robotics & Autonomous Platforms | [Link](https://doi.org/10.3390/plants15081218) |
| 2026 | From UAV Imagery to Agronomic Reasoning: A Multimodal LLM Benchmark for Plant Phenotyping | Yu Wu et al. |  | Agentic AI & Reasoning | [Link](https://arxiv.org/abs/2604.09907) |
| 2026 | Empowering Farmers with Artificial Intelligence: A Retrieval-Augmented Generation Based Large Language Model Advisory Framework | Sawant, Shreeram and Nair, Rahul and Hariharan, Siddharth | Journal of Agricultural Engineering | Agentic AI & Reasoning | [Link](https://doi.org/10.4081/jae.2026.1908) |
| 2026 | Dynamic, Adaptive and Modular Digital Twin Framework for Resource-Efficient Controlled Environment Agriculture | Frontzek, Julius and Wagner, Zuhal and Streif, Stefan | Frontiers in Plant Science | Digital Twins & Smart CEA | [Link](https://doi.org/10.3389/fpls.2026.1864757) |
| 2026 | Digital Twin of a Dual-Arm Autonomous Seeding Robot for Hydroponic Greenhouses | Rodri | Computers and Electronics in Agriculture | Digital Twins & Smart CEA | [Link](https://doi.org/10.1016/j.compag.2026.111967) |
| 2026 | A Digital Framework for Smart Greenhouse Tomato Cultivation | Guo, Jianjun et al. | Smart Agricultural Technology | Digital Twins & Smart CEA | [Link](https://doi.org/10.1016/j.atech.2026.101879) |
| 2026 | A Crop Digital Twin System for Predictive Growth Monitoring and Adaptive Light Control in Controlled Environment Agriculture | Ojo, Mike Oluwatayo et al. | Internet of Things | Digital Twins & Smart CEA | [Link](https://doi.org/10.1016/j.iot.2026.101935) |
| 2025 | Unmanned Aerial Systems Based Field High Throughput Phenotyping as Plant Breeders' Toolbox: A Comprehensive Review | Khuimphukhieo, Ittipon and da Silva, Jorge A. | Smart Agricultural Technology | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1016/j.atech.2025.100888) |
| 2025 | Transfer Learning in Agriculture: A Review | Hossen, Md Ismail et al. | Artificial Intelligence Review | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1007/s10462-024-11081-x) |
| 2025 | Smart Greenhouse: Global Market to Reach US\$3.9 Billion by 2030 | Global Industry Analysts |  | Digital Twins & Smart CEA | [Link](https://www.marketresearch.com/Global-Industry-Analysts-v1039/Smart-Greenhouse-41287848/) |
| 2025 | Simulink-Driven Digital Twin Implementation for Smart Greenhouse Environmental Control | Arshad, Jehangir et al. | Egyptian Informatics Journal | Digital Twins & Smart CEA | [Link](https://doi.org/10.1016/j.eij.2025.100679) |
| 2025 | Plant Phenotyping Market Size and Share Analysis: Growth Trends and Forecasts 2025--2030 | Mordor Intelligence |  | High-Throughput Phenotyping & Strategy | [Link](https://www.mordorintelligence.com/industry-reports/plant-phenotyping-market) |
| 2025 | Multi-Criteria Decision Support System for the Evaluation of UAV Intelligent Agricultural Sensors | Kizielewicz, Bartl | Artificial Intelligence Review | Robotics & Autonomous Platforms | [Link](https://doi.org/10.1007/s10462-025-11201-1) |
| 2025 | Machine Learning Techniques for Coffee Classification: A Comprehensive Review of Scientific Research | Motta, Isabela V. C. et al. | Artificial Intelligence Review | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1007/s10462-024-11004-w) |
| 2025 | Leveraging Vision Language Models for Specialized Agricultural Tasks | Muhammad Arbab Arshad et al. |  | Agentic AI & Reasoning | [Link](https://arxiv.org/abs/2407.19617) |
| 2025 | Image-Based Deep Learning for Smart Digital Twins: A Review | Islam, M. R. and Subramaniam, M. and Huang, P. C. | Artificial Intelligence Review | Digital Twins & Smart CEA | [Link](https://doi.org/10.1007/s10462-024-11002-y) |
| 2025 | How the Internet of Things Technology Improves Agricultural Efficiency | Duguma, Amenu Leta and Bai, Xiuguang | Artificial Intelligence Review | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1007/s10462-024-11046-0) |
| 2025 | From Sensors to Insights: Technological Trends in Image-Based High-Throughput Plant Phenotyping | Wang, Rui-Feng and Qu, Hao-Ran and Su, Wen-Hao | Smart Agricultural Technology | Multimodal Sensing & Imaging | [Link](https://doi.org/10.1016/j.atech.2025.101257) |
| 2025 | Digital Twin/MARS-CycleGAN: Enhancing Sim-to-Real Crop/Row Detection for MARS Phenotyping Robot Using Synthetic Images | Liu, David and Li, Zhengkun and Wu, Zihao and Li, Changying | Journal of Field Robotics | Digital Twins & Smart CEA | [Link](https://doi.org/10.1002/rob.22473) |
| 2025 | DigiHortiRobot: An AI-Driven Digital Twin Architecture for Hydroponic Greenhouse Horticulture with Dual-Arm Robotic Automation | Ferna | Future Internet | Digital Twins & Smart CEA | [Link](https://doi.org/10.3390/fi17080347) |
| 2025 | Deep Learning and Computer Vision in Plant Disease Detection: A Comprehensive Review of Techniques, Models, and Trends in Precision Agriculture | Upadhyay, Abhishek et al. | Artificial Intelligence Review | AI & Deep Learning Perception | [Link](https://doi.org/10.1007/s10462-024-11100-x) |
| 2025 | Closing the Phenotyping Gap with Non-Invasive Belowground Field Phenotyping | Blanchy, Guillaume et al. | SOIL | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.5194/soil-11-67-2025) |
| 2025 | Application of Deep Learning for High-Throughput Phenotyping of Seed: A Review | Jin, Chen et al. | Artificial Intelligence Review | Seed & Root Phenotyping | [Link](https://doi.org/10.1007/s10462-024-11079-5) |
| 2025 | Application of Deep Learning for High-Throughput Phenotyping of Seed: A Review | Jin, Chen et al. | Artificial Intelligence Review | Seed & Root Phenotyping | [Link](https://doi.org/10.1007/s10462-024-11079-5) |
| 2025 | Agricultural Robots Market Size, Share and Trends Analysis Report 2030 | Grand View Research |  | Robotics & Autonomous Platforms | [Link](https://www.grandviewresearch.com/industry-analysis/agricultural-robots-market) |
| 2025 | A Comprehensive Survey of Retrieval-Augmented Large Language Models for Decision Making in Agriculture: Unsolved Problems and Research Opportunities | Vizniuk, Artem et al. | Journal of Artificial Intelligence and Soft Computing Research | Agentic AI & Reasoning | [Link](https://doi.org/10.2478/jaiscr-2025-0007) |
| 2024 | Global Plant Phenotyping Market Growth Status and Outlook 2024--2030 | LP Information |  | High-Throughput Phenotyping & Strategy | [Link](https://www.marketresearchreports.com/lpi/global-plant-phenotyping-market-growth-status-and-outlook-2024-2030) |
| 2024 | Foundation Models in Smart Agriculture: Basics, Opportunities, and Challenges | Li, Jiajia et al. | Computers and Electronics in Agriculture | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1016/j.compag.2024.109032) |
| 2024 | Digital Twin Framework for Smart Greenhouse Management Using Next-Gen Mobile Networks and Machine Learning | Rahman, Hameedur et al. | Future Generation Computer Systems | Digital Twins & Smart CEA | [Link](https://doi.org/10.1016/j.future.2024.03.023) |
| 2024 | Deep Learning in Image-Based Plant Phenotyping | Murphy, Katherine M. et al. | Annual Review of Plant Biology | AI & Deep Learning Perception | [Link](https://doi.org/10.1146/annurev-arplant-070523-042828) |
| 2024 | Deep Learning Implementation of Image Segmentation in Agricultural Applications: A Comprehensive Review | Lei, Lian et al. | Artificial Intelligence Review | AI & Deep Learning Perception | [Link](https://doi.org/10.1007/s10462-024-10775-6) |
| 2024 | DC-YOLO: An Improved Field Plant Detection Algorithm Based on YOLOv7-Tiny | Li, Wenwen and Zhang, Yun | Scientific Reports | AI & Deep Learning Perception | [Link](https://doi.org/10.1038/s41598-024-77865-x) |
| 2024 | Computer Vision-Based Plants Phenotyping: A Comprehensive Survey | Meraj, Talha et al. | iScience | AI & Deep Learning Perception | [Link](https://doi.org/10.1016/j.isci.2023.108709) |
| 2024 | A Systematic Review of Deep Learning Techniques for Plant Diseases | Pacal, Ishak et al. | Artificial Intelligence Review | AI & Deep Learning Perception | [Link](https://doi.org/10.1007/s10462-024-10944-7) |
| 2023 | Visual Intelligence in Precision Agriculture: Exploring Plant Disease Detection via Efficient Vision Transformers | Parez, Sana et al. | Sensors | Multimodal Sensing & Imaging | [Link](https://doi.org/10.3390/s23156949) |
| 2023 | Vision Transformer Meets Convolutional Neural Network for Plant Disease Classification | Thakur, Poornima Singh et al. | Ecological Informatics | AI & Deep Learning Perception | [Link](https://doi.org/10.1016/j.ecoinf.2023.102245) |
| 2023 | UAV Multisensory Data Fusion and Multi-Task Deep Learning for High-Throughput Maize Phenotyping | Nguyen, Canh et al. | Sensors | Robotics & Autonomous Platforms | [Link](https://doi.org/10.3390/s23041827) |
| 2023 | TrIncNet: A Lightweight Vision Transformer Network for Identification of Plant Diseases | Gole, Pushkar et al. | Frontiers in Plant Science | AI & Deep Learning Perception | [Link](https://doi.org/10.3389/fpls.2023.1221557) |
| 2023 | Toolformer: Language Models Can Teach Themselves to Use Tools | Schick, Timo and Dwivedi-Yu, Jane and Dessi | Advances in Neural Information Processing Systems | AI & Deep Learning Perception | [Link](https://proceedings.neurips.cc/paper_files/paper/2023/hash/d842425e4bf79ba039352da0f658a906-Abstract-Conference.html) |
| 2023 | Smart Agriculture and Digital Twins: Applications and Challenges in a Vision of Sustainability | Cesco, Stefano et al. | European Journal of Agronomy | Digital Twins & Smart CEA | [Link](https://doi.org/10.1016/j.eja.2023.126809) |
| 2023 | Segment Anything | Kirillov, Alexander et al. | Proceedings of the IEEE/CVF International Conference on Computer Vision | AI & Deep Learning Perception | [Link](https://doi.org/10.1109/ICCV51070.2023.00371) |
| 2023 | ReAct: Synergizing Reasoning and Acting in Language Models | Yao, Shunyu et al. | International Conference on Learning Representations | High-Throughput Phenotyping & Strategy | [Link](https://openreview.net/forum?id=WE_vluYUL-X) |
| 2023 | Physiological Alterations and Nondestructive Test Methods of Crop Seed Vigor: A Comprehensive Review | Xing, Muye et al. | Agriculture | Seed & Root Phenotyping | [Link](https://doi.org/10.3390/agriculture13030527) |
| 2023 | PMVT: A Lightweight Vision Transformer for Plant Disease Identification on Mobile Devices | Li, Guoqiang et al. | Frontiers in Plant Science | AI & Deep Learning Perception | [Link](https://doi.org/10.3389/fpls.2023.1256773) |
| 2023 | Multispectral Plant Disease Detection with Vision Transformer-Convolutional Neural Network Hybrid Approaches | de Silva, Malithi and Brown, Dane | Sensors | Multimodal Sensing & Imaging | [Link](https://doi.org/10.3390/s23208531) |
| 2023 | Field Robot for High-Throughput and High-Resolution 3D Plant Phenotyping: Towards Efficient and Sustainable Crop Production | Esser, Felix and Rosu, Radu Alexandru and Corneliss | IEEE Robotics \& Automation Magazine | Robotics & Autonomous Platforms | [Link](https://doi.org/10.1109/MRA.2023.3321402) |
| 2023 | Enhancing Smart Agriculture by Implementing Digital Twins: A Comprehensive Review | Peladarinos, Nikolaos et al. | Sensors | Digital Twins & Smart CEA | [Link](https://doi.org/10.3390/s23167128) |
| 2023 | Digital Twins in Agriculture: A State-of-the-Art Review | Purcell, Warren and Neubauer, Thomas | Smart Agricultural Technology | Digital Twins & Smart CEA | [Link](https://doi.org/10.1016/j.atech.2022.100094) |
| 2023 | Digital Twin Deployment for Smart Agriculture in Cloud-Fog-Edge Infrastructure | Kalyani, Yogeswaranathan et al. | Enterprise Information Systems | Digital Twins & Smart CEA | [Link](https://doi.org/10.1080/17445760.2023.2235653) |
| 2023 | Detection of Tomato Plant Phenotyping Traits Using YOLOv5-Based Single Stage Detectors | Cardellicchio, Angelo et al. | Computers and Electronics in Agriculture | AI & Deep Learning Perception | [Link](https://doi.org/10.1016/j.compag.2023.107757) |
| 2023 | Current Optical Sensing Applications in Seeds Vigor Determination | Zhang, Jian et al. | Agronomy | Seed & Root Phenotyping | [Link](https://doi.org/10.3390/agronomy13041167) |
| 2023 | An Approach for Plant Leaf Image Segmentation Based on YOLOv8 and the Improved DeepLabV3 | Yang, Tingting et al. | Plants | AI & Deep Learning Perception | [Link](https://doi.org/10.3390/plants12193438) |
| 2022 | Seed Vigour in the 21st Century | Powell, Alison A. | Seed Science and Technology | Seed & Root Phenotyping | [Link](https://doi.org/10.15258/sst.2022.50.1.s.04) |
| 2022 | Seed Germination and Vigor: Ensuring Crop Sustainability in a Changing Climate | Reed, Reagan C. and Bradford, Kent J. and Khanday, Imtiyaz | Heredity | Seed & Root Phenotyping | [Link](https://doi.org/10.1038/s41437-022-00497-2) |
| 2022 | Genotype x Environment x Management (GEM) Reciprocity and Crop Productivity | Mahmood, Tariq and Ahmed, Talaat and Trethowan, Richard | Frontiers in Agronomy | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.3389/fagro.2022.800365) |
| 2022 | Digital Twins and Industry 4.0 Technologies for Agricultural Greenhouses | Slob, Naftali and Hurst, William | Smart Cities | Digital Twins & Smart CEA | [Link](https://doi.org/10.3390/smartcities5030059) |
| 2022 | A Deep Learning Based Approach for Automated Plant Disease Classification Using Vision Transformer | Borhani, Yasamin and Khoramdel, Javad and Najafi, Esmaeil | Scientific Reports | AI & Deep Learning Perception | [Link](https://doi.org/10.1038/s41598-022-15163-0) |
| 2021 | The PRISMA 2020 Statement: An Updated Guideline for Reporting Systematic Reviews | Page, Matthew J. et al. | BMJ | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1136/bmj.n71) |
| 2021 | Tackling G $times$ E $times$ M Interactions to Close On-Farm Yield-Gaps: Creating Novel Pathways for Crop Improvement by Predicting Contributions of Genetics and Management to Crop Productivity | Cooper, Mark et al. | Theoretical and Applied Genetics | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1007/s00122-021-03812-3) |
| 2021 | Root Phenotyping: Important and Minimum Information Required for Root Modeling in Crop Plants | Takahashi, Hirokazu and Pradal, Christophe | Breeding Science | Seed & Root Phenotyping | [Link](https://doi.org/10.1270/jsbbs.20126) |
| 2021 | Robotic Technologies for High-Throughput Plant Phenotyping: Contemporary Reviews and Future Perspectives | Atefi, Abbas et al. | Frontiers in Plant Science | Robotics & Autonomous Platforms | [Link](https://doi.org/10.3389/fpls.2021.611940) |
| 2021 | On the Opportunities and Risks of Foundation Models | Bommasani, Rishi et al. |  | High-Throughput Phenotyping & Strategy | [Link](https://arxiv.org/abs/2108.07258) |
| 2021 | Learning Transferable Visual Models from Natural Language Supervision | Radford, Alec et al. | Proceedings of Machine Learning Research | AI & Deep Learning Perception | [Link](https://proceedings.mlr.press/v139/radford21a.html) |
| 2021 | Genotype $times$ Environment Interaction in Crop Breeding | Egea-Gilabert, Catalina et al. | Agronomy | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.3390/agronomy11081644) |
| 2021 | Development and Testing of a UAV-Based Multi-Sensor System for Plant Phenotyping and Precision Agriculture | Xu, Rui and Li, Changying and Bernardes, Sergio | Remote Sensing | Robotics & Autonomous Platforms | [Link](https://doi.org/10.3390/rs13173517) |
| 2021 | An Image Is Worth 16x16 Words: Transformers for Image Recognition at Scale | Dosovitskiy, Alexey et al. | International Conference on Learning Representations | AI & Deep Learning Perception | [Link](https://arxiv.org/abs/2010.11929) |
| 2020 | Trait-Based Root Phenotyping as a Necessary Tool for Crop Selection and Improvement | McGrail, Rebecca K. et al. | Agronomy | Seed & Root Phenotyping | [Link](https://doi.org/10.3390/agronomy10091328) |
| 2020 | Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks | Lewis, Patrick et al. | Advances in Neural Information Processing Systems | Agentic AI & Reasoning | [Link](https://proceedings.neurips.cc/paper/2020/hash/6b493230205f780e1bc26945df7481e5-Abstract.html) |
| 2020 | Phenotyping: New Windows into the Plant for Breeders | Watt, Michelle and Fiorani, Fabio and Usadel, Bjo | Annual Review of Plant Biology | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1146/annurev-arplant-042916-041124) |
| 2020 | Greenotyper: Image-Based Plant Phenotyping Using Distributed Computing and Deep Learning | Tausen, Marni and Clausen, Marc and Moeskjae | Frontiers in Plant Science | AI & Deep Learning Perception | [Link](https://doi.org/10.3389/fpls.2020.01181) |
| 2020 | Global Wheat Head Detection 2020: A Large and Diverse Dataset of High-Resolution RGB-Labelled Images to Develop and Benchmark Wheat Head Detection Methods | David, Etienne et al. | Plant Phenomics | AI & Deep Learning Perception | [Link](https://doi.org/10.34133/2020/3521852) |
| 2020 | Enabling Reusability of Plant Phenomic Datasets with MIAPPE 1.1 | Papoutsoglou, Evangelia A. et al. | New Phytologist | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1111/nph.16544) |
| 2020 | Crop Improvement from Phenotyping Roots: Highlights Reveal Expanding Opportunities | Tracy, Saoirse R. et al. | Trends in Plant Science | Seed & Root Phenotyping | [Link](https://doi.org/10.1016/j.tplants.2019.10.015) |
| 2020 | Convolutional Neural Networks for Image-Based High-Throughput Plant Phenotyping: A Review | Jiang, Yu and Li, Changying | Plant Phenomics | AI & Deep Learning Perception | [Link](https://doi.org/10.34133/2020/4152816) |
| 2020 | Assessment of Multi-Image Unmanned Aerial Vehicle Based High-Throughput Field Phenotyping of Canopy Temperature | Perich, Gregor et al. | Frontiers in Plant Science | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.3389/fpls.2020.00150) |
| 2020 | An Extended Root Phenotype: The Rhizosphere, Its Formation and Impacts on Plant Fitness | de la Fuente Canto | The Plant Journal | Seed & Root Phenotyping | [Link](https://doi.org/10.1111/tpj.14781) |
| 2019 | Uncovering the Hidden Half of Plants Using New Advances in Root Phenotyping | Atkinson, Jonathan A. et al. | Current Opinion in Biotechnology | Seed & Root Phenotyping | [Link](https://doi.org/10.1016/j.copbio.2018.06.002) |
| 2019 | Plant Phenotyping: Past, Present, and Future | Pieruschka, Roland and Schurr, Ulrich | Plant Phenomics | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.34133/2019/7507131) |
| 2019 | Plant Disease Detection and Classification by Deep Learning | Saleem, Muhammad Hammad et al. | Plants | AI & Deep Learning Perception | [Link](https://doi.org/10.3390/plants8110468) |
| 2019 | Perspectives for Remote Sensing with Unmanned Aerial Vehicles in Precision Agriculture | Maes, Wouter H. and Steppe, Kathy | Trends in Plant Science | Robotics & Autonomous Platforms | [Link](https://doi.org/10.1016/j.tplants.2018.11.007) |
| 2019 | Ear Density Estimation from High Resolution RGB Imagery Using Deep Learning Technique | Madec, Simon et al. | Agricultural and Forest Meteorology | AI & Deep Learning Perception | [Link](https://doi.org/10.1016/j.agrformet.2018.10.013) |
| 2019 | Crop Yield Prediction Using Deep Neural Networks | Khaki, Saeed and Wang, Lizhi | Frontiers in Plant Science | AI & Deep Learning Perception | [Link](https://doi.org/10.3389/fpls.2019.00621) |
| 2019 | A Comparative Study of Fine-Tuning Deep Learning Models for Plant Disease Identification | Too, Edna Chebet and Yujian, Li and Njuki, Sam and Yingchun, Liu | Computers and Electronics in Agriculture | AI & Deep Learning Perception | [Link](https://doi.org/10.1016/j.compag.2018.03.032) |
| 2018 | Soil Quality: A Critical Review | Bu | Soil Biology and Biochemistry | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1016/j.soilbio.2018.01.030) |
| 2018 | Machine Learning in Agriculture: A Review | Liakos, Konstantinos G. et al. | Sensors | Multimodal Sensing & Imaging | [Link](https://doi.org/10.3390/s18082674) |
| 2018 | Deep Learning in Agriculture: A Survey | Kamilaris, Andreas and Prenafeta-Boldu | Computers and Electronics in Agriculture | AI & Deep Learning Perception | [Link](https://doi.org/10.1016/j.compag.2018.02.016) |
| 2018 | Deep Learning Models for Plant Disease Detection and Diagnosis | Ferentinos, Konstantinos P. | Computers and Electronics in Agriculture | AI & Deep Learning Perception | [Link](https://doi.org/10.1016/j.compag.2018.01.009) |
| 2017 | Unlocking the Potential of Plant Phenotyping Data Through Integration and Data-Driven Approaches | Coppens, Frederik and Wuyts, Nathalie and Inze | Current Opinion in Systems Biology | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1016/j.coisb.2017.07.002) |
| 2017 | Smart Farming Is Key to Developing Sustainable Agriculture | Walter, Achim et al. | Proceedings of the National Academy of Sciences of the United States of America | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1073/pnas.1707462114) |
| 2017 | Plant Phenomics, From Sensors to Knowledge | Tardieu, Francc | Current Biology | Multimodal Sensing & Imaging | [Link](https://doi.org/10.1016/j.cub.2017.05.055) |
| 2017 | Field Scanalyzer: An Automated Robotic Field Phenotyping Platform for Detailed Crop Monitoring | Virlet, Nicolas et al. | Functional Plant Biology | Robotics & Autonomous Platforms | [Link](https://doi.org/10.1071/FP16163) |
| 2017 | Deep Plant Phenomics: A Deep Learning Platform for Complex Plant Phenotyping Tasks | Ubbens, Jordan R. and Stavness, Ian | Frontiers in Plant Science | AI & Deep Learning Perception | [Link](https://doi.org/10.3389/fpls.2017.01190) |
| 2017 | Deep Machine Learning Provides State-of-the-Art Performance in Image-Based Plant Phenotyping | Pound, Michael P. et al. | GigaScience | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1093/gigascience/gix083) |
| 2017 | Big Data in Smart Farming: A Review | Wolfert, Sjaak et al. | Agricultural Systems | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1016/j.agsy.2017.01.023) |
| 2016 | Using Deep Learning for Image-Based Plant Disease Detection | Mohanty, Sharada P. and Hughes, David P. and Salathe | Frontiers in Plant Science | AI & Deep Learning Perception | [Link](https://doi.org/10.3389/fpls.2016.01419) |
| 2016 | Pampered Inside, Pestered Outside? Differences and Similarities Between Plants Growing in Controlled Conditions and in the Field | Poorter, Hendrik et al. | New Phytologist | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1111/nph.14243) |
| 2015 | Seed Vigor Testing: An Overview of the Past, Present and Future Perspective | Marcos-Filho, Julio | Scientia Agricola | Seed & Root Phenotyping | [Link](https://doi.org/10.1590/0103-9016-2015-0007) |
| 2015 | Root Phenotyping: From Component Trait in the Lab to Breeding | Kuijken, Richard C. P. et al. | Journal of Experimental Botany | Seed & Root Phenotyping | [Link](https://doi.org/10.1093/jxb/erv239) |
| 2015 | Low-Altitude, High-Resolution Aerial Imaging Systems for Row and Field Crop Phenotyping: A Review | Sankaran, Sindhuja et al. | European Journal of Agronomy | Robotics & Autonomous Platforms | [Link](https://doi.org/10.1016/j.eja.2015.07.004) |
| 2015 | Image Analysis: The New Bottleneck in Plant Phenotyping | Minervini, Massimo and Scharr, Hanno and Tsaftaris, Sotirios A. | IEEE Signal Processing Magazine | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1109/MSP.2015.2405111) |
| 2014 | Field High-Throughput Phenotyping: The New Crop Breeding Frontier | Araus, Jose | Trends in Plant Science | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1016/j.tplants.2013.09.008) |
| 2014 | Development and Evaluation of a Field-Based High-Throughput Phenotyping Platform | Andrade-Sanchez, Pedro et al. | Functional Plant Biology | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1071/FP13126) |
| 2013 | Yield Trends Are Insufficient to Double Global Crop Production by 2050 | Ray, Deepak K. et al. | PLOS ONE | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1371/journal.pone.0066428) |
| 2013 | Next-Generation Phenotyping: Requirements and Strategies for Enhancing Our Understanding of Genotype-Phenotype Relationships and Its Relevance to Crop Improvement | Cobb, Joshua N. et al. | Theoretical and Applied Genetics | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1007/s00122-013-2066-0) |
| 2013 | Future Scenarios for Plant Phenotyping | Fiorani, Fabio and Schurr, Ulrich | Annual Review of Plant Biology | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1146/annurev-arplant-050312-120137) |
| 2013 | BreedVision: A Multi-Sensor Platform for Non-Destructive Field-Based Phenotyping in Plant Breeding | Busemeyer, Lucas and Mentrup, Daniel and Mo | Sensors | Multimodal Sensing & Imaging | [Link](https://doi.org/10.3390/s130302830) |
| 2012 | Seed Germination and Vigor | Rajjou, Loi | Annual Review of Plant Biology | Seed & Root Phenotyping | [Link](https://doi.org/10.1146/annurev-arplant-042811-105550) |
| 2012 | Field-Based Phenomics for Plant Genetics Research | White, Jeffrey W. et al. | Field Crops Research | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1016/j.fcr.2012.04.003) |
| 2011 | Shovelomics: High Throughput Phenotyping of Maize Root Architecture in the Field | Trachsel, Samuel et al. | Plant and Soil | Seed & Root Phenotyping | [Link](https://doi.org/10.1007/s11104-010-0623-8) |
| 2011 | Proximal Soil Sensing: An Effective Approach for Soil Measurements in Space and Time | Viscarra Rossel, Raphael A. et al. | Advances in Agronomy | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1016/B978-0-12-386473-4.00005-1) |
| 2011 | Phenomics: Technologies to Relieve the Phenotyping Bottleneck | Furbank, Robert T. and Tester, Mark | Trends in Plant Science | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1016/j.tplants.2011.09.005) |
| 2011 | Global Food Demand and the Sustainable Intensification of Agriculture | Tilman, David et al. | Proceedings of the National Academy of Sciences of the United States of America | High-Throughput Phenotyping & Strategy | [Link](https://doi.org/10.1073/pnas.1116437108) |

---

## 💾 Data Assets

- **BibTeX Database**: [`data/references.bib`](data/references.bib)  
  Import directly into Zotero, Mendeley, EndNote, or Overleaf.
- **CSV Spreadsheet**: [`data/references.csv`](data/references.csv)  
  Contains `key`, `year`, `title`, `author`, `venue`, `category`, `doi`, `url` for spreadsheet and table analysis.
- **JSON Format**: [`data/references.json`](data/references.json)  
  Ideal for web visualization, dashboards, and automated metadata querying.

---

## 🛠️ Reproducibility & Updating

To re-parse the bibliography or regenerate `references.csv`, `references.json`, and `README.md`:

```bash
python scripts/parse_references.py
```

---

## 📑 Citation

If you find this curated repository or our review paper useful in your research, please cite:

```bibtex
@article{owais2026phenoagent,
  title   = {Recent Advances in Agentic Agri-Robotic Phenotyping: A Perspective Review from Fragmented Multimodal Sensing to Unified PhenoAgent Intelligence},
  author  = {Owais, Muhammad and Iqbal, Ehtesham and Khan, Samee Ullah and Umraiz, Muhammad and Abdulrahman, Yusra and Hussain, Irfan},
  journal = {Preprint / Perspective Review under Submission},
  year    = {2026}
}
```

---

## 📄 License

This repository is distributed under the [MIT License](LICENSE).
