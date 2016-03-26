
---


---

# Due to unfortunate closure of Google Code, the cmater-bioinfo repository has been permanently shifted to http://www.cmaterju.org/bioinfo.htm #


---


---


## FunPred-2: Protein Function Prediction through Protein Interaction Network Using Protein Complex and Physico-Chemical Properties of Amino Acid ##

### Sovan Saha <sup>1</sup>, Piyali Chatterjee <sup>2</sup>, Subhadip Basu <sup>3</sup>, Mahantapas Kundu <sup>3</sup>, Mita Nasipuri <sup>3</sup> ###

<sup>1</sup> Department of Computer Science and Engineering, Dr. Sudhir Chandra Sur Degree Engineering College, Dumdum, Kolkata-700 074, India

<sup>2</sup> Department of Computer Science and Engineering, Netaji Subhash Engineering College,Garia, Kolkata – 700152, India

<sup>3</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India


**ABSTRACT:**
Proteins are the most versatile macromolecules in living systems and serve crucial functions. With successful sequencing of several genomes, the challenging problem now is to determine the functions of proteins in post genomic era. Determining protein functions experimentally is a laborious and time consuming task involving many resources. Therefore, research is going on to predict protein functions using various computational methods. One of such method uses PPI network where we consider proteins and their interconnections. Now locally dense regions in PPI networks are very likely to be protein complexes. Since protein complexes play a key role in many biological processes, detecting protein complexes in PPI networks is also one of important tasks. FunPred 2 predicts protein function from protein interaction network by identifying protein complexes and using physico-chemical properties of amino acids. The overall accuracy achieved in FunPred 2 involving hetero-interactions in 650 yeast proteins is around 85.5%, which is higher than the accuracy of many of the state-of-the-art protein function prediction methods described in the literature. The test datasets and the complete source code of the developed software are now freely available at https://code.google.com/p/cmater-bioinfo/.

