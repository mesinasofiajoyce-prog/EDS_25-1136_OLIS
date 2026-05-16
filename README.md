##  Project Description

This project is a Python-based data analysis and statistical evaluation system designed to assess the performance and repeatability of a robotic arm system. The study focuses on analyzing robotic arm motion data, including positional coordinates, joint movements, and end-effector trajectories, in order to evaluate accuracy, consistency, and measurement uncertainty.

The implementation follows an object-oriented programming (OOP) structure, where the entire workflow is organized into modular classes and methods for data loading, preprocessing, statistical computation, and visualization. This design ensures a clear separation of concerns and improves code reusability and scalability.

The dataset used in this study is obtained from online sources and existing robotic arm research datasets. It is processed to extract meaningful performance indicators such as positional deviation, repeatability error, and statistical variation across multiple trials.

Through exploratory data analysis and visualization, the system provides insights into the kinematic behavior of the robotic arm, highlighting patterns in movement consistency and sources of mechanical or measurement error. The results of this project can be used for improving robotic control systems, calibration accuracy, and industrial automation reliability.


## How to Run the Project

### 1. Clone or Download the Project
If using Git:
git clone <your-repository-link>
cd <your-project-folder>

Or simply download and extract the ZIP file.

---

### 2. Create a Virtual Environment 
This helps keep dependencies clean and avoids version conflicts.

python -m venv venv

Activate the virtual environment:

Windows:
venv\Scripts\activate

Mac/Linux:
source venv/bin/activate

---

### 3. Install Required Libraries
Install all dependencies using the requirements.txt file:

pip install -r requirements.txt

---

### 4. Run the Main Python Program
Run the main script of the project:

python main.py

---

### 5. Expected Output
After running the program, the system will:

- Load and preprocess robotic arm motion or kinematic dataset (position, joint angles, or end-effector coordinates)
- Perform statistical analysis of robotic arm performance such as:
  - Mean positioning error
  - Standard deviation of repeated trials
  - Maximum deviation (worst-case error)
  - Repeatability index of the robotic arm
- Generate visualizations 
---

### Notes
- Make sure you are using Python 3.8 or higher
- Ensure all dataset files are placed in the correct folder (e.g., /data)
- If errors occur, reinstall dependencies using pip install -r requirements.txt
