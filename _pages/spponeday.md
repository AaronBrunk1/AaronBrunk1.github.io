---
title: "One-day workshop SPP2256"
permalink: /spponeday/
layout: single
author_profile: false
classes: wide
---


## About the Workshop

This one-day workshop aims to bridge mathematical theory, numerical analysis, and practical computation by bringing together foundational concepts and hands-on tools. We focus on the derivation of gradient flow formulations and the incompressible Navier-Stokes equations and subsequent time discretisation techniques, providing participants with a unified perspective on modern PDE modeling and simulation. 
Complementing the theoretical sessions, practical tutorials on **Git** and **NGSolve** equip participants with essential skills for reproducible, collaborative, and efficient scientific computing. The workshop is designed to foster understanding, cross-disciplinary dialogue, and immediate applicability in research and teaching.

## Date & Location
- **Date:** 21-22 September 2026  
- **Location:** Universität Regensburg, Germany

## Schedule
### Monday

| Time          | Topic            | Speaker |
|---------------|------------------|---------|
| 13:15–14:45   | Lecture: Gradient flows   | Brunk       |
| 15:15–16:45   | Lecture: Navier–Stokes    | Brunk       |

### Tuesday

| Time          | Topic                     | Speaker |
|---------------|---------------------------|---------|
| 08:15–10:00   | Lecture: Zeitdiskretisierung       | Brunk       |
| 10:30–12:00   | HandsOn: Git + Tutorial            | Höhn       |
| 13:00–15:00   | HandsOn: NGSolve + Tutorial        | Höhn       |

## Prerequisites
Participants are asked to **complete the installations below before the workshop**.

## 1. Git (Version Control)

Please install **either Git (command line)** or **GitHub Desktop (GUI)**.
### Windows
- Install **Git for Windows** https://git-scm.com/download/win  
- *OR* GitHub Desktop  https://desktop.github.com/

### macOS
- Install **Git** (if not already present): brew install git
- *OR* GitHub Desktop https://desktop.github.com/

### Ubuntu / Linux 
- sudo apt update
- sudo apt install gi
- git --version


## 2. NGSolve (Numerical PDE Library)

The hands-on session uses **NGSolve installed via Python**.  
### Requirements
- **Python 3.9 or newer**
- Internet connection

### Virtual Environment
- sudo apt install python3 python3-pip python3-venv

### Win
- python -m venv ngsolve-env
- ngsolve-env\Scripts\activate

### macOS/Linux
- python3 -m venv ngsolve-env
- source ngsolve-env/bin/activate

### Installation
- python -m pip install --upgrade pip
- python -m pip install numpy scipy matplotlib jupyter
- python -m pip install --upgrade ngsolve webgui_jupyter_widgets



## Contact

Email: abrunk@uni-mainz.de

