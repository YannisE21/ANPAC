<h1 align="center">
  <br>
  <img src="https://placehold.co/600x400" width="260"></a>
  <br>
    Automatic Neptune Printing and Clearing

  <br>
</h1>

  <p align="center">
    <a href="https://github.com/YannisE21/BatchOS/issues">Report Bug</a>
    .
    <a href="https://github.com/YannisE21/BatchOS/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/YannisE21/BatchOS/total) ![Contributors](https://img.shields.io/github/contributors/YannisE21/BatchOS?color=dark-green) ![Issues](https://img.shields.io/github/issues/YannisE21/BatchOS) ![License](https://img.shields.io/github/license/YannisE21/BatchOS) 


## Overview

Welcome to the Neptune-4 ANPAC mod for continuous printing! This enhancement is designed for the Neptune 4 (Pro) 3D printer running OpenNeptune, enabling seamless and flawless continuous printing. Say goodbye to interruptions and hello to uninterrupted creativity!

## Features

- **Continuous Printing**: Effortlessly print large models without the need for manual restarts.
- **Easy Installation**: Simple setup process to get you up and running quickly.
- **Compatibility**: Fully compatible with the Neptune 4 (Pro) and OpenNeptune firmware.

# What is [OpenNeptune](https://github.com/OpenNeptune3D/OpenNept4une)?
[OpenNeptune](https://github.com/OpenNeptune3D/OpenNept4une) is an open-source firmware specifically developed for the Neptune 4 series of 3D printers. It provides advanced features and improvements over the stock firmware, enhancing the overall printing experience. With OpenNeptune, users gain access to customizable settings, improved stability, and a growing community of enthusiasts contributing to its ongoing development. One of the standout features of OpenNeptune is its **queue function**, which allows multiple print jobs to be scheduled and executed in succession without manual intervention. This functionality makes continuous printing possible, enabling users to run complex projects or large batches seamlessly.

## Installation and Setup

### 1. **Download the Latest Release**
   - Visit the [Releases page](./releases) and download the latest version of ANPAC.

### 2. **Upload Files to Your Printer**
   - Connect your printer to your computer via USB or SD card.
   - Upload the downloaded ANPAC files to your device.

### 3. **Create the ANPAC Folder**
   - Create a new folder on your printer called `ANPAC`.
   - This keeps all relevant files organized and easy to access.

### 4. **Move the ANPAC Configuration File**
   - Move the `ANPAC.cfg` file into the newly created `ANPAC` folder.
   - This configuration file contains all the key settings for the ANPAC system.

### 5. **Check the Settings**
   - Open the `ANPAC.cfg` file and review the default settings.
   - Customize the parameters for cooling, wiping, and retraction to suit your needs, or use the default values.

### 6. **Replace End G-Code in Your Slicer**
   - Replace your slicer's end G-code with the command `ANPAC_END`.
   - This ensures that after each print, the ANPAC macro is triggered to clean the print bed and prepare the printer for the next job.

### 7. **Test the Installation**
   - Run a test print to verify that ANPAC is working correctly.
   - Observe if the macro activates after the print finishes and cleans the print bed as expected.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

<p align="center">
<img src="./Photos/built-for-klipper-made-with-love.svg" width="400">
</p>
