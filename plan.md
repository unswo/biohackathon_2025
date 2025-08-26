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

* Generate mamba environment ready for the hackathon

* (assuming scenic+) prepare pycistopic object from existing muon object.

* Query resolution that GRNs reflect - cell level or cell type level?


### During hackathon

* 



