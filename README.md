# Deep Learning Models used for Off-target predicitons in CRISPR-Cas 9 gene editing
This is a an ensemble learning framework which synergizes multiple tools with genomic annotations together to predict the off-target activities of CRISPR/Cas9 in different combinations. 

# PREREQUISITE
SynergizingCRISPR was conducted by using Python 2.7.13 version and TensorFLow v1.4.1. 
Following Python packages should be installed:
<ul>
<li><p>scipy</p></li>
<li><p>numpy</p></li>
<li><p>pandas</p></li>
<li><p>scikit-learn</p></li>
<li><p>TensorFlow</p></li>
</ul>


# CONTAINS:
<ul>
<li><p>main.ipynb : Python script to run SynergizingCRISPR and get griphics and results</p></li>
<li><p>chromatin annotations.R : R script to get the ChromHMM and Segway</p></li>
<li><p>conservation.R : R script to get the PhyloP and PhastCons</p></li>
<li><p>Crispr_Data.csv : it stores the raw data including DNA sequences, sgRNA sequences, and features</p></li>
</ul>

---------------------------------------
Jiecong Lin

jieconlin3-c@my.cityu.edu.hk

January 27 2018
