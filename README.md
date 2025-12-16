# Tevo Tarantula PrusaSlicer Settings

![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)

This repository provides a curated collection of PrusaSlicer configuration profiles specifically optimized for the **Tevo Tarantula 3D printer**. These settings aim to enhance print quality, reliability, and ease of use for users of this popular FDM printer.

## Table of Contents

*   [About This Project](#about-this-project)
*   [Features](#features)
*   [Installation](#installation)
*   [Usage](#usage)
*   [Contributing](#contributing)
*   [License](#license)

## About This Project

The Tevo Tarantula is a widely adopted 3D printer, and achieving optimal print results often requires fine-tuning slicer settings. This project consolidates and refines PrusaSlicer profiles to leverage the capabilities of the Tevo Tarantula, offering a solid starting point for various printing needs.

## Features

*   **Optimized Profiles:** Pre-configured settings designed to work well with the Tevo Tarantula's hardware characteristics.
*   **Quality Enhancements:** Settings focused on improving surface finish, dimensional accuracy, and structural integrity.
*   **Ease of Use:** Simplified setup for both beginners and experienced users.
*   **Open Source:** Developed and distributed under the GNU General Public License v3.0.

## Installation

To use these settings, you need to import them into your PrusaSlicer installation.

1.  **Download the Configuration Files:**
    *   Clone this repository to your local machine:
        ```bash
        git clone https://github.com/yourusername/Tevo-Tarantula-Prusa-Slic3r-Settings.git
        ```
    *   Alternatively, download the `.ini` files directly from the repository.

2.  **Import into PrusaSlicer:**
    *   Open PrusaSlicer.
    *   Navigate to **File > Import > Import Config Bundle...**.
    *   Select the `PrusaSlicer_config_bundle.ini` file from the downloaded repository.

    *Alternatively, for individual profile import (e.g., specific print settings):
    *   Navigate to **File > Import > Import Config...**.
    *   Select the desired `.ini` file (e.g., `Tevo Tarantula.ini`).

    The imported settings will appear in the respective sections (Printer, Print, Filament, etc.) within PrusaSlicer.

## Usage

Once imported, you can select the appropriate profiles for your printing tasks.

1.  **Select Printer Profile:** Ensure the "Tevo Tarantula" or a similarly named profile is selected in the Printer dropdown.
2.  **Select Print Settings Profile:** Choose a profile that best suits your desired print quality and speed. For example:
    *   `Tevo Tarantula 0.06mm`: For high-detail prints requiring fine layer heights.
    *   `Tevo Tarantula`: A general-purpose profile for balanced quality and speed.

    *Note: The `PrusaSlicer_config_bundle.ini` file contains multiple profiles, including a high-detail profile (`Tevo Tarantula 0.06mm`) and a standard profile (`Tevo Tarantula`). You can also find individual `.ini` files for specific configurations.

3.  **Slice Your Model:** Load your `.stl` or `.3mf` model, select your desired filament, and slice the model using the chosen profiles.

### Example Print Settings:

*   **`Tevo Tarantula.ini`:**
    *   Layer Height: `0.3mm`
    *   Infill Density: `20%` (Honeycomb pattern)
    *   Supports: Enabled, buildplate only, rectilinear pattern.
    *   Outer Perimeter Speed: `50%`
    *   First Layer Height: `0.35mm`
    *   First Layer Speed: `30mm/s`

*   **`PrusaSlicer_config_bundle.ini` (Profile: `Tevo Tarantula 0.06mm`):**
    *   Layer Height: `0.06mm`
    *   Infill Density: `30%` (Cubic pattern)
    *   Perimeters: `4`
    *   External Perimeter Speed: `50%`
    *   First Layer Height: `0.1mm`
    *   First Layer Speed: `30mm/s`
    *   Perimeter Generator: `arachne`

## Contributing

Contributions are welcome! If you have found improvements or new settings that benefit the Tevo Tarantula, please feel free to:

1.  **Fork the repository.**
2.  **Create a new branch** for your feature or fix.
3.  **Make your changes** and commit them.
4.  **Submit a Pull Request** with a clear description of your changes.

If you encounter any issues or have suggestions, please open an issue in the repository.

## License

This project is licensed under the **GNU General Public License v3.0**. See the `LICENSE` file for more details.
