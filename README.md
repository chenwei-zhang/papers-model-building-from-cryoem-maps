# Paper List for Protein Atomic Model Building 

## Table of Contents

- [Paper List for Protein Atomic Model Building](#paper-list-for-protein-atomic-model-building)
  - [Table of Contents](#table-of-contents)
  - [1. Introduction](#1-introduction)
  - [2. Methods](#2-methods)
    - [2.1 Atomic Model Building Methods](#atomic-model)
    - [2.2 Review Papers for Model Building Using DL](#review)
    - [2.2 Protein Structure Prediction Methods](#predict-protein)
  - [3. Contributing](#3-contributing)
  - [4. License](#4-license)

## 1. Introduction<a name="introduction"></a>

This repository provides a list of the state-of-the-art methods in atomic model building (with cryo-EM density maps). These methods leverage a combination of machine learning, deep learning, and other computational algorithms. 
<br>
*Note: Model names from the papers are coloured with* ${\color{red} \texttt{[RED]}}$.

## 2. Methods<a name="methods"></a>

> ### 2.1. Atomic Model Building Methods<a name="atomic-model"></a>

**Automated model building and protein identification in cryo-EM maps** <br>
<sub>Kiarash Jamali, Lukas Käll, Rui Zhang, Alan Brown, Dari Kimanius, Sjors H.W. Scheres</sub> <br>
*bioRXiv, May 2023* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2023.05.16.541002v1) [[code]](https://github.com/3dem/model-angelo) ${\color{red}\texttt{[ModelAngelo 1.0]}}$

**A graph neural network approach to automated model building in cryo-EM maps** <br>
<sub>Kiarash Jamali, Dari Kimanius, Sjors H.W. Scheres</sub> <br>
*ICLR, February 2023* <br>
[[paper]](https://arxiv.org/pdf/2210.00006.pdf) [[code]](https://github.com/3dem/model-angelo) ${\color{red}\texttt{[ModelAngelo 0.3]}}$

**Data-driven regularisation lowers the size barrier of cryo-EM structure determination** <br>
<sub>Dari Kimanius, Kiarash Jamali, Max E Wilkinson, Sofia Lövestam, Vaithish Velazhahan, Takanori Nakane, Sjors H.W. Scheres</sub><br>
*bioRXiv, October 2023.* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2023.10.23.563586v1.full.pdf) [[code]](https://github.com/3dem/relion) ${\color{red}\texttt{[Blush Regularisation]}}$

**Model building of protein complexes from intermediate-resolution cryo-EM maps with deep learning-guided automatic assembly** <br>
<sub>Jiahua He, Peicong Lin, Ji Chen, Hong Cao, Sheng-You Huang</sub> <br>
*Nature Communications, July 2022.* <br>
[[paper]](https://www.nature.com/articles/s41467-022-31748-9) [[code]](http://huanglab.phys.hust.edu.cn/EMBuild/) ${\color{red}\texttt{[EMBuild]}}$
	
**Integrated Protocol of Protein Structure Modeling for Cryo-EM with Deep Learning and Structure Prediction** <br>
<sub>Genki Terashi, Xiao Wang, Devashish Prasad, Tsukasa Nakamura, Daisuke Kihara</sub> <br>
*bioRXiv, October 2023.* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2023.10.19.563151v1.full.pdf) [[code]](https://github.com/kiharalab/DeepMainMast) ${\color{red}\texttt{[DeepMainMast]}}$
	
**FFF: Fragment-Guided Flexible Fitting for Building Complete Protein Structures**<br>
<sub>Weijie Chen, Xinyan Wang, Yuhang Wang</sub>
<br>
*CVPR, February 2023.* <br>
[[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_FFF_Fragment-Guided_Flexible_Fitting_for_Building_Complete_Protein_Structures_CVPR_2023_paper.pdf) [[demo1]](https://app.bohrium.dp.tech/fff) [[demo2]](https://nb.bohrium.dp.tech/detail/2412744727) ${\color{red}\texttt{[FFF]}}$

**Improved AlphaFold modeling with implicit experimental information**<br>
<sub>Thomas C. Terwilliger, Billy K. Poon, Pavel V. Afonine, Christopher J. Schlicksup, Tristan I. Croll, Claudia Millán, Jane. S. Richardson, Randy J. Read, Paul D. Adams</sub>
<br>
*Nature Methods, October 2022.* <br>
[[paper]](https://www.nature.com/articles/s41592-022-01645-6) [[code]](https://github.com/phenix-project/Colabs) ${\color{red}\texttt{[Iterative AlphaFold]}}$

**$A^2$-Net: Molecular Structure Estimation from Cryo-EM Density Volumes**<br>
<sub>Kui Xu, Zhe Wang, Jianping Shi, Hongsheng Li, Qiangfeng Cliff Zhang</sub>
<br>
*AAAI, July 2019.* <br>
[[paper]](https://arxiv.org/pdf/1901.00785.pdf) [[code]](https://github.com/phenix-project/Colabs) ${\color{red}{\texttt{[}}A^2\texttt{-Net]}}$

**Automated model building and protein identification in cryo-EM maps**<br>
<sub>Kiarash Jamali, Lukas Käll, Rui Zhang, Alan Brown, Dari Kimanius, Sjors H.W. Scheres</sub>
<br>
*bioRXiv, May 2023.* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2023.05.16.541002v1.full.pdf) [[code]](https://github.com/3dem/model-angelo) ${\color{red}\texttt{[ModelAngelo]}}$

**DeepTracer-ID: De novo protein identification from cryo-EM maps**<br>
<sub>Luca Chang, Fengbin Wang, Kiernan Connolly, Hanze Meng, Zhangli Su, Virginija Cvirkaite-Krupovic, Mart Krupovic, Edward H. Egelman, Dong Si</sub>
<br>
*Biophysical Journal, August 2022.* <br>
[[paper]](https://www.cell.com/biophysj/pdf/S0006-3495(22)00511-2.pdf) [[demo]](https://deeptracer.uw.edu/home) ${\color{red}\texttt{[DeepTracer-ID]}}$

**DeepTracer for fast de novo cryo-EM protein structure modeling and special studies on CoV-related complexes**<br>
<sub>Kiarash Jamali, Lukas Käll, Rui Zhang, Alan Brown, Dari Kimanius, Sjors H.W. Scheres</sub>
<br>
*PNAS, December 2020.* <br>
[[paper]](https://www.pnas.org/doi/epdf/10.1073/pnas.2017525118) [[demo]](https://deeptracer.uw.edu/home) ${\color{red}\texttt{[DeepTracer]}}$

**Deep learning geometrical potential for high-accuracy ab initio protein structure prediction**<br>
<sub>Yang Li, Chengxin Zhang, Dong-Jun Yu, Yang Zhang</sub>
<br>
*Iscience, June 2022.* <br>
[[paper]](https://doi.org/10.1016/j.isci.2022.104425) [[code]](https://zhanggroup.org/DeepPotential/) ${\color{red}\texttt{[DeepPotential]}}$

**Folding non-homologous proteins by coupling deep-learning contact maps with I-TASSER assembly simulations**<br>
<sub>Xiaogen Zhou, Wei Zheng, Yang Li, Robin Pearce, Chengxin Zhang, Eric W. Bell, Guijun Zhang and Yang Zhang</sub>
<br>
*Nature Protocols, August 2022.* <br>
[[paper]](https://zhanggroup.org/papers/2022_7.pdf) [[code]](https://zhanggroup.org/I-TASSER-MTD/) ${\color{red}\texttt{[I-TASSER-MTD]}}$

**Folding non-homologous proteins by coupling deep-learning contact maps with I-TASSER assembly simulations**<br>
<sub>Wei Zheng, Chengxin Zhang, Yang Li, Robin Pearce, Eric W Bell, Yang Zhang</sub>
<br>
*Cell Reports Methods, July 2021.* <br>
[[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8336924/) [[code]](https://zhanggroup.org/C-I-TASSER/) ${\color{red}\texttt{[C-I-TASSER]}}$

**CR-I-TASSER: assemble protein structures from cryo-EM density maps using deep convolutional neural networks**<br>
<sub>Xi Zhang, Biao Zhang, Peter L. Freddolino, Yang Zhang</sub>
<br>
*Nature Methods, February 2022.* <br>
[[paper]](https://www.nature.com/articles/s41592-021-01389-9) [[code]](https://zhanggroup.org/CR-I-TASSER/) ${\color{red}\texttt{[CR-I-TASSER]}}$

**I-TASSER: a unified platform for automated protein structure and function prediction**<br>
<sub>Ambrish Roy, Alper Kucukural, Yang Zhang</sub>
<br>
*Nature Protocols, March 2010.* <br>
[[paper]](https://www.nature.com/articles/nprot.2010.5) [[code]](https://zhanggroup.org/I-TASSER/) ${\color{red}\texttt{[I-TASSER]}}$

**The I-TASSER Suite: protein structure and function prediction**<br>
<sub>Jianyi Yang, Renxiang Yan, Ambrish Roy, Dong Xu, Jonathan Poisson, Yang Zhang</sub>
<br>
*Nature Methods, December 2014.* <br>
[[paper]](https://www.nature.com/articles/nmeth.3213) [[code]](http://zhanglab.ccmb.med.umich.edu/I-TASSER/download/) ${\color{red}\texttt{[I-TASSER Suite]}}$

**EMNUSS: a deep learning framework for secondary structure annotation in cryo-EM maps**<br>
<sub>Jiahua He, Sheng-You Huang</sub>
<br>
*Briefings in bioinformatics, November 2021.* <br>
[[paper]](https://academic.oup.com/bib/article/22/6/bbab156/6265218) [[code]](https://github.com/JiahuaHe/EMNUSS) ${\color{red}\texttt{[EMNUSS]}}$

**Haruspex: A Neural Network for the Automatic Identification of Oligonucleotides and Protein Secondary Structure in Cryo-Electron Microscopy Maps**<br>
<sub>Philipp Mostosi, Hermann Schindelin, Philip Kollmannsberger, Andrea Thorn</sub>
<br>
*Angewandte Chemie International Edition, March 2020.* <br>
[[paper]](https://onlinelibrary.wiley.com/doi/epdf/10.1002/anie.202000421) [[code]](https://github.com/thorn-lab/haruspex) ${\color{red}\texttt{[Haruspex]}}$

**Deep Learning to Predict Protein Backbone Structure from High-Resolution Cryo-EM Density Maps**<br>
<sub>Dong Si, Spencer A. Moritz, Jonas Pfab, Jie Hou, Renzhi Cao, Liguo Wang, Tianqi Wu, Jianlin Cheng</sub>
<br>
*Scientific reports, March 2020.* <br>
[[paper]](https://www.nature.com/articles/s41598-020-60598-y) [[code]](https://github.com/DrDongSi/Ca-Backbone-Prediction) ${\color{red}\texttt{[Cascaded-CNN]}}$

**Full-length de novo protein structure determination from cryo-EM maps using deep learning**<br>
<sub>Jiahua He, Sheng-You Huang</sub>
<br>
*Bioinformatics, October 2021.* <br>
[[paper]](https://doi.org/10.1093/bioinformatics/btab357) [[code]](https://github.com/JiahuaHe/DeepMM) ${\color{red}\texttt{[DeepMM]}}$

**Deep convolutional neural networks for detecting secondary structures in protein density maps from cryo-electron microscopy**<br>
<sub>Rongjian Li, Dong Si, Tao Zeng, Shuiwang Ji, Jing He</sub>
<br>
*IEEE, December 2016.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/7822490/authors#authors) ${\color{red}\texttt{[CNN-Based]}}$

**AAnchor: CNN guided detection of anchor amino acids in high resolution cryo-EM density maps**<br>
<sub>Mark Rozanov, Haim J. Wolfson</sub>
<br>
*IEEE, January 2019.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/8621288) [[demo]](http://bioinfo3d.cs.tau.ac.il/AAnchor/) ${\color{red}\texttt{[AAnchor]}}$

**Detecting protein and DNA/RNA structures in cryo-EM maps of intermediate resolution using deep learning**<br>
<sub>Xiao Wang, Eman Alnabati, Tunde W. Aderinwale, Sai Raghavendra Maddhuri Venkata Subramaniya, Genki Terashi & Daisuke Kihara</sub>
<br>
*Nature Communications, April 2021.* <br>
[[paper]](https://www.nature.com/articles/s41592-019-0500-1) [[code]](https://github.com/kiharalab/Emap2sec) ${\color{red}\texttt{[Emap2sec+]}}$

**Protein secondary structure detection in intermediate-resolution cryo-EM maps using deep learning**<br>
<sub>MSai Raghavendra Maddhuri Venkata Subramaniya, Genki Terashi, Daisuke Kihara</sub>
<br>
*Nature Methods, July 2019.* <br>
[[paper]](https://www.nature.com/articles/s41592-019-0500-1) [[code]](https://github.com/kiharalab/Emap2sec) ${\color{red}\texttt{[Emap2sec]}}$

**Sequence-guided protein structure determination using graph convolutional and recurrent networks**<br>
<sub>Po-Nan Li, Saulo H. P. de Oliveira, Soichi Wakatsuki, Henry van den Bedem</sub>
<br>
*IEEE, December 2020.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/9287979) [[code]](https://github.com/liponan/structure-generator) ${\color{red}\texttt{[Structure Generator]}}$

**Progressive assembly of multi-domain protein structures from cryo-EM density maps**<br>
<sub>Xiaogen Zhou, Yang Li, Chengxin Zhang, Wei Zheng, Guijun Zhang, Yang Zhang</sub>
<br>
*Nature Computational Science, April 2022.* <br>
[[paper]](https://www.nature.com/articles/s43588-022-00232-1) [[code]](https://zhanggroup.org/DEMO-EM/) ${\color{red}\texttt{[DEMO-EM]}}$

**Building Protein Atomic Models from Cryo-EM Density Maps and Residue Co-Evolution**<br>
<sub>Guillaume Bouvier, Benjamin Bardiaux, Riccardo Pellarin, Chiara Rapisarda, Michael Nilges</sub>
<br>
*Biomolecules, September 2022.* <br>
[[paper]](https://www.mdpi.com/2218-273X/12/9/1290) [[code]](https://github.com/bougui505/EMEC) ${\color{red}\texttt{[EMEC]}}$
 
**Cryo2Struct: A Large Labeled Cryo-EM Density Map Dataset for AI-based Reconstruction of Protein Structures**<br>
<sub>Genki Terashi, Daisuke Kihara</sub>
<br>
*bioRXiv, June 2023.* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2023.06.14.545024v1.full.pdf) [[code]](https://github.com/BioinfoMachineLearning/cryo2struct) ${\color{red}\texttt{[Cryo2Struct]}}$
 
**EM-GAN: Data-Driven Fast Stress Analysis for Multi-Segment Interconnects**<br>
<sub>Wentian Jin, Sheriff Sadiqbatcha, Zeyu Sun, Han Zhou, Sheldon X.-D. Tan</sub>
<br>
*IEEE, December 2020.* <br>
[[paper]](https://ieeexplore.ieee.org/document/9283508) [[code]](https://github.com/kiharalab/EM-GAN) ${\color{red}\texttt{[EM-GAN]}}$
 
**Ab initio protein structure assembly using continuous structure fragments and optimized knowledge-based force field**<br>
<sub>Dong Xu, Yang Zhang</sub>
<br>
*Proteins: Structure, Function, and Bioinformatics, March 2012.* <br>
[[paper]](https://zhanggroup.org/papers/2012_7.pdf) [[code]](https://zhanggroup.org/QUARK/) ${\color{red}\texttt{[QUARK]}}$

**Improving fragment-based ab initio protein structure assembly using low-accuracy contact-map predictions**<br>
<sub>S. M. Mortuza, Wei Zheng, Chengxin Zhang, Yang Li, Robin Pearce, Yang Zhang </sub>
<br>
*Nature Communications, and Bioinformatics,  August 2021.* <br>
[[paper]](https://seq2fun.dcmb.med.umich.edu//papers/2021_13.pdf) [[code]](https://zhanggroup.org/C-QUARK/) ${\color{red}\texttt{[C-QUARK]}}$

**Cryo_fit: Democratization of flexible fitting for cryo-EM**<br>
<sub>Doo Nam Kim, Nigel W. Moriarty, Serdal Kirmizialtin, Pavel V. Afonine, Billy Poon, Oleg V. Sobolev, Paul D. Adams, Karissa Sanbonmatsu</sub>
<br>
*Journal of Structural Biology, October 2019.* <br>
[[paper]](https://doi.org/10.1016/j.jsb.2019.05.012) [[code]](https://phenix-online.org/documentation/tutorials/cryo_fit_install.html) ${\color{red}\texttt{[Cryo-fit]}}$

**A fully automatic method yielding initial models from high-resolution cryo-electron microscopy maps**<br>
<sub>Thomas C. Terwilliger, Paul D. Adams, Pavel V. Afonine, Oleg V. Sobolev</sub>
<br>
*Nature Methods, October 2018.* <br>
[[paper]](https://www.nature.com/articles/s41592-018-0173-1) [[code]](https://phenix-online.org/documentation/reference/map_to_model.html) ${\color{red}\texttt{[phenix.map-to-model]}}$


**Macromolecular structure determination using X-rays, neutrons and electrons: recent developments in Phenix**<br>
<sub>Dorothee Liebschner, Pavel V. Afonine, Matthew L. Baker, Gábor Bunkóczi, Vincent B. Chen, Tristan I. Croll, Bradley Hintze, Li-Wei Hung, Swati Jain, Airlie J. McCoy, Nigel W. Moriarty, Robert D. Oeffner, Billy K. Poon, Michael G. Prisant, Randy J. Read, Jane S. Richardson, David C. Richardson, Massimo D. Sammito, Oleg V. Sobolev, Duncan H. Stockwell, Thomas C. Terwilliger, Alexandre G. Urzhumtsev, Lizbeth L. Videau, Christopher J. Williams, Paul D. Adams</sub>
<br>
*Structural Biology, October 2019.* <br>
[[paper]](https://journals.iucr.org/d/issues/2019/10/00/di5033/index.html) [[code]](https://phenix-online.org/documentation/reference/dock_in_map.html) ${\color{red}\texttt{[phenix.dock-in-map]}}$


**De novo main-chain modeling for EM maps using MAINMAST**<br>
<sub>Genki Terashi, Daisuke Kihara</sub>
<br>
*Nature Communications, April 2018.* <br>
[[paper]](https://www.nature.com/articles/s41467-018-04053-7) [[code]](https://kiharalab.org/emsuites/mainmast.php) ${\color{red}\texttt{[MAINMAST]}}$


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

**Accurate prediction of protein structures and interactions using a three-track neural network**<br>
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
