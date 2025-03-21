---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

{% include base_path %}

## Reconstructing evolutionary history of cancer genomes
The reconstruction of cancer evolutionary history is important for early detection, prognosis, and treatment of patients. 
Phylogenetic inference methods have been widely used to reconstruct evolutionary history of cancer cells with different types of markers.

<figure>
  <a href="/images/cnetml.jpg">
  <img src="/images/cnetml.jpg" align="right" alt =  "Phylogeny inference from copy number profiles of multiple samples" />
    </a>
  <!-- <figcaption>Phylogeny inference from copy number profiles of multiple samples </figcaption> -->
</figure>

Using copy number alterations (CNAs) as markers, we have developed CNETML,the first program to jointly infer the tree topology, node ages, and CNA rates from longitudinal samples.

With the recent MRC award, we will develop more realistic models of  evolution that integrate CNAs at different levels and Bayesian methods that support variable CNA rates in time. 

### References:
* Bingxin Lu. (2024). Cancer phylogenetic inference using copy number alterations detected from DNA sequencing data. Cancer Pathogenesis and Therapy, 2, E27-E77. https://doi.org/10.1016/j.cpt.2024.04.003

* Cheng Zhao, Darren P. Ennis, Bingxin Lu, Hasan B. Mirza, Chishimba Sokota, Baljeet Kaur, Naveena Singh et al. (2024). The genomic trajectory of ovarian high grade serous carcinoma can be observed in STIC lesions. The Journal of Pathology. https://doi.org/10.1002/path.6322

* Bingxin Lu, Kit Curtius, Trevor A. Graham, Ziheng Yang, Chris P. Barnes (2023). CNETML: maximum likelihood inference of phylogeny from copy number profiles of multiple samples. Genome Biology, 24, 144. https://doi.org/10.1186/s13059-023-02983-0.


## Computational modelling of human genomes
Linking genomics with stochastic modelling and Bayesian inference provides a powerful approach to quantify somatic evolution, which may help to predict disease progression and drug response.

<figure>
  <a href="/images/abc.jpg">
  <img src="/images/abc.jpg" align="right" alt =  "Parameter inference with approximate Bayesian computation (ABC)" />
    </a>
  <!-- <figcaption>Parameter inference with approximate Bayesian computation (ABC)</figcaption> -->
</figure>

We have applied this approach to model CNAs and structural variants (SVs) resulted from chromosome instability from experimental and real cancer patient data. 

Our previous inferences of important prognosis-related parameters including chromosome mis-segregation rates and selection strengths were limited by the mixture of signals in bulk sequencing data. Therefore, we are interested in improving the inference at a higher resolution with increasingly available single cell data.

We are also interested in applying the latest genomic language models to tackle challenges related to human genomics.


### References:
* William Cross\*, Salpie Nowinski\*, George Cresswell\*, Maximilian Mossner\*, Abhirup Banerjee\*, Bingxin Lu\*, et al. (2024). Negative selection may cause grossly altered but broadly stable karyotypes in metastatic colorectal cancer. bioRxiv: https://doi.org/10.1101/2020.03.26.007138. (* co-first authors)

* Bingxin Lu, Samuel Winnall, William Cross, Chris P. Barnes (2023). Cell-cycle dependent DNA repair and replication unifies patterns of chromosome instability. bioRxiv. https://doi.org/10.1101/2024.01.03.574048


* Yannik Bollen, Ellen Stelloo, Petra van Leenen, Bas Ponsioen, Myrna van den Bos, Bingxin Lu, et al. (2021). Reconstructing single-cell karyotype alterations in colorectal cancer identifies punctuated and gradual diversification patterns. Nature Genetics, 53(8), 1187-1195. https://doi.org/10.1038/s41588-021-00891-2.


