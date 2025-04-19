# 🔐 BD-Attacks-Defenses

**BD-Attacks-Defenses** is a comprehensive and extensible research toolkit designed for implementing, evaluating, and analyzing **backdoor attacks** and their **defense mechanisms** in deep learning models. With a focus on reproducibility and modularity, this project brings together a wide range of state-of-the-art attack strategies and corresponding defense techniques, enabling researchers, students, and security practitioners to study and mitigate adversarial threats in machine learning.

## 🔥 Backdoor Attacks

| **Method**        | **Description**                                 |
|-------------------|--------------------------------------------------|
| **BadNets**        | Simple static trigger + label flipping           |
| **Blended**        | Pattern blending with data                       |
| **WaNet**          | Warping-based stealthy trigger                   |
| **TUAP**           | Universal adversarial perturbations              |
| **ISSBA**          | Sample-specific backdoor generation              |
| **Refool**         | Natural reflection-trigger injection             |
| **SleeperAgent**   | Triggered via semantic features                  |
| **LabelConsistent**| Consistency-preserving poisoning                 |
| **AdaptivePatch**  | Physically plausible patch attacks               |
| **BATT, LIRA, IAD**| Advanced attack families                         |


## 🛡️ Defense Techniques

| **Method**             | **Description**                                  |
|------------------------|--------------------------------------------------|
| **ShrinkPad**           | Shrinking and padding purification               |
| **NAD**                 | Neural attention distillation                    |
| **FineTuning**          | Model retraining on clean subset                 |
| **CutMix**              | Regularization through sample mixing             |
| **AutoEncoderDefense**  | Denoising-based purification                     |
| **ABL, MCR, IBD_PSC**   | Advanced learning-based defenses                 |


## 📌 Project Objective

The primary goal of this project is to provide a **practical and unified framework** for:

- Implementing both traditional and advanced **backdoor attack methods**.
- Evaluating **defensive countermeasures** under controlled and realistic conditions.
- Comparing the **effectiveness of defenses** under clean and poisoned environments.
- Facilitating **hands-on research and experimentation** in adversarial machine learning.

This repository is particularly useful for:

- 🔬 Researchers exploring the robustness and trustworthiness of ML models.
- 🎓 Graduate-level courses and academic training on AI security.
- 🛡️ Developers working on safe deployment of machine learning pipelines.


## 📁 Repository Structure
```BD-Attacks-Defenses/ 
│ ├── main/ 
│ ├── attack/ # Complete suite of backdoor attack methods 
│ ├── defense/ # Defense techniques against backdoor threats 
│ ├── models/ # Model architectures used for evaluation 
│ ├── touchattacks/ # Experimental physical-world backdoor attacks 
│ └── utils/ # Utility functions 
│ ├── tests/ # Unit and integration tests 
│ ├── Attack_BadNets.py # Script to run BadNets attack 
├── Attack_Blended.py # Script to run Blended attack 
├── Defense_ShrinkPad.py # Script to run ShrinkPad defense 
├── .gitignore └── README.md # Project documentation
```


## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Miraj-Rahman-AI/BD-Attacks-Defenses.git
cd BD-Attacks-Defenses
```
```
python -m venv bdenv
source bdenv/bin/activate  # For Linux/macOS
# bdenv\Scripts\activate   # For Windows
```

