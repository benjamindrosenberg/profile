# Profile
# Benjamin Rosenberg

MS, Cybersecurity Engineering

I am a cybersecurity researcher and engineer with a focus on formal methods, 
AI safety, and automotive security. My work applies modal logic and neuro-symbolic 
architectures to problems in autonomous vehicle safety, intrusion detection, 
and risk analysis — with a parallel interest in the theoretical foundations of 
post-quantum cryptography and quantum information theory. I am equally 
comfortable operating at the hardware level (embedded systems, microcontrollers, 
FPGA) and at the level of formal logical frameworks and learned representations.

A major component of my research has been the use of modal logic as a unifying 
formal structure for access control, risk analysis, and interpretable 
machine learning. My published and submitted work supports the position that 
interpretability and formal rigor in a security-first posture are not in tension 
with performance.

---

## Skills & Tools

| Category | Technologies |
|---|---|
| **Languages** | Python, C/C++, Bash/Shell, SystemVerilog, PCL (machine language) |
| **AI / ML** | PyTorch, NumPy, pandas, Jupyter |
| **Cybersecurity Tools** | Wireshark, Nmap/Nessus, Ghidra, IDA Pro, Metasploit, Burp Suite, ITEMIS Security, Kleopatra |
| **Security Frameworks & Standards** | NIST CSF, ISO 27001, ISO/SAE 21434, J1939-91C, CDS A&A, JVAP |
| **Hardware & Embedded** | Vivado (FPGA/SoC), STLink, PCL |
| **Infrastructure** | Linux, Docker, VMware/VirtualBox, Oracle Cloud |
| **Dev & Research Tools** | Git/GitHub, LaTeX, SQL Server, PostgreSQL |

Graduate coursework includes quantum information theory, real analysis, and two 
mathematically rigorous deep learning seminars.

---

## Projects

| Project | Area | Description | Links |
|---|---|---|---|
| **Neuro-Symbolic Decision Making for Autonomous Vehicles** | AI Safety / AV | Applied a modal logical neural network to AV decision-making; hybrid neuro-symbolic architecture consistently surfaced interpretable safety-relevant predicates (stopping behavior, crosswalk occupancy, pedestrian intent) while performing competitively against MLP baselines. Submitted to ICMLA 2025. | [Repo](#) · [Paper](#) |
| **Causal Intervention-Based Multimodal Fusion for Robust AV Perception** | AI Safety / AV | Applied Pearl's causal hierarchy to a LiDAR-camera fusion architecture (simplified EPNet: PointNet++ point cloud pipeline with spurious correlation injection, ResNet50 image backbone, 2D CNN fusion) to mitigate adversarial perturbations and sensor degradation. Demonstrated improved robustness in knowledge-poor environments and strong learned semantic acuity in knowledge-rich settings. Selected for student symposium presentation; recipient of competitive travel grant. | [Repo](#) |
| **Hybrid Tsetlin Machine / Modal-Logical IDS for CAN Bus Networks** | AI Security / Automotive | Designed a neuro-symbolic IDS architecture combining a Tsetlin machine with a modal logical neural network to generalize role descriptions (modal formulae over CAN frame traffic patterns) from stream windows, then derive atomic FOL constraints from live data — preserving Tsetlin machine performance while reducing sensitivity to masked CAN datasets. Implementation ongoing; current work focuses on resolving Tsetlin machine integration issues. | [Repo](#) |
| **General Modal Logical Risk Analysis Framework** | Security Research | Developed a domain-general risk analysis framework grounded in modal logic, unifying Safety Studies and Cybersecurity under a common formal structure. Emerged from independent network security research supervised by a graduate course instructor; framework and codebase complete, write-up in progress. | [Repo](#) |
| **Modal Logical Access Control for Vehicle Systems** | Security Engineering / Automotive | Developed a modal logical framework for access control in vehicle network systems; served as the foundation for subsequent independent research in network security and the general modal logical risk analysis framework. | [Repo](#) |
| **Hardware-Deployed DES Encryption Module** | Embedded Security | Implemented DES encryption in C++ and deployed to a microcontroller via STLink. Demonstrates low-level cryptographic implementation and embedded hardware security workflow. | [Repo](#) |
| **QuakeML Seismic Event Database & Focal Mechanism Visualizer** | Scientific Computing | Designed a SQL Server database schema around USGS QuakeML notification attributes as a foundation for P- and S-wave visualization; motivated by an interest in statistical inference of earthquake focal mechanisms (beach ball determination). Visualizer and inference component in development. | [Repo](#) |
| **Quantum First Drafts: The Qubit** | Science Communication / Interactive Art | Collaborative interactive installation exhibited at CNXNS, a formal campus event exploring the relationship between art and science. Co-developed a Cesium Ion 3D visualization to illustrate mathematical spin and provide an intuitive foundation for understanding the qubit. | [Repo](#) |
| **Automotive Camera Testing Automation** | Professional / Tooling | VBA macros and batch scripts developed professionally to automate data processing workflows for vehicle camera field testing, storage, and reporting. | [Repo](#) |

---

## Writing & Research

- **Quantum Computing and Post-Quantum Cryptography: A Hardware Perspective** —
  IEEE-style seminar paper. Explored quantum theory, its application to computing,
  and hardware implications. (Sole author)

- **Quantum Computing vs. Post-Quantum Encryption: A Mathematical Distinction** —
  IEEE-style seminar paper. Rigorous mathematical treatment distinguishing quantum
  computing approaches from post-quantum cryptographic methods. (Collaborative)

---

## Contact

- LinkedIn: [Your LinkedIn](#)
- Email: [Your Email]
