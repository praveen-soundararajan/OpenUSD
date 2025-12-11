# OpenUSD Learning Journey  
*A hands-on exploration of Pixar’s Universal Scene Description (USD) and its role in simulation, robotics, and digital twins*

This repository documents my personal learning journey with **OpenUSD**, the core data framework that powers NVIDIA Omniverse and the next generation of 3D simulation, robotics development, and physical AI.  

My objective is to build strong technical fluency with USD—its primitives, schemas, composition arcs, layers, and scene construction—before expanding into Omniverse, Isaac Sim, and large-scale digital twin workflows.  
This is a **public technical notebook** to demonstrate my ability to write code, build USD assets, and understand 3D data systems end to end.

---

## 🎯 Purpose of This Repository

This repo is not a tutorial. Its goal is to show:

- My hands-on experimentation with USD through Python  
- My ability to construct, manipulate, and visualize USD stages  
- My structured progression toward simulation, robotics, and digital-twin engineering  
- My interest in building foundational skills required for Omniverse applications and physical AI systems  

It serves as a visible record of my continuous learning.

---

## 📘 What’s Included

### **1. Jupyter Notebook**  
`OpenUSD_Tutorials.ipynb`  

Captures step-by-step exercises where I explore:

- Creating USD stages  
- Defining and editing prims  
- Working with hierarchy, transforms, and attributes  
- Understanding layers, references, and composition  
- Loading assets and using USD tooling  
- Time-sampled animation experiments  

The notebook grows as I learn more.

---

### **2. Example USD Assets (`assets/`)**

This folder contains simple `.usda` files I created as part of the learning process:

- Basic prim structures  
- Attribute/property exercises  
- Composition arc demonstrations  
- Example scenes used for debugging and visualization  
- Timecode and animation samples  

Each file exists to internalize a specific USD concept.

---

## 🧱 Why I’m Learning OpenUSD

OpenUSD is rapidly becoming the **interoperability standard for 3D worlds**, foundational for:

- Digital twins  
- Robotics simulation  
- Synthetic data generation  
- Industrial and scientific workflows  
- Real-time simulation in Omniverse  
- Sensor-accurate environments for physical AI  

To build robust simulations and robotics workflows, understanding USD at the file, data, and composition level is essential.  
This repository represents my preparation for that future work.

---

## 🚀 Tools & Development Setup

I am using:

- **Python 3.11**  
- **Pixar USD Python bindings**  
- **usdview** for visualization  
- **VS Code + Jupyter** for iterative experimentation  

Install USD with:

```bash
pip install usd-core
```

## 📂 Repository Structure
OpenUSD/
│
├── assets/                    # Example USD files used in exercises
├── OpenUSD_Tutorials.ipynb    # Main learning notebook
├── README.md                  # Documentation
└── .gitignore                 # Excludes unwanted folders/files


## 🔭 What Comes Next

This repository will continue to expand as I deepen my expertise. Upcoming additions include:

- More advanced OpenUSD scenes that incorporate complex composition arcs, layered data models, and richer asset hierarchies.
- Custom USD schemas and metadata experiments to better understand how large-scale digital twin systems structure and manage information.
- Omniverse Kit extensions, where I begin building small tools, UI components, or automation workflows inside the Omniverse ecosystem.
- Early robotics simulations using Isaac Sim, focusing on environment setup, sensor simulation, and training pipelines for physical AI.
- Foundational digital twin prototypes, leveraging OpenUSD for real-time synchronization, simulation, and system modeling.

This repository is a living record of my progression into simulation technologies, robotics platforms, and the broader 3D/AI ecosystem.

Any suggestions, inputs or feedback is most welcome. I am at the very start of my journey.