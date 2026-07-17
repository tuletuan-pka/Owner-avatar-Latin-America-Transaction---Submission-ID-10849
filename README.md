# Latin-America-Transaction---Submission-ID-10849
# Paper ID: 10849
# Paper Title: A Circular Polarization MIMO Antenna using Sequentially Rotated Feeding Network for WLAN Applications

**Authors:**
* Ngoc-Lan Nguyen¹
* Dang-Khoa Ho¹ 
* Quoc-Hung Bui¹ 
* Tan Dao-Duc² ✉

**Affiliations:**
> ¹ Faculty of Telecommunications 2, Posts and Telecommunications Institute of Technology, Ho Chi Minh City, Vietnam. *(Emails: lannn@ptit.edu.vn, n21dcvt046@student.ptithcm.edu.vn, n21dcvt041@student.ptithcm.edu.vn)*
> ² Faculty of Electrical and Electronic Engineering, PHENIKAA School of Engineering, PHENIKAA University, Hanoi 12116, Vietnam.
> ✉ *Corresponding author: Tan Dao-Duc (tan.daoduc@phenikaa-uni.edu.vn)*

---

This repository contains the 3D electromagnetic simulation files and corresponding numerical data for our antenna design project. The files cover the progression from single-element designs to a full MIMO antenna system.

## 📁 Repository Structure

### Simulation Files (`.cst`)
The repository includes several CST Studio Suite project files representing different stages of the antenna design process:

*   **`Single_element.cst`**: The baseline 3D simulation for the single antenna element.
*   **`Single element_coaxial.cst`**: The single antenna element design utilizing a coaxial feeding mechanism.
*   **`4phantu_f.cst`**: The 3D simulation file for the 4-element antenna array.
*   **`feeding_f.cst`**: The simulation project detailing the sequentially rotated feeding network designed for the array/MIMO system.
*   **`mimo_f.cst`**: The complete, integrated Multiple-Input Multiple-Output (MIMO) antenna system simulation.

### Data Files
*   **`Data for simulation/`**: A directory containing the extracted numerical data (Excel `.xlsx` format) used to plot the results in the associated documentation or research paper (e.g., S-parameters, radiation patterns, efficiency, and ECC).
*   Included figure data:
* **Figure 3**: `Fig3a.xlsx`, `Fig3b.xlsx`
* **Figure 4**: `Fig4a.xlsx`, `Fig4b.xlsx`, `Fig4c.xlsx`
* **Figure 6**: `Fig6a.xlsx`, `Fig6b.xlsx`
* **Figure 8**: `Fig8a.xlsx`, `Fig8b.xlsx`, `Fig8c.xlsx`
* **Figure 10**: `Fig10a.xlsx`, `Fig10b.xlsx`, `Fig10c.xlsx`
* **Figure 12**: `Fig12a.xlsx`, `Fig12b.xlsx`
* **Figure 13**: `Fig13a.xlsx`, `Fig13b.xlsx`, `Fig13c.xlsx`
* **Figure 14**: `Fig14a.xlsx`, `Fig14b.xlsx`, `Fig14c.xlsx`
* **Figure 15**: `Fig15a.xlsx`, `Fig15b.xlsx`, `Fig15c.xlsx`
* **Figure 16**: `Fig16.xlsx`
*   **`README.md`**: Project overview and file directory descriptions (this file).

## 💻 Prerequisites & Software Requirements

To open and interact with the files in this repository, you will need:

1.  **CST Studio Suite** (Dassault Systèmes): Required to open, view, and recalculate the `.cst` simulation models.
2.  **Microsoft Excel** (or any compatible spreadsheet/data analysis software like MATLAB, Python, or OriginLab): Required to analyze and plot the `.xlsx` files located in the data folder.

## 🚀 Usage

1.  **Simulation:** Open `mimo_f.cst` in CST Studio Suite to view the 3D model, investigate the mesh, or re-calculate the solver results. 
2.  **Data Plotting:** Navigate to the `Data for simulation/` directory and open the respective `.xlsx` file to access the raw data points used for our graphical results. You can use this data to recreate the graphs in MATLAB, Python (Matplotlib), OriginLab, or Excel.
