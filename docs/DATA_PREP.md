# Data Preparation Guide

## HD-Map Data

The HD-Map data for each town is available on Hugging Face:

- **Hugging Face Dataset**: [Bench2Drive-Map](https://huggingface.co/datasets/rethinklab/Bench2Drive-Map/tree/main)

This dataset contains high-definition map files for all towns used in Bench2Drive. Each town has a corresponding `Town[ID]_HD_map.npz` file containing road information, lane markings, and topology data.

### Available Map Files

The dataset includes HD map files for the following towns:

- Town01_HD_map.npz (7.61 MB)
- Town02_HD_map.npz (3.4 MB)
- Town03_HD_map.npz (22.4 MB)
- Town04_HD_map.npz (46.2 MB)
- Town05_HD_map.npz (32.6 MB)
- Town06_HD_map.npz (25.2 MB)
- Town07_HD_map.npz (12.7 MB)
- Town10HD_HD_map.npz (7.09 MB)
- Town11_HD_map.npz (1.62 GB)
- Town12_HD_map.npz (1.41 GB)
- Town13_HD_map.npz (1.9 GB)
- Town15_HD_map.npz (84.8 MB)

### Download Instructions

You can download the HD map files using the Hugging Face CLI:

```bash
huggingface-cli download --repo-type dataset rethinklab/Bench2Drive-Map --local-dir Bench2Drive-Maps
```

Or download directly from the [Hugging Face dataset page](https://huggingface.co/datasets/rethinklab/Bench2Drive-Map/tree/main).

### Data Structure

For detailed information about the HD-Map data structure, please refer to the [HD-Map Data Structure section](anno.md#hd-map-data-structure) in `anno.md`.

### Alternative Mirror

If you have trouble accessing Hugging Face, you can use the mirror site:
- Mirror link: https://hf-mirror.com/datasets/rethinklab/Bench2Drive-Map

