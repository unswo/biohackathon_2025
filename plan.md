# Biohackathon plan

Investigate the feasibility of including GRNs into a CellRank2 kernel

## Background

Binding of earlier TFs may be maintained, resulting in a 'footprint' that represents the earlier developmental history of the cell. It may be possible to use these footprints to identify recover cell lineages, either solo in conjunction with another method.

CellRank2 can combine multiple 'views' of single cell datasets in order to recover genes that drive cell fate transitions. Thus fair I have applied several methods in order to recover 'timekeepers' from ATAC-seq and RNA-seq data. These methods include recovery of somatic mutations, (relative) mitotic age and state inference. During the hackathon I will generate GRNs for the data I am currently working with, and then incorporate these GRNs into a CellRank2 kernel.

## Milestones

### Preparation before hackathon 

* Integrate data using scanpy/muon :heavy_check_mark:

* Review existing work on CellRank2 kernel

* Finalise method selection - presumably scenic+

* If _not_ using scenic+, identify method from literature review

* Generate mamba environment ready for the hackathon and install snakemake pipeline

* (assuming scenic+) prepare pycistopic object from existing muon object.

* Query resolution that GRNs reflect - cell level or cell type level? Presumably runs on an aggregate of cells - would it be better to use cell annotations/leiden/both?

* Generate cisTarget database

* Generate config (yaml) file

* **Run pipeline a week prior to hackathon**


### During hackathon

#### Day 1

(Assuming scenic+)

* Review output of scenic+ (having not worked with scenic+ before, I'm not entirely sure what the outputs look like)

* Explore the data, and relate results back to existing retinal research where possible.

* Generate ideas on how to use these results to order cells - can we use regulon scores? 

* Do the results agree with what was identified in Birthe's paper? Compare results from this dataset to the analysis in Birthe's paper.

#### Day 2

* (Fill this in based on plan generated on the previous day)

#### Day 3

* Wrap up any remaining issues from day 2

* Plan (and write, if time allows) documentation relating to the CellRank 2 kernel

### Stretch goals

* _Complete_ documentation

* Perturbation simulation





