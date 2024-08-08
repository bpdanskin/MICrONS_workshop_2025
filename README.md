# MICrONS workshop for NeuroAI Conference, 8 August 2024

Offered in participation with the Neuroscience and Artificial Intelligence Conference at the University of Washington. [See conference program and details here](https://www.neuroaiseattle.com/))

![neuro-ai](https://github.com/user-attachments/assets/2e41f315-9db4-4099-b53d-16c5d2b092be)

## MICrONS dataset tutorial: Functional connectomics spanning multiple areas of mouse visual cortex
Presented by Bethanny Danskin and Casey Schneider-Mizell.

The MICrONS dataset is a large functional connectomics dataset with dense calcium imaging and electron microscopy based cell reconstruction of a millimeter scale volume.
All neurons were automatically reconstructed and all synapses detected.
Subsequent proofreading in this volume yielded reconstructions that include complete dendritic trees for all ~70 thousand neurons as well the local and inter-areal axonal projections of a subset of neurons that map up to thousands of cell-to-cell connections per neuron.
Functional measurements and connectivity can be related for ~12 thousand neurons which were coregistered between the calcium and EM volumes.
In this tutorial, we introduce the dataset, as well as both interactive and programmatic tools to analyze it.
The tutorial will contain exercises for hands on work and time to explore the dataset on your own laptop.   

Manuscript describing the dataset: [Functional connectomics spanning multiple areas of mouse visual cortex](https://www.biorxiv.org/content/10.1101/2021.07.28.454025v3.abstract)

### Dataset introduction

#### Slides

Introductory presentation: [MICrONS Overview 2024](https://docs.google.com/presentation/d/14QBz8wXxm8ubIoGiYYQGwlPiM0bBJgpH-eOxlLS3toQ/edit?usp=sharing)


#### Neuroglancer: data visualization and exploration

Click on the links below to view the prepared neuroglancer states for the walk through. **Use any google profile to login when prompted.**

1. Neuroglancer introduction: [navigation and fundamentals](https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/6541269837807616)
2. Neuroglancer advanced: [view multiple cells and segment properties](https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/5449595451604992)
3. Neuroglancer annotations: [make and export notes as you work](https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/5100449909702656)

More curated neuroglancer examples available at [the MICrONS Explorer Gallery](https://www.microns-explorer.org/gallery-mm3)

#### DashApps: interactive online analysis

Browse the data tables, such as cell type classifications with the [Table Viewer](https://minnie.microns-daf.com/dash/datastack/minnie65_public/apps/table_viewer/?datastack=%22minnie65_public%22).

Query and visualize synaptic connectivity of neurons with the [Connectivity Viewer](https://minnie.microns-daf.com/dash/datastack/minnie65_public/apps/connectivity/?anno-id=%22%22&id-type=%22root_id%22&mat-version=943&cell-type-table-dropdown=%22%22&datastack=%22minnie65_public%22)

### Programmatic Access: using the Connectome Annotation Versioning Engine (CAVE) ecosystem

Follow the tutorial for [CAVE setup and quickstart here](https://alleninstitute.github.io/microns_tutorial/programmatic_access/em_py_01_caveclient_setup.html)

There are two options for following the tutorial and doing the exercises:
1. Local: [Create a new conda environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands) using Python 3.11 and `pip install caveclient` into it as well as your favorite notebook package (e.g. `pip install jupyter`).
2. Online: Go to the `ProgrammaticAccess.ipynb` notebook in [Google Colab](https://colab.research.google.com/github/AllenInstitute/MICrONS_workshop_neuroai2024/blob/main/tutorials/ProgrammaticAccess.ipynb) (requires GMail or other Google-related account). Google Colab lets you run executable notebooks in the cloud with minimal setup.

#### Further reading relevant to the demonstration

Cell Type Model: [Perisomatic Features Enable Efficient and Dataset Wide Cell-Type Classifications Across Large-Scale Electron Microscopy Volumes](https://www.biorxiv.org/content/10.1101/2022.07.20.499976v2)

Inhibitory Connectivity: [Cell-type-specific inhibitory circuitry from a connectomic census of mouse visual cortex](https://www.biorxiv.org/content/10.1101/2023.01.23.525290v3)

Data Infrastructure: [CAVE: Connectome Annotation Versioning Engine](https://www.biorxiv.org/content/10.1101/2023.07.26.550598v1)

### Dataset documentation

More complete documentation that includes the above information as well as guides to interacting with meshes, skeletons, and imagery, [can be found online at the MICrONS Tutorial webpages](https://alleninstitute.github.io/microns_tutorial/em_01_background.html).

### Credits

Tutorial material by Bethanny Danskin, Casey Schneider-Mizell, Sven Dorkenwald and Forrest Collman.
Full MICrONs project credits can be found at [MICrONs Explorer](https://www.microns-explorer.org).
