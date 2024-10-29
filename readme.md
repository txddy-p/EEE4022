# 🎮 Optimal Swing-Up on Quanser Pendulum
![MATLAB](https://img.shields.io/badge/MATLAB-R2021a-blue) ![Python](https://img.shields.io/badge/Python-3.8+-green) ![Pyomo](https://img.shields.io/badge/Pyomo-6.4.2-orange) ![IPOPT](https://img.shields.io/badge/IPOPT-3.14.11-red) ![Simulink](https://img.shields.io/badge/Simulink-R2021a-lightblue)

Exploring advanced control strategies for the Quanser QUBE-Servo 2 pendulum system 🤖  
*Part of the EEE4022 Research Project 🎓*

---

## 📚 Project Overview

- **Modelling & Analysis** (Jupyter Notebooks):  
  *System dynamics via Lagrangian mechanics,* with approaches including spherical and rotation matrix-based models. Key analyses cover position/velocity definitions, energy calculations, equations of motion, 3D visualisation, and trajectory optimisation using Pyomo/IPOPT.

- **Control Implementation** (Simulink):  
  Swing-up controllers including energy-based, LQR-based, and sliding mode control (SMC), plus an LQR balance controller for stable positioning. Hardware interface setup for the Quanser QUBE-Servo 2.

- **Key Features**:  
  Complete dynamics modelling, multiple swing-up strategies, trajectory optimisation, 3D visualisation, real hardware implementation, and performance comparisons.

---

## ⭐ Highlights

- **Trajectory Optimisation** – Framework for optimised motion paths.
- **Swing-Up Control** – Energy-efficient (39% lower with SMC), fast (2s with LQR).
- **Real-World Testing** – Simulink-ready for Quanser system.
- **3D Visualisation** – Jupyter-based plotting for model insights.

---

## 🔧 Dependencies

- **MATLAB/Simulink**
- **Python**:
  - *Jupyter, Pyomo, IPOPT*
- **Quanser QUBE-Servo 2**

---

## 📝 Usage Notes

- Multiple modelling options maintained for flexibility.
- Update 3D plotting code with model adjustments.
- Simulink models tested for hardware compatibility.
- Educational resources embedded in notebooks.

---

## 🏆 Results Summary

- **SMC**: 39% energy savings during swing-up.
- **LQR**: Fastest swing-up (2s achieved).
- **Optimised Trajectories**: Demonstrated efficiency in simulation.

## 🎥 Videos
*Coming soon!* Watch the pendulum in action!

## 👥 Contributors
- **Piwani** - *Main Developer* 🚀

---

*Made with ❤️ and lots of ☕*
