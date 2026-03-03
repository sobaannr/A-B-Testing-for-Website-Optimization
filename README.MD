🚀 A/B Testing Simulation for Internee.pk Homepage
📊 Data Science Project | UX Optimization | Statistical Experimentation
🎯 Project Objective

This project simulates an A/B test to evaluate how homepage design changes can improve user engagement on Internee.pk.

Since real Google Analytics access was not available, I:

Extracted homepage structural features via web scraping

Designed two UX variations (A & B)

Simulated user engagement behavior

Performed statistical hypothesis testing

Built interactive visualizations

🌐 Data Source

Public homepage HTML data from Internee.pk.

Extracted metrics:

Number of links

Number of buttons

Number of internship cards

Page size (HTML length)

These structural elements were used as engagement predictors.

🧠 A/B Design Variations
🅰 Design A — Original Layout

Minimal call-to-action buttons

Limited visible internships

Basic interaction density

🅱 Design B — Improved UX Version

Increased CTA buttons

Featured internship cards

Enhanced navigation structure

Optimized engagement flow

Hypothesis: Design B increases engagement.

🧪 Statistical Framework

Null Hypothesis (H0):
No significant difference in engagement between Design A and Design B.

Alternative Hypothesis (H1):
Design B results in higher engagement.

Method Used:

Independent Two-Sample T-Test

Significance Level:

α = 0.05

📊 Interactive Features

✔ Engagement score simulation
✔ Adjustable UX variables (buttons, links, cards)
✔ Real-time histogram comparison
✔ Statistical significance output

Users can dynamically modify homepage elements and observe engagement changes instantly.

🛠 Tech Stack

Python

NumPy

Pandas

SciPy

Matplotlib

BeautifulSoup

Requests

ipywidgets

📂 Project Structure

A-B-Testing-InterneePK/
│
├── A-B-Testing-InterneePK.ipynb
├── ab_testing_simulation.py
├── README.md
└── data/

▶️ How to Run
Option 1 — Notebook (Recommended)

Open the notebook in Jupyter or Google Colab

Run all cells sequentially

Use interactive sliders to explore engagement impact

Option 2 — Python Script

Install dependencies:

pip install -r requirements.txt

Run:

python ab_testing_simulation.py

📈 Results

Design B shows higher simulated engagement scores

Statistical testing confirms significance (p < 0.05)

Improved UX structure leads to better modeled performance

📌 Key Learnings

Practical implementation of A/B testing methodology

UX experimentation using structural web features

Statistical validation of product decisions

Engagement modeling without direct analytics access

🔮 Future Improvements

Real Google Analytics integration

Conversion probability modeling

Logistic regression instead of linear simulation

Deployment as a Streamlit web app

👨‍💻 Author

Sobaan
Data Science Project
