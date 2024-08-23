# FIFA 23 Players Data - Streamlit Learning Project

Welcome to the **FIFA 23 Players Data** project! This repository is designed to help you learn how to use Streamlit by creating an interactive web app that showcases and analyzes player data from FIFA 23. Whether you're new to Streamlit or a football enthusiast looking to explore player statistics, this project provides a practical and engaging introduction.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Running the App](#running-the-app)
- [Project Structure](#project-structure)
- [Features](#features)
- [Customization](#customization)
- [License](#license)

## Introduction

This project demonstrates how to use Streamlit to build a web app that allows users to explore and analyze data about players in FIFA 23. You'll learn how to create interactive widgets, display and filter player data, and visualize statistics with just a few lines of Python code.

## Installation

To get started with this project, you'll need to have Python installed on your machine. You can install the required dependencies using pip:

```bash
pip install streamlit pandas
```

You may also want to create a virtual environment:

```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

Then install the dependencies:
```bash
pip install -r requirements.txt
```

## Running the App
Once you have installed the dependencies, you can run the app with the following command:
```bash
streamlit run 1_🏠_home.py
```

This will launch a local web server, and you can view the app in your web browser at http://localhost:8501.

## Project Structure
1_🏠_home.py.py: The main script that runs the Streamlit app.
datasets/: This directory contains the dataset with FIFA 23 player statistics.
pages/: This directory contains the other pages
requirements.txt: A file listing the Python dependencies needed to run the app.

## Features
- Player Search: Search for specific players by name, club, or nationality.
- Filtering: Filter players based on various attributes like overall rating, potential, position, and more.
- Data Visualization: Visualize player attributes and compare players using interactive charts.

## Customization
Feel free to customize the project by adding new features or modifying the existing ones. Some ideas include:

- Adding more detailed player comparisons.
- Including additional visualizations for player performance metrics.
- Expanding the dataset with more detailed statistics or historical data.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
