# README: Multi-Modes for Detecting Experimental Measurement Error

Raymond Duch, Denise Laroze, Thomas Robinson and Pablo Beramendi

Last edit: June 2019

## Abstract:
Experiments should be designed to facilitate the detection of experimental measurement error. To this end, we advocate the implementation of identical experimental protocols employing diverse experimental modes.  We suggest iterative non-parametric estimation techniques for assessing the magnitude of heterogeneous treatment effects across these modes.  And we propose two diagnostic strategies -- measurement metrics embedded in experiments, and measurement experiments -- that help assess whether any observed heterogeneity reflects experimental measurement error.  To illustrate our argument, first we conduct, and analyze results from, four identical interactive experiments in the lab; online with subjects from the CESS lab subject pool; online with an online subject pool; and online with MTurk workers. Secondly, we implement a measurement experiment in India with CESS Online subjects and MTurk workers.


## Contents:
1. **experimental_code** - Instructions and experimental code to run the experiments (both online and lab)
   * Lab code includes: z-Tree scripts and written instructions that were read out load.
   * Online code includes:
   a) Nodegame script
   b) PDF of the instructions that were presented on screen
   c) Authentication script used to limit the re-entry of participants (each subject could participate only once).
2. **data** - CSV exports for each separate experiment:
   * baseline_uk.csv - Lying behaviour lab experiment
   * CESS_Panel_DS_Feb2018.csv - Lying behaviour CESS Online UK experiment
   * lab_online_sync_edited.csv  - Lying behaviour lab online experiment
   * Mturk_DS_Sept2017.csv - Lying behaviour Mturk online experiment
   * mturk_exp.csv - India vignette experiment Mturk subjects
   * mturk_exp_incentivised.csv - India vignette experiment Mturk subejcts with incentivisation
   * co_exp.csv - India vignette experiment  CESS Online subjects

3. **replication_scripts** - All R code for generation of statistics, tables and figures.
   * main_replication.R - main replication file
   * simulation_replication.R -  replication material for Figure 1
   * indian_vignette_replication.R - replication material for experimental results incl. Tables 3, B4, B5, and B6
4. **screenshots** - of lab and online experiments
5. **tables** - .tex files of tables in main article and appendix
6. **figures** - image files of figures in main article and appendix
7. **replication_guide.md** - further information on reproducing the analysis in this article, including package dependencies/versions.
