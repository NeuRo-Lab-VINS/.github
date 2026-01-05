# Contributing to NeuRo-Lab VINS Projects

First off, thank you for considering contributing to our research! This guide helps to maintain the laboratory standards and facilitates collaboration.

##  Branching Strategy
Please do not commit directly to the `main` branch. Use the following naming convention:

* **New Features:** `feature/feature-name` (e.g., `feature/imu-calibration`)
* **Bug Fixes:** `fix/bug-name` (e.g., `fix/camera-driver`)
* **Documentation:** `docs/topic` (e.g., `docs/installation-guide`)

##  Commit Messages
Commit messages should be clear and use the imperative mood:
* ✅ Good: `Add wheel odometry support to VINS`
* ❌ Bad: `added some code`

##  Code Style
* **C++:** Follow the Google C++ Style Guide or ROS C++ Style Guide.
* **Python:** Follow PEP 8 standards.
* Variable and function names must be in English and descriptive.

##  Testing
Before submitting your code, ensure that it builds successfully and does not break existing algorithms.

---
Thank you,
NeuRo-Lab Team
