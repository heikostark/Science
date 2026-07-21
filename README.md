# Science - Compiled Scientific Tools Collection

A comprehensive collection of pre-compiled scientific software tools for data processing, visualization, and analysis across multiple platforms and architectures.

## Overview

**Science** is a centralized repository containing pre-compiled binaries of various scientific and research tools developed by Heiko Stark. This repository provides ready-to-use executables for multiple platforms and architectures, eliminating the need to compile from source.

All tools are organized by platform and architecture, making it easy to download and run the appropriate binary for your system.

## Available Tools

The Science repository includes binaries for the following tools:

### Cloud2 - Data Processing and Visualization Tool

**Purpose:** Process and visualize complex geometric and spatial data including point clouds, vector fields, space curves, and meshes.

**Key Features:**
- Import multiple data formats (OBJ, STL, PDB, FEBio, Amira, ASCII)
- 3D visualization with multiple projection views (XY, XZ, YZ, XT, ZT)
- Geometric transformations and mathematical operations
- Boolean operations on geometric objects
- Mesh generation and processing
- POV-Ray export for high-quality rendering
- Curve analysis (curvature, torsion calculations)
- Scripting and batch processing capabilities

**Use Cases:**
- Point cloud processing from 3D scanners
- Mesh generation and optimization
- Computational geometry analysis
- Biomechanical modeling
- Scientific visualization

**Website:** https://stark-jena.de/research-interests/software/cloud2/

### Didiwiki - Personal Wiki System

**Purpose:** A lightweight, personal wiki system for documentation, note-taking, and knowledge management.

**Key Features:**
- Simple and intuitive wiki interface
- Local file-based storage
- Support for formatted text and links
- Page search functionality
- Easy to set up and use
- Minimal system requirements

**Use Cases:**
- Personal research documentation
- Lab notebook management
- Project documentation
- Knowledge base creation
- Quick reference guide building

**Website:** https://stark-jena.de/research-interests/software/didiwiki/

### Gordon1966 - FEBio Muscle Contraction Plugin

**Purpose:** A specialized FEBio plugin for simulating muscle contraction mechanics based on the Gordon et al. (1966) force-length relationship.

**Key Features:**
- Transversely isotropic hyperelastic material model
- Passive and active muscle behavior
- Gordon force-length curve implementation
- FEBio framework integration
- Parametric material definition
- Support for biomechanical simulations

**Use Cases:**
- Muscle tissue mechanics simulation
- Biomechanical modeling
- Finite element analysis of contractile tissues
- Research in muscle physiology
- Clinical biomechanics applications

**Website:** https://stark-jena.de/research-interests/software/contraction/material-models/

### Additional Research Tools

The repository may contain additional compiled scientific tools and utilities. For a complete and up-to-date list, please visit the main research software page.

**Research Software Overview:** https://stark-jenKannst du mir bitte eine vollständige Readme-Datei für das Repository Didiwiki schreiben?a.de/research-interests/software/

## Supported Platforms and Architectures

This repository provides pre-compiled binaries for extensive platform and architecture support:

### Operating Systems
- **Linux** - Multiple distributions (Debian, Ubuntu, Fedora, Red Hat, Arch, etc.)
- **Windows** - 32-bit (i386) and 64-bit (x86_64) versions
- **macOS** - Intel (i386, x86_64) and Apple Silicon (aarch64)
- **FreeBSD** - Multiple versions
- **Android** - Multiple ARM architectures
- **Other Unix Systems** - Solaris, DragonFly BSD

### CPU Architectures

#### x86/x64 Processors
- **i386-win32** - 32-bit Windows
- **i386-linux** - 32-bit Linux
- **i386-freebsd** - 32-bit FreeBSD
- **i386-darwin** - 32-bit macOS (legacy Intel)Kannst du mir bitte eine vollständige Readme-Datei für das Repository Didiwiki schreiben?
- **i386-solaris** - 32-bit Solaris
- **x86_64-win64** - 64-bit Windows
- **x86_64-linux** - 64-bit Linux (standard)
- **x86_64-freebsd** - 64-bit FreeBSD
- **x86_64-darwin** - 64-bit macOS (Intel)
- **x86_64-dragonfly** - 64-bit DragonFly BSD
- **x86_64-solaris** - 64-bit Solaris

