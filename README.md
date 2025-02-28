# **HAII_Assignment_3**

This repository contains the materials and code for Assignment 3 of the HAII course. The assignment focuses on data analysis and visualization related to various causes of death by age.

## **Table of Contents**

- [Project Overview](#project-overview)
- [Setup Instructions](#setup-instructions)
  - [1. Clone the Repository](#1-clone-the-repository)
  - [2. Set Up a Virtual Environment](#2-set-up-a-virtual-environment)
  - [3. Activate the Virtual Environment](#3-activate-the-virtual-environment)
  - [4. Install Dependencies](#4-install-dependencies)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Notes](#notes)

## **Project Overview**

The project includes:

- **Assignment 3.pdf**: The assignment brief detailing the tasks and objectives.
- **Bayesian_reasoning.md**: A markdown file discussing Bayesian reasoning in the context of the assignment.
- **dataPlotter.py**: A Python script for plotting data related to various causes of death by age.
- **Images**: PNG files visualizing data for different causes of death.

## **Setup Instructions**

To set up the project on your local machine, follow these steps:

### 1. Clone the Repository

```sh
git clone https://github.com/VinzR-2159109/HAII_Assigment_3.git
cd HAII_Assigment_3
```

### 2. Set Up a Virtual Environment

It's recommended to use a virtual environment to manage dependencies:

```sh
python -m venv venv
```

This command creates a virtual environment named `venv` in the project directory.

### 3. Activate the Virtual Environment

Activate the virtual environment to isolate project dependencies:

- **Windows (Command Prompt):**

  ```sh
  venv\Scripts\activate
  ```

- **Windows (PowerShell):**

  ```sh
  venv\Scripts\Activate.ps1
  ```

- **macOS/Linux:**

  ```sh
  source venv/bin/activate
  ```

After activation, your terminal prompt will typically include `(venv)` to indicate that you're working within the virtual environment.

### 4. Install Dependencies

With the virtual environment activated, install the required packages:

```sh
pip install -r requirements.txt
```

This command installs all the packages listed in the `requirements.txt` file.

## **Project Structure**

```
HAII_Assigment_3/
│── venv/                           # Virtual environment directory (not included in version control)
│── Assignment 3.pdf                # Assignment brief
│── Bayesian_reasoning.md           # Discussion on Bayesian reasoning
│── dataPlotter.py                  # Script for data plotting
│── requirements.txt                # List of required Python packages
│── death_counts_by_age.png         # Visualization of death counts by age
│── drug_use_deaths_by_age.png      # Visualization of drug use deaths by age
│── flu_deaths_by_age.png           # Visualization of flu deaths by age
│── motor_vehicle_accident_deaths_by_age.png  # Visualization of motor vehicle accident deaths by age
```

## **Usage**

To run the data plotting script:

```sh
python dataPlotter.py
```

Ensure that the virtual environment is activated before running the script to access the installed dependencies.

## **Notes**

- The `venv` directory is typically excluded from version control systems like Git. Ensure your `.gitignore` file includes `venv/` to prevent it from being tracked.
- If you encounter issues with package installations, consider upgrading `pip`:

  ```sh
  python -m pip install --upgrade pip
  ```

- To deactivate the virtual environment when you're finished working:

  ```sh
  deactivate
  ```
