# Data generated and additional visualizations from  [Pantoja et al. 2022](https://ui.adsabs.harvard.edu/abs/2022MNRAS.517.3660P/abstract)

## Clustering

As mentioned in the paper, the dimensionality reduction is done with __UMAP__ for both visualizing the data (to __2D__) and clustering (to __20D__). The visualizations are used to guide the clustering analysis and are nice to see the final results.

## Generated Data
The data resulting from the clustering for each of the catalogs is stored in /datasets/datasets.zip

Each file has the id of each star, the position in the first UMAP embedding  __*(X_0,Y_0)*__  and the position in the second UMAP (of a cluster) __*(X_1,Y_1)*__ . The column __*labels_L0*__ corresponds to the assigned labels from the first clustering level, and __*labels*__ corresponds to the assigned label for the second and third clustering levels.

# Visualizations

## Catalina Surveys (CSSCVS)

[//]: # (1)

<h3 align="center">
  UMAP visualization of CSSCVS (GROUND TRUE classes)
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/d356eac1925576552a3800f4573f81a22b14009f/visualizations/CSSCVS_viz.pdf.png" width="720" title="Visualization of CSSCVS">
</p>

[//]: # (2)

<h3 align="center">
  UMAP visualization of first pass of HDBSCAN clustering on CSSCVS
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/603b7a9b00775a9d9379debcc1edd3419f515d98/visualizations/csscvs_l1.gif" width="500" title="Visualization of CSSCVS">
</p>

[//]: # (3)

<h3 align="center">
  UMAP visualization of CSSCVS cluster C12 (GROUND TRUE classes)
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/b8f068caf9d3663710ad02db08a138ed3e2ccb08/visualizations/CSSCVS_C12_viz.pdf.png" width="500" title="Visualization of cluster C12">
</p>

[//]: # (4)

<h3 align="center">
  UMAP visualization of the results of HDBSCAN clustering on cluster C12
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/603b7a9b00775a9d9379debcc1edd3419f515d98/visualizations/csscvs_c12.gif" width="500" title="Visualization of cluster C12">
</p>

## Gaia DR2 (GDR2CVS)

[//]: # (1)

<h3 align="center">
  UMAP visualization of GDR2CVS (GROUND TRUE classes)
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/d356eac1925576552a3800f4573f81a22b14009f/visualizations/GDR2CVS_viz.pdf.png" width="720" title="Visualization of GDR2CVS">
</p>

[//]: # (2)

<h3 align="center">
  UMAP visualization of first pass of HDBSCAN clustering on GDR2CVS
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/603b7a9b00775a9d9379debcc1edd3419f515d98/visualizations/gdr2cvs_l1.gif" width="500" title="Visualization of GDR2CVS">
</p>

[//]: # (3)

<h3 align="center">
  UMAP visualization of GDR2CVS cluster C13 (GROUND TRUE classes)
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/603b7a9b00775a9d9379debcc1edd3419f515d98/visualizations/GDR2CVS_C13_viz.pdf.png" width="500" title="Visualization of cluster C13">
</p>

[//]: # (4)

<h3 align="center">
  UMAP visualization of the results of HDBSCAN clustering on cluster C13
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/603b7a9b00775a9d9379debcc1edd3419f515d98/visualizations/gdr2cvs_c13.gif" width="500" title="Visualization of cluster C13 clustering">
</p>

## OGLE-III (OCVS)


[//]: # (1)

<h3 align="center">
  UMAP visualization of OCVS (GROUND TRUE classes)
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/c06b83f6c0a9c040686cdbc651f06e969f3f9bd6/visualizations/OCSV_viz.pdf.png" width="720" title="Visualization of OCVS">
</p>

[//]: # (2)

<h3 align="center">
  UMAP visualization of first pass of HDBSCAN clustering on OCVS
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/c06b83f6c0a9c040686cdbc651f06e969f3f9bd6/visualizations/ocvs_l1.gif" width="500" title="Visualization of OCVS clustering">
</p>

[//]: # (3)

<h3 align="center">
  UMAP visualization of OCVS cluster C4 (GROUND TRUE classes)
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/c06b83f6c0a9c040686cdbc651f06e969f3f9bd6/visualizations/OCVS_C4_viz.pdf.png" width="500" title="Visualization of cluster C4">
</p>

[//]: # (4)

<h3 align="center">
  UMAP visualization of the results of HDBSCAN clustering on cluster C4
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/c06b83f6c0a9c040686cdbc651f06e969f3f9bd6/visualizations/ocvs_c4.gif" width="500" title="Visualization of cluster C13 clustering">
</p>


[//]: # (5)

<h3 align="center">
  UMAP visualization of OCVS cluster C5 (GROUND TRUE classes)
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/c06b83f6c0a9c040686cdbc651f06e969f3f9bd6/visualizations/OCVS_C5_viz.pdf.png" width="500" title="Visualization of cluster C5">
</p>

[//]: # (6)

<h3 align="center">
  UMAP visualization of the results of HDBSCAN clustering on cluster C5
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/c06b83f6c0a9c040686cdbc651f06e969f3f9bd6/visualizations/ocvs_c5.gif" width="500" title="Visualization of cluster C5 clustering">
</p>


[//]: # (7)

<h3 align="center">
  UMAP visualization of OCVS cluster C8 (GROUND TRUE classes)
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/c06b83f6c0a9c040686cdbc651f06e969f3f9bd6/visualizations/OCVS_C8_viz.pdf.png" width="500" title="Visualization of cluster C8">
</p>

[//]: # (8)

<h3 align="center">
  UMAP visualization of the results of HDBSCAN clustering on cluster C5
</h3>

<p align="center">
  <img src="https://github.com/rdpantoja/clustering_variable_stars_2022/blob/c06b83f6c0a9c040686cdbc651f06e969f3f9bd6/visualizations/ocvs_c8.gif" width="500" title="Visualization of cluster C5 clustering">
</p>