#### x86_64 with AVX Support
- **x86_64_avx-linux** - 64-bit Linux with AVX optimizations
- **x86_64_avx-win64** - 64-bit Windows with AVX
- **x86_64_avx-darwin** - 64-bit macOS with AVX
- **x86_64_avx-freebsd** - 64-bit FreeBSD with AVX
- **x86_64_avx-dragonfly** - 64-bit DragonFly BSD with AVX
- **x86_64_avx-solaris** - 64-bit Solaris with AVX

#### ARM Processors
- **arm-linux** - ARM Linux systems
- **arm-android** - ARM Android systems
- **aarch64-linux** - ARM64 Linux (64-bit ARM)
- **aarch64-darwin** - ARM64 macOS (Apple Silicon M1/M2/M3)
- **aarch64-android** - ARM64 Android

#### Other Architectures
- **mips-linux** - MIPS Linux systems
- **mipsel-linux** - MIPS Little-Endian Linux
- **mipsel-android** - MIPS Little-Endian Android
- **powerpc-linux** - PowerPC Linux
- **powerpc-darwin** - PowerPC macOS (legacy)
- **powerpc64-linux** - PowerPC 64-bit Linux
- **sparc-linux** - SPARC Linux systems
- **sparc64-linux** - SPARC 64-bit Linux systems

### Selecting the Right Binary

To download and use the correct binary:

1. **Identify your operating system:** Windows, Linux, macOS, FreeBSD, etc.
2. **Determine your CPU architecture:** Use these commands:
   - **Linux/macOS/BSD:** `uname -m`
   - **Windows:** Check System Properties or run `wmic os get osarchitecture`
3. **Navigate to the appropriate directory** in the repository
4. **Download the binary** for your specific platform-architecture combination
5. **Make executable (Linux/macOS/BSD):** `chmod +x binary_name`
6. **Run the tool**

## Repository Structure

```
Science/
├── README.md                    This file
├── aarch64-android/            ARM 64-bit Android binaries
├── aarch64-darwin/             ARM 64-bit macOS binaries (Apple Silicon)
├── aarch64-linux/              ARM 64-bit Linux binaries
├── arm-android/                ARM 32-bit Android binaries
├── arm-linux/                  ARM 32-bit Linux binaries
├── arm-wince/                  ARM Windows CE binaries
├── i386-android/               Intel 32-bit Android binaries
���── i386-darwin/                Intel 32-bit macOS binaries (legacy)
├── i386-freebsd/               Intel 32-bit FreeBSD binaries
├── i386-linux/                 Intel 32-bit Linux binaries
├── i386-solaris/               Intel 32-bit Solaris binaries
├── i386-win32/                 Intel 32-bit Windows binaries
├── i386-wince/                 Intel Windows CE binaries
├── mips-linux/                 MIPS Linux binaries
├── mipsel-android/             MIPS Little-Endian Android binaries
├── mipsel-linux/               MIPS Little-Endian Linux binaries
├── powerpc-darwin/             PowerPC macOS binKannst du mir bitte eine vollständige Readme-Datei für das Repository Didiwiki schreiben?aries
├── powerpc-linux/              PowerPC Linux binaries
├── powerpc64-linux/            PowerPC 64-bit Linux binaries
├── sparc-linux/                SPARC Linux binaries
├── sparc64-linux/              SPARC 64-bit Linux binaries
├── x86_64-android/             x86_64 Android binaries
├── x86_64-darwin/              x86_64 macOS binaries (Intel)
├── x86_64-dragonfly/           x86_64 DragonFly BSD binaries
├── x86_64-freebsd/             x86_64 FreeBSD binaries
├── x86_64-linux/               x86_64 Linux binaries (standard)
├── x86_64-solaris/             x86_64 Solaris binaries
├── x86_64-win64/               x86_64 Windows binaries
├── x86_64_avx-android/         x86_64 Android binaries with AVX
├── x86_64_avx-darwin/          x86_64 macOS binaries with AVX
├── x86_64_avx-dragonfly/       x86_64 DragonFly BSD with AVX
├── x86_64_avx-freebsd/         x86_64 FreeBSD with AVX
├── x86_64_avx-linux/           x86_64 Linux with AVX (optimized)
├── x86_64_avx-solaris/         x86_64 Solaris with AVX
└── x86_64_avx-win64/           x86_64 Windows with AVX (optimized)
```

