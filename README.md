# 🤖 Self-Balancing Bot — Minor Project Report

> **PID Implementation on a Self-Balancing Bot**  
> Minor Project | Bachelor's Degree in Computer Engineering  
> Department of Electronics and Computer Engineering, Purwanchal Campus, IOE, Tribhuvan University

---

## 👥 Team

| Name | Roll No. |
|------|----------|
| Bishakha Pokhrel | PUR078BEI010 |
| Rudra Khatri | PUR078BEI031 |
| Sneha Yadav | PUR078BEI040 |
| Susant Dahal | PUR078BEI046 |

**Supervisor:** Er. Manoj Kumar Guragai  
**Submission Date:** March 2, 2025  
**Defense Status:** ✅ Successfully defended

---

## 📂 Repository Structure

```
self-balancing-bot-report/
│
├── README.md                        # Project overview (this file)
├── Minor_Project_Report_Final.pdf   # Full project report
│
├── design/                          # CAD & circuit design files
│   ├── cad/
│   │   ├── bot_assembly.SLDASM      # SolidWorks assembly file
│   │   ├── *.SLDPRT                 # Individual part files
│   │   └── images/
│   │       ├── SOLIDWORKS.jpg       # CAD render/screenshot
│   │       ├── botbase.jpg          # Bot base design
│   │       └── botbase2.jpg         # Bot base (alternate view)
│   └── schematics/
│       └── circuit_diagram.*        # Circuit/wiring diagram
│
├── manufacturing/                   # Build process documentation
│   ├── images/                      # Build photos
│   └── videos/
│       └── botmanufacturing.mp4     # Assembly walkthrough video
│
├── testing/                         # Testing & results
│   ├── pid/
│   │   ├── images/
│   │   │   ├── pidbeforeresponse.png  # System response BEFORE PID tuning
│   │   │   ├── afterpidresponse.png   # System response AFTER PID tuning
│   │   │   ├── pidtuning.jpg          # PID tuning process
│   │   │   └── piduningweb.jpg        # PID tuning via web interface
│   │   └── data/
│   │       └── pid_tuning_data.*      # Experimental tuning data
│   ├── hardware/
│   │   └── videos/
│   │       └── mpucallibration.mp4    # MPU6050 calibration demo
│   └── results/
│       ├── data/
│       │   └── mpudata.mp4            # MPU sensor data recording
│       └── videos/
│           ├── result1.mp4            # Test run 1
│           ├── result2.mp4            # Test run 2
│           ├── result3.mp4            # Test run 3
│           ├── jittering.mp4          # Jittering behavior (before fix)
│           └── testingbot.mp4         # Final bot test
│
├── code/
│   └── self_balancing_bot.ino        # Arduino source code (PID implementation)
│
└── data/
    └── experimental_data.*           # Raw sensor/experimental data (if applicable)
```

---

## 🔧 Hardware Components

| Component | Purpose |
|-----------|---------|
| Arduino Nano | Microcontroller |
| MPU6050 | Gyroscope & Accelerometer |
| L298N Motor Driver | Motor control |
| Encoder Motors | Speed feedback |
| Battery, Jumper Wires, Breadboard | Power & connections |

---

## 💻 Software Tools

| Tool | Purpose |
|------|---------|
| Arduino IDE | Programming the Arduino Nano |
| SolidWorks | CAD design of bot frame |
| Serial Plotter | Real-time sensor data visualization |

---

## 📊 Results & Key Observations

- ✅ Bot successfully maintains balance using PID control
- ⚠️ Minor oscillations observed — requires further PID fine-tuning
- ✅ Encoder feedback improves stability
- ✅ Successfully demonstrated during Minor Project Defense

**Before vs. After PID Tuning:**

| | Before | After |
|-|--------|-------|
| Response | Unstable, large oscillations | Stable with minor jitter |
| Balance duration | Short | Sustained |

**Future Improvements:**
- Better PID parameter optimization
- Improved sensor calibration
- More rigid frame for mechanical stability

---

## 🚀 How to Use This Repository

1. **📄 Read the Report** — `Minor_Project_Report_Final.pdf` covers all theory, hardware, and control logic
2. **🎥 Watch the Videos** — Browse `manufacturing/` and `testing/` to see the build and test process
3. **🔩 View the CAD Design** — Open `.SLDASM` in SolidWorks or view screenshots in `design/cad/images/`
4. **💻 Try the Code** — Upload `code/self_balancing_bot.ino` to an Arduino Nano and tune PID values

---

## 📜 License

This project report is shared for **educational purposes**.  
You may reference or use it for learning but must give appropriate credit to the authors.

---

⭐ *If you find this project helpful, consider starring the repository!*
