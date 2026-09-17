# Science - Compiled Scientific Tools Collection

This repository contains pre-compiled binaries of scientific and image-processing tools assembled for multiple operating systems and CPU architectures. The software in this repository is organized by platform and architecture so that the correct executable can be selected quickly.

## Overview

The `Science` repository provides ready-to-use executables for research and computational work in fields such as microscopy, sequence analysis, scientific visualization, and image processing. The available programs are bundled as platform-specific binaries and can be used directly after downloading the appropriate archive or executable.

## Included Software

The repository currently contains the following tools and programs:

### Cloud2
- 3D visualization and processing of geometric and spatial data
- Import/export of meshes, curves, and point clouds
- Scientific visualization workflows

### Enzyme2
- Sequence and biomolecular analysis tool
- Related to enzyme and sequence-processing workflows

### FASTA2MAX
- Conversion and processing of FASTA-based sequence data
- Useful for preparing and transforming sequence information

### Hexagon
Hexagon is a scientific analysis and visualization tool focused on geometric, image-based, and spatial data processing. It is designed for research workflows that require inspection, transformation, and quantitative analysis of structured data in 2D and 3D contexts.

Typical use cases include:
- Analysis of scientific image and geometry data
- Visualization of structured spatial information
- Transformation and measurement of coordinate-based data
- Research workflows in microscopy, imaging, and computational analysis
- Use alongside related tools in the `Science` collection for data preparation and exploration

### Image
- Basic image processing and analysis tool
- Used for viewing and manipulating image data

### Image3D
- 3D image processing and analysis utility
- Supports volumetric scientific image workflows

### ImageXD
- Extended image display and processing tool
- Often used for scientific image inspection and manipulation

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
Several Unix/Linux versions are shipped with X11-based variants such as:
- `Xenzyme2`
- `Xhexagon`
- `Ximagexd`

These are the graphical X-based executables for systems where the non-X variant is insufficient or not applicable.

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

For questions or issues related to this repository, please refer to the maintainer and repository project pages associated with the original software.

---

Repository: https://github.com/heikostark/Science