## Downloading and Using Binaries

### Quick Start

#### Linux (x86_64)
```bash
# Navigate to the appropriate directory
cd x86_64-linuxKannst du mir bitte eine vollständige Readme-Datei für das Repository Didiwiki schreiben?

# Download or view available binaries
ls -la

# Make binary executable
chmod +x cloud2

# Run the tool
./cloud2
```

#### macOS (Intel x86_64)
```bash
cd x86_64-darwin
chmod +x cloud2
./cloud2
```

#### macOS (Apple Silicon M1/M2/M3)
```bash
cd aarch64-darwin
chmod +x cloud2
./cloud2
```

#### Windows (64-bit)
```powershell
# Navigate to directory
cd x86_64-win64

# Run the executable
.\cloud2.exe
```

### Performance Optimization

For systems supporting AVX (Advanced Vector Extensions):
- Use binaries from `x86_64_avx-*` directories for better performance
- AVX provides significant speedup for floating-point operations
- Most modern processors (2011+) support AVX

To check if your system supports AVX:

**Linux/macOS:**
```bash
grep avx /proc/cpuinfo  # Linux
sysctl -a | grep avx     # macOS
```

**Windows:**
```powershell
Get-WmiObject -Query "select * from Win32_Processor" | select Name, Family, Model, Stepping
```

## Installation and Setup

### System Dependencies

Most binaries are self-contained, but may require:
- GTK2 libraries (for graphical tools like Cloud2)
- Standard C/C++ runtime libraries
- Platform-specific runtime components

#### Linux

```bash
# Debian/Ubuntu - GTK2 support
sudo apt-get install libgtk2.0-0 libgdk-pixbuf2.0-0

# Fedora/RHEL
sudo dnf install gtk2 gdk-pixbuf2

# Arch Linux
sudo pacman -S gtk2 gdk-pixbuf2
```

#### macOS

```bash
# Using Homebrew for GTK2 support (if needed)
brew install gtk+2
```

#### Windows

- Most tools include required dependencies
- Ensure Visual C++ Redistributable is installed
- Windows Defender may require exception for external tools

### Running the Tools

1. Download the appropriate binary for your system
2. Extract (if in archive format)
3. Make executable (on Unix-like systems): `chmod +x binary_name`
4. Run: `./binary_name` (Unix) or `binary_name.exe` (Windows)

## Troubleshooting

### Binary Not Found or Wrong Architecture

**Problem:** "No such file or directory" or "wrong architecture"

**Solution:**
- Verify your system architecture: `uname -m` (Linux/macOS)
- Ensure you downloaded the binary for the correct platform
- Check 32-bit vs 64-bit compatibility

### Missing Dependencies

**Problem:** "Cannot open shared object file" or "library not found"

**Solution:**
- Install required system libraries (GTK2, runtime libraries)
- Check dynamic dependencies: `ldd ./binary` (Linux) or `otool -L binary` (macOS)
- Use library path: `export LD_LIBRARY_PATH=/usr/local/lib:$LD_LIBRARY_PATH` (Linux)

### Permission Denied

**Problem:** "Permission denied"

**Solution:**
- Make file executable: `chmod +x binary_name`
- Check file permissions: `ls -l binary_name`

### Display/GUI Issues

**Problem:** GTK errors or display not working

**Solution:**
- Ensure GTK2 is properly installed
- Check X11 display: `echo $DISPLAY` (should be `:0` or similar)
- For SSH connections, use X11 forwarding: `ssh -X user@host`

### Performance Issues

**Problem:** Tool running slowly

**Solution:**
- Use AVX-optimized binaries if available
- Reduce input data size
- Close other applications
- Check available system memory

## Updating and Building from Source

