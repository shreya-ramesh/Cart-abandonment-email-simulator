# 🛒 Cart Abandonment Predictor & Email Simulator

This project predicts **cart abandonment behavior** using real-world e-commerce session data and simulates basic **email recovery strategies** to help businesses understand and reduce abandonment rates.

## Project Overview

- Predicts whether a user will **abandon their cart** based on session behavior.
- Uses machine learning models trained on enhanced features.
- Includes a basic **email simulator** to model how timely emails can help recover sales.
- Built with **Streamlit** for real-time input and visualization.

---

## Dataset Source

The dataset was obtained from Medium blog.

---

## ML Models Used

Trained 3 models and compared performance:

<pre>

Logistic Regression     : 98.13%

Random Forest           : 97.55%

XG Boost                : 98.13%
</pre>
---

## Email Simulator

The email simulator is a lightweight tool to test recovery actions:

- Inputs are passed to the trained model to detect abandonment.
- If predicted as “abandoned”, the system triggers a mock email alert.
- Designed to showcase basic **user re-engagement logic**.

> You can enhance it by integrating real-time campaign tools or analytics dashboards.

---

## Tech Stack

- Python (Numpy,Pandas, Scikit-learn, Streamlit)
- Jupyter Notebook (Model development)
- Pickle (Model storage)
- Matplotlib / Seaborn (EDA)

---

## Folder Structure
<pre> 
cart_abandonment/
│
├── data/
│ └── data_cart_abandonment.csv #source data
├── model/
│ └── model.pkl #trained models
├── notebook/
│ └── model.ipynb # Notebook with EDA + training
├── simulation.py #email and streamlit logic
├── requirements.txt # Python dependencies
└── README.md </pre>

---

> GitHub does not render Jupyter notebook outputs. To view the notebook properly, use nbviewer.

---

## Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/yourrepo.git
   cd yourrepo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the simulator:
    ```bash
   streamlit run simulation.py
---

## Contact
For queries or collaboration:
SHREYA RAMESH — shreya.ramesh22@gmail.com