[Dataset](https://www.dropbox.com/sh/i2revmfqs71rsho/AACV8Fl7aSH_ql_qTAuOVXYsa?dl=0)
[FunPred-2 Source-Code ](https://www.dropbox.com/sh/uq6p64u7bhlqg31/AADfstVZsmgxkDPXeQAxyhK5a?dl=0)


---


## A novel algorithm for fast extraction of biclusters ##

### Brijesh Kumar Sriwastava <sup>1</sup>, Subhadip Basu <sup>2</sup>, Ujjwal Maulik <sup>2</sup> ###


<sup>1</sup> Department of Computer Science and Engineering, Government College of Engineering and Leather Technology, Kolkata-700098,India

<sup>2</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India


**ABSTRACT:**

_Motivation:_ Fast extraction of biclusters from large binary datasets is essential in many applications. The work algorithm presented here attempts to achieve this objective with a novel encoding and search strategy. The developed method significantly reduces the computational overhead in comparison to the state-of-the-art biclustering algorithms.

_Results:_ Experiments on both synthetic and experimental datasets show significant computational benefits, with respect to the state-of-the-art BiBit algorithm (Rodriguez-Baena, et al., 2011),. In 100 synthetic binary datasets, our algorithmour method took ~71.1 seconds to extract 494872 biclusters, in comparison to ~3.4 hours by BiBit. In other 100 synthetic binary dataset, our algorithm takes 2565319.1 miliseconds on average to generate 435144.3 biclusters whereas it takes 0.367561 milisecond per bicluster on average. In the human PPI database of size 3788×3788, our method generates 1480 biclusters in ~69.8 seconds, where BiBit takes around ~251 seconds. On a central nervous system embryonic tumor gene expression dataset of size 7129×40, our algorithm takes ~101 minutes to produce 747069 biclusters while BiBit takes ~56 hours to produces the same result.

_Availability:_ The software tool is available for free download from https://code.google.com/p/cmater-bioinfo/.
Contact: subhadip@cse.jdvu.ac.in

_Supplementary information:_ Supplementary document along with the synthetic and experimental datasets are available at https://code.google.com/p/cmater-bioinfo/.

[Software and Datasets](https://www.dropbox.com/sh/cum2dhmbt4yhtrr/AAA-55RmZDhU_HjoRv8HLloha?dl=0)



---


## Human Protein Cluster Analysis Using Amino Acid Frequencies: An n-gram Based Software Tool ##

### Anup Kumar Halder <sup>1</sup>, Piyali Chatterjee <sup>2</sup>, Mita Nasipuri <sup>1</sup>, Subhadip Basu <sup>1</sup> ###

<sup>1</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India

<sup>2</sup> Department of Computer Science and Engineering, Netaji Subhash Engineering College,Garia, Kolkata – 700152, India

**ABSTRACT:**
This paper presents a protein cluster analysis tool by combining, 1) n-gram based amino
acid frequency features and 2) hierarchical clustering techniques. We try to justify both
qualitatively and quantitatively that proteins with increasing sequence similarity are
grouped in similar clusters. Specifically, we have considered three different values of n,
i.e., n = 1 or unigram, n = 2 or bigram and n = 3 or trigram. Our experiment with
20,213 reviewed human proteins show that a trigram based approach assures better
cluster compactness in cases of proteins with similar functional groups, similar biological processes or sharing common domains. Direct comparisons with the work of Vernone et al.(PLoS ONE. 2013;8(4):e60220) show improved clustering results with the use of n = 2 and n = 3, in large repetitive protein groups like aquaporins, keratins etc. Quantitative analysis over 12 functional properties, related pathways and diseases show significant improvement in cluster compactness in bigram and trigram based clustering methods, in comparison to the unigram based results of the respective protein groups. The supplementary files and the developed tool are available for free download through
https://code.google.com/p/cmater-bioinfo/.

[Software Tool](https://www.dropbox.com/sh/on2g82gtss4zc4k/AADQuW7o7D03pEOOlOtqPdapa?dl=0)
[Supplementary Files](https://www.dropbox.com/sh/ts1gs17tw2vj0f7/AACPP1vwhl0a1YQFgu5WPAePa?dl=0)



---


## PDP-CON: Prediction of domain boundaries in protein sequences using a consensus approach ##

### Piyali Chatterjee <sup>1</sup>, Subhadip Basu <sup>2</sup>, Julian Zubek <sup>3</sup>, Mahantapas Kundu <sup>2</sup>, Mita Nasipuri <sup>2</sup>, Dariusz Plewczynski <sup>3</sup> ###


<sup>1</sup> Department of Computer Science and Engineering, Netaji Subhash Engineering College,Garia, Kolkata – 700152, India

<sup>2</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India

<sup>3</sup> Interdisciplinary Centre for Mathematical and Computational Modeling, University of Warsaw, 5a Street, 02-106 Warsaw, Poland


**ABSTRACT:**
The domain boundary prediction is a crucial task for functional classification of proteins, homology-based protein structure prediction and for high-throughput structural genomics. A novel consensus based technique is applied here to predict domain regions in a protein sequence by finding ordered regions along protein chain. Each amino acid is represented using a set of physico-chemical properties. Six different classifiers, namely, Decision tree, Gaussian naïve Bayes, Linear Discriminant analysis, Support Vector Machine classifier, Random Forest Classifier and Multi-layer perceptron are explored for accurate prediction of domain regions by training on the curated dataset obtained from the CATH database.   The software is tested on proteins of CASP-6, CASP-8, CASP-9 and CASP-10 targets in order to evaluate its prediction accuracy using three-fold cross validation experiments. Finally, a consensus approach is used to combine results of the classifiers obtained through the cross-validation experiments. The recall, precision scores achieved by PDP-1-star, 2-star and 3-star are 0.98 and 0.89 on average for prediction of CASP targets. The overall accuracy and F-scores of PDP-Cons methods are 0.89 and 0.91. The dataset and the supplementary materials are available at https://code.google.com/p/cmater-bioinfo/ for academic use.

[Supplementary Documents](https://www.dropbox.com/sh/4c3tf5vz5f5yfpd/AADt5Z_jZA8I4IQNrzPOyif9a?dl=0)



---


## JUPred-1: A web-server for accurate prediction of protein secondary structure and relative solvent accessibility from primary sequence information ##

### Sagnik Banerjee<sup>1</sup>, Piyali Chatterjee <sup>2</sup>, Mita Nasipuri <sup>1</sup>, Subhadip Basu <sup>1</sup> ###

<sup>1</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India

<sup>2</sup> Department of Computer Science and Engineering, Netaji Subhash Engineering College,Garia, Kolkata – 700152, India


**ABSTRACT:**
JUPred-1 (www.cmaterju.org/PSSM.aspx) offers a web-service for prediction of protein secondary structure (PSS) and relative solvent accessibility (RSA) from the primary sequence. The three-class PSS prediction performance (AUC) is obtained as 0.82, 0.81 and 0.81 for the benchmark CASP proteins (9, 10, 11) respectively. The two-class RSA prediction system with 25% accessibility threshold achieves AUC of 0.79, 0.79 and 0.78 for three sets of CASP targets respectively. For ~12-18% benchmark proteins we achieve best prediction results in comparison to the available web-services.

[PSS Supplementary File](https://www.dropbox.com/s/gotna95orv4ipmj/PSS_supplementary.xlsx?dl=0)
[RSA Supplementary File](https://www.dropbox.com/s/ajc7nyl10rqmz8j/RSA_supplementary.xlsx?dl=0)
[JUPred-1 Web Server ](http://93.188.165.199/index.php)



---


## Protein-Protein interaction site prediction in Homo sapiens and E. coli using an interaction-affinity based membership function in Fuzzy SVM ##

### Brijesh Kumar Sriwastava <sup>1</sup>, Subhadip Basu <sup>2</sup>, Ujjwal Maulik <sup>2</sup> ###


<sup>1</sup> Department of Computer Science and Engineering, Government College of Engineering and Leather Technology, Kolkata-700098,India

<sup>2</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India


**ABSTRACT:**
Protein–protein interaction (PPI) site prediction aids to ascertain the interface residues that participate in interaction processes. Fuzzy support vector machine (F-SVM) is proposed as an effective method to solve this problem and we have shown that the performance of the classical SVM can further be improved with the use of a custom-designed fuzzy membership function. We have evaluated the performances of both SVM and F-SVM on the PPI databases of the Homo sapiens and E. coli organisms and estimated the statistical significance of the developed method over classical SVM and other fuzzy membership based SVM methods available in the literature. Our membership function uses the residue-level interaction affinity scores for each pair of positive and negative sequence fragments. The average area under ROC curve (AUC) performances on the test samples in 10-fold cross validation experiment are measured as 79.94% and 80.48% for the Homo sapiens and E. coli organisms respectively. For independent test dataset, AUC scores are obtained as 76.59% and 80.17% for the two organisms respectively. In almost all cases, the developed F-SVM method improves the performances obtained by the corresponding classical SVM and the other classifiers, available in the literature.

[Supplementary.docx](https://www.dropbox.com/s/bbqwrzyw0svlxyc/Supplementary%20Document.docx?dl=0)
[Database](https://www.dropbox.com/sh/zn5akbzaw3jfsn1/AABgUQKDSabSH_rJKbNfT1zAa?dl=0)
[FSVM software](https://www.dropbox.com/sh/dd38g4n91vf10p4/AABF-2j-e7JIeMhOjFM0yFVna?dl=0)

**Citation:**
Journal of Biosciences (in press).


---


## FunPred-1: Protein Function Prediction from Protein Interaction Network Using Neighborhood Analysis ##

### Sovan Saha <sup>1</sup>, Piyali Chatterjee <sup>2</sup>, Subhadip Basu <sup>3</sup>, Mahantapas Kundu <sup>3</sup>, Mita Nasipuri <sup>3</sup> ###

<sup>1</sup> Department of Computer Science and Engineering, Dr. Sudhir Chandra Sur Degree Engineering College, Dumdum, Kolkata-700 074, India

<sup>2</sup> Department of Computer Science and Engineering, Netaji Subhash Engineering College,Garia, Kolkata – 700152, India

<sup>3</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India


**ABSTRACT:**
Proteins are responsible for all biological activities in a living object. With the advent of genome sequencing projects for different organisms, large amounts of DNA and protein sequence data are now available, whereas their biological functions are still un-annotated in most of the cases. Unknown function of such an un-annotated protein may be derived from its neighbors in a protein interaction network. Two new methods are proposed in this work to predict protein functions from the network neighborhood properties. The first method, FunPred 1.1, uses a combination of three simple-yet-effective scoring techniques: neighborhood ratio, proteins’ path connectivity and relative functional similarity. FunPred 1.2 applies a heuristic approach using edge clustering coefficient to reduce the search space by identifying densely connected neighborhood regions. The overall accuracy achieved in FunPred 1.2 over 8 functional groups involving hetero-interactions in 650 Yeast proteins is around 87%, which is higher than FunPred 1.1 and many of the state-of-the-art protein function prediction methods available in literature. The train-test datasets and the complete source code of the developed software are now freely available at http://code.google.com/p/cmater-bioinfo/.

[Supplementary Files](https://www.dropbox.com/sh/jvtqanwl887r8rq/AABIQ2HtCMe3PQv3h2YvR4Iea)
[FunPred-1 Source ](https://www.dropbox.com/sh/pwur5qlabaspp65/AAD5CXAyfjs4VqdlxMPe0EUea)

[PubMed link](http://www.ncbi.nlm.nih.gov/pubmed/25424913)

**Citation:**
Saha, Sovan, Piyali Chatterjee, Subhadip Basu, Mahantapas Kundu, and Mita Nasipuri. "FunPred-1: Protein function prediction from a protein interaction network using neighborhood analysis." Cellular & Molecular Biology Letters (2014): 1-17.


---


## Predicting protein-protein interaction sites with a novel membership based Fuzzy SVM classifier ##

### Brijesh Kumar Sriwastava <sup>1</sup>, Subhadip Basu <sup>2</sup>, Ujjwal Maulik <sup>2</sup> ###


<sup>1</sup> Department of Computer Science and Engineering, Government College of Engineering and Leather Technology, Kolkata-700098,India

<sup>2</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India


**ABSTRACT:**
Predicting residues that participate in protein–protein interactions (PPI) helps to identify, which amino acids are located at the interface. In this paper we show that the performance of the classical support vector machine (SVM) algorithm can further be improved with the use of a custom-designed fuzzy membership function, for the partner-specific PPI interface prediction problem. We evaluated the performances of both classical SVM and fuzzy SVM (F-SVM) on the PPI databases of three different model proteomes of Homo sapiens, Escherichia coli and Saccharomyces Cerevisiae and calculated the statistical significance of the developed F-SVM over classical SVM algorithm. We also compared our performance with the available state-of-the-art fuzzy methods in this domain and observed significant performance improvements. To predict interaction sites in protein complexes, local composition of amino acids together with their physico-chemical characteristics are used, where the F-SVM based prediction method exploits the membership function for each pair of sequence fragments. The average F-SVM performance (area under ROC curve) on the test samples in 10-fold cross validation experiment are measured as 77.07%, 78.39%, and 74.91% for the aforementioned organisms respectively. Performances on independent test sets are obtained as 72.09%, 73.24% and 82.74% respectively. The software is available for free download from http://code.google.com/p/cmater-bioinfo.

[Supplementary.docx](https://www.dropbox.com/s/qhc38e9omunkxfz/Supplementary%20Document_final.docx)
[FSVM-PPI Software](https://www.dropbox.com/sh/b3wdcop582afr1b/AAAIKLwTpe0yD96J4lloSjWia)

**Citation:**
IEEE/ACM Transactions on Computational Biology and Bioinformatics (in press).



---


## PPIcons: identification of protein-protein interaction sites in selected proteomes using local sequence segments ##

### Brijesh Kumar Sriwastava <sup>1</sup>, Subhadip Basu <sup>2</sup>, Ujjwal Maulik <sup>2</sup>, Dariusz Plewczynski <sup>3</sup> ###


<sup>1</sup> Department of Computer Science and Engineering, Government College of Engineering and Leather Technology, Kolkata-700098,India

<sup>2</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India

<sup>3</sup> Interdisciplinary Centre for Mathematical and Computational Modeling, University of Warsaw, 5a Street, 02-106 Warsaw, Poland


**ABSTRACT:**
The physico-chemical properties of interaction interfaceshave a crucial role in characterization of protein–protein interactions (PPI). In silico prediction of participating amino acids helps to suggest interface residues for further experimental verification using muta-tional analysis, or inhibition studies by screening library of ligands against given protein. Given the unbound structure of a protein and the fact that it forms a complex with another known protein, the objective of this work is to identify the residues that are involved in the interaction. We attempt to predict interaction sites in protein complexes using local composition of amino acids together with theirphysico-chemical characteristics. The local sequence segments (LSS) are dissected from the proteins sequences using sliding window of 21 amino acids. The list of LSSs is passed to the support vector machine (SVM) predictor, which identifies interacting residue pairs considering their inter-atom distances. We have analyzed three different model proteomes of Escherichia coli, Saccharomyces Cerevisiae and Homo sapiens, where the numbers of considered hetero-complexes are equal to 40, 123 and 33 respectively. Moreover, the unified multi-organism PPI meta-predictor is also developed under the current work by combining the training databases of above organisms. The PPIcons interface residues prediction method exploits the consensus between multiple SVM classifiers, with the high performance on the test samples, as measured by area under ROC curve(AUC) equal to 0.82, 0.75,0.74 and 0.77for the aforementioned organisms and the meta-predictor respectively.

[Supplementary Documents](http://code.google.com/p/cmater-bioinfo/downloads/detail?name=PPIcons_Supl.rar&can=2&q=)
[Database and the Predictor Software](http://code.google.com/p/cmater-bioinfo/downloads/detail?name=PPIcons.zip&can=2&q=)

[PubMed link](http://www.ncbi.nlm.nih.gov/pubmed/23729008)

**Citation:**
Sriwastava, Brijesh K., Subhadip Basu, Ujjwal Maulik, and Dariusz Plewczynski. "PPIcons: identification of protein-protein interaction sites in selected organisms." Journal of molecular modeling (2013): 1-12.


---


## PSP\_MCSVM: brainstorming consensus prediction of protein secondary structures using two-stage multiclass support vector machines ##

### Piyali Chatterjee <sup>1</sup>, Subhadip Basu <sup>2</sup>, Mahantapas Kundu <sup>2</sup>, Mita Nasipuri <sup>2</sup> and Dariusz Plewczynski <sup>3</sup> ###


<sup>1</sup> Department of Computer Science and Engineering, Netaji Subhash Engineering College,Garia, Kolkata – 700152, India

<sup>2</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India

<sup>3</sup> Interdisciplinary Centre for Mathematical and Computational Modeling, University of Warsaw, 5a Street, 02-106 Warsaw, Poland


**ABSTRACT:**
The secondary structure prediction is a crucial task for understanding the variety of protein structures and performed biological functions. The prediction of secondary structures for new proteins using their amino acids sequences has the fundamental importance in bioinformatics. We propose a novel algorithm for assigning protein secondary structure, which is based on position-specific scoring matrix and exploiting physico-chemical properties of amino acids. Two levels of multi-class support-vector machines are used. In the first network, sequence profiles from PSI-BLAST and physicochemical properties of amino acids are used for local sequence to structure predictions. Three output structural classes are used for representing helix, sheet, and coil. Confidence values for forming helix, sheet and coil that are obtained from the first level network are then used in the second level network for performing structure to structure predictions.  The two level cascaded classifiers (PSP\_MCSVM) are designed to predict secondary structure by training 126 proteins from RS126 dataset using three-fold cross validation. The method is also tested on target proteins of Critical Assessment of Protein Structure Prediction Experiment (CASP) to measure its prediction accuracy. It achieves better results than PSIPRED, JPRED, and DSC for some of the target proteins.

[Supplementary Documents](https://code.google.com/p/cmater-bioinfo/downloads/detail?name=Supplementary_revised5.xls&can=2&q=#makechanges)
[Prediction Software](https://code.google.com/p/cmater-bioinfo/downloads/detail?name=PSP_MCSVM_source.rar&can=2&q=#makechanges)

[PubMed link](http://www.ncbi.nlm.nih.gov/pubmed/21594694)

**Citation:**
Chatterjee, Piyali, Subhadip Basu, Mahantapas Kundu, Mita Nasipuri, and Dariusz Plewczynski. "PSP\_MCSVM: brainstorming consensus prediction of protein secondary structures using two-stage multiclass support vector machines." Journal of molecular modeling 17, no. 9 (2011): 2191-2201.


---


## PPI\_SVM: prediction of protein-protein interactions using machine learning, domain-domain affinities and frequency tables ##

### Piyali Chatterjee <sup>1</sup>, Subhadip Basu <sup>2</sup>, Mahantapas Kundu <sup>2</sup>, Mita Nasipuri <sup>2</sup> and Dariusz Plewczynski <sup>3</sup> ###


<sup>1</sup> Department of Computer Science and Engineering, Netaji Subhash Engineering College,Garia, Kolkata – 700152, India

<sup>2</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India

<sup>3</sup> Interdisciplinary Centre for Mathematical and Computational Modeling, University of Warsaw, 5a Street, 02-106 Warsaw, Poland


**ABSTRACT:**
Protein-protein interactions (PPI) control most of the biological processes in a living cell. In order to fully understand protein functions, a knowledge of protein-protein interactions is necessary. Prediction of PPI is challenging, especially when the three-dimensional structure of interacting partners is not known. Recently, a novel prediction method was proposed by exploiting physical interactions of constituent domains. We propose here a novel knowledge-based prediction method, namely PPI\_SVM, which predicts interactions between two protein sequences by exploiting their domain information. We trained a two-class support vector machine on the benchmarking set of pairs of interacting proteins extracted from the Database of Interacting Proteins (DIP). The method considers all possible combinations of constituent domains between two protein sequences, unlike most of the existing approaches. Moreover, it deals with both single-domain proteins and multi domain proteins; therefore it can be applied to the whole proteome in high-throughput studies. Our machine learning classifier, following a brainstorming approach, achieves accuracy of 86%, with specificity of 95%, and sensitivity of 75%, which are better results than most previous methods that sacrifice recall values in order to boost the overall precision. Our method has on average better sensitivity combined with good selectivity on the benchmarking dataset. The PPI\_SVM source code, train/test datasets and supplementary files are available freely in the public domain at: http://code.google.com/p/cmater-bioinfo/.

[Supplementary Documents](https://code.google.com/p/cmater-bioinfo/downloads/detail?name=proteininteraction.rar&can=2&q=#makechanges)
[Readme file](https://code.google.com/p/cmater-bioinfo/downloads/detail?name=ReadMe_PPI_SVM.txt&can=2&q=#makechanges)

[PubMed link](http://www.ncbi.nlm.nih.gov/pubmed/21442443)

**Citation:**
Chatterjee, Piyali, Subhadip Basu, Mahantapas Kundu, Mita Nasipuri, and Dariusz Plewczynski. "PPI\_SVM: Prediction of protein-protein interactions using machine learning, domain-domain affinities and frequency tables." Cellular & Molecular Biology Letters 16, no. 2 (2011): 264-278.


---


## AMS 4.0: consensus prediction of post-translational modifications in protein sequences ##

### Dariusz Plewczynski <sup>1</sup>, Subhadip Basu <sup>2</sup>, Indrajit Saha <sup>2</sup> ###

<sup>1</sup> Interdisciplinary Centre for Mathematical and Computational Modeling, University of Warsaw, 5a Street, 02-106 Warsaw, Poland

<sup>2</sup> Department of Computer Science and Engineering, Jadavpur University, Kolkata – 700032, India

**ABSTRACT:**
We present here the 2011 update of the AutoMotif Service (AMS 4.0) that predicts the wide selection of 88 different types of the single amino acid post-translational modifications (PTM) in protein sequences. The selection of experimentally confirmed modifications is acquired from the latest UniProt and Phospho.ELM databases for training. The sequence vicinity of each modified residue is represented using amino acids physico-chemical features encoded using high quality indices (HQI) obtaining by automatic clustering of known indices extracted from AAindex database. For each type of the numerical representation, the method builds the ensemble of Multi-Layer Perceptron (MLP) pattern classifiers, each optimising different objectives during the training (for example the recall, precision or area under the ROC curve (AUC)). The consensus is built using brainstorming technology, which combines multi-objective instances of machine learning algorithm, and the data fusion of different training objects representations, in order to boost the overall prediction accuracy of conserved short sequence motifs. The performance of AMS 4.0 is compared with the accuracy of previous versions, which were constructed using single machine learning methods (artificial neural networks, support vector machine). Our software improves the average AUC score of the earlier version by close to 7 % as calculated on the test datasets of all 88 PTM types. Moreover, for the selected most-difficult sequence motifs types it is able to improve the prediction performance by almost 32 %, when compared with previously used single machine learning methods. Summarising, the brainstorming consensus meta-learning methodology on the average boosts the AUC score up to around 89 %, averaged over all 88 PTM types. Detailed results for single machine learning methods and the consensus methodology are also provided, together with the comparison to previously published methods and state-of-the-art software tools. The source code and precompiled binaries of brainstorming tool are available at [http://code.google.com/p/automotifserver/](http://code.google.com/p/automotifserver/) under Apache 2.0 licensing.

[PubMed link](http://www.ncbi.nlm.nih.gov/pubmed/22555647)

**Citation:**
Plewczynski, Dariusz, Subhadip Basu, and Indrajit Saha. "AMS 4.0: consensus prediction of post-translational modifications in protein sequences." Amino acids 43.2 (2012): 573-582.


---


## AMS 3.0: prediction of post-translational modifications ##

### Subhadip Basu <sup>1</sup> and Dariusz Plewczynski <sup>2</sup> ###


<sup>1</sup> Department of Computer Science and Engineering, Netaji Subhash Engineering College,Garia, Kolkata – 700152, India

<sup>2</sup> Interdisciplinary Centre for Mathematical and Computational Modeling, University of Warsaw, 5a Street, 02-106 Warsaw, Poland


**ABSTRACT:**

Background

We present here the recent update of AMS algorithm for identification of post-translational modification (PTM) sites in proteins based only on sequence information, using artificial neural network (ANN) method. The query protein sequence is dissected into overlapping short sequence segments. Ten different physicochemical features describe each amino acid; therefore nine residues long segment is represented as a point in a 90 dimensional space. The database of sequence segments with confirmed by experiments post-translational modification sites are used for training a set of ANNs.
Results

The efficiency of the classification for each type of modification and the prediction power of the method is estimated here using recall (sensitivity), precision values, the area under receiver operating characteristic (ROC) curves and leave-one-out tests (LOOCV). The significant differences in the performance for differently optimized neural networks are observed, yet the AMS 3.0 tool integrates those heterogeneous classification schemes into the single consensus scheme, and it is able to boost the precision and recall values independent of a PTM type in comparison with the currently available state-of-the art methods.
Conclusions

The standalone version of AMS 3.0 presents an efficient way to indentify post-translational modifications for whole proteomes. The training datasets, precompiled binaries for AMS 3.0 tool and the source code are available at [http://code.google.com/p/automotifserver](http://code.google.com/p/automotifserver) under the Apache 2.0 license scheme.

[PubMed link](http://www.ncbi.nlm.nih.gov/pubmed/20423529)

**Citation:**
Basu, Subhadip, and Dariusz Plewczynski. "AMS 3.0: prediction of post-translational modifications." BMC bioinformatics 11.1 (2010): 210.

---
