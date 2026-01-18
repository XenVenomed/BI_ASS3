# BI_ASS3

## Github repo link: https://github.com/XenVenomed/BI_ASS3
## Student a: Avelardo Ramirez - 12435655
## Student b: Agon Sylejmani - 01556207

# Obesity Level Classification using CRISP-DM

# NOTE:
During the final submission phase, persistent HTTP 500 (Internal Server Error) issues with the provenance server stopped our progress.

Problems faced:

Testing: We were unable to perform final end-to-end tests or verify code execution since the server was unresponsive.
Formatting: Final text adjustments to strictly follow ACM guidelines were not possible before the deadline.
Visuals: We could not finalize the inclusion of figures and graphs.

Despite these technical constraints, we have ensured that the core logic and data provenance entries are as complete as the server stability allowed.

## Project Overview

This project implements a complete machine learning pipeline following the **CRISP-DM methodology** to classify obesity levels based on eating habits and physical condition. The dataset includes records from Mexico, Peru, and Colombia with 7 obesity classification levels.

---

## Dataset

**Source:** Palechor & De la Hoz Manotas (2019)  
**Title:** "Estimation of obesity levels based on eating habits and physical condition"  
**Published in:** Data in Brief, Volume 25, August 2019
---

## Installation

### Prerequisites
- Python 3.11
- Conda package manager
- GraphDB instance (for provenance tracking)

### Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/obesity-classification.git
cd obesity-classification
```

2. **Create conda environment:**
```bash
conda create -n BI2025 python=3.11 -y
conda activate BI2025
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

4. **Configure GraphDB connection:**
   - Update the GraphDB credentials in the notebook
   - Ensure GraphDB server is running and accessible

5. **Run the notebook:**
```bash
jupyter notebook Obesity_Ass3.ipynb
```
---

