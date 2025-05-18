# 🌍 LAZ to DGM Converter

![GitHub release](https://img.shields.io/github/release/DrabTaqweem/laz-to-dgm.svg)
![GitHub issues](https://img.shields.io/github/issues/DrabTaqweem/laz-to-dgm.svg)
![GitHub stars](https://img.shields.io/github/stars/DrabTaqweem/laz-to-dgm.svg)

## Overview

Welcome to the **LAZ to DGM Converter** repository! This project calculates Digital Ground Models (DGMs) and Digital Surface Models (DSMs) from LAZ files. It serves as a powerful tool for professionals in GIS, remote sensing, and terrain analysis.

You can find the latest releases of this tool [here](https://github.com/DrabTaqweem/laz-to-dgm/releases). Download the necessary files and execute them to start your conversion process.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Supported Formats](#supported-formats)
5. [Examples](#examples)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Features

- **Efficient Conversion**: Quickly convert LAZ files to DGMs and DSMs.
- **Multiple Formats**: Support for various output formats including GeoTIFF.
- **User-Friendly Interface**: Simple command-line interface for easy usage.
- **High Accuracy**: Reliable results for elevation data.
- **Open Source**: Freely available for modification and distribution.

## Installation

To install the LAZ to DGM Converter, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/DrabTaqweem/laz-to-dgm.git
   ```
2. Navigate to the project directory:
   ```bash
   cd laz-to-dgm
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To use the LAZ to DGM Converter, run the following command in your terminal:

```bash
python convert.py input.laz output.tif
```

Replace `input.laz` with the path to your LAZ file and `output.tif` with the desired output file name.

For detailed options, you can use:

```bash
python convert.py --help
```

This will provide you with all available options for customization.

## Supported Formats

The LAZ to DGM Converter supports the following formats:

- **Input**: LAZ
- **Output**: GeoTIFF (TIFF)

## Examples

### Basic Conversion

To convert a simple LAZ file to a GeoTIFF, use:

```bash
python convert.py myfile.laz myfile.tif
```

### Advanced Options

You can specify additional parameters for advanced users. For example, to set a specific resolution, use:

```bash
python convert.py myfile.laz myfile.tif --resolution 1
```

## Contributing

We welcome contributions! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out via GitHub or create an issue in the repository.

---

You can find the latest releases of this tool [here](https://github.com/DrabTaqweem/laz-to-dgm/releases). Download the necessary files and execute them to start your conversion process.

Happy converting! 🌲