# Jupyter Setup Exercises

Materials for setting up a Jupyter data science environment and exploring introductory data science concepts.

## Files

### Setup Guides

| File | Description |
|------|-------------|
| `jupyter_setup_guide.md` | Complete step-by-step guide for installing Python, creating virtual environments, and setting up Jupyter Notebook/Lab on Windows, macOS, and Linux |
| `jupyter_quick_reference.md` | Cheat sheet with common commands for daily Jupyter workflow, keyboard shortcuts, pip commands, and troubleshooting tips |

### Setup Scripts

| File | Description |
|------|-------------|
| `setup_jupyter_macos_linux.sh` | Automated setup script for macOS/Linux that creates a project directory, virtual environment, installs Jupyter and data science libraries |
| `setup_jupyter_windows.bat` | Automated setup script for Windows that performs the same setup process via Command Prompt |

### Tutorial Materials

| File | Description |
|------|-------------|
| `data_science_tour.ipynb` | Interactive Jupyter notebook demonstrating core data science skills: data loading, cleaning, filtering, visualization, correlation analysis, group-by operations, feature engineering, and predictive insights |
| `student_performance.csv` | Dataset containing 14,000+ student records with features like study hours, attendance, exam scores, motivation, stress level, and final grades — used in the data science tour notebook |

## Getting Started

1. Follow `jupyter_setup_guide.md` to install Python and Jupyter
2. Or run the appropriate setup script for your OS:
   - macOS/Linux: `chmod +x setup_jupyter_macos_linux.sh && ./setup_jupyter_macos_linux.sh`
   - Windows: Double-click `setup_jupyter_windows.bat`
3. Open `data_science_tour.ipynb` in Jupyter to explore the tutorial

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scipy, scikit-learn
