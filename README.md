# 🤖 Robotics & Computer Vision Course

<div align="center">

![Course Banner](https://img.shields.io/badge/Spring%202026-Robotics%20%26%20CV-blue?style=for-the-badge&logo=robot&logoColor=white)
![University](https://img.shields.io/badge/K.N.%20Toosi%20University-KNTU-red?style=for-the-badge&logo=graduation-cap)
![ARAS Lab](https://img.shields.io/badge/Laboratory-ARAS-green?style=for-the-badge)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![MATLAB](https://img.shields.io/badge/MATLAB-2022a%2B-yellow?logo=matlab&logoColor=white)](https://www.mathworks.com/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-green?logo=opencv&logoColor=white)](https://opencv.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-red?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

</div>

---

## 📖 Course Overview

Welcome to the **Robotics & Computer Vision Course**! This repository contains a comprehensive collection of resources for students exploring the intersection of robotic systems, computer vision, and modern artificial intelligence. Taught at **K. N. Toosi University of Technology (KNTU)** in affiliation with the **ARAS Laboratory**, this course emphasizes **practical, systems-level integration** over theoretical proofs.

### 👨‍🏫 Instructors
- **Prof. Hamid D. Taghirad** – Director, ARAS Lab | Robotics & Control Systems
- **Mohammad Javad Ahmadi** – Lead Instructor | Applied Vision & AI Systems

### 🎯 Course Philosophy
This course bridges classical robotics with cutting-edge computer vision and deep learning. Students will:
- ✅ Master spatial transformations and kinematics
- ✅ Implement industrial-grade vision pipelines
- ✅ Deploy neural networks for object detection and tracking
- ✅ Integrate vision-language models into embodied agents
- ✅ Execute end-to-end robotics projects

---

## 📚 Course Syllabus & Topics

| # | Topic | Duration | Key Concepts | Resources |
|---|-------|----------|--------------|-----------|
| 1️⃣ | **Spatial Description** | Week 1-2 | Rotation matrices, Euler angles, Quaternions | [Lecture](Lectures/01_Spatial_Description.md) \| [Tutorial](Tutorials_and_HandsOn/) |
| 2️⃣ | **Homogeneous Transformations** | Week 2-3 | SE(3), Frame Chaining, Transformation Arithmetic | [Lecture](Lectures/02_Homogeneous_Transformations.md) \| [Code](Code_Playground/) |
| 3️⃣ | **Kinematics Fundamentals** | Week 3-5 | DH Parameters, Forward/Inverse Kinematics, Dynamics | [Lecture](Lectures/03_Kinematics_Fundamentals.md) \| [Assignment](Assignments/Questions/) |
| 4️⃣ | **Classical Computer Vision** | Week 5-6 | Camera Model, Calibration, Filtering, Morphology | [Lecture](Lectures/04_Classical_ComputerVision.md) \| [Tutorial](Tutorials_and_HandsOn/) |
| 5️⃣ | **Neural Network Foundations** | Week 6-7 | MLPs, Activations, Backpropagation, Optimization | [Lecture](Lectures/05_Neural_Networks.md) \| [Code](Code_Playground/) |
| 6️⃣ | **Convolutional Neural Networks** | Week 7-8 | Convolution, Transfer Learning, Architecture Design | [Lecture](Lectures/06_CNNs.md) \| [Assignment](Assignments/Questions/) |
| 7️⃣ | **Object Detection** | Week 8-9 | YOLO, mAP, IoU, Real-time Inference | [Lecture](Lectures/07_Object_Detection.md) \| [Tutorial](Tutorials_and_HandsOn/) |
| 8️⃣ | **Object Tracking & Video** | Week 9-10 | Optical Flow, Data Association, Kalman Filters | [Lecture](Lectures/08_Tracking_Video.md) \| [Assignment](Assignments/Questions/) |
| 9️⃣ | **Transformers in Vision** | Week 10 | Self-Attention, Vision Transformers (ViT), ViLBERT | [Lecture](Lectures/09_Transformers_Vision.md) \| [Tutorial](Tutorials_and_HandsOn/) |
| 🔟 | **Advanced Segmentation** | Week 11 | Semantic/Instance Segmentation, Mask R-CNN, SAM | [Lecture](Lectures/10_Advanced_Segmentation.md) \| [Code](Code_Playground/) |
| 1️⃣1️⃣ | **Modern Embodied AI** | Week 12 | Vision-Language Models, Planning, Sim2Real, Safety | [Lecture](Lectures/11_Embodied_AI.md) \| [Project](Projects/Final_Project/) |

---

## 📊 Grading & Assessment

| Component | Points | Weight |
|-----------|--------|--------|
| **Assignments** (8 total) | 8 pts | 40% |
| **Midterm Exam** | 8 pts | 40% |
| **Final Project** | 4-8 pts | 20% |
| **Bonus/Participation** | +2 pts | Extra |
| **Total** | **20-24 pts** | **100%** |

### 🏆 Grade Mapping
- **18-20+ pts**: A (Excellent)
- **16-18 pts**: B (Good)
- **14-16 pts**: C (Satisfactory)
- **12-14 pts**: D (Passing)
- **<12 pts**: F (Incomplete)

---

## 🚀 Quick Start Guide

### Prerequisites
- **Python 3.8+** (Anaconda/Miniconda recommended)
- **MATLAB 2022a+** (optional, for control design)
- **Git** & **GitHub** account
- Basic knowledge of linear algebra and calculus

### Installation & Environment Setup

#### 1. Clone Repository
```bash
git clone https://github.com/mjahmadee/Robotics_Computer_Vision_Course.git
cd Robotics_Computer_Vision_Course
```

#### 2. Create Conda Environment
```bash
# Using the provided environment file
conda env create -f environment.yml -n rcv_course

# Activate environment
conda activate rcv_course
```

#### 3. Verify Installation
```bash
python -c "import cv2, torch, numpy; print('✅ All dependencies installed!')"
cd Tutorials_and_HandsOn
jupyter notebook  # Launch Jupyter for interactive tutorials
```

---

## 📁 Repository Structure

```
Robotics_Computer_Vision_Course/
│
├── 📋 README.md                          # This file
├── 📄 LICENSE                            # MIT License
├── 🔧 environment.yml                    # Conda environment specification
│
├── 📂 Syllabus_and_Info/
│   ├── Course_Syllabus.md
│   ├── Course_Policies.md
│   ├── Assessment_Rubric.md
│   └── Reference_Books.md
│
├── 🎓 Lectures/                          # Lecture slide outlines (11 topics)
│   ├── 01_Spatial_Description.md
│   ├── 02_Homogeneous_Transformations.md
│   ├── 03_Kinematics_Fundamentals.md
│   ├── 04_Classical_ComputerVision.md
│   ├── 05_Neural_Networks.md
│   ├── 06_CNNs.md
│   ├── 07_Object_Detection.md
│   ├── 08_Tracking_Video.md
│   ├── 09_Transformers_Vision.md
│   ├── 10_Advanced_Segmentation.md
│   └── 11_Embodied_AI.md
│
├── 🤝 Tutorials_and_HandsOn/             # Jupyter notebooks
│   ├── 01_Spatial_Transforms_Tutorial.ipynb
│   ├── 02_Kinematics_SE3_Tutorial.ipynb
│   ├── 03_Image_Filtering_Tutorial.ipynb
│   ├── 04_YOLO_Inference_Tutorial.ipynb
│   └── 05_ViT_Classification_Tutorial.ipynb
│
├── 📝 Assignments/
│   ├── Questions/                        # Problem statements
│   │   ├── Assignment_01_Kinematics_ColorSpace.md
│   │   ├── Assignment_02_CNN_Filters.md
│   │   ├── Assignment_03_YOLO_Detection.md
│   │   └── ... (8 total)
│   ├── Smart_Guides/                     # Hints & debugging logic
│   │   ├── Guide_01_Hints.md
│   │   └── ... (corresponding guides)
│   └── Solutions/                        # Reference implementations
│       ├── solution_01.py
│       └── ... (corresponding solutions)
│
├── 🎯 Projects/
│   ├── Mini_Projects/                    # Mid-term evaluations
│   │   ├── Project_01_Arm_Kinematics.md
│   │   ├── Project_02_Hand_Tracking.md
│   │   └── Project_03_SLAM_Vision.md
│   └── Final_Project/                    # Capstone projects (3 tracks)
│       ├── FINAL_PROJECT_SPECIFICATIONS.md
│       ├── Track_01_Surgical_Instrument_Tracking.md
│       ├── Track_02_Autonomous_Navigation.md
│       └── Track_03_Robotic_Manipulation.md
│
├── 💻 Code_Playground/
│   ├── Python/
│   │   ├── kinematics_toolbox.py
│   │   ├── cv_utilities.py
│   │   ├── neural_networks_basic.py
│   │   └── detection_inference.py
│   └── MATLAB/
│       ├── fk_solver.m
│       └── trajectory_planner.m
│
└── 🔬 Research_and_Beyond/
    ├── RESEARCH_TOPICS.md                # Cutting-edge research directions
    ├── Paper_Recommendations.md          # Curated published papers
    └── Further_Learning_Resources.md     # Online courses, datasets
```

---

## 📖 Reference Books & Resources

### Core Textbooks
- **Robotic Fundamentals** - Spong, Hutchinson, Vidyasagar (UR)
- **Introduction to Robotics: Mechanics and Control** - Craig, J.J.
- **Robotics, Vision and Control** - Corke, P.I.
- **Computer Vision: A Modern Approach** - Forsyth & Ponce
- **Multiple View Geometry in Computer Vision** - Hartley & Zisserman

### Deep Learning & Vision
- **Deep Learning** - Goodfellow, Bengio, Courville
- **Hands-On Machine Learning** - Aurélien Géron
- **Neural Networks and Deep Learning** - Michael Nielsen

### Online References
- [OpenCV Documentation](https://docs.opencv.org/)
- [PyTorch Tutorials](https://pytorch.org/tutorials/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)

---

## 🎯 Learning Outcomes

By the end of this course, students will:

| Learning Outcome | Assessment |
|------------------|-----------|
| Apply spatial transformations & kinematics to serial manipulators | Assignments 1-2, Project 1 |
| Implement classical & modern vision pipelines | Assignments 3-5, Mini Projects |
| Deploy CNNs for detection, tracking, and segmentation | Assignments 6-8, Final Project |
| Integrate vision-language models into robotics systems | Final Project |
| Execute end-to-end systems integration projects | Final Project (All Tracks) |
| Present technical findings professionally | Project presentations |

---

## 🤝 How to Use This Repository

### For Students
1. **Clone** the repository to your local machine
2. **Set up** the Conda environment (see Quick Start)
3. **Follow** lectures sequentially (Lectures/ folder)
4. **Complete** hands-on tutorials (Tutorials_and_HandsOn/)
5. **Solve** assignments with the help of Smart Guides
6. **Execute** projects in your own environment
7. **Submit** work via GitHub pull requests (see guidelines)

### For Instructors/Contributors
- Fork the repository
- Create feature branches for new content
- Submit pull requests for review
- Follow the style guide in [CONTRIBUTING.md](#)

---

## ✨ Key Features

<details>
<summary><b>🎨 Beautiful Markdown Formatting</b></summary>

This repository uses professional Markdown styling with:
- Collapsible sections for better organization
- Informational badges for quick reference
- Clean tables for structured data
- Code syntax highlighting
- LaTeX math rendering for equations

</details>

<details>
<summary><b>🔬 Research-Driven Content</b></summary>

All lectures and tutorials reference current research papers and industry practices from:
- IEEE Xplore
- arXiv Computer Vision & Robotics
- CVPR, ICCV, ECCV proceedings
- Robotics Science and Systems (RSS)

</details>

<details>
<summary><b>💡 "AI-Tutor" Smart Guides</b></summary>

Each assignment includes Smart Guides that:
- Provide step-by-step logical hints (no code spoilers)
- Ask guiding questions to develop problem-solving
- Offer debugging strategies
- Link to relevant tutorial sections

</details>

<details>
<summary><b>🚀 Industry-Ready Code</b></summary>

Code examples follow best practices:
- Type hints and docstrings
- Modular, reusable components
- Comprehensive error handling
- Performance-optimized implementations
- Unit tests for critical functions

</details>

---

## 📬 Communication & Support

| Channel | Purpose | Response Time |
|---------|---------|---|
| **GitHub Issues** | Bug reports, feature requests | 24-48h |
| **GitHub Discussions** | Q&A, general discussion | 24-48h |
| **Email** | Private concerns, accommodations | 48h |

---

## 🔐 Academic Integrity

All students must adhere to KNTU's academic integrity policies:
- ✅ Cite all sources and references
- ✅ Do not plagiarize code or solutions
- ✅ Use Smart Guides to learn, not copy final code
- ✅ Collaborate responsibly with peer acknowledgment
- ✅ Report suspected violations

See [Syllabus_and_Info/Course_Policies.md](Syllabus_and_Info/Course_Policies.md) for details.

---

## 📅 Important Dates (Spring 2026)

```
Course Start:        January 2026
Syllabus Review:     January 10, 2026
Assignment Deadlines: Bi-weekly (see Assignments/)
Midterm Exam:        Mid-March 2026
Project Proposals:   Late March 2026
Final Project Demo:  Late May 2026
Course End:          June 15, 2026
```

---

## 🙏 Acknowledgments

This course and repository were developed with inspiration from:
- **Peter Corke's** Robotics courses (QUT)
- **Andrew Ng's** Deep Learning Specialization
- **Stanford CS231N** (Computer Vision)
- **MIT 6.034** (AI)
- The vibrant robotics and computer vision research community

---

## 📜 License

This repository is licensed under the **MIT License**. See [LICENSE](LICENSE) file for details.

You are free to use, modify, and distribute this educational material with proper attribution.

---

<div align="center">

### 🎓 Ready to Master Robotics & Computer Vision?

[📖 Start with Lecture 1](Lectures/01_Spatial_Description.md) | [🚀 Try Tutorial 1](Tutorials_and_HandsOn/01_Spatial_Transforms_Tutorial.ipynb) | [📝 First Assignment](Assignments/Questions/Assignment_01_Kinematics_ColorSpace.md)

**Questions?** Open an issue or start a discussion!

---

**Last Updated:** Spring 2026 | **Version:** 1.0 | **Status:** ✅ Active

</div>
