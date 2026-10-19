# KangC Xu

English · [简体中文](README.zh-CN.md)

**Algorithm Engineer · Applied AI & Machine Vision · Suzhou, China**

I build AI-powered vision and industrial measurement tools, combining YOLO model training, ONNX inference, and C++ / Qt application development. ChatGPT and Codex are part of my everyday engineering workflow.

## Technical Focus

| Area | Technologies and interests |
| --- | --- |
| Industrial software | C++17, Qt 6, CMake, modular desktop applications, and device integration |
| Machine vision | OpenCV, 2D / 3D measurement, and calibration |
| Applied AI | YOLO, Docker-based training, model validation, ONNX export, and ONNX Runtime |
| AI tools & workflows | ChatGPT, Codex, Ollama, reusable skills, and MCP integrations |
| Data analysis | Python, pandas, NumPy, and data visualization |

## AI in Practice

- **Vision model training:** Train YOLO object-detection models in Docker, using mounted folders for datasets and experiment outputs. Work with training and validation runs and export models to ONNX for inference integration.
- **Inference in applications:** Integrate ONNX inference, image preprocessing, and result visualization into desktop applications. [OnePiece](https://github.com/KangC-Xu/OnePiece) includes a MobileNet classification example using ONNX Runtime.
- **AI-assisted engineering:** Primarily use ChatGPT and Codex for code understanding, implementation, debugging, and bilingual documentation. Explore reusable skills, MCP integrations, and codebase knowledge graphs to provide relevant project context, with changes checked through review, builds, focused tests, and visual inspection.
- **Local model exploration:** Have used Ollama to run models locally, alongside hosted AI tools.

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

### [OnePiece — Algorithm Plugin Platform](https://github.com/KangC-Xu/OnePiece)

A personal C++ / Qt learning project for exploring how algorithms become usable desktop tools.

- **Plugin architecture:** A Qt host discovers DLL plugins, creates algorithm instances through factories, and uses shared interfaces for inputs, parameters, and results.
- **Algorithm examples:** OpenCV thresholding, edge and contour detection; height-map-based point-cloud sampling and statistics; MobileNet inference with ONNX Runtime.
- **Interactive workflow:** Parameter forms, image input, algorithm execution, and result previews in a Qt Widgets interface.

**Technology:** C++17 · Qt 6 · OpenCV · ONNX Runtime · CMake  
**Source:** [GitHub repository](https://github.com/KangC-Xu/OnePiece) · MIT License · English / 简体中文 documentation.

Additional experiments include image enhancement, geometric measurement, and sensor communications.

## Education

**Master's · Artificial Intelligence**  
Anglia Ruskin University (ARU), United Kingdom.

**Bachelor's · Electrical Engineering and Automation**  
Jiangsu University of Technology.

## Contact

[xukangc.pro@gamil.com](mailto:xukangc.pro@gamil.com)
