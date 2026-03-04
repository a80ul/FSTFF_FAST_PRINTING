# 🚀 FSTFF - FAST EXPORT (BETA v2.3.3)

**FSTFF (Fast Export)** is a workflow automation solution for the printing industry. This application is specifically designed to overcome a classic challenge: *the scale discrepancy between design canvases and real-world print outputs.*

Designers often use a 1:10 scale in CorelDRAW (in millimeters) to keep their computers running smoothly. **FSTFF** allows you to export these files into production-ready formats (JPG/TIFF) at their original full size automatically, with just a few clicks.

---

## 🛠️ Key Features

* **⚡ Auto Scale 1:10 (Precision Mode):** Automatically converts small-scale design files into giant print-ready sizes without losing detail.
* **📦 Batch Engine:** Export an entire folder containing hundreds of TIFF files in one go!
* **🎯 Target DPI Control:** Adjust the output resolution to match your printing machine's requirements.
* **☀️ Brightness Enhancer:** Fine-tune image brightness directly before exporting.
* **✂️ Outline (PX) Clipping:** A feature to add or trim borders/edges with precision.
* **🔍 System Source Inspection:** Automatically detects color profiles and original dimensions before processing.

---

## 💡 Parameter Guide (Prevention of System Hangs)

To maintain your PC's performance and stability, please use the following recommended values:

| Parameter | Recommendation | Important Note |
| :--- | :--- | :--- |
| **Target DPI** | **72 - 300 DPI** | For large-scale prints (Billboards/Banners), **72 DPI** is usually sufficient. Entering values above 300 DPI on large files can cause your PC to *Freeze* or *Crash* due to extreme RAM usage. |
| **Brightness** | **1.0 - 1.2** | A value of **1.0** is standard. If your machine's output tends to be dark, increase to **1.1** or **1.2**. Avoid excessively high values to prevent color distortion. |
| **Outline (PX)** | **0 - 50 PX** | Used to remove edges or add a thin black margin. If not needed, keep it at **0**. |

---

## 🖥️ How to Use

1.  **Select Mode:** Use `SINGLE PROCESS` for a single file or `BATCH ENGINE` for an entire folder.
2.  **Load Source:** Import your TIFF files (exported from your design software at 1:10 scale).
3.  **Set Parameters:** Follow the recommendation table above for optimal results.
4.  **Execute:** Click **EXECUTE ENGINE** and wait for the progress bar to complete.
5.  **Output:** The print-ready `.jpg` files will appear in the same directory as the source files.

---

## 🔓 License & Community
This application is **100% FREE** and open for everyone in the printing industry. There are no subscription fees. Built by the community, for the community, to accelerate our daily production workflow.

---

## 📋 Requirements
* **OS:** Windows 10/11 (64-bit).
* **Standalone:** Runs directly from the `.exe` file. No Python installation required.
* **Minimum RAM:** 
  * **8 GB RAM:** Recommended for standard small to medium format prints.
  * **16 GB+ RAM:** Highly recommended for large format prints (e.g., billboards over 5 meters) or when using the Batch Engine to avoid system instability.

---

## 🤝 Support & Donation

If this project makes your work easier, consider providing support to keep the development of new features going:

| Platform | Link |
| :--- | :--- |
| **Ko-fi** | [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/a80ul) |
| **Saweria** | [![Saweria](https://img.shields.io/badge/Saweria-Donasi-orange?style=for-the-badge&logo=heart)](https://saweria.co/A80ul421) |

