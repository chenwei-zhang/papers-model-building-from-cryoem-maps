# Paper List for Protein Atomic Model Building 

## Table of Contents

- [Paper List for Protein Atomic Model Building](#paper-list-for-protein-atomic-model-building)
  - [Table of Contents](#table-of-contents)
  - [1. Introduction](#1-introduction)
  - [2. Methods](#2-methods)
  - [3. Contributing](#3-contributing)
  - [4. License](#4-license)

## 1. Introduction<a name="introduction"></a>

This repository provides a list of the state-of-the-art methods in atomic model building with cryo-EM density maps. These methods leverage a combination of machine learning, deep learning, and other computational approaches. 
<br>
*Note: Model names from the papers are coloured with* ${\color{red}Red}$.

## 2. Methods<a name="methods"></a>

> ### 2.1. Atomic Model Building Methods<a name="atomic-model"></a>

**Model building of protein complexes from intermediate-resolution cryo-EM maps with deep learning-guided automatic assembly** <br>
<sub>Jiahua He, Peicong Lin, Ji Chen, Hong Cao, Sheng-You Huang</sub> <br>
*Nature Communications, July 2022.* <br>
[[paper]](https://www.nature.com/articles/s41467-022-31748-9) [[code]](http://huanglab.phys.hust.edu.cn/EMBuild/) ${\color{red}\texttt{EMBuild}}$
	
**FFF: Fragment-Guided Flexible Fitting for Building Complete Protein Structures**<br>
<sub>Weijie Chen, Xinyan Wang, Yuhang Wang</sub>
<br>
*CVPR, Feburary 2023.* <br>
[[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_FFF_Fragment-Guided_Flexible_Fitting_for_Building_Complete_Protein_Structures_CVPR_2023_paper.pdf) [[demo1]](https://app.bohrium.dp.tech/fff) [[demo2]](https://nb.bohrium.dp.tech/detail/2412744727) <strong><span style="color: blue;">FFF</span></strong>

**Improved AlphaFold modeling with implicit experimental information**<br>
<sub>Thomas C. Terwilliger, Billy K. Poon, Pavel V. Afonine, Christopher J. Schlicksup, Tristan I. Croll, Claudia Millán, Jane. S. Richardson, Randy J. Read, Paul D. Adams</sub>
<br>
*Nature Methods, October 2022.* <br>
[[paper]](https://www.nature.com/articles/s41592-022-01645-6) [[code]](https://github.com/phenix-project/Colabs) <strong><span style="color: blue;">Iterative AlphaFold</span></strong>

**Automated model building and protein identification in cryo-EM maps**<br>
<sub>Kiarash Jamali, Lukas Käll, Rui Zhang, Alan Brown, Dari Kimanius, Sjors H.W. Scheres</sub>
<br>
*bioRXiv, May 2023.* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2023.05.16.541002v1.full.pdf) [[code]](https://github.com/3dem/model-angelo) <strong><span style="color: blue;">ModelAngelo</span></strong>

**DeepTracer for fast de novo cryo-EM protein structure modeling and special studies on CoV-related complexes**<br>
<sub>Kiarash Jamali, Lukas Käll, Rui Zhang, Alan Brown, Dari Kimanius, Sjors H.W. Scheres</sub>
<br>
*PNAS, December 2020.* <br>
[[paper]](https://www.pnas.org/doi/epdf/10.1073/pnas.2017525118) [[demo]](https://deeptracer.uw.edu/home) <strong><span style="color: blue;">DeepTracer</span></strong>

**DeepTracer-ID: De novo protein identification from cryo-EM maps**<br>
<sub>Luca Chang, Fengbin Wang, Kiernan Connolly, Hanze Meng, Zhangli Su, Virginija Cvirkaite-Krupovic, Mart Krupovic, Edward H. Egelman, Dong Si</sub>
<br>
*Biophysical Journal, August 2022.* <br>
[[paper]](https://www.cell.com/biophysj/pdf/S0006-3495(22)00511-2.pdf) [[demo]](https://deeptracer.uw.edu/home) <strong><span style="color: blue;">DeepTracer-ID</span></strong>

**CR-I-TASSER: assemble protein structures from cryo-EM density maps using deep convolutional neural networks**<br>
<sub>Xi Zhang, Biao Zhang, Peter L. Freddolino, Yang Zhang</sub>
<br>
*Nature Methods, Feburary 2022.* <br>
[[paper]](https://www.nature.com/articles/s41592-021-01389-9) [[code]](https://zhanggroup.org/CR-I-TASSER/) <strong><span style="color: blue;">CR-I-TASSER</span></strong>

**EMNUSS: a deep learning framework for secondary structure annotation in cryo-EM maps**<br>
<sub>Jiahua He, Sheng-You Huang</sub>
<br>
*Briefings in bioinformatics, November 2021.* <br>
[[paper]](https://watermark.silverchair.com/bbab156.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAA1AwggNMBgkqhkiG9w0BBwagggM9MIIDOQIBADCCAzIGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMwO8SZZzx-zr4xF4_AgEQgIIDA6mV7c-NiL1AsibRt4bSt7I37TmhDVI8Bt8AOzrVhSIjE_pHpBpsUzrUYd1ZU8zJc9F-sjzCD7gB0xL2VfaDZxU2uC_BmeL0j8AHSN1EC7FnLqghlqW7NV6ZxW7ZWEE9x8k6bJG_u7DMPMRfYWCkbll6fIFSut3XFw47_0WTPRerOcs7RutECxJ4MSo2-VmffZoeB-AaTN3Gfr5yhpIrTN_YgWucIQ9Pj5lkXfVm-6qBS6mhh78ZQZP2SB4ugrl0BMpnt98prVuY_LFTsFeuLPQTg_McFyCcPUNgGEMkiSd94F-2TaA5A7AuFt0Ic8ork9d-zwCjxweGji6fUqU0Vp9_Wy4tivz_95Z1fb1dBAcuiea34pc-MGYpZHfRK6hdpiql7jMeUkodp08An6r79PGJwEvdjnLj1IhnOZGYkBMn0qypZYf-KGcd9rYWiSN2myL89exaDzL6CEUVNTuVroapkD09ww6Tbn5IybBH0qWd2nvvV_LVsoveqvcKCNQY5Du-et-ci3q_Pq3pm31S-dqu_3dGUbBChiIpmq3z64GSfsCuHHGNo1ysFJWrQEnw8Y_Ky-w_CwfOTVFFY1AHaY4kSNwgIanTRJIQR2Ew5yopOYyKUTWoYJJRbTscZ1l3yR3RFMftWFv3uZ1RDWHgmTArZm3jKuLH8NbDqHBBzOwx3Wmjogni4JEiqLta56OqtXS8i7tx4hzCCC9bkaGPOmV6v_uDYQsaew-8MpyOEf_1ADKITn_Nvif5LiGOcKz69xIEEu6nj7lroPAHD9xIDhS2bhdAfHecCKXAb659bNPzuRWOHWl7ckqmH2zeFV6aZt1iikgWwCMtHAl9P6HrhTyvbZiUT8nHvQETAig2kz8tns2kK-UwwoWU52uvustkmB3-hrNl-wvtm6smFHw48uwzsXhqkmer_jLqq4AjzBeHYmhmXMQI5mXyDOfVnKgi-CdTMeY7i3tl2-P3PCw_qSCGLCUHorGnKO-OkRqaPuurgaaYi3MIEe2JCZt9OAFQ3G4vyw) [[code]](https://github.com/JiahuaHe/EMNUSS) <strong><span style="color: blue;">EMNUSS</span></strong>

**Haruspex: A Neural Network for the Automatic Identification of Oligonucleotides and Protein Secondary Structure in Cryo-Electron Microscopy Maps**<br>
<sub>Philipp Mostosi, Hermann Schindelin, Philip Kollmannsberger, Andrea Thorn</sub>
<br>
*Angewandte Chemie International Edition, March 2020.* <br>
[[paper]](https://onlinelibrary.wiley.com/doi/epdf/10.1002/anie.202000421) [[code]](https://github.com/thorn-lab/haruspex) <strong><span style="color: blue;">Haruspex</span></strong>

**Deep Learning to Predict Protein Backbone Structure from High-Resolution Cryo-EM Density Maps**<br>
<sub>Dong Si, Spencer A. Moritz, Jonas Pfab, Jie Hou, Renzhi Cao, Liguo Wang, Tianqi Wu, Jianlin Cheng</sub>
<br>
*Scientific reports , March 2020.* <br>
[[paper]](https://www.nature.com/articles/s41598-020-60598-y) [[code]](https://github.com/DrDongSi/Ca-Backbone-Prediction) <strong><span style="color: blue;">cascaded-CNN (C-CNN)</span></strong>

**Deep convolutional neural networks for detecting secondary structures in protein density maps from cryo-electron microscopy**<br>
<sub>Rongjian Li, Dong Si, Tao Zeng, Shuiwang Ji, Jing He</sub>
<br>
*IEEE , December 2016.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/7822490/authors#authors)

**AAnchor: CNN guided detection of anchor amino acids in high resolution cryo-EM density maps**<br>
<sub>Mark Rozanov, Haim J. Wolfson</sub>
<br>
*IEEE, January 2019.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/8621288) [[demo]](http://bioinfo3d.cs.tau.ac.il/AAnchor/) <strong><span style="color: blue;">AAnchor</span></strong>

**Protein secondary structure detection in intermediate-resolution cryo-EM maps using deep learning**<br>
<sub>MSai Raghavendra Maddhuri Venkata Subramaniya, Genki Terashi, Daisuke Kihara</sub>
<br>
*Nature Methods, July 2019.* <br>
[[paper]](https://www.nature.com/articles/s41592-019-0500-1) [[code]](https://github.com/kiharalab/Emap2sec) <strong><span style="color: blue;">Emap2sec</span></strong>

**Sequence-guided protein structure determination using graph convolutional and recurrent networks**<br>
<sub>Po-Nan Li, Saulo H. P. de Oliveira, Soichi Wakatsuki, Henry van den Bedem</sub>
<br>
*IEEE, December 2020.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/9287979) [[code]](https://github.com/liponan/structure-generator) <strong><span style="color: blue;">Structure Generator</span></strong>

**Progressive assembly of multi-domain protein structures from cryo-EM density maps**<br>
<sub>Xiaogen Zhou, Yang Li, Chengxin Zhang, Wei Zheng, Guijun Zhang, Yang Zhang</sub>
<br>
*Nature computational science, April 2022.* <br>
[[paper]](https://www.nature.com/articles/s43588-022-00232-1) [[code]](https://zhanggroup.org/DEMO-EM/) <strong><span style="color: blue;">DEMO-EM</span></strong>


<br>
<br>

> ### 2.2. Protein Structure Prediction Methods<a name="predict-protein"></a>

**Highly accurate protein structure prediction with AlphaFold** <br>
<sub>John Jumper, Richard Evans, Alexander Pritzel, Tim Green, Michael Figurnov, Olaf Ronneberger, Kathryn Tunyasuvunakool, Russ Bates, Augustin Žídek, Anna Potapenko, Alex Bridgland, Clemens Meyer, Simon A. A. Kohl, Andrew J. Ballard, Andrew Cowie, Bernardino Romera-Paredes, Stanislav Nikolov, Rishub Jain, Jonas Adler, Trevor Back, Stig Petersen, David Reiman, Ellen Clancy, Michal Zielinski, Martin Steinegger, Michalina Pacholska, Tamas Berghammer, Sebastian Bodenstein, David Silver, Oriol Vinyals, Andrew W. Senior, Koray Kavukcuoglu, Pushmeet Kohli, Demis Hassabis</sub> <br>
*Nature, July 2021.* <br>
[[paper]](https://www.nature.com/articles/s41586-021-03819-2) [[code]](https://github.com/google-deepmind/alphafold) <strong><span style="color: blue;">AlphaFold 2</span></strong>

**Accurate prediction of protein structures and interactions using a three-track neural network**<br>
<sub>Minkyung Baek, Frank Dimaio, Ivan Anishchenko, Justas Dauparas, Sergey Ovchinnikov, Gyu Rie Lee, Jue Wang, Qian Cong, Lisa N. Kinch, R. Dustin Schaeffer, Claudia Millán, Hahnbeom Park, Carson Adams, Caleb R. Glassman, Andy Degiovanni, Jose H. Pereira, Andria V. Rodrigues, Alberdina A. Van Dijk, Ana C. Ebrecht, Diederik J. Opperman, Theo Sagmeister, Christoph Buhlheller, Tea Pavkov-Keller, Manoj K. Rathinaswamy, Udit Dalwadi, Calvin K. Yip, John E. Burke, K. Christopher Garcia, Nick V. Grishin, Paul D. Adams, Randy J. Read, David Baker</sub>
<br>
*Science, August 2021.* <br>
[[paper]](https://www.science.org/doi/10.1126/science.abj8754) [[code]](https://github.com/RosettaCommons/RoseTTAFold) <strong><span style="color: blue;">RoseTTAFold</span></strong>



<br>
<br>

## 3. Contributing<a name="contributing"></a>

We welcome contributions from the community. If you have suggestions, bug reports, or would like to add a new method, please email cwzhang@cs.ubc.ca.

## 4. License<a name="license"></a>

This project is licensed under the [MIT License](LICENSE).

---

*Note: Please refer to the individual method's documentation for specific details and requirements.*

Feel free to star, fork, and contribute to this repository. Happy modeling!
