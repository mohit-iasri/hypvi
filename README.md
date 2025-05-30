# HypVI  
### A Software Tool for Hyperspectral Data Analysis and Vegetation Indices Computation  

---

### 🌿 Hyperspectral Index Highlights

- **240 VNIR Indices**  
- **79 SWIR Indices**  
- **53 Mixed Indices**  

---

This tool offers a comprehensive set of functionalities for processing raw hyperspectral images. It enables the extraction of data into a structured data cube, facilitating efficient organization and analysis. Additionally, it provides visualization capabilities for spectral curves, allowing users to examine spectral signatures across different wavelengths. Furthermore, the tool supports the computation of **372 vegetation indices**, enabling advanced analysis of plant health, biomass estimation, and environmental monitoring. These features make it a powerful resource for remote sensing, precision agriculture, and ecological research.

---

### 📦 Downloads

- [Download Software (Google Drive)](https://drive.google.com/file/d/1DaXT93FeKj_sG6wH-KLLhOmI9ATEMbhS/view?usp=sharing)
- [Download Sample Data (Google Drive)](https://drive.google.com/file/d/1wfT7MheEpiAuOlbnc5Tn7uXl0t5Gajqk/view?usp=drive_link)

---

## Instructions for Software Use

### 1. Download and Extract Zip Files

Download the software and sample data, which are provided in ZIP format. Extract the files to a preferred location.

The sample dataset comprises **VNIR (Visible and Near-Infrared)** data in raw format.  
The software operates with a structured file system organized within a `Data` folder, which contains multiple sample or plant directories.

Each sample directory includes dedicated subfolders named `VNIR_SV` or `SWIR_SV`, where the corresponding hyperspectral data is systematically stored for analysis.

---

### 2. Launch the Software

Open the extracted software folder and double-click on `app.exe`. This will launch the home page of the software.

---

### 3. Data Extraction
 
- Select **Data Extraction** from the software interface.  
- Select the folder that contains the sample data.  
- Choose the data type as **VNIR** since the sample data is in VNIR format.  
- Click on **"Click here to process"**.  
  This will process the sample data and generate the hyperspectral data cube along with a pseudo RGB image.

---

### 4. Visualization of Reflectance Curve

- Click on **Visualization** and select a folder containing hyperspectral images.  
- Optionally, select a **Region of Interest (ROI)** for analysis.  
- Run the process by clicking **"Click here to process"**.

---

### 5. Computation of Vegetation Indices

- Click on the **Vegetation Indices** radio button.  
- Select the appropriate data type for your data.  
- Choose the folder containing the extracted hyperspectral data.  
- Optionally, select an ROI.  
- Click **"Click here to process"**.  
  The software will compute the vegetation indices and generate a CSV file saved in the software directory.

---
