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
*Nature Communications, June 2024.* <br> 
[[paper]](https://www.nature.com/articles/s41467-024-49647-6) [[code]](https://github.com/jianlin-cheng/Cryo2Struct) ${\color{red}\texttt{[Cryo2Struct]}}$

**Automated model building and protein identification in cryo-EM maps** <br>
<sub>Kiarash Jamali, Lukas Käll, Rui Zhang, Alan Brown, Dari Kimanius, Sjors H.W. Scheres</sub> <br>
*Nature, Feb 2024* <br>
[[paper]](https://www.nature.com/articles/s41586-024-07215-4) [[code]](https://github.com/3dem/model-angelo) ${\color{red}\texttt{[ModelAngelo 1.0]}}$

**Fast and automated protein-DNA/RNA macromolecular complex modeling from cryo-EM maps** <br>
<sub>Andrew Nakamura, Hanze Meng, Minglei Zhao, Fengbin Wang, Jie Hou, Renzhi Cao, Dong Si</sub> <br>
*Briefings in Bioinformatics, March 2023.* <br>
[[paper]](https://academic.oup.com/bib/article/24/2/bbac632/6995410) [[demo]](https://deeptracer.uw.edu/home) ${\color{red}\texttt{[DeepTracer-2.0]}}$

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

<br>



> ### 2.2. Indirect Atomic Model-Building Methods<a name="indirect-method"></a>

**DEMO-EM2: assembling protein complex structures from cryo-EM maps through intertwined chain and domain fitting**<br>
<sub>Ziying Zhang, Yaxian Cai, Biao Zhang, Wei Zheng, Lydia Freddolino, Guijun Zhang, Xiaogen Zhou</sub>
<br>
*Briefings in Bioinformatics, March 2024.* <br>
[[paper]](https://academic.oup.com/bib/article/25/2/bbae113/7631480) [[code]](https://zhanggroup.org/DEMO-EM/DEMO-EM2/) ${\color{red}\texttt{[DEMO-EM2]}}$

**DiffModeler: Large Macromolecular Structure Modeling in Low-Resolution Cryo-EM Maps Using Diffusion Model** <br>
<sub>Xiao Wang, Han Zhu, Genki Terashi, Manav Taluja, Daisuke Kihara</sub> <br>
*bioRXiv, January 2024.* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2024.01.20.576370v1.full.pdf) [[code]](https://github.com/kiharalab/DiffModeler) ${\color{red}\texttt{[DiffModeler]}}$

**DeepMainmast: integrated protocol of protein structure modeling for cryo-EM with deep learning and structure prediction** <br>
<sub>Genki Terashi, Xiao Wang, Devashish Prasad, Tsukasa Nakamura, Daisuke Kihara</sub> <br>
*Nature Methods, December 2023.* <br>
[[paper]](https://www.nature.com/articles/s41592-023-02099-0) [[code]](https://github.com/kiharalab/DeepMainMast) ${\color{red}\texttt{[DeepMainmast]}}$

**FFF: Fragment-Guided Flexible Fitting for Building Complete Protein Structures**<br>
<sub>Weijie Chen, Xinyan Wang, Yuhang Wang</sub>
<br>
*CVPR, February 2023.* <br>
[[paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_FFF_Fragment-Guided_Flexible_Fitting_for_Building_Complete_Protein_Structures_CVPR_2023_paper.pdf) [[demo1]](https://app.bohrium.dp.tech/fff) [[demo2]](https://nb.bohrium.dp.tech/detail/2412744727) ${\color{red}\texttt{[FFF]}}$

**Improved AlphaFold modeling with implicit experimental information**<br>
<sub>Thomas C. Terwilliger, Billy K. Poon, Pavel V. Afonine, Christopher J. Schlicksup, Tristan I. Croll, Claudia Millán, Jane S. Richardson, Randy J. Read, Paul D. Adams</sub>
<br>
*Nature Methods, October 2022.* <br>
[[paper]](https://www.nature.com/articles/s41592-022-01645-6) [[code]](https://github.com/phenix-project/Colabs) ${\color{red}\texttt{[Iterative-AlphaFold]}}$

**Folding non-homologous proteins by coupling deep-learning contact maps with I-TASSER assembly simulations**<br>
<sub>Xiaogen Zhou, Wei Zheng, Yang Li, Robin Pearce, Chengxin Zhang, Eric W. Bell, Guijun Zhang, Yang Zhang</sub>
<br>
*Nature Protocols, August 2022.* <br>
[[paper]](https://zhanggroup.org/papers/2022_7.pdf) [[code]](https://zhanggroup.org/I-TASSER-MTD/) ${\color{red}\texttt{[I-TASSER-MTD]}}$

**DeepTracer-ID: De novo protein identification from cryo-EM maps**<br>
<sub>Luca Chang, Fengbin Wang, Kiernan Connolly, Hanze Meng, Zhangli Su, Virginija Cvirkaite-Krupovic, Mart Krupovic, Edward H. Egelman, Dong Si</sub>
<br>
*Biophysical Journal, August 2022.* <br>
[[paper]](https://www.cell.com/biophysj/pdf/S0006-3495(22)00511-2.pdf) [[demo]](https://deeptracer.uw.edu/home) ${\color{red}\texttt{[DeepTracer-ID]}}$

**Model building of protein complexes from intermediate-resolution cryo-EM maps with deep learning-guided automatic assembly** <br>
<sub>Jiahua He, Peicong Lin, Ji Chen, Hong Cao, Sheng-You Huang</sub> <br>
*Nature Communications, July 2022.* <br>
[[paper]](https://www.nature.com/articles/s41467-022-31748-9) [[code]](http://huanglab.phys.hust.edu.cn/EMBuild/) ${\color{red}\texttt{[EMBuild]}}$

**Progressive assembly of multi-domain protein structures from cryo-EM density maps**<br>
<sub>Xiaogen Zhou, Yang Li, Chengxin Zhang, Wei Zheng, Guijun Zhang, Yang Zhang</sub>
<br>
*Nature Computational Science, April 2022.* <br>
[[paper]](https://www.nature.com/articles/s43588-022-00232-1) [[code]](https://zhanggroup.org/DEMO-EM/) ${\color{red}\texttt{[DEMO-EM]}}$

**CR-I-TASSER: assemble protein structures from cryo-EM density maps using deep convolutional neural networks**<br>
<sub>Xi Zhang, Biao Zhang, Peter L. Freddolino, Yang Zhang</sub>
<br>
*Nature Methods, February 2022.* <br>
[[paper]](https://www.nature.com/articles/s41592-021-01389-9) [[code]](https://zhanggroup.org/CR-I-TASSER/) ${\color{red}\texttt{[CR-I-TASSER]}}$

**Cryo_fit: Democratization of flexible fitting for cryo-EM**<br>
<sub>Doo Nam Kim, Nigel W. Moriarty, Serdal Kirmizialtin, Pavel V. Afonine, Billy Poon, Oleg V. Sobolev, Paul D. Adams, Karissa Sanbonmatsu</sub>
<br>
*Journal of Structural Biology, October 2019.* <br>
[[paper]](https://doi.org/10.1016/j.jsb.2019.05.012) [[code]](https://phenix-online.org/documentation/tutorials/cryo_fit_install.html) ${\color{red}\texttt{[Cryo-fit]}}$

**Macromolecular structure determination using X-rays, neutrons and electrons: recent developments in Phenix**<br>
<sub>Dorothee Liebschner, Pavel V. Afonine, Matthew L. Baker, Gábor Bunkóczi, Vincent B. Chen, Tristan I. Croll, Bradley Hintze, Li-Wei Hung, Swati Jain, Airlie J. McCoy, Nigel W. Moriarty, Robert D. Oeffner, Billy K. Poon, Michael G. Prisant, Randy J. Read, Jane S. Richardson, David C. Richardson, Massimo D. Sammito, Oleg V. Sobolev, Duncan H. Stockwell, Thomas C. Terwilliger, Alexandre G. Urzhumtsev, Lizbeth L. Videau, Christopher J. Williams, Paul D. Adams</sub>
<br>
*Acta Crystallographica Section D: Structural Biology, October 2019.* <br>
[[paper]](https://journals.iucr.org/d/issues/2019/10/00/di5033/index.html) [[code]](https://phenix-online.org/documentation/reference/dock_in_map.html) ${\color{red}\texttt{[phenix.dock-in-map]}}$

<br>


> ### 2.3. Review Papers on Atomic Model Building<a name="review"></a>

**Novel Artificial Intelligence-Based Approaches for Ab Initio Structure Determination and Atomic Model Building for Cryo-Electron Microscopy**<br>
<sub>Megan C. DiIorio， Arkadiusz W. Kulczyk</sub>
<br>
*Micromachines, August 2023.* <br>
[[paper]](https://www.mdpi.com/2072-666X/14/9/1674)

**Deep learning for reconstructing protein structures from cryo-EM density maps: Recent advances and future directions**<br>
<sub>Nabin Giri, Raj S. Roy, Jianlin Cheng</sub>
<br>
*Current Opinion in Structural Biology, April 2023.* <br>
[[paper]](https://www.sciencedirect.com/science/article/pii/S0959440X23000106#:~:text=Deep%20learning%20is%20a%20promising,from%20cryo%2DEM%20density%20maps.&text=Convolutional%20neural%20networks%20and%20U,from%20cryo%2DEM%20density%20maps)

**Machine Learning for Structure Determination in Single-Particle Cryo-Electron Microscopy: A Systematic Review**<br>
<sub>Jia-Geng Wu, Yang Yan, Dong-Xu Zhang, Bo-Wen Liu, Qing-Bing Zheng, Xiao-Liang Xie</sub>
<br>
*IEEE Transactions on Neural Networks and Learning Systems, December 2021.* <br>
[[paper]](https://ieeexplore.ieee.org/abstract/document/9657494)

**Artificial intelligence advances for de novo molecular structure modeling in cryo-electron microscopy**<br>
<sub>Dong Si, Andrew Nakamura, Runbang Tang, Haowen Guan, Jie Hou, Ammaar Firozi, Renzhi Cao, Kyle Hippe, Minglei Zhao</sub>
<br>
*Advanced Review, May 2021.* <br>
[[paper]](https://wires.onlinelibrary.wiley.com/doi/abs/10.1002/wcms.1542)

<br>



> ### 2.4. Cryo-EM Map Sharpening Methods<a name="enhance-map"></a>

**CryoTEN: Efficiently Enhancing Cryo-EM Density Maps Using Transformers**<br>
<sub>Joel Selvaraj, Liguo Wang, Jianlin Cheng</sub>
<br>
*bioRXiv, September 2024.* 
<br>
[[paper]](https://www.biorxiv.org/content/10.1101/2024.09.06.611715v1.full.pdf) [[code]](https://github.com/jianlin-cheng/cryoten) ${\color{red}\texttt{[CryoTEN]}}$

**Integrating AlphaFold and deep learning for atomistic interpretation of cryo-EM maps** <br>
<sub>Xin Dai, Longlong Wu, Shinjae Yoo, Qun Liu</sub> <br>
*Briefings in Bioinformatics, November 2023.* 
<br>
[[paper]](https://doi.org/10.1093/bib/bbad405) [[code]](https://github.com/Structurebiology-BNL/CryoFEM) ${\color{red}\texttt{[CryoFEM]}}$

**Enhancing cryo-EM maps with 3D deep generative networks for assisting protein structure modeling**<br>
<sub>Sai Raghavendra Maddhuri Venkata Subramaniya, Genki Terashi, Daisuke Kihara</sub>
<br>
*Bioinformatics, August 2023.*
<br>
[[paper]](https://doi.org/10.1093/bioinformatics/btad494) [[code]](https://github.com/kiharalab/EM-GAN) ${\color{red}\texttt{[EM-GAN]}}$

**Improvement of cryo-EM maps by simultaneous local and non-local deep learning**<br> 
<sub>Jiahua He, Tao Li, Sheng-You Huang</sub> <br> 
*Nature Communications, June 2023.* 
<br> 
[[paper]](https://www.nature.com/articles/s41467-023-39031-1) [[code]](http://huanglab.phys.hust.edu.cn/EMReady/) ${\color{red}\texttt{[EMReady]}}$

**DeepTracer-Denoising: Deep Learning for 3D Electron Density Map Denoising**<br> 
<sub>Haowen Guan, Dong Si</sub> <br> 
*IEEE International Conference on Bioinformatics and Biomedicine, December 2022.* 
<br> 
[[paper]](https://ieeexplore.ieee.org/document/9994879) [[code]](https://github.com/HaowenGuan/DeepTracer-Denoising) ${\color{red}\texttt{[DeepTracer-Denoising]}}$

**DeepEMhancer: a deep learning solution for cryo-EM volume post-processing**<br> 
<sub>Ruben Sanchez-Garcia, Josue Gomez-Blanco, Ana Cuervo, Jose Maria Carazo, Carlos Oscar S. Sorzano, Javier Vargas</sub> <br> 
*Nature Communications Biology, July 2021.* 
<br> 
[[paper]](https://www.nature.com/articles/s42003-021-02399-1) [[code]](https://github.com/rsanchezgarc/deepEMhancer) ${\color{red}\texttt{[DeepEMhancer]}}$

**Local computational methods to improve the interpretability and analysis of cryo-EM maps**<br> 
<sub>Satinder Kaur, Josue Gomez-Blanco, Ahmad A. Z. Khalifa, Swathi Adinarayanan, Ruben Sanchez-Garcia, Daniel Wrapp, Jason S. McLellan, Khanh Huy Bui, Javier Vargas</sub> <br> 
*Nature Communications, February 2021.* 
<br> 
[[paper]](https://www.nature.com/articles/s41467-021-21509-5) [[code]](https://github.com/1aviervargas/LocSpiral-LocBSharpen-LocBFactor-LocOccupancy) ${\color{red}\texttt{[LocSpiral, LocBSharpen, LocBFactor, LocOccupancy]}}$

**Automated map sharpening by maximization of detail and connectivity**<br> 
<sub>Thomas C. Terwilliger, Oleg V. Sobolev, Pavel V. Afoninec, Paul D. Adamsd</sub> <br> 
*Acta Crystallographica Section D: Structural Biology, June 2018.* 
<br> 
[[paper]](https://journals.iucr.org/d/issues/2018/06/00/ic5102/index.html) [[code]](https://phenix-online.org/documentation/reference/auto_sharpen.html) ${\color{red}\texttt{[phenix.auto-sharpen]}}$

**Model-based local density sharpening of cryo-EM maps**<br> 
<sub>Arjen J Jakobi, Matthias Wilmanns, Carsten Sachse</sub> <br> 
*Structural Biology and Molecular Biophysics, November 2017.* 
<br> 
[[paper]](https://elifesciences.org/articles/27131) [[code]](https://github.com/wrigjz/ppihotspotid/) ${\color{red}\texttt{[LocScale]}}$

<br>



> ### 2.5. De Novo Protein Structure Prediction Methods<a name="predict-protein"></a>

**Simulating 500 million years of evolution with a language model**<br>
<sub>Thomas Hayes, Roshan Rao, Halil Akin, Nicholas J. Sofroniew, Deniz Oktay,  View ORCID ProfileZeming Lin, Robert Verkuil, Vincent Q. Tran, Jonathan Deaton, Marius Wiggert, Rohil Badkundri, Irhum Shafkat, Jun Gong, Alexander Derry, Raul S. Molina, Neil Thomas, Yousuf Khan, Chetan Mishra, Carolyn Kim, Liam J. Bartie, Matthew Nemeth, Patrick D. Hsu, Tom Sercu, Salvatore Candido, Alexander Rives</sub>
<br>
*bioRXiv, July 2024.* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2024.07.01.600583v1.full.pdf) [[code]](https://github.com/evolutionaryscale/esm) ${\color{red}\texttt{[ESM3]}}$

**Accurate structure prediction of biomolecular interactions with AlphaFold 3** <br>
<sub>Josh Abramson, Jonas Adler, Jack Dunger, Richard Evans, Tim Green, Alexander Pritzel, Olaf Ronneberger, Lindsay Willmore, Andrew J. Ballard, Joshua Bambrick, Sebastian W. Bodenstein, David A. Evans, Chia-Chun Hung, Michael O’Neill, David Reiman, Kathryn Tunyasuvunakool, Zachary Wu, Akvilė Žemgulytė, Eirini Arvaniti, Charles Beattie, Ottavia Bertolli, Alex Bridgland, Alexey Cherepanov, Miles Congreve, Alexander I. Cowen-Rivers, Andrew Cowie, Michael Figurnov, Fabian B. Fuchs, Hannah Gladman, Rishub Jain, Yousuf A. Khan, Caroline M. R. Low, Kuba Perlin, Anna Potapenko, Pascal Savy, Sukhdeep Singh, Adrian Stecula, Ashok Thillaisundaram, Catherine Tong, Sergei Yakneen, Ellen D. Zhong, Michal Zielinski, Augustin Žídek, Victor Bapst, Pushmeet Kohli, Max Jaderberg, Demis Hassabis, John M. Jumper</sub>
<br>
*Nature, May 2024.* <br>
[[paper]](https://www.nature.com/articles/s41586-024-07487-w) [[server]](https://alphafoldserver.com/about) ${\color{red}\texttt{[AlphaFold 3]}}$

**OpenFold: retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization** <br>
<sub>Gustaf Ahdritz, Nazim Bouatta, Christina Floristean, Sachin Kadyan, Qinghui Xia, William Gerecke, Timothy J. O’Donnell, Daniel Berenberg, Ian Fisk, Niccolò Zanichelli, Bo Zhang, Arkadiusz Nowaczynski, Bei Wang, Marta M. Stepniewska-Dziubinska, Shang Zhang, Adegoke Ojewole, Murat Efe Guney, Stella Biderman, Andrew M. Watkins, Stephen Ra, Pablo Ribalta Lorenzo, Lucas Nivon, Brian Weitzner, Yih-En Andrew Ban, Shiyang Chen, Minjia Zhang, Conglong Li, Shuaiwen Leon Song, Yuxiong He, Peter K. Sorger, Emad Mostaque, Zhao Zhang, Richard Bonneau, Mohammed AlQuraishi</sub>
<br>
*Nature Methods, May 2024.* <br>
[[paper]](https://www.nature.com/articles/s41592-024-02272-z) [[code]](https://github.com/aqlaboratory/openfold) ${\color{red}\texttt{[OpenFold]}}$

**Generalized biomolecular modeling and design with RoseTTAFold All-Atom**<br>
<sub>Rohith Krishna, Jue Wang, Woody Ahern, Pascal Sturmfels, Preetham Venkatesh, Indrek Kalvet, Gyu Rie Lee, Felix S. Morey-Burrows, Ivan Anishchenko, Ian R. Humphreys, Ryan McHugh, Dionne Vafeados, Xinting Li, George A. Sutherland, Andrew Hitchcock, C. Neil Hunter, Alex Kang, Evans Brackenbrough, Asim K. Bera, Minkyung Baek, Frank DiMaio, David Baker</sub>
<br>
*Science, March 2024.* <br>
[[paper]](https://www.science.org/doi/10.1126/science.adl2528) [[code]](https://github.com/baker-laboratory/RoseTTAFold-All-Atom) ${\color{red}\texttt{[RoseTTAFold All-Atom]}}$

**Illuminating protein space with a programmable generative model** <br>
<sub>John B. Ingraham, Max Baranov, Zak Costello, Karl W. Barber, Wujie Wang, Ahmed Ismail, Vincent Frappier, Dana M. Lord, Christopher Ng-Thow-Hing, Erik R. Van Vlack, Shan Tie, Vincent Xue, Sarah C. Cowles, Alan Leung, João V. Rodrigues, Claudio L. Morales-Perez, Alex M. Ayoub, Robin Green, Katherine Puentes, Frank Oplinger, Nishant V. Panwar, Fritz Obermeyer, Adam R. Root, Andrew L. Beam, Frank J. Poelwijk, Gevorg Grigoryan</sub>
<br>
*Nature, November 2023.* <br>
[[paper]](https://www.nature.com/articles/s41586-023-06728-8) [[code]](https://github.com/generatebio/chroma) ${\color{red}\texttt{[Chroma]}}$

**Efficient and accurate prediction of protein structure using RoseTTAFold2**<br>
<sub>Minkyung Baek,  View ORCID ProfileIvan Anishchenko, Ian R. Humphreys, Qian Cong, David Baker, Frank DiMaio</sub>
<br>
*bioRXiv, May 2023.* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2023.05.24.542179v1.full.pdf) [[code]](https://github.com/uw-ipd/RoseTTAFold2) ${\color{red}\texttt{[RoseTTAFold 2]}}$

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

**High-resolution de novo structure prediction from primary sequence**<br>
<sub>Ruidong Wu, Fan Ding, Rui Wang, Rui Shen, Xiwen Zhang, Shitong Luo, Chenpeng Su, Zuofan Wu, Qi Xie, Bonnie Berger, Jianzhu Ma, Jian Peng</sub>
<br>
*bioRXiv, July 2022.* <br>
[[paper]](https://www.biorxiv.org/content/10.1101/2022.07.21.500999v1.full.pdf) [[code]](https://github.com/HeliXonProtein/OmegaFold) ${\color{red}\texttt{[OmegaFold]}}$

**Accurate prediction of protein structures and interactions using a three-track neural network**<br>
<sub>Minkyung Baek, Frank Dimaio, Ivan Anishchenko, Justas Dauparas, Sergey Ovchinnikov, Gyu Rie Lee, Jue Wang, Qian Cong, Lisa N. Kinch, R. Dustin Schaeffer, Claudia Millán, Hahnbeom Park, Carson Adams, Caleb R. Glassman, Andy Degiovanni, Jose H. Pereira, Andria V. Rodrigues, Alberdina A. Van Dijk, Ana C. Ebrecht, Diederik J. Opperman, Theo Sagmeister, Christoph Buhlheller, Tea Pavkov-Keller, Manoj K. Rathinaswamy, Udit Dalwadi, Calvin K. Yip, John E. Burke, K. Christopher Garcia, Nick V. Grishin, Paul D. Adams, Randy J. Read, David Baker</sub>
<br>
*Science, August 2021.* <br>
[[paper]](https://www.science.org/doi/10.1126/science.abj8754) [[code]](https://github.com/RosettaCommons/RoseTTAFold) ${\color{red}\texttt{[RoseTTAFold]}}$

**Highly accurate protein structure prediction with AlphaFold** <br>
<sub>John Jumper, Richard Evans, Alexander Pritzel, Tim Green, Michael Figurnov, Olaf Ronneberger, Kathryn Tunyasuvunakool, Russ Bates, Augustin Žídek, Anna Potapenko, Alex Bridgland, Clemens Meyer, Simon A. A. Kohl, Andrew J. Ballard, Andrew Cowie, Bernardino Romera-Paredes, Stanislav Nikolov, Rishub Jain, Jonas Adler, Trevor Back, Stig Petersen, David Reiman, Ellen Clancy, Michal Zielinski, Martin Steinegger, Michalina Pacholska, Tamas Berghammer, Sebastian Bodenstein, David Silver, Oriol Vinyals, Andrew W. Senior, Koray Kavukcuoglu, Pushmeet Kohli, Demis Hassabis</sub> <br>
*Nature, July 2021.* <br>
[[paper]](https://www.nature.com/articles/s41586-021-03819-2) [[code]](https://github.com/google-deepmind/alphafold) ${\color{red}\texttt{[AlphaFold 2]}}$

**Improved protein structure prediction using potentials from deep learning** <br>
<sub>Andrew W. Senior, Richard Evans, John Jumper, James Kirkpatrick, Laurent Sifre, Tim Green, Chongli Qin, Augustin Žídek, Alexander W. R. Nelson, Alex Bridgland, Hugo Penedones, Stig Petersen, Karen Simonyan, Steve Crossan, Pushmeet Kohli, David T. Jones, David Silver, Koray Kavukcuoglu, Demis Hassabis</sub> 
<br>
*Nature, January 2020.* <br>
[[paper]](https://www.nature.com/articles/s41586-019-1923-7) ${\color{red}\texttt{[AlphaFold 1]}}$



## 3. Contributing<a name="contributing"></a>

We welcome contributions from the community. If you have suggestions, or bug reports, or would like to add a new method, please email cwzhang@cs.ubc.ca.

## 4. License<a name="license"></a>

This project is licensed under the [MIT License](LICENSE).

---

*Note: Please refer to the individual method's documentation for specific details and requirements.*

Feel free to star, fork, and contribute to this repository. Happy modeling!
