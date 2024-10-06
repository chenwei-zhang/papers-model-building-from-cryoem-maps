# Papers on DL-based Methods for Atomic Model Building from Cryo-EM Density Maps

## Table of Contents

- [Papers on Protein Atomic Model Building](#papers-on-protein-atomic-model-building)
  - [Table of Contents](#table-of-contents)
  - [1. Introduction](#1-introduction)
  - [2. Methods](#2-methods)
    - [2.1 Direct Model-Building Methods](#direct-method)
    - [2.2 Indirect Model-Building Methods](#indirect-method)
    - [2.3 Review Papers on Atomic Model Building](#review)
    - [2.4 Cryo-EM Map Sharpening Methods](#enhance-map)
    - [2.5 De Novo Protein Structure Prediction Methods](#predict-protein)
  - [3. Contributing](#3-contributing)
  - [4. License](#4-license)

## 1. Introduction<a name="introduction"></a>

This repository provides a list of the state-of-the-art methods on (i) atomic model building from cryo-EM density maps, (ii) cryo-EM map sharpening, and (iii) de novo protein structure prediction. These methods leverage a combination of machine learning, deep learning, and other optimization algorithms. 
<br>
*Note: Model names from the papers are coloured with* ${\color{red} \texttt{[RED]}}$.

## 2. Methods<a name="methods"></a>

> ### 2.1. Direct Atomic Model-Building Methods<a name="direct-method"></a>

**De novo atomic protein structure modeling for cryoEM density maps using 3D transformer and HMM**<br> <sub>Nabin Giri, Jianlin Cheng</sub> <br> 
*Nature Communications, June 2024. <br> 
[[paper]](https://www.nature.com/articles/s41467-024-49647-6) [[code]](https://github.com/jianlin-cheng/Cryo2Struct) ${\color{red}\texttt{[Cryo2Struct]}}$

**Automated model building and protein identification in cryo-EM maps** <br>
<sub>Kiarash Jamali, Lukas Käll, Rui Zhang, Alan Brown, Dari Kimanius, Sjors H.W. Scheres</sub> <br>
*Nature, Feb 2024* <br>
[[paper]](https://www.nature.com/articles/s41586-024-07215-4) [[code]](https://github.com/3dem/model-angelo) ${\color{red}\texttt{[ModelAngelo 1.0]}}$

**A graph neural network approach to automated model building in cryo-EM maps** <br>
<sub>Kiarash Jamali, Dari Kimanius, Sjors H.W. Scheres</sub> <br>
*ICLR, February 2023* <br>
[[paper]](https://arxiv.org/pdf/2210.00006.pdf) [[code]](https://github.com/3dem/model-angelo) ${\color{red}\texttt{[ModelAngelo 0.3]}}$

**Building Protein Atomic Models from Cryo-EM Density Maps and Residue Co-Evolution**<br>
<sub>Guillaume Bouvier, Benjamin Bardiaux, Riccardo Pellarin, Chiara Rapisarda, Michael Nilges</sub>
<br>
*Biomolecules, September 2022.* <br>
[[paper]](https://www.mdpi.com/2218-273X/12/9/1290) [[code]](https://github.com/bougui505/EMEC) ${\color{red}\texttt{[EMEC]}}$

**EMNUSS: a deep learning framework for secondary structure annotation in cryo-EM maps**<br>
<sub>Jiahua He, Sheng-You Huang</sub>
<br>
*Briefings in Bioinformatics, November 2021.* <br>
[[paper]](https://academic.oup.com/bib/article/22/6/bbab156/6265218) [[code]](https://github.com/JiahuaHe/EMNUSS) ${\color{red}\texttt{[EMNUSS]}}$

**Full-length de novo protein structure determination from cryo-EM maps using deep learning**<br>
<sub>Jiahua He, Sheng-You Huang</sub>
<br>
*Bioinformatics, October 2021.* <br>
[[paper]](https://doi.org/10.1093/bioinformatics/btab357) [[code]](https://github.com/JiahuaHe/DeepMM) ${\color{red}\texttt{[DeepMM]}}$

**Detecting protein and DNA/RNA structures in cryo-EM maps of intermediate resolution using deep learning**<br>
<sub>Xiao Wang, Eman Alnabati, Tunde W. Aderinwale, Sai Raghavendra Maddhuri Venkata Subramaniya, Genki Terashi, Daisuke Kihara</sub>
<br>
*Nature Communications, April 2021.* <br>
[[paper]](https://www.nature.com/articles/s41467-021-22577-3) [[code]](https://github.com/kiharalab/Emap2sec) ${\color{red}\texttt{[Emap2sec+]}}$

**DeepTracer for fast de novo cryo-EM protein structure modeling and special studies on CoV-related complexes**<br>
<sub>Luca Chang, Hanze Meng, Hongmin Li, Edward H. Egelman, Dong Si</sub>
<br>
*PNAS, December 2020.* <br>
[[paper]](https://www.pnas.org/doi/epdf/10.1073/pnas.2017525118) [[demo]](https://deeptracer.uw.edu/home) ${\color{red}\texttt{[DeepTracer]}}$

**Sequence-guided protein structure determination using graph convolutional and recurrent networks**<br>
<sub>Po-Nan Li, Saulo H. P. de Oliveira, Soichi Wakatsuki, Henry van den Bedem</sub>
<br>
*IEEE, December 2020.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/9287979) [[code]](https://github.com/liponan/structure-generator) ${\color{red}\texttt{[Structure Generator]}}$

**Haruspex: A Neural Network for the Automatic Identification of Oligonucleotides and Protein Secondary Structure in Cryo-Electron Microscopy Maps**<br>
<sub>Philipp Mostosi, Hermann Schindelin, Philip Kollmannsberger, Andrea Thorn</sub>
<br>
*Angewandte Chemie International Edition, March 2020.* <br>
[[paper]](https://onlinelibrary.wiley.com/doi/epdf/10.1002/anie.202000421) [[code]](https://github.com/thorn-lab/haruspex) ${\color{red}\texttt{[Haruspex]}}$

**Deep Learning to Predict Protein Backbone Structure from High-Resolution Cryo-EM Density Maps**<br>
<sub>Dong Si, Spencer A. Moritz, Jonas Pfab, Jie Hou, Renzhi Cao, Liguo Wang, Tianqi Wu, Jianlin Cheng</sub>
<br>
*Scientific Reports, March 2020.* <br>
[[paper]](https://www.nature.com/articles/s41598-020-60598-y) [[code]](https://github.com/DrDongSi/Ca-Backbone-Prediction) ${\color{red}\texttt{[Cascaded-CNN]}}$

**$A^2$-Net: Molecular Structure Estimation from Cryo-EM Density Volumes**<br>
<sub>Kui Xu, Zhe Wang, Jianping Shi, Hongsheng Li, Qiangfeng Cliff Zhang</sub>
<br>
*AAAI, July 2019.* <br>
[[paper]](https://arxiv.org/pdf/1901.00785.pdf) ${\color{red}\texttt{[}A^2\texttt{-Net]}}$

**Protein secondary structure detection in intermediate-resolution cryo-EM maps using deep learning**<br>
<sub>Sai Raghavendra Maddhuri Venkata Subramaniya, Genki Terashi, Daisuke Kihara</sub>
<br>
*Nature Methods, July 2019.* <br>
[[paper]](https://www.nature.com/articles/s41592-019-0500-1) [[code]](https://github.com/kiharalab/Emap2sec) ${\color{red}\texttt{[Emap2sec]}}$

**AAnchor: CNN guided detection of anchor amino acids in high resolution cryo-EM density maps**<br>
<sub>Mark Rozanov, Haim J. Wolfson</sub>
<br>
*IEEE, January 2019.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/8621288) [[demo]](http://bioinfo3d.cs.tau.ac.il/AAnchor/) ${\color{red}\texttt{[AAnchor]}}$

**A fully automatic method yielding initial models from high-resolution cryo-electron microscopy maps**<br>
<sub>Thomas C. Terwilliger, Paul D. Adams, Pavel V. Afonine, Oleg V. Sobolev</sub>
<br>
*Nature Methods, October 2018.* <br>
[[paper]](https://www.nature.com/articles/s41592-018-0173-1) [[code]](https://phenix-online.org/documentation/reference/map_to_model.html) ${\color{red}\texttt{[phenix.map-to-model]}}$

**De novo main-chain modeling for EM maps using MAINMAST**<br>
<sub>Genki Terashi, Daisuke Kihara</sub>
<br>
*Nature Communications, April 2018.* <br>
[[paper]](https://www.nature.com/articles/s41467-018-04053-7) [[code]](https://kiharalab.org/emsuites/mainmast.php) ${\color{red}\texttt{[MAINMAST]}}$

**Deep convolutional neural networks for detecting secondary structures in protein density maps from cryo-electron microscopy**<br>
<sub>Rongjian Li, Dong Si, Tao Zeng, Shuiwang Ji, Jing He</sub>
<br>
*IEEE, December 2016.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/7822490/authors#authors) ${\color{red}\texttt{[CNN-classifier]}}$



> ### 2.2. Indirect Atomic Model-Building Methods<a name="indirect-method"></a>


<br>
<br>


> ### 2.2. Review Papers for Model Building Using DL<a name="review"></a>
**Deep learning for reconstructing protein structures from cryo-EM density maps: Recent advances and future directions**<br>
<sub>Nabin Giri, Raj S. Roy, Jianlin Cheng</sub>
<br>
*Current Opinion in Structural Biology, April 2023.* <br>
[[paper]](https://www.sciencedirect.com/science/article/pii/S0959440X23000106#:~:text=Deep%20learning%20is%20a%20promising,from%20cryo%2DEM%20density%20maps.&text=Convolutional%20neural%20networks%20and%20U,from%20cryo%2DEM%20density%20maps)

**Novel Artificial Intelligence-Based Approaches for Ab Initio Structure Determination and Atomic Model Building for Cryo-Electron Microscopy**<br>
<sub>Megan C. DiIorio， Arkadiusz W. Kulczyk</sub>
<br>
*Micromachines, August 2023.* <br>
[[paper]](https://www.mdpi.com/2072-666X/14/9/1674)



<br>
<br>


> ### 2.3. Protein Structure Prediction Methods<a name="predict-protein"></a>

**Highly accurate protein structure prediction with AlphaFold** <br>
<sub>John Jumper, Richard Evans, Alexander Pritzel, Tim Green, Michael Figurnov, Olaf Ronneberger, Kathryn Tunyasuvunakool, Russ Bates, Augustin Žídek, Anna Potapenko, Alex Bridgland, Clemens Meyer, Simon A. A. Kohl, Andrew J. Ballard, Andrew Cowie, Bernardino Romera-Paredes, Stanislav Nikolov, Rishub Jain, Jonas Adler, Trevor Back, Stig Petersen, David Reiman, Ellen Clancy, Michal Zielinski, Martin Steinegger, Michalina Pacholska, Tamas Berghammer, Sebastian Bodenstein, David Silver, Oriol Vinyals, Andrew W. Senior, Koray Kavukcuoglu, Pushmeet Kohli, Demis Hassabis</sub> <br>
*Nature, July 2021.* <br>
[[paper]](https://www.nature.com/articles/s41586-021-03819-2) [[code]](https://github.com/google-deepmind/alphafold) ${\color{red}\texttt{[AlphaFold 2]}}$

**Accurate prediction of protein structures and interactions using a three-track neural network**<br>
<sub>Minkyung Baek, Frank Dimaio, Ivan Anishchenko, Justas Dauparas, Sergey Ovchinnikov, Gyu Rie Lee, Jue Wang, Qian Cong, Lisa N. Kinch, R. Dustin Schaeffer, Claudia Millán, Hahnbeom Park, Carson Adams, Caleb R. Glassman, Andy Degiovanni, Jose H. Pereira, Andria V. Rodrigues, Alberdina A. Van Dijk, Ana C. Ebrecht, Diederik J. Opperman, Theo Sagmeister, Christoph Buhlheller, Tea Pavkov-Keller, Manoj K. Rathinaswamy, Udit Dalwadi, Calvin K. Yip, John E. Burke, K. Christopher Garcia, Nick V. Grishin, Paul D. Adams, Randy J. Read, David Baker</sub>
<br>
*Science, August 2021.* <br>
[[paper]](https://www.science.org/doi/10.1126/science.abj8754) [[code]](https://github.com/RosettaCommons/RoseTTAFold) ${\color{red}\texttt{[RoseTTAFold]}}$

**Evolutionary-scale prediction of atomic-level protein structure with a language model**<br>
<sub>Zeming Lin, Halil Akin, Roshan Rao, Brian Hie, Zhongkai Zhu, Wenting Lu, Nikita Smetanin, Robert Verkuil, Ori Kabeli, Yaniv Shmueli, Allan Dos Santos Costa, Maryam Fazel-Zarandi, Tom Sercu, Salvatore Candido, Alexander Rives</sub>
<br>
*Science, March 2023.* <br>
[[paper]](https://www.science.org/doi/full/10.1126/science.ade2574) [[code]](https://github.com/facebookresearch/esm) ${\color{red}\texttt{[ESMFold]}}$

**Single-sequence protein structure prediction using a language model and deep learning**<br>
<sub>Ratul Chowdhury, Nazim Bouatta, Surojit Biswas, Christina Floristean, Anant Kharkar, Koushik Roy, Charlotte Rochereau, Gustaf Ahdritz, Joanna Zhang, George M. Church, Peter K. Sorger, Mohammed AlQuraishi</sub>
<br>
*Nature Biotechnology, October 2022.* <br>
[[paper]](https://www.nature.com/articles/s41587-022-01432-w) [[code]](https://github.com/aqlaboratory/rgn2) ${\color{red}\texttt{[RGN2]}}$

<br>


## 3. Contributing<a name="contributing"></a>

We welcome contributions from the community. If you have suggestions, bug reports, or would like to add a new method, please email cwzhang@cs.ubc.ca.

## 4. License<a name="license"></a>

This project is licensed under the [MIT License](LICENSE).

---

*Note: Please refer to the individual method's documentation for specific details and requirements.*

Feel free to star, fork, and contribute to this repository. Happy modeling!