## Investigating intratumour heterogeneity and clonal evolution in cancer genomes
Intratumour heterogeneity (ITH) and clonal evolution often cause therapy failure and drug resistance in cancer patients. 
We worked on the analysis of genomic ITH in lung adenocarcinoma (LUAD) and hepatocellular carcinoma (HCC) patients previously. 

<figure>
  <a href="/images/psite.jpg">
  <img src="/images/psite.jpg" align="right" alt =  "The ﬂow chart of PSiTE" />
    </a>
  <!-- <figcaption>The ﬂow chart of PSiTE</figcaption> -->
</figure>


To evaluate the performances of different variant callers and clonal decomposition methods, we also developed a phylogeny guided simulator for tumour evolution (PSITE). 

We are interested in developing new methods to decompose ITH and decipher clonal evolution.



### References:
* Kasper Karlsson, Moritz Przybilla, Eran Kotler, Aziz Khan, Hang Xu, Kremena Karagyozova,
Alexandra Sockell, Wing H. Wong, Katherine Liu, Amanda Mah, Yuan-Hung Lo, Bingxin Lu, et al. (2023). Deterministic evolution and stringent selection during preneoplasia. Nature, 618, 383–393. https://doi.org/10.1038/s41586-023-06102-8.

* Weiwei Zhai\*, Hannah Lai\*, Neslihan Arife Kaya\*, Jianbin Chen\*, Hechuan Yang\*, Bingxin Lu\*, et al. (2022). Dynamic phenotypic heterogeneity and the evolution of multiple RNA subtypes in Hepatocellular Carcinoma: the PLANET study. National Science Review, 9(3), nwab192. https://academic.oup.com/nsr/article/9/3/nwab192/6414014. (* co-first authors)

* Jianbin Chen, Hechuan Yang, Audrey Su Min Teo, Lidyana Bte Amer, Faranak Ghazi Sherbaf, Chu Quan Tan, Jacob Josiah Santiago Alvarez, Bingxin Lu, et al. (2020). Genomic landscape and ethnic specificity of lung adenocarcinoma in Asia. Nature Genetics, 52(2), 177-186. https://doi.org/10.1038/s41588-019-0569-6.

* Hechuan Yang, Bingxin Lu, Lan Huong Lai, Abner Herbert Lim, Jacob Josiah Santiago Alvarez, Weiwei Zhai (2019). PSiTE: A phylogeny guided simulator for tumor evolution. Bioinformatics, 35(17), 3148-3150. https://doi.org/10.1093/bioinformatics/btz028.


## Understanding the evolution of microbial genomes 
Lateral gene transfer (LGT) and recombination are common and important evolutionary processes in microbes.
We have developed two machine learning methods to predict genomic islands (GIs), a large genomic region probably acquired by LGT which may contain genes related to pathogenesis and antibiotic resistance.
We are also interested in developing and applying new methods to other important problems in microbial evolution. 

<figure>
  <a href="/images/gicluster.jpg">
  <img src="/images/gicluster.jpg" align="right" alt =  "The ﬂow chart of GI-Cluster" />
    </a>
  <!-- <figcaption>The ﬂow chart of GI-Cluster</figcaption> -->
</figure>



### References:
* Bingxin Lu, Hon Wai Leong (2018). GI-Cluster: detecting genomic islands via consensus clustering on multiple features. Journal of Bioinformatics and Computational Biology, 16(03), 1840010. https://doi.org/10.1142/S0219720018400103.

* Bingxin Lu, Hon Wai Leong (2016). Computational methods for predicting genomic islands in microbial genomes. Computational and Structural Biotechnology Journal, 14:200-206. https://doi.org/10.1016/j.csbj.2016.05.001.

* Bingxin Lu, Hon Wai Leong (2016). GI-SVM: A sensitive method for predicting genomic islands
based on unannotated sequence of a single genome. Journal of Bioinformatics and Computational Biology, 14(01), 1640003. https://doi.org/10.1142/S0219720016400035.



