<img width="150" img align="right" alt="NSF-logo" src="https://user-images.githubusercontent.com/5705572/95711667-1d953c00-0c18-11eb-817b-1cc6a90d504d.png">

**Project Title**: CDS&E: HyLoC: Objective-driven Adaptive Hybrid Lossy Compression Framework for Extreme-Scale Scientific Applications

**Principle Investigators**: [Dingwen Tao](https://www.dingwentao.com/), [Sheng Di](https://www.mcs.anl.gov/~shdi/)

**Award Numbers**: [2042084](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2042084), [2003709](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2003709)

**Project Duration**: 8/1/2020 - 7/31/2023

## Abstract

Today's extreme-scale scientific simulations and instruments are producing huge amounts of data that cannot be transmitted or stored effectively. Lossy compression, a data compression approach leading to certain data distortion, has been considered as a promising solution, because it can significantly reduce the data size while maintaining high data fidelity. However, the existing lossy compression methods may not always work effectively on all datasets used in specific applications because of their distinct and diverse characteristics. Moreover, the user objectives in compression quality and performance may vary with applications, datasets or circumstances. This project aims to develop a hybrid lossy compression framework to automatically construct the best-fit compression for diverse user objectives in data-intensive scientific research. Educational and engagement activities are provided to develop new curriculum related to scientific data compression and promote research collaborations with national laboratories.

Designing an efficient, adaptive, hybrid framework that can always choose the best-fit compression strategy is nontrivial, since existing state-of-the-art lossy compression methods are developed with distinct principles. The project has a three-stage research plan. First, the project decouples the state-of-the-art error-bounded lossy compression approaches into multiple stages and effectively models the working efficiency (e.g., compression ratio, error, speed) of particular approaches in each stage. Second, the project develops a loosely-coupled framework to aggregate the decoupled compression stages together and also explores as many compression pipelines composed of different stages as possible, to optimize the classic compression efficiency, including compression quality and performance. Third, the project optimizes the synthetic data-movement performance regarding the external devices and resources, such as I/O performance. The team evaluates the proposed framework on multiple extreme-scale scientific applications, including cosmological simulations, light source instrument data analytics, quantum circuit simulations, and climate simulations. The project may create technologies that can increase the storage availability and improve the performance for extreme-scale scientific applications, opening opportunities for new discoveries.

## Team

### Principal Investigators

<img width="200" alt="dingwen-photo" src="https://user-images.githubusercontent.com/5705572/95699439-45c17280-0bf9-11eb-8d43-38f1b65d65fc.jpg">

**Dingwen Tao (Lead PI), Washington State University**

Dingwen Tao is an assistant professor in the School of Electrical Engineering & Computer Science at Washington State University. He is also adjunct professor in the Department of Computer Science at the University of Alabama. He has published in the top-tier HPC and big data conferences and journals, including IEEE/ACM SC, ACM ICS, ACM HPDC, ACM PPoPP, ACM PACT, IEEE IPDPS, IEEE Cluster, IEEE/ACM DAC, IEEE BigData, ICPP, IEEE TPDS, etc. He is the receipt of the 2020 IEEE Computer Society TCHPC Early Career Researchers Award for Excellence in High Performance Computing, 2020 NSF CRII Award, and 2017 UCR Dissertation Year Program Award.

<img width="200" alt="sheng-photo" src="https://user-images.githubusercontent.com/5705572/95699426-3cd0a100-0bf9-11eb-9e61-fcaed9698b20.jpg">

**Sheng Di, University of Chicago and Argonne National Laboratory**

Sheng Di is a computer scientist at Argonne National Laboratory, USA. He is an IEEE senior member. He is a scientist at Large through the Consortium for Advanced Science and Engineering (CASE) at the University of Chicago. He is an institute fellow of Northwestern-Argonne Institute of Science and Engineering (NAISE). He has published 100+ refereed journal and conference papers, including TPDS, TC, TCC, TKDE, JPDC, IJHPCA, PPoPP, SC, IPDPS, HPDC, PACT, MSST, DSN, ICPP, CLUSTER, BigData, IWQoS, CCGrid, HiPC, Grid, CLOUD, UCC, EuroPar, ICPADS, Europar, etc. He is the receipient of 2018 IEEE Chicago Section Distinguished Mentoring Award and 2019 IEEE Chicago Section Distinguished Research and Development Award.

### Collaborators

<img width="200" alt="Ian-photo" src="https://user-images.githubusercontent.com/5705572/95700253-625eaa00-0bfb-11eb-93e0-e2ffaa3c3263.jpeg">

**Ian Foster, University of Chicago**

*Online Data Analysis and Reduction*

<img width="200" alt="kyle-photo" src="https://user-images.githubusercontent.com/5705572/95700249-625eaa00-0bfb-11eb-8717-92b8da1c5064.jpg">

**Kyle Chard, University of Chicago**

*Online Data Analysis and Reduction*

<img width="200" alt="fred-photo" src="https://user-images.githubusercontent.com/5705572/95700250-625eaa00-0bfb-11eb-9d27-e51cc7160dac.jpg">

**Fred Chong, University of Chicago**

*Quantum Computing Simulations*

<img width="200" alt="junjing-photo" src="https://user-images.githubusercontent.com/5705572/95700247-61c61380-0bfb-11eb-863e-530ea8f48601.jpg">

**Junjing Deng, Argonne National Laboratory**

*X-ray Imaging for Crystallography Analyses*

<img width="200" alt="zarija-photo" src="https://user-images.githubusercontent.com/5705572/95700245-612d7d00-0bfb-11eb-9b0c-78a319289d3d.png">

**Zarija Lukic, Lawrence Berkeley National Laboratory**

*Cosmological Simulations*

### Students

<img width="200" alt="sian-photo" src="https://user-images.githubusercontent.com/5705572/178404152-09d1d297-a99a-401e-88c5-2c28b82ee79f.jpg">

**Sian Jin, Washington State University**

<img width="200" alt="daoce-photo" src="https://user-images.githubusercontent.com/5705572/95711377-77e1cd00-0c17-11eb-8d6f-893b092983a1.jpg">

**Daoce Wang, Washington State University**

<img width="200" alt="yuanjian-photo" src="https://user-images.githubusercontent.com/5705572/120055464-22fa9780-bfeb-11eb-8817-c4cb6ae44c51.jpeg">

**Yuanjian Liu, University of Chicago**

## Publications

- [**TPDS '22**]  Yuanjian Liu, Sheng Di, Kai Zhao, Sian Jin, Cheng Wang, Kyle Chard, Dingwen Tao, Ian Foster, and Franck Cappello. Optimizing Error-Bounded Lossy Compression for Scientific Data with Diverse Constraints. *IEEE Transactions on Parallel and Distributed Systems*. 
- [**SC '22**] Sian Jin, Dingwen Tao, Houjun Tang, Sheng Di, Suren Byna, Zarija Lukic, and Franck Cappello. Accelerating Parallel Write via Deeply Integrating Predictive Lossy Compression with HDF5. In *Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis*, Dallas, TX, USA, November 13–18, 2022.
- [**ICDE '22**] Sian Jin, Sheng Di, Jiannan Tian, Suren Byna, Dingwen Tao, and Franck Cappello. Improving Prediction-Based Lossy Compression Dramatically via Ratio-Quality Modeling. In *Proceedings of the 38th IEEE International Conference on Data Engineering*, Virtual Event, May 9–12, 2022.
- [**HPDC '22**] Daoce Wang, Jesus Pulido, Pascal Grosset, Sian Jin, Jiannan Tian, James Ahrens, and Dingwen Tao. TAC: Optimizing Error-Bounded Lossy Compression for Three-Dimensional Adaptive Mesh Refinement Simulations. In *Proceedings of the 31st ACM International Symposium on High-Performance Parallel and Distributed Computing*, Minneapolis, MN, June 27–July 1, 2022.
- [**HPDC '22**] Xiaodong Yu, Sheng Di, Kai Zhao, Jiannan Tian, Dingwen Tao, Xin Liang, and Franck Cappello. Ultra-fast Error-bounded Lossy Compression for Scientific Dataset. In *Proceedings of the 31st ACM International Symposium on High-Performance Parallel and Distributed Computing*, Minneapolis, MN, June 27–July 1, 2022.
- [**IPDPS ’22**] Cody Rivera, Sheng Di, Xiaodong Yu, Jiannan Tian, Dingwen Tao, and Franck Cappello. Optimizing Huffman Decoding for Error-Bounded Lossy Compression on GPUs. In *Proceedings of the 36th IEEE International Parallel and Distributed Symposium*, Lyon, France, May 30–June 3, 2022. 
- [**HPDC '21**] Sian Jin, Jesus Pulido, Pascal Grosset, Jiannan Tian, Dingwen Tao, and James Ahrens. Adaptive Configuration of In Situ Lossy Compression for Cosmology Simulations via Fine-Grained Rate-Quality Modeling. In *Proceedings of the 30th ACM International Symposium on High-Performance Parallel and Distributed Computing*, Virtual Event, Sweden, June 21-25, 2021.
- [**ICDE '21**] Kai Zhao, Sheng Di, Maxim Dmitriev, Thierry-Laurent D. Tonellot, Zizhong Chen, and Franck Cappello. Optimizing Error-Bounded Lossy Compression for Scientiﬁc Data by Dynamic Spline Interpolation In *Proceeding of the 37th IEEE International Conference on Data Engineering*, Chania, Crete, Greece, Apr 19-22, 2021.
- [**IPDPS '21**] Jiannan Tian, Cody Rivera, Sheng Di, Jieyang Chen, Xin Liang, Dingwen Tao, and Franck Cappello. Revisiting Huffman Coding: Toward Extreme Performance on Modern GPU Architectures. In *2021 IEEE International Parallel and Distributed Processing Symposium*, Portland, Oregon, May 17-21, 2021. 
- [**BigData '21**] Jinyang Liu, Sihuan Li, Sheng Di, Xin Liang, Kai Zhao, Dingwen Tao, Zizhong Chen, and Franck Cappello. Improving Lossy Compression for SZ by Exploring the Best-Fit Lossless Compression Techniques. In *2021 IEEE International Conference on Big Data (Big Data)*, Virtual Event, December 15-18, 2021.
- [**HiPC '21**] Yuanjian Liu, Sheng Di, Kai Zhao, Sian Jin, Chen Wang, Kyle Chard, Dingwen Tao, Ian Foster, and Franck Cappello. Optimizing Multi-Range based Error-Bounded Lossy Compression for Scientific Datasets. In *2021 IEEE 28th International Conference on High Performance Computing, Data, and Analytics*, Virtual Event, December 18–21, 2021.
- [**HPDC '20**] Kai Zhao, Sheng Di, Xin Liang, Sihuan Li, Dingwen Tao, Zizhong Chen, and Franck Cappello. Significantly Improving Lossy Compression for HPC Datasets with Second-Order Prediction and Parameter Optimization. In *Proceedings of the 29th ACM International Symposium on High-Performance Parallel and Distributed Computing*, Stockholm, Sweden, June 23-26, 2020. 

## Software

- SZauto: SZ C++ Version that Supports Second-Order Prediction and Parameter Optimization ([https://github.com/szcompressor/SZauto](https://github.com/szcompressor/SZauto))
- HDF5 Parallel I/O with SZ ([https://github.com/jinsian/HDF5-SZ](https://github.com/jinsian/HDF5-SZ))

## Outreach
- [2022 NSF CSSI PI Meeting](https://cssi-pi-community.github.io/2022-meeting/) for "Towards a Sustainable Data and Software Cyberinfrastructure" at Alexandria, VA. 
- [The 2nd International Workshop on Big Data Reduction](https://iwbdr.github.io/iwbdr21/) held with 2021 IEEE Big Data conference.
- [The 1st International Workshop on Big Data Reduction](https://iwbdr.github.io/iwbdr20/) held with 2020 IEEE Big Data conference.

## Acknowledgement & Disclaimer

This material is based upon work supported by the National Science Foundation under Grants No. 2042084 and 2003709. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation.
