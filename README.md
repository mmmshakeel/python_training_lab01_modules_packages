# Python Modules and Packages Training 📦

Welcome to the hands-on repository for learning Python modules, packages, and dunder mechanisms! This project is designed to help you understand how Python handles file execution and code organization.

## 🛠️ Repository Structure

This repository is organized into three progressive Git branches. Each branch adds a new concept on top of the previous one:

1. `feature/01-modules`: Core concepts of modules, scripts, and the `__name__` variable.
2. `feature/02-packages`: Organizing modules into a package directory using `__init__.py`.
3. `feature/03-execution`: Making an entire package directory executable using `__main__.py`.


## How to Use This Repo

Follow these steps to explore the concepts sequentially:

### Step 1: Clone the Repository
```bash
git clone git@github.com:mmmshakeel/python_training_lab01_modules_packages.git
cd python_training_lab01_modules_packages
```

### Step 2: Explore Basic Modules
Switch to the modules branch to see how `__name__` changes between direct scripts and imports.
```bash
git checkout feature/01-modules
python3 main.py
```
#### Folder structure
```
python_training_lab01_modules_packages/
├── geometry.py
└── main.py
```

### Step 3: See Package Initialization
Switch to the packages branch to watch `__init__.py` automatically execute upon importing a folder.
```bash
git checkout feature/02-packages
python3 main.py
```
#### Folder structure
```
python_training_lab01_modules_packages/
├── main.py
└── shapes/
    ├── __init__.py
    └── geometry.py
```

### Step 4: Execute a Package Directory
Switch to the execution branch to run the entire folder directory directly as a script using the module flag.
```bash
git checkout feature/03-execution
python3 -m shapes
```
#### Folder structure
```
python_training_lab01_modules_packages/
└── shapes/
    ├── __init__.py
    ├── __main__.py
    └── geometry.py
```