While this repository contains pre-compiled binaries, the source code for most tools is available in separate repositories:

- **Cloud2:** https://github.com/heikostark/Cloud2
- **Gordon1966:** https://github.com/heikostark/Gordon1966
- **Didiwiki:** https://github.com/heikostark/Didiwiki

To build from source:

1. Clone the source repository
2. Install development tools and dependencies
3. Follow the build instructions in each project's README
4. Compile using the project's build system (Lazarus, cmake, etc.)

## Version Information

Binaries in this repository are compiled versions of the source code. To check version information:

- Look for `VERSION` or `version.txt` in the binary directory
- Run binary with `--version` or `-v` flag (if supported)
- Check the project's GitHub repository for version history

## License and Attribution

Each tool has its own license. Please check:
- Individual project repositories for license details
- Source code headers for attribution information
- Project README files for license terms

## Support and Feedback

For issues, questions, or feature requests:

1. **Check the project's GitHub repository** for specific issues
2. **Visit the research website** for documentation
3. **Report bugs** in the appropriate project's issue tracker

### Project Links

- **Main Research Page:** https://stark-jena.de/research-interests/software/
- **Cloud2:** https://github.com/heikostark/Cloud2
- **Gordon1966:** https://github.com/heikostark/Gordon1966
- **Didiwiki:** https://github.com/heikostark/Didiwiki

## Research Applications

These tools have been developed for and used in:

- **Computational Geometry** - Algorithm development and testing
- **Biomechanics** - Muscle contraction and tissue simulation
- **Medical Imaging** - 3D anatomical data processing
- **Material Science** - Microstructure and property analysis
- **Fluid Dynamics** - Vector field visualization and analysis
- **Scientific Computing** - General data processing and visualization
- **Engineering** - Finite element model preparation and analysis

## Contributing

Improvements and contributions are welcome! To contribute:

1. Check the relevant project repository (Cloud2, Gordon1966, etc.)
2. Fork the repository
3. Create a feature branch
4. Make your improvements
5. Submit a pull request

## Acknowledgments

These tools have been developed with support from:
- Free Pascal and Lazarus communities
- Open-source software libraries
- Research collaborators and colleagues

## Platform Availability Summary

| Tool | Linux | Windows | macOS | FreeBSD | Android | Other |
|------|-------|---------|-------|---------|---------|-------|
| Cloud2 | ✅ | ✅ | ✅ | ✅ | ⚠️ | ✅ |
| Gordon1966 | ✅ | ✅ | ✅ | - | - | ✅ |
| Didiwiki | ✅ | ✅ | ✅ | ✅ | - | ✅ |

✅ = Full support  
⚠️ = Limited/experimental support  
\- = Not available

## Changelog and Updates

The repository is regularly updated with:
- New binary compilations
- Additional platform support
- Performance improvements
- Bug fixes

Check the commit history for recent changes:
https://github.com/heikostark/Science/commits/master

## Getting Started

**Quick Start Guide:**

1. Determine your system: `uname -s -m` (macOS/Linux)
2. Navigate to corresponding directory in repository
3. Download the binary for your tool
4. Make executable: `chmod +x binary_name`
5. Run: `./binary_name`
6. Refer to tool-specific documentation for usage

For detailed usage of each tool, visit:
- https://stark-jena.de/research-interests/software/cloud2/ - Cloud2
- https://stark-jena.de/research-interests/software/didiwiki/ - Didiwiki
- https://stark-jena.de/research-interests/software/contraction/material-models/ - Gordon1966

## Future Directions

Planned improvements:
- Additional platform support (e.g., iOS, WebAssembly)
- Automated nightly builds
- Continuous integration pipeline
- Docker containers for easier deployment
- Performance profiling and optimization
- Extended tool collection

## Contact

For research collaboration inquiries or tool-specific questions:

**Heiko Stark**  
Friedrich-Schiller-University Jena

**Website:** https://stark-jena.de/  
**Research:** https://stark-jena.de/research-interests/

---

**Repository:** https://github.com/heikostark/Science  
**Last Updated:** March 2025  
**Maintained By:** Heiko Stark
