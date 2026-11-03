
# 🔭 The Exoplanet Hunter

### Recovering an exoplanet transit signal using NASA Kepler observations and Python

## 🌌 About the Project

The Exoplanet Hunter is a beginner-level astronomical data science project focused on understanding how scientists detect exoplanets using the transit method.

When a planet passes in front of its host star, it blocks a small fraction of the star's light. This produces a tiny, measurable decrease in brightness.

By analysing these brightness variations, we can investigate the presence of an orbiting planet.

In this project, I aim to analyse real observations from NASA's Kepler Space Telescope and attempt to recover the transit signal of **Kepler-10b**.

## 🎯 Project Objectives

- Understand the physics behind the exoplanet transit method.
- Obtain and explore real astronomical observations.
- Extract and visualise stellar brightness measurements.
- Clean and prepare astronomical time-series data.
- Search for periodic transit signals.
- Estimate the orbital period using the Box Least Squares (BLS) algorithm.
- Visualise the recovered transit and interpret the results.

## 🛰️ Dataset

**Mission:** NASA Kepler Space Telescope  
**Target:** Kepler-10  
**Planet of interest:** Kepler-10b  
**Data type:** Stellar photometric observations

Data will be retrieved using the Lightkurve Python package.

## 🛠️ Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Lightkurve
- Jupyter Notebook
- Git and GitHub

## 📊 Planned Analysis

1. Retrieve astronomical observations.
2. Explore the telescope's measurements.
3. Generate stellar light curves.
4. Clean and normalise the observations.
5. Search for periodic signals.
6. Fold the light curve using the estimated period.
7. Compare the recovered signal with the known planet.

## 📁 Project Structure

```text
exoplanet-hunter/
│
├── data/
├── notebooks/
├── figures/
├── src/
├── README.md
├── requirements.txt
└── .gitignore
```

## 📈 Project Status

🟡 In progress — currently setting up the research environment and learning the fundamentals of astronomical data analysis.

## 📚 Learning Goals

This project is an independent learning exercise to explore the intersection of:

- Astrophysics
- Astronomy
- Data Science
- Time-Series Analysis
- Scientific Computing

The aim is not only to build a working analysis pipeline, but also to understand the scientific meaning behind the data and the methods used.

## 👩‍💻 Author

Anuvya Srivastava

*An independent exploration of astronomy through data science.*

