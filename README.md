# Student Marks Calculator (Tkinter + OpenCV)

This is a Python GUI application that allows users to input, analyze, visualize, and save student marks using a simple and intuitive interface. It includes statistical analysis tools and integrates a splash screen using OpenCV.

---

## 🚀 Features

- **Grade Input & Validation**
  - Enter grades manually (supports comma-separated values).
  - Load grades from a `.txt` file.
  - Validates that inputs are numeric and within 0–100.

- **Statistical Analysis**
  - Mean
  - Median
  - Mode (handles duplicates)
  - Skewness (asymmetry in the distribution)

- **File Handling**
  - Save current grades and statistics to a `.txt` file.
  - Load grades from an existing `.txt` file.

- **GUI Interface**
  - Built using Tkinter
  - Buttons for each action: Add, Load, Save, Reset, Exit
  - Real-time updates of the marks list
  - Message boxes to show calculated results

- **OpenCV Splash Screen**
  - Professional welcome screen shown before the GUI starts

---

## 🧰 Requirements

Make sure you have the following Python packages installed:

```bash
pip install opencv-python numpy scipy
```

---

## 📁 File Structure

- `student_marks_gui_save_enabled.py` — Main application script
- `Appendix_Student_Marks_Application.txt` — Code explanation appendix
- `README.md` — Project documentation (this file)

