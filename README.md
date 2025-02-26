# NetFlex - Networked Control Systems (NCS) Simulation Framework

## 📌 Overview
NetFlex is a **MATLAB-based simulation framework** for **Networked Control Systems (NCS)**. It provides an **object-oriented architecture** to model network-induced effects (delays, dropouts, buffering) while implementing control and observer algorithms in a modular fashion.

This toolbox is built on top of **MATLAB Simulink TrueTime** to enable seamless simulation of communication-constrained control systems.

---

## 🚀 Features
✔ **Object-Oriented MATLAB Framework** – Modular and scalable architecture.  
✔ **Flexible Network Nodes** – Includes delay, dropout, and buffering mechanisms.  
✔ **State Feedback & Observer Implementations** – Supports advanced control strategies.  
✔ **Easily Extendable** – Define new nodes, control laws, and observer mechanisms.  
✔ **Integration with Simulink** – Uses TrueTime blocks for real-time network simulations.  
✔ **Predefined Examples** – Ready-to-use NCS simulation setups.  

---

## 📁 Project Structure

```
NetFlex-Framework/
│── docs/                  # Documentation (user guides, UML diagrams)
│── examples/              # Example simulation scripts
│── src/                   # Main MATLAB source code
│   │── core/              # Base classes (abstract classes, utilities)
│   │── nodes/             # Network node implementations
│   │── controllers/       # Control system implementations
│   │── observers/         # Estimation algorithms
│   │── simulations/       # High-level simulation scripts
│   └── utils/             # Helper functions (logging, data handling, etc.)
│── tests/                 # Unit tests for framework components
│── data/                  # Example datasets, simulation results
│── .gitignore             # Ignore unnecessary files
│── README.md              # Project overview
│── LICENSE                # License details
└── requirements.txt       # Dependencies (if any)
```

---

## 🔧 Installation & Setup

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/YOUR-USERNAME/NetFlex-Framework.git
cd NetFlex-Framework
```

### 2️⃣ **MATLAB Setup**
Ensure you have:
- MATLAB R2023a or later
- Simulink & TrueTime Toolbox installed

### 3️⃣ **Run an Example**
Open MATLAB and run:
```matlab
cd examples
run example_simulation.m
```
This will launch a **predefined simulation** of an NCS with delays and dropouts.

---

## 🏗️ Object-Oriented Design (UML Overview)
The framework follows a **class-based architecture**, where each network component is implemented as a **MATLAB class**:

- **`NetworkNode`** → Base class for networked components.
- **`NetworkDelay`** → Implements transmission delay effects.
- **`NetworkDropout`** → Models packet loss in communication.
- **`StateFeedbackController`** → Implements control strategies.
- **`SwitchedLyapunovObserver`** → Observer-based state estimation.
  
Detailed UML diagrams are available in `docs/`.

---

## 📜 Contributing
We welcome contributions!  
- To add a feature, **fork the repository**, make changes, and submit a **pull request**.  
- Report issues or feature requests in the **GitHub Issues** section.

---

## 📄 License
NetFlex is released under the **GPL v3**.  
See [LICENSE](LICENSE) for details.

---

## 👨‍💻 Authors & Acknowledgements
Developed by:  
- Maris Siljak  
- Katarina Stanojevic  

Special thanks to the **Institute of Automation and Control, Graz University of Technology**.

---

## ⭐ Support
If you find this project useful, **star the repository** 🌟 on GitHub!  
