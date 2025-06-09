# Custom Applications for JSON Data Analysis (Windows Only)

This repository contains a number of applications I created during as part of my work in iSentioLabs. They helped me to streamline the data cleaning and analysis process and allow others to perform data analysis without the requirement to use Python like I had been doing. These tools were originally created for use on our office laptops, so they are compatible only with 64-bit Windows operating systems.

All applications are bundled together in a single downloadable ZIP file available in this repository.

---

## Contents of the ZIP Package

Inside the zip file (`Custom_Apps_Windows64.zip`), you'll find:

- Several standalone `.exe` applications for processing iSentio JSON files
- A **sample JSON file** included in the root folder for testing and demonstration purposes
- Usage instructions for each app in the form of either tooltips, prompts, or included documentation

---

## Available Applications

These tools support the following data processing tasks:

1. **Concatenate JSON Files**  
   Combines multiple files, ensuring smooth time continuity.

2. **Snip JSON by Time Range**  
   Trim JSON data by specifying start and end times. 

3. **Feature Extraction - Generic**  
   Extracts average and standard deviation from user-selected time ranges. Outputs annotated Word and Excel reports.

4. **Feature Extraction - Peaks & Troughs**  
   Allows the user to select multiple trough/peak pairs and computes the load difference between them.

5. **Load Sign Flipping**  
   Inverts all load values in selected files.

6. **Load Zeroing at a Point**  
   Lets the user define new zero points and adjusts all subsequent values accordingly.

7. **Remove Load Values Outside Range**  
   Deletes values outside user-defined upper/lower bounds in selected time ranges.

8. **Draw Over Load Data**  
   Enables manual correction of load values by selecting regions and drawing new interpolated curves.

---

## Sample JSON File

A sample JSON file is included in the ZIP to allow users to trial each application without needing to prepare or locate a data file.

---

## System Requirements

- **Operating System:** Windows 10 or later (64-bit only)  
- **No Python installation required** – All apps are packaged as standalone executables.


## File Layout (After Unzipping)
Custom_Apps_Windows64/
├── Concatenate_JSON.exe
├── Snip_JSON.exe
├── Feature_Extraction_Generic.exe
├── Feature_Extraction_Peaks_Troughs.exe
├── Load_Sign_Flipping.exe
├── Load_Zeroing.exe
├── Remove_Load_Outside_Range.exe
├── Draw_Over_Load_Data.exe
├── sample_file.json

