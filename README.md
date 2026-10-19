# KangC Xu

English · [简体中文](README.zh-CN.md)

**Algorithm Engineer · Suzhou, China**

I focus on machine vision, industrial software, and data analysis, combining C++ / Qt engineering with Python-based analytical tools.

## Technical Focus

| Area | Technologies and interests |
| --- | --- |
| Industrial software | C++17, Qt 6, CMake, modular desktop applications, and device integration |
| Machine vision | OpenCV, 2D / 3D measurement, calibration, and model inference |
| Data analysis | Python, pandas, NumPy, and data visualization |

## Engineering Experience

### Industrial Vision & Measurement Software

I develop algorithms and application software for an internal industrial inspection system. My responsibilities span vision and measurement algorithms, calibration, software architecture, operator interfaces, and hardware integration.

- **Vision & alignment:** Develop fiducial detection and workpiece alignment using geometric image processing and ONNX-based detection, connecting image coordinates with CAD/DXF and machine coordinates for positioning and scan setup.
- **Dimensional measurement:** Develop and integrate 2D profile and 3D point-cloud methods for thickness, height, width, gap, presence/absence, and surface-flatness inspection. Convert measurement results into configurable pass/fail decisions.
- **Calibration:** Develop camera-to-motion-stage and camera-to-measurement-sensor calibration workflows to align coordinate systems for automated measurement.
- **Software architecture:** Develop a modular C++17 / Qt 6 application with separate UI, workflow, algorithm, device, and data responsibilities. Use a central algorithm interface and background acquisition/processing to connect algorithms with automated inspection workflows.
- **Operator tools & device integration:** Build Qt interfaces for calibration, recipes, live profiles, 3D visualization, and result analysis; integrate cameras, measurement sensors, motion control, lighting, and lens control, with diagnostic logs and result export.

**Technology:** C++17 · Qt 6 Widgets · OpenCV · CMake · VTK · Qwt

![Simplified industrial measurement architecture: a Qt operator interface and measurement workflow coordinate vision algorithms, device integration, and inspection data.](assets/industrial-measurement.svg)

*This overview describes general engineering responsibilities. Company source code, customer information, internal parameters, and implementation details remain confidential.*

## Personal Engineering

### OnePiece — Algorithm Plugin Platform

A personal C++ / Qt learning project for exploring how algorithms become usable desktop tools.

- **Plugin architecture:** A Qt host discovers DLL plugins, creates algorithm instances through factories, and uses shared interfaces for inputs, parameters, and results.
- **Algorithm examples:** OpenCV thresholding, edge and contour detection; height-map-based point-cloud sampling and statistics; MobileNet inference with ONNX Runtime.
- **Interactive workflow:** Parameter forms, image input, algorithm execution, and result previews in a Qt Widgets interface.

**Technology:** C++17 · Qt 6 · OpenCV · ONNX Runtime · CMake  
**Status:** Personal learning project; source not yet published on GitHub.

Additional experiments include image enhancement, geometric measurement, and sensor communications.

## Education

**Master's Programme in Artificial Intelligence**  
CJLU-ARU Joint Institute — China Jiliang University & Anglia Ruskin University (ARU), United Kingdom.  

**Undergraduate Studies in Electrical Engineering and Automation**  
Jiangsu University of Technology.

## Contact

[xukangc.pro@gamil.com](mailto:xukangc.pro@gamil.com)
