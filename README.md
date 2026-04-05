# 🚀 STL Volume & Mass Analytics Tool

A high-performance command-line utility for 3D printing enthusiasts and engineers. This tool provides a comprehensive analysis of 3D models, including volume, surface area, bounding box, and estimated mass across various materials.

---

## 🌟 Key Features

* **🔍 Comprehensive Analysis**: Get instant file size, triangle count, bounding box, surface area, and volume with a single command.
* **⚖️ Infill Mass Comparison**: Automatically compares model mass at a custom infill (default 20%) against a 100% solid version.
* **🧪 Multi-Material Estimation**: Supports over **20+ professional materials** including PLA, ABS, Titanium, Gold, and Carbon Fiber.
* **📋 Pro Console Output**: Displays data in beautifully formatted, easy-to-read tables.
* **🤖 Developer Ready**: Supports **JSON output** for seamless integration with AI workflows and web applications.
* **🏥 Medical Format Support**: Full compatibility with **STL (ASCII/Binary)**, **NIfTI**, and **DICOM** files.

---

## 🛠️ Installation

Ensure you have **Python 3.8+** installed on your system.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/youssefshawat/STL-Volume-Analytics.git](https://github.com/youssefshawat/STL-Volume-Analytics.git)
    cd STL-Volume-Analytics
    ```
2.  **Install the package:**
    ```bash
    pip install .
    ```

---

## 🚀 Usage Guide

After installation, you can run the `volume-calculator` command from any directory.

### 1. Default Full Analysis
```bash
--- 
###  volume-calculator MyModel.stl

 2. Custom Infill & JSON Output
volume-calculator MyModel.stl --infill 15 --output-format json

Argument,Description
filename,"Path to your model file (STL, NIfTI, DICOM)."
--calculation,Optimize by running: volume or area.
--infill <%>,Set infill percentage (Default: 20.0).
--unit <unit>,Display in cm (default) or inch.
--output-format,Choose between table (default) or json.
--list-materials,Show all supported materials and their IDs.

💎 Supported Materials
The tool includes density profiles for:

Polymers: PLA, ABS, PETG, Resin, Nylon.

Metals: Aluminum, Steel, Titanium, Brass, Copper, Gold (14K/18K).

Specialty: Carbon Fiber (3k CFRP), Alumide, Red Oak.

👨‍💻 About the Author
Youssef Yasser (Youssef Shawat)
Data Science & AI Student @ Alexandria University

GitHub: github.com/youssefshawat

LinkedIn: www.linkedin.com/inyoussef-shawat-49971939

Watsapp :+20 01284926787
