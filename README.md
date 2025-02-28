# DSS5105 Exercise #1 - Checkerboard Pattern

##  Project Overview 
This project aims to generate a **synthetic checkerboard pattern** using Python and `matplotlib`.The core task involves: 
- Initializing a Git repository 
- Making and committing changes 
-Pushing code to a remote GitHub repository 
- Working with branches (Bonus Task) 

##  Repository Introduction 
This repository contains: 
- **`checkerboard.py`** : A Python script to generate and display a checkerboard pattern. 
- **`README.md`** : Instructions on how to run the project and understand the Git workflow. 
- **Two Git branches**: 
	- `main` :The primary branch containing the initial checkerboard script. 
	- `change-colormap`: A modified version with a different colormap. 

## Getting Started

### 1. Clone the Repository
To get started, clone the repository to your local machine:

```bash
git clone https://github.com/rongrrrrrr/my_project_remote.git
cd my_project_remote
```

### 2. Setup the Environment
Ensure you have Python installed. You can set up a virtual environment (optional):

```bash
python3 -m venv env
source env/bin/activate  # On macOS/Linux
env\Scripts\activate  # On Windows
```

Then, install the required dependencies:

```bash
pip install numpy matplotlib
```

### 3. Run the Checkerboard Script
Execute the Python script to generate and display the checkerboard pattern:

```bash
python3 checkerboard.py
```

### 4. Modify the Colormap
Switch to the `change-colormap` branch and run the updated script with a different colormap:

```bash
git checkout change-colormap
python3 checkerboard.py
```

### Author
**[Rong Rong]**  
National University of Singapore  
Semester 2, AY2024-25
```
