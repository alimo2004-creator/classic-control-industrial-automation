# CAD Simu Industrial Automation Projects
 
🏆 **1st Place Ranking - IEEE ASUB Workshop Final Assessment (Score: 98.2%)**
 
A collection of electrical control and automation schematic projects developed during the IEEE ASUB Workshop. These projects showcase practical PLC-based motor control systems, relay logic design, and industrial automation circuits.
 
**Workshop:** IEEE ASUB Workshop - Automation & Industrial Control  
**Technology:** CAD Simu Classic Industrial Automation Software  
**Focus Area:** Electrical Control Systems & Industrial Automation  
**Developed by:** Ali Mohamed Ahmed, Mechatronics & Robotics Engineering Student (Ain Shams University)
 
---
 
## 💼 Technical Expertise
 
This repository represents hands-on projects developed during intensive training in:
- **Electrical Automation** - Industrial control circuits and relay logic
- **PLC Programming** - Ladder logic and sequential control
- **Motor Control Systems** - 3-phase motor operation and protection
- **Safety Systems** - Emergency stops, interlocks, and fail-safes
- **CAD Design** - Professional schematic documentation in CAD Simu
**Related Skills:** SolidWorks CAD/CAM (CSWA), MATLAB/Simulink, Ladder Logic, AutoCAD, CNC Operations
 
---
 
## 📋 Overview
 
This repository contains CAD Simu electrical automation projects focused on designing and simulating industrial control circuits. Projects demonstrate practical applications of motor control, relay logic, PLC programming, and real-world automation scenarios using standard electrical components and control devices.
 
---
 
## 🎯 Key Projects
 
### Project 1: Basic Motor Control with Start/Stop Logic
**Description:** Fundamental motor control circuit demonstrating basic start/stop operations with safety interlocks.  
**Components:**
- 3-phase AC motor with thermal overload protection
- Start/Stop push buttons with latching relay logic
- Main contactor (KMAIN) and backup contactor (KSTAR)
- Overload relay and kill/delete logic for safe shutdown
- Emergency stop functionality
**Complexity Level:** Beginner  
**Skills Demonstrated:** Basic relay logic, motor protection, control circuit fundamentals
  
![start stop](images/start_stop)
![leds](images/leds_start_stop)

---
 
### Project 2: Advanced Motor Control with Forward/Reverse Operation
**Description:** Dual-direction motor control system with forward/reverse selection and safety interlocks to prevent simultaneous forward/reverse activation.  
**Components:**
- 3-phase AC motor
- Forward (FWD) and Reverse (REV) contactors with mechanical interlock
- Start/Stop controls with selector switch
- Protective devices: thermal overload relays (KDEL, KSTAR)
- Anti-plugging circuit design
**Complexity Level:** Intermediate  
**Skills Demonstrated:** Bidirectional motor control, safety interlocking, control logic optimization

![fwd_rev1](images/led_fwd_reverse) 
![fwd_rev2](images/forward_reverse) 
 
---
 
### Project 3: Multi-Station Control System
**Description:** Complex automation system controlling multiple motor stations with synchronized start/stop and independent speed controls. Demonstrates scalable control architecture.  
**Components:**
- Multiple 3-phase AC motors (M1, M2, M3)
- Distributed relay logic for each station
- Time delay relays (T1, T2, T3) for sequencing
- Individual stop buttons per station
- Master control with selective activation
**Complexity Level:** Advanced  
**Skills Demonstrated:** Multi-motor coordination, timing circuits, distributed control systems, sequence management

![continues](images/continues)
![alternating](images/depending_alternating)
 
---
 
### Project 4: Process Control with Timing and Interlocking
**Description:** Comprehensive control circuit demonstrating timed sequences and safety interlocks for coordinated industrial processes.  
**Components:**
- 3-phase motors with soft-start capability
- Multiple time-delay relays creating process sequences
- Interlock circuits preventing unsafe simultaneous operations
- Stop and emergency shutdown logic
- Green/Red indicator lights for system status feedback
**Complexity Level:** Advanced  
**Skills Demonstrated:** Process automation, timing logic, status indication, safety design principles

![delta](images/delta_star)
![dependingalternating](images/depending)
 
---
 
## 📁 Project Structure
 
