# Marks-Analyzer-and-Grading-System

This Python script reads student marks from a `marks.csv` file, calculates the total marks, overall percentage, and a corresponding letter grade for each student. It then prints a class report and statistics to the console and saves the full report to a new file named `report.csv`.

---

## 🚀 Getting Started

### Prerequisites

You need **Python 3.x** installed on your system. No external libraries are required, as the script only uses the built-in `csv` module.

### Input File

The script requires an input file named **`marks.csv`** in the same directory. This CSV file must contain the following columns, with marks assumed to be out of **100** for each subject:

| Column Name | Description | Example Data |
| :--- | :--- | :--- |
| `Roll` | Student's Roll Number | `01`, `02` |
| `Name` | Student's Full Name | `Alice Smith`, `Bob Johnson` |
| `Calculus` | Marks in Calculus | `85`, `72` |
| `Physics` | Marks in Physics | `92`, `65` |
| `Chemistry` | Marks in Chemistry | `78`, `88` |
| `English` | Marks in English | `60`, `95` |
| `Computer Science` | Marks in Computer Science | `98`, `80` |

### How to Run

1.  Ensure you have your `marks.csv` file ready.
2.  Save the Python code as a file (e.g., `process_marks.py`).
3.  Open your terminal or command prompt.
4.  Navigate to the directory where you saved the files.
5.  Run the script using the Python interpreter:

```bash
python process_marks.py
