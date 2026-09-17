# Science - Compiled Scientific Tools Collection

This repository contains pre-compiled binaries of scientific and image-processing tools for multiple operating systems and CPU architectures. The programs are grouped by platform and architecture to make selection and execution straightforward.

## Overview

The `Science` repository provides ready-to-use executables for research and computational work in areas such as scientific imaging, geometric analysis, sequence data processing, and visualization. Each tool is distributed as a platform-specific binary so it can be used directly after downloading the correct version.

## Included Software

The repository currently contains the following tools and programs:

### Cloud2
- 3D visualization and processing of geometric and spatial data
- Import/export of meshes, curves, and point clouds
- Scientific visualization workflows

### Enzyme2
Enzyme2 is a command-line tool for processing and evaluating metabolic networks and microarray data. It uses data from Affymetrix microarray resources, BioCyc pathway/genome databases, and the Gene Ontology (GO) to support the analysis of metabolic pathways and gene-expression information.

Typical capabilities include:
- Metabolic network processing and evaluation
- Analysis of microarray and expression data
- Pathway and ontology integration
- Database-driven research workflows for systems biology
- Compatibility with tools such as Bioconductor, Cytoscape, Galaxy, Mayday, MeV, and Vanted

The software is intended for non-commercial research use and provides a command documentation file (`enzyme2.macro`) that lists available commands when the program is started for the first time.

### FASTA2MAX
- Conversion and processing of FASTA-based sequence data
- Useful for preparing and transforming sequence data

### Hexagon
Hexagon is a scientific analysis and visualization tool for geometric and spatial data. It is intended for workflows involving inspection, transformation, and quantitative analysis of structured scientific datasets.

Typical use cases include:
- Analysis of geometric and spatial data
- Visualization of structured scientific information
- Coordinate-based transformations and measurements
- Research workflows in imaging and computational analysis

### Image
- Basic image processing and analysis tool
- Used for viewing and manipulating image data

### Image3D
- 3D image processing and analysis utility
- Supports volumetric scientific image workflows

### ImageXD
ImageXD is the image display and processing component of the toolkit. It is designed for scientific image inspection, viewing, and manipulation, and is suited to workflows that require detailed examination of image data.

Typical applications include:
- Scientific image display and inspection
- Image processing and enhancement
- Visual review of microscopy or measurement data
- Image-based analysis workflows in research environments

### Launcher
- Tool launcher / application entry point for the toolbox collection

### Master
- Central utility for toolbox access and project execution

### Transform2
- Transformation and coordinate-processing tool
- Useful in geometric and image-based workflows

### VCF Dumper
- Extraction and processing of VCF data
- Used for variant data handling and export

### X11 variants
Several Unix/Linux builds include X11-based variants such as:
- `Xenzyme2`
- `Xhexagon`
- `Ximagexd`

These are the graphical X-based executables intended for systems where the non-X variant is not applicable or sufficient.

## Repository Structure

The repository is organized by architecture and operating system, for example:

```text
Science/
├── README.md
├── x86_64-linux/
├── x86_64-win64/
├── x86_64-darwin/
├── aarch64-linux/
├── arm-linux/
├── i386-linux/
├── x86_64_freebsd/
├── x86_64_avx-linux/
├── ...
└── platform-specific binaries
```

Each directory contains the compiled executables for the corresponding operating system and CPU architecture.

## Supported Platforms

The repository contains binaries for multiple platforms, including:

- Linux
- Windows
- macOS
- FreeBSD
- Solaris
- Android
- other Unix-like environments

Architectures include:

- x86 / x86_64
- ARM / AArch64
- MIPS / MIPSel
- PowerPC / PowerPC64
- SPARC / SPARC64

## Download and Use

1. Select the directory matching your OS and architecture.
2. Download the relevant binary or archive.
3. On Unix-like systems, make the file executable if required:

```bash
chmod +x binary_name
```

4. Run the program from the terminal or by double-clicking it on Windows.

## Important Note

This repository contains the compiled tools listed above. It does not include unrelated projects such as Didiwiki or Gordon1966, and those names have been removed from the current project description.

## License and Source

The tools in this repository are distributed as compiled binaries. Their source code and licensing terms may be available in the respective upstream projects, if applicable.

## Contact

For questions or issues related to this repository, please refer to the maintainer and project pages associated with the original software.

---

Repository: https://github.com/heikostark/Science