```
├── Session_4_Task_1/
│   ├── schematic.cad
│   ├── README.md
│   └── documentation/
│
├── CADe_S1/
│   ├── schematic.cad
│   ├── README.md
│   └── documentation/
│
├── Task_1_2D/
│   ├── schematic.cad
│   ├── README.md
│   └── documentation/
│
├── Session_2_Task_1/
│   ├── schematic.cad
│   ├── README.md
│   └── documentation/
│
└── Advanced_Multi_Motor_Systems/
    ├── schematic.cad
    ├── README.md
    └── documentation/
```
 
---
 
## 🚀 Getting Started
 
### Prerequisites
- **CAD Simu Classic** (Industrial Automation version)
- Recommended: 4GB RAM minimum
- Windows/Linux compatible system
- Basic understanding of electrical schematics and relay logic
### Installation
 
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/cade-simu-automation.git
   cd cade-simu-automation
   ```
 
2. **Open a project:**
   - Launch CAD Simu Classic
   - Navigate to the desired project folder
   - Open the `.cad` schematic file
   - Use CAD Simu's simulation mode to test the control circuit
3. **Review documentation:**
   - Each project includes detailed README with circuit explanation
   - Check `documentation/` for component specifications and control logic flowcharts
   - Review wiring diagrams and safety interlocks
---
 
## 🔧 Core Technologies & Components
 
### Control Devices
- **Contactors (K1, K2, K3, KMAIN, KSTAR):** Power switching devices for motor circuits
- **Relays (KDEL, KSTAR):** Logic control and auxiliary switching
- **Time-Delay Relays (T1, T2, T3):** Sequential timing for process control
- **Thermal Overload Relays:** Motor protection against overcurrent
### Circuit Elements
- **Start/Stop Push Buttons:** User interface for control
- **Emergency Stop (E-Stop):** Safety shutdown mechanism
- **Indicator Lights:** Status feedback (Green/Red)
- **Selector Switches:** Mode selection (Forward/Reverse)
- **Power Supply Lines:** (L1, L2, L3) 3-phase power distribution
### Motors
- **3-Phase AC Induction Motors:** Industrial standard power elements
- **Motor Protection:** Thermal overload and short-circuit protection
---
 
## 📊 Technical Specifications
 
| Aspect | Details |
|--------|---------|
| **Software** | CAD Simu Classic (Industrial Automation) |
| **Diagram Type** | Electrical Control Schematics (IEC Standard) |
| **Control Type** | Relay Logic & PLC-based automation |
| **Power System** | 3-Phase AC (50/60 Hz) |
| **Motor Types** | Squirrel-cage induction motors |
| **Complexity Range** | Beginner to Advanced |
| **Simulation Type** | Discrete logic simulation |
 
---
 
## 💡 Key Concepts Demonstrated
 
- **Motor Control Fundamentals:** Starting, stopping, and direction control
- **Relay Logic Design:** Combinatorial and sequential circuits
- **Safety Interlocks:** Preventing hazardous simultaneous operations
- **Overload Protection:** Thermal and electronic protection strategies
- **Time-Delay Circuits:** Sequential control and process timing
- **Emergency Stop Systems:** Critical safety mechanisms
- **Status Indication:** Visual feedback through indicator lights
- **Bidirectional Control:** Forward/Reverse motor operation
- **Multi-Motor Coordination:** Synchronized or sequential motor activation
- **Soft-Start Circuits:** Smooth motor acceleration
- **Control Architecture Scaling:** From single motor to multi-station systems
---
 
## 🎓 Learning Path & Progression
 
### Beginner Level
Start with **Project 1: Basic Motor Control** to understand:
- Simple relay logic circuits
- Motor protection mechanisms
- Start/Stop control fundamentals
- Safety interlocks and emergency stop
### Intermediate Level
Progress to **Project 2: Forward/Reverse Control** to learn:
- Bidirectional motor operation
- Mechanical and electrical interlocks
- Protective relay coordination
- Complex control logic design
### Advanced Level
Master **Projects 3 & 4** for expertise in:
- Multi-motor coordination and synchronization
- Timing sequences and process control
- Large-scale automation architecture
- Industrial-grade safety systems
---
 
## 📝 How to Use These Projects
 
### For Learning:
1. **Study the Schematic:**
   - Trace the control logic path from input to output
   - Identify power circuits vs. control circuits
   - Understand component interconnections
2. **Simulate & Experiment:**
   - Run the circuit simulation in CAD Simu
   - Activate start/stop buttons and observe responses
   - Test emergency stop functionality
   - Verify overload protection triggers
3. **Modify & Test:**
   - Change timing relay settings
   - Adjust overload thresholds
   - Add additional control elements
   - Document observed behaviors
### For Reference:
- Use these circuits as templates for similar automation tasks
- Adapt relay logic for your specific applications
- Study safety interlock design patterns
- Reference proper schematic drawing standards
### For Documentation:
- Each project includes detailed component lists
- Pin connections and terminal mappings documented
- Control logic flowcharts provided
- Circuit behavior descriptions and operational sequences explained
---
 
## 🔌 Reading the Schematics
 
### Schematic Conventions Used:
- **Blue Lines:** Main power circuit (L1, L2, L3)
- **Red Lines:** Control/signal circuits
- **K1, K2, K3:** Contactors (three-phase power switches)
- **KMAIN, KSTAR:** Main and backup contactors
- **KDEL:** Delete/abort contactor
- **T1, T2, T3:** Time-delay relays for sequencing
- **E (coil symbol):** Emergency stop elements
- **Green/Red circles:** Indicator light feedback
---
 
## 🎓 Learning Resources
 
### Official Documentation
- [CAD Simu Documentation](https://www.cadsimulator.com)
- IEEE ASUB Workshop Training Materials
- IEC 60617 Electrical Symbols Standard
### Recommended Reading
- **"Industrial Motor Control"** - Fundamental motor protection and control
- **"Programmable Logic Controllers"** - PLC fundamentals applicable to relay logic
- **"Electrical Installation Work"** - Safety standards and wiring practices
- CAD Simu User Manual - Software-specific features
### Key Standards
- **IEC 60617:** Electrical circuit symbols
- **IEC 61131-3:** Industrial control programming
- **EN 60204-1:** Safety of machinery - Electrical equipment
---
 
## 🛠️ Troubleshooting & Tips
 
### Common Issues
 
| Problem | Solution |
|---------|----------|
| **Schematic won't simulate** | Verify all connections are complete; check for floating nodes |
| **Motor won't start** | Confirm START button logic; check that KMAIN coil is energized |
| **Thermal overload not triggering** | Verify overload relay settings; ensure proper current flow |
| **Forward/Reverse both active** | Check mechanical/electrical interlocks between FWD and REV |
| **Timing sequence incorrect** | Review time-delay relay settings (T1, T2, T3 values) |
 
### Best Practices
- Always include emergency stop in your circuits
- Use mechanical interlocks on reversing contactors
- Label all components clearly for maintenance
- Document logic sequences with state diagrams
- Test circuits thoroughly before implementation
---
 
## 📋 Component Reference
 
### Standard Components Used
 
| Component | Symbol | Function |
|-----------|--------|----------|
| **Contactor** | K1, K2 | Power switching for motors |
| **Relay** | KDEL, KSTAR | Logic switching and protection |
| **Timer Relay** | T1, T2, T3 | Delayed switching for sequences |
| **Thermal Overload** | PE, U1, V1, W1 | Motor overcurrent protection |
| **Push Button** | START, STOP | User control inputs |
| **Emergency Stop** | E-STOP | Rapid shutdown system |
| **Motor** | M | Power conversion element |
| **Indicator Light** | Green/Red circles | Status feedback |
 
---
 
## 📈 Expected Learning Outcomes
 
After completing these projects, you will understand:
- ✅ How to design basic to complex motor control circuits
- ✅ Proper use of protection devices in industrial applications
- ✅ Safety interlock design principles
- ✅ Time-delay relay applications for sequencing
- ✅ Forward/reverse control with safety considerations
- ✅ Multi-motor coordination and control
- ✅ How to read and create professional electrical schematics
- ✅ IEC 60617 standard electrical symbols and conventions
---
 
## 🤝 Contributing
 
Contributions and improvements are welcome! Help us expand this collection of automation projects.
 
### How to Contribute:
 
1. **Fork the repository**
   ```bash
   git clone https://github.com/yourusername/fork-of-repo.git
   ```
 
2. **Create a feature branch:**
   ```bash
   git checkout -b feature/new-automation-circuit
   ```
 
3. **Add your project:**
   - Create a new project folder with clear naming
   - Include `.cad` schematic file
   - Add detailed README explaining the circuit
   - Document all components and their functions
   - Include safety considerations
4. **Commit and push:**
   ```bash
   git add .
   git commit -m 'Add: [Project Name] - [Brief Description]'
   git push origin feature/new-automation-circuit
   ```
 
5. **Open a Pull Request**
   - Describe the circuit and learning objectives
   - Include schematic screenshots
   - Reference any standards (IEC 60617, EN 60204-1, etc.)
### Contribution Guidelines:
- ✅ Use IEC 60617 standard symbols
- ✅ Include comprehensive documentation
- ✅ Document all safety interlocks
- ✅ Test circuits thoroughly before submitting
- ✅ Follow existing project structure
- ✅ Add comments explaining complex logic
- ✅ Include component specifications and ratings
- ✅ Verify schematic clarity and readability
---
 
## 📋 Documentation Checklist
 
For each project submission, include:
- [ ] Schematic diagram in `.cad` format
- [ ] Component list with specifications
- [ ] Operation description and control logic explanation
- [ ] Safety considerations and interlocks
- [ ] Timing diagrams (if applicable)
- [ ] Troubleshooting guide
- [ ] PDF export of schematic for easy viewing
- [ ] Test results and verification data
---
 
## 📄 License
 
[MIT License](LICENSE) - Feel free to use, modify, and distribute these educational projects.
 
---
 
## 🙏 Acknowledgments
 
- **IEEE ASUB Workshop** - Organizers and instructors for the comprehensive training program
- **CAD Simu Development Team** - For providing excellent automation design tools
- **Industrial Automation Community** - For standardized practices and best practices
- **Workshop Participants** - Fellow learners and collaborators
---
 
## 👤 Author
 
**Ali Mohamed Ahmed**  
Mechatronics & Robotics Engineering Student | Ain Shams University  
**Email:** alimohamedahmedhassan2004@gmail.com  
**Phone:** +20 1020120158  
**Location:** Nasr City, Cairo, Egypt  
 
**Certifications:**
- 🏆 IEEE Automation & Industrial Control - Ranked 1st (98.2%)
- 🏆 CSWA (Certified SolidWorks Associate)
- 🏆 OSHA Occupational Health & Safety
- 🏆 PMI Project Management
**GitHub:** [alimo2004-creator](https://github.com/alimo2004-creator)  
**LinkedIn:** [Ali Mohamed Ahmed](https://www.linkedin.com/in/ali-mohamed-ahmed)  
 
---
 
## 📞 Support & Contact
 
### Getting Help:
- 📧 **Email:** alimohamedahmedhassan2004@gmail.com
- 💬 **GitHub Issues:** Report bugs or ask questions
- 💡 **Discussions:** Share ideas and solutions
- 🔗 **LinkedIn:** [Connect with me](https://www.linkedin.com/in/ali-mohamed-ahmed)
- 📱 **WhatsApp:** +20 1020120158
### Common Questions:
 
**Q: How do I simulate these circuits?**  
A: Open the `.cad` file in CAD Simu, go to Mode > Simulate, and use the interactive controls to test the circuit behavior.
 
**Q: Can I modify these circuits for my specific application?**  
A: Absolutely! These are educational projects designed to be adapted. Maintain safety standards and test thoroughly.
 
**Q: What version of CAD Simu is required?**  
A: These projects were created with CAD Simu Classic. Compatibility may vary with other versions.
 
**Q: How do I interpret the schematic symbols?**  
A: Refer to the IEC 60617 standard. Most symbols are explained in each project's documentation.
 
---
 
## 📅 Repository Updates
 
**Last Updated:** [Update with your date]  
**Version:** 1.0  
**Status:** Active Development
 
---
 
## 🚀 Future Enhancements
 
Planned additions to the repository:
- [ ] Video tutorials for each circuit
- [ ] Interactive simulation walkthroughs
- [ ] PLC ladder logic equivalents
- [ ] 3D mechanical assembly integration
- [ ] Advanced process control examples
- [ ] Predictive maintenance circuits
- [ ] Energy efficiency optimization projects
---
 
## 📊 Repository Statistics
 
- **Total Projects:** 4+
- **Complexity Levels:** Beginner to Advanced
- **Components Used:** 50+
- **Educational Value:** Comprehensive motor control knowledge
---
 
**⭐ If you find these projects helpful and educational, please consider leaving a star!**
 
**🔗 Share your learning journey using #CADeSimuAutomation #IEEEASUBWorkshop**
