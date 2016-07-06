---
title: "vignette"
author: "Elizabeth Baskin", "Ewy Mathe", "Rick Farouni"
date: "July 6, 2016"
---
<center> <h1>Welcome to ALTRE</h1> </center>
  
ALTRE(ALTered Regulatory Elements) is a software package that streamlines and simplifies the analysis of data generated from genome-wide chromatin accessibility assays such as DHS-seq (a.k.a. Dnase-seq), FAIRE-seq, ATAC-seq, and THS-seq. The analysis workflow consists of eight steps as displayed in the sidebar.

Chromatin accessibility data maps the location of regulatory elements (REs), including enhancers and promoters.  REs are involved in regulating gene transcription – they control genes and pathways that can be investigated as putative therapeutic targets, or they may serve as targets themselves. Chromatin accessibility assays allows us to identify the location of regulatory regions genome-wide by identifying “open” chromatin (i.e. euchromatin). Identifying regulatory regions that differ between cell types, such as cancerous and noncancerous cell lines and tissues, holds promise for discovering new mechanisms involved in cellular development and disease progression. While assays for defining regulatory regions are well established, currently there are few workflows that guide researchers though the process of analysing data, starting with aligned reads and peak calls, all the way to obtaining meaningful results such as determining a set of putative pathways and genes for further investigation. 

### How to Get Started and Load Data

To get started, please load in a CSV (comma separated values) file in Step 1.
The CSV file should contain the following five columns:
1. full path for the location of the alignment (BAM format) and peak (BED format) files
2. name of bamfiles
3. name of peakfiles
4. sample name
5. replicate number (a minimum of 2 replicates per sample is required to run the workflow)
NOTE: the column names for the CSV file should be "datapath","bamfiles","peakfiles","sample",and "replicate".  An example CSV file can be accessed <a href="https://raw.githubusercontent.com/rfarouni/AltreDataRepo/master/DNaseEncodeWindows.csv" target="_blank">here</a>.

For convenience and package testing purpose, we are providing a restricted subset of the data with one chromosome (i.e. chromosome 21). The data can be found on this <a href="http://rfarouni.github.io/AltreDataRepo/" target="_blank">page</a>. To download the entire data containing all chromosomes, please use a *file download manager* to download the files from the links listed on the same page. After you download the files, please modify the datapath column of the csv file so that all of the rows contain the file paths pointing to the location of the data files on your local machine.

### Questions
For any questions or issues that arise from using ALTRE, please contact XXX



