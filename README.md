# Science - Compiled Scientific Tools Collection

This repository contains pre-compiled binaries of scientific and image-processing tools for multiple operating systems and CPU architectures. The programs are grouped by platform and architecture to make selection and execution straightforward.

## Overview

The `Science` repository provides ready-to-use executables for research and computational work in areas such as scientific imaging, geometric analysis, sequence data processing, and visualization. Each tool is distributed as a platform-specific binary so it can be used directly after downloading the correct version.

## Included Software

The repository currently contains the following tools and programs:

### Cloud2
Cloud2 is a powerful tool for processing different types of data. Cloud (to) can transform, process, and evaluate data such as point clouds, vector fields, space curves, and meshes. In addition, it has a powerful renderer that allows stunning graphics (see slideshow).

Typical use cases include:
- Point cloud processing
- Geometric analysis and transformation
- Mesh generation and evaluation
- Vector field and curve analysis
- Scientific visualization and rendering

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
Hexagon is a command-line tool to simulate the Game of Life. With this cellular automaton, complex rules can be defined and the process over time displayed.

Typical use cases include:
- Cellular automaton simulation
- Rule-based life-like system modeling
- Temporal evolution and pattern display
- Experimentation with automaton behavior
- Visualization of dynamic system states over time

### ImageXD
ImageXD is the successor to `image` and `image3d`; `image3d` already superseded `transform2`. ImageXD can be used for a wide range of applications. It processes 2D images, 3D image stacks, vector fields, tensor fields (`symmatrix`), surface networks (meshes), and unstructured data such as fibres and networks.

The program is designed for large scientific datasets. On 64-bit systems, the addressable dataset size is principally limited by the available hardware and operating-system resources (up to approximately 2^64 bytes in the address space), rather than by a small fixed application limit. Many functions are optimized for multicore processors.

Typical applications include:
- 2D image processing
- 3D image-stack and volumetric-data processing
- Vector-field and tensor-field analysis
- Processing of meshes and surface networks
- Analysis of fibres, networks, and other unstructured data
- Multicore-enabled scientific image and dataset processing

The repository may still contain binaries named `image`, `image3d`, and `transform2` for legacy or platform-specific compatibility. For new workflows, ImageXD is the successor and should be preferred where a suitable binary is available.

### Launcher
- Tool launcher / application entry point for the toolbox collection

### Master
- Central utility for toolbox access and project execution

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
├── x86_64-freebsd/
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
