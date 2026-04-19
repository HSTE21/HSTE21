<div align="center">
  <h1>Hi, I'm Hans 👋</h1>
  <p><em>Technical Medicine @ University of Twente · Deep Learning · Medical Imaging · Surgical Robotics</em></p>

<a href="https://www.linkedin.com/in/stegehuis-hans/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <img src="https://img.shields.io/badge/Enschede%2C%20Netherlands-🏙️-blue?style=for-the-badge" alt="Location" />
</div>

---

## 🧠 About Me

I'm a **Technical Medicine** master's student at the **University of Twente**, working at the intersection of clinical medicine, medical image analysis, and artificial intelligence. I focus on developing robust deep learning algorithms for medical imaging, biosignal processing, and exploring computer-assisted interventions.

- 🫁 Developing **2D U-Net models for cardiac MRI segmentation** (ACDC challenge), optimizing for high specificity and robust deep feature extraction
- 🫀 Researching **adversarial robustness of 1D ResNet ECG classifiers** using targeted PGD attacks and adaptive defenses
- 🦾 Bridging computer vision and control via **real-time hand-tracking for 6-DOF robotic manipulation**
- 🖥️ Running a personal **homelab** for GPU-accelerated ML experiments and containerized workflows
- 📍 Based in **Enschede, Netherlands**

---

## 🔭 Research & Clinical Interests

- **Medical Image Analysis:** Cardiac MRI segmentation, radiomics, and generative models for medical imaging
- **Trustworthy Clinical AI:** Adversarial robustness, adaptive defenses, and reliable deployment of deep learning in healthcare
- **Surgical Robotics:** Computer-assisted interventions, kinematic modeling, and real-time spatial tracking
- **Biosignal Processing:** Deep learning for physiological time-series analysis, including ECG and EMG

---

## 🛠️ Tech Stack

- **Languages:** Python · MATLAB
- **Medical AI:** PyTorch · TensorFlow · MONAI · Jupyter
- **Vision & Robotics:** OpenCV · MediaPipe · PyBullet · Unity
- **Infrastructure:** Docker · Linux · Git · Raspberry Pi
- **Medical imaging ecosystem:** SimpleITK · nibabel · pydicom · PyRadiomics · ART

> *Familiar with ecosystem libraries including NumPy, Pandas, Scikit-learn, SimpleITK, PyRadiomics, nibabel, pydicom, and ART.*

---

## 📌 Featured Projects

### 🔬 Medical AI & Imaging

| Project | Description | Stack |
| --- | --- | --- |
| [🫁 ACDC Cardiac MRI Segmentation](https://github.com/MarkoHaralovic/acdc_challenge) | Built an end-to-end 2D U-Net pipeline for multi-class cardiac MRI segmentation. Implemented robust preprocessing (spatial resampling, volume-wise intensity normalization) and conducted a systematic ablation study of six loss functions to handle class imbalance. Demonstrated that weighted cross-entropy yielded the best performance with a mean global Dice score of 0.915. | PyTorch · MONAI · nibabel · SimpleITK |
| [🫀 ECG Adversarial Robustness](https://github.com/HSTE21/ECG-Adversarial-Robustness) | "Small Changes, Big Errors" — Investigated the vulnerability of a 34-layer 1D ResNet ECG classifier to targeted PGD attacks, exposing a critical drop in Atrial Fibrillation detection (F1: 0.73 → 0.18). Engineered an adaptive adversarial retraining pipeline that restored robustness against active attacks (ϵ=0.2) and acted as a powerful regularizer, boosting the baseline clinical performance to an F1-score of 0.87. | TensorFlow · ART · wfdb |

### 🤖 Computer Vision & Control

| Project | Description | Stack |
| --- | --- | --- |
| [✋ 6-DOF Hand Tracking Control](https://github.com/HSTE21/faze4-hand-tracking) | Built a real-time hand-tracking controller for the Faze4 robotic arm. Integrated MediaPipe with PyBullet inverse kinematics and implemented monocular depth estimation for full 3D control. Engineered an exponential moving average (EMA) filter for smooth trajectory generation and streamed commands to a Unity simulation with grip detection. | MediaPipe · PyBullet · OpenCV · Unity |

### 💻 Software Engineering

| Project | Description | Stack |
| --- | --- | --- |
| [📋 Event Registration System](https://github.com/HSTE21/evenementen-inschrijf-systeem) | Developed a lightweight, full-stack web application for associations to streamline event sign-ups. Features include an automated waitlist system, user management, and automated email confirmations built on top of a SQLite database. | Flask · SQLAlchemy · SQLite |

---

## 📫 Let's Connect

I'm always open to collaborating on **medical imaging**, **clinical AI**, or **surgical robotics** research.

Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/stegehuis-hans/).
