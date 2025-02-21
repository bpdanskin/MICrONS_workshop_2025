# MICrONS workshop: Brain Stimulation at the Microscopic Scale, 23 February 2025

Offered in participation with __The 6th International Brain Stimulation Conference in Kobe Japan__. [See conference program and details here](https://neuromodec.org/events/brain-stimulation-at-the-microscopic-scale-multiscale-models-and-cellular-studies-february-2025/)

![image](https://github.com/user-attachments/assets/fefdf6a7-1fbc-4640-b22e-7ba3d46857a7)


## MICrONS dataset tutorial: Functional connectomics spanning multiple areas of mouse visual cortex
Presented by Bethanny Danskin

The MICrONS dataset is a large functional connectomics dataset with dense calcium imaging and electron microscopy based cell reconstruction over one cubic millimeter of mouse visual cortex. All neurons were automatically reconstructed and all synapses detected.
Subsequent proofreading in this volume yielded reconstructions that include complete dendritic trees for all ~70 thousand neurons as well the local and inter-areal axonal projections of a subset of neurons that map up to thousands of cell-to-cell connections per neuron.
Functional measurements and connectivity can be related for ~12 thousand neurons which were coregistered between the calcium and EM volumes.
In this tutorial, we introduce the dataset, as well as both interactive and programmatic tools to analyze it.

The tutorial will contain examples of how to access: annotations, connectivity, segmentation, meshes, and neuron-skeletons.

Manuscript describing the dataset: [Functional connectomics spanning multiple areas of mouse visual cortex](https://www.biorxiv.org/content/10.1101/2021.07.28.454025v3.abstract)

[Video of the presentation](https://drive.google.com/file/d/1X5rFmj5ledWjejD9Qs1GW817y4V1pr0G/view?usp=sharing) 

## Dataset introduction

### Programmatic Access: using the Connectome Annotation Versioning Engine (CAVE) ecosystem

This repository includes curated Data Access examples and tutorials. To work in your local environment, clone the repo and create a new virtual environment withe the _environment_microns2025.yml_ file. 

Aleternately, you can run each notebook in __Google Colab__ by accessing the github urls, or clicking the following links:
1. [Programmatic Access](https://colab.research.google.com/github/https://github.com/bpdanskin/MICrONS_workshop_2025/blob/main/tutorials_colab/ProgrammaticAccess_colab.ipynb)
2. [Downloading Meshes](https://colab.research.google.com/github/https://github.com/bpdanskin/MICrONS_workshop_2025/blob/main/tutorials_colab/MeshAccess_colab.ipynb)
3. [Downloading Skeletons](https://colab.research.google.com/github/https://github.com/bpdanskin/MICrONS_workshop_2025/blob/main/tutorials_colab/SkeletonAccess_colab.ipynb)

(requires GMail or other Google-related account). Google Colab lets you run executable notebooks in the cloud with minimal setup.

[Additional tools for programmatic access](https://docs.google.com/presentation/d/1sTDuqfxR1mvqd3uD9Lrq4yLMBwTC6H9UcbmtHG22yn0/edit?usp=sharing)

#### Neuroglancer: data visualization and exploration

Neuroglancer navigation instructions at [MICrONS Explorer Tools](https://www.microns-explorer.org/ngl-instructions)

More curated neuroglancer examples available at [the MICrONS Explorer Gallery](https://www.microns-explorer.org/gallery-mm3)

#### DashApps: interactive online analysis

Browse the data tables, such as cell type classifications with the [Table Viewer](https://minnie.microns-daf.com/dash/datastack/minnie65_public/apps/table_viewer/?datastack=%22minnie65_public%22).

Query and visualize synaptic connectivity of neurons with the [Connectivity Viewer](https://minnie.microns-daf.com/dash/datastack/minnie65_public/apps/connectivity/?anno-id=%22%22&id-type=%22root_id%22&mat-version=943&cell-type-table-dropdown=%22%22&datastack=%22minnie65_public%22)


#### Further reading relevant to the demonstration

Cell Type Model: [Perisomatic Features Enable Efficient and Dataset Wide Cell-Type Classifications Across Large-Scale Electron Microscopy Volumes](https://www.biorxiv.org/content/10.1101/2022.07.20.499976v2)

Inhibitory Connectivity: [Cell-type-specific inhibitory circuitry from a connectomic census of mouse visual cortex](https://www.biorxiv.org/content/10.1101/2023.01.23.525290v3)

Data Infrastructure: [CAVE: Connectome Annotation Versioning Engine](https://www.biorxiv.org/content/10.1101/2023.07.26.550598v1)

### Dataset documentation

More complete documentation that includes the above information as well as guides to interacting with meshes, skeletons, and imagery, [can be found online at the MICrONS Tutorial webpages](https://alleninstitute.github.io/microns_tutorial/em_01_background.html).

### Credits

Tutorial material prepared by Bethanny Danskin, Casey Schneider-Mizell, Sven Dorkenwald and Forrest Collman.
Full MICrONs project credits can be found at [MICrONs Explorer](https://www.microns-explorer.org).