## Solving problems related to phylogenetic networks  
Phylogenetic networks are becoming essential to represent complex evolutionary relationships when LGT and other reticulation events are involved.

<figure>
  <a href="/images/phynetwork.jpg">
  <img src="/images/phynetwork.jpg" align="right" alt =  "An example of a phylogenetic network" />
    </a>
  <!-- <figcaption>An example of a phylogenetic network</figcaption> -->
</figure>


We previously developed algorithms related to two fundamental problems in phylogenetic networks, the tree containment problem (TCP) and the cluster containment problem (CCP). 
We are interested in solving other related problems.


### References:
* Andreas D.M. Gunawan, Bingxin Lu, Louxin Zhang (2018). Fast methods for solving the Cluster Containment Problem for phylogenetic networks. arXiv:1801.04498. https://doi.org/10.48550/arXiv.1801.04498.

* Bingxin Lu, Louxin Zhang, HonWai Leong (2017). A program to compute the soft Robinson–Foulds distance between phylogenetic networks. BMC Genomics, 18(2), 111. https://doi.org/10.1186/s12864-017-3500-5.

* Andreas D.M. Gunawan\*, Bingxin Lu\*, Louxin Zhang (2016). A program for verification of phylogenetic network models. Bioinformatics, 32(17), i503-i510. https://doi.org/10.1093/bioinformatics/btw467. (* co-first authors) 



## Integrating multi-omics data to solve problems in cancer and microbial biology
To understand all the underlying processes shaping cancer evolution and inform treatment, it is necessary to integrate data measurements of various types. High-throughput sequencing has been generating huge amounts of multi-omics data, which provide a rich resource of information to address important questions in cancer evolution. However, it is challenging to systematically integrate these heterogeneous data types. 
Machine learning has emerged as a promising technique for multi-omics data integration, but there are still many challenges including data of high dimension yet low sample size, data noise and missing information, and biological interpretations.
We are interested in developing new machine learning methods that leverage multi-omics data to tackle key challenges in cancer and microbial biology.

<!-- Drug repurposing with ex vivo drug sensitivity testing and computational omics -->
Despite multiple options and drugs to treat cancer, treatments often fail due to intratumour heterogeneity, metastasis, and drug resistance. However, it remains very expensive and time-consuming to develop new cancer drugs. Drug repurposing serves as a cost-effective option to provide patients with affordable and effective individualized treatments. We are interested in developing new machine learning methods for effective drug combinations or personalized drug recommendations.


### References:
* Jinwen Feng, Chen Ding, Naiqi Qiu, Xiaotian Ni, Dongdong Zhan, Wanlin Liu, Xia Xia, Peng Li, Bingxin Lu, et al. (2017). Firmiana: Towards a one-stop proteomic cloud platform for data processing and analysis. Nature Biotechnology, 35(5), 409-412. https://doi.org/10.1038/nbt.3825.


* Bingxin Lu, Zhenbing Zeng, Tieliu Shi (2013). Comparative study of de novo assembly and genome guided assembly strategies for transcriptome reconstruction based on RNA-Seq. Science China Life Sciences, 56(2), 143-155. https://doi.org/10.1007/s11427-013-4442-z.



## Reconstructing and analyzing genome graphs
SVs often alter large genomic regions and play an important role in both species evolution and cancer development. However, the complete landscape of SVs in the genomes has been understudied due to technical limitations and gradually gets improved with the new sequencing techniques such as long-read sequencing. 

<figure>
  <a href="/images/graph.jpg">
  <img src="/images/graph.jpg" align="right" alt = "An example of reconstructed cancer genome graphs" />
    </a>
  <!-- <figcaption>An example of reconstructed cancer genome graphs</figcaption> -->
</figure>

Due to the extreme variety of SVs, graph-based genome representation provides a natural way to analyze SVs, but the utilities of these graphs have not been fully exploited.
We are interested in developing new approaches to better understand the patterns and mechanisms of SVs with genome graphs.

