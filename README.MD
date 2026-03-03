📊 A/B Testing Simulation for Internee.pk Homepage





🚀 Project Overview

This project simulates an A/B Test for improving the homepage user experience of Internee.pk.

Since real analytics access was unavailable, I:

Scraped homepage structural features

Engineered UX-based metrics

Simulated user engagement

Performed statistical hypothesis testing

Built an interactive experimentation dashboard

Goal: Identify which homepage design drives higher engagement.

🎯 Objective

Design and analyze A/B tests to improve:

User Engagement

Bounce Rate (simulated proxy)

Conversion Probability (modeled)

🌐 Data Source

Homepage structural data extracted from:

Internee.pk (public website HTML)

Extracted Features:

Number of links

Number of buttons

Number of internship cards

Page size (HTML length)

🧠 A/B Design Variations
<details> <summary><strong>🅰 Design A (Original Homepage)</strong></summary>

Minimal CTA buttons

Limited visible internships

Lower interaction density

Represents current structural layout.

</details> <details> <summary><strong>🅱 Design B (Improved UX Version)</strong></summary>

More call-to-action buttons

Featured internship cards

Increased navigation options

Optimized engagement flow

Hypothesis: Improves user engagement.

</details>
🧪 Hypothesis Testing
Null Hypothesis (H0)

There is no significant difference in engagement between Design A and B.

Alternative Hypothesis (H1)

Design B results in higher user engagement.

Statistical Method Used:

Independent Two-Sample T-Test

📊 What Makes This Project Interactive?

✔ Engagement simulation using probabilistic modeling
✔ Dynamic homepage feature adjustments
✔ Real-time histogram visualization
✔ Adjustable UX variables (buttons, links, cards)

You can modify:

Number of buttons

Number of links

Number of internship cards

And instantly see engagement impact 📈

🛠 Tech Stack

Python

NumPy

Pandas

SciPy

Matplotlib

BeautifulSoup

Requests

ipywidgets

🗂 Project Structure
A-B-Testing-InterneePK/
│
├── A-B-Testing-InterneePK.ipynb
├── ab_testing_simulation.py
├── README.md
└── data/
▶️ How to Run the Project
Option 1 — Jupyter Notebook (Recommended)

Open A-B-Testing-InterneePK.ipynb

Run cells sequentially

Use interactive sliders to explore engagement changes

Option 2 — Python Script
pip install -r requirements.txt
python ab_testing_simulation.py
📈 Sample Output

Engagement Distribution Comparison (A vs B)

Statistical Significance (p-value)

Interactive Engagement Simulation Dashboard

If p-value < 0.05 → Design B significantly improves UX.

📌 Key Learnings

How A/B testing works in real-world product teams

Statistical validation of UX decisions

Engagement modeling without direct analytics access

Practical application of hypothesis testing

💡 Future Improvements

Real Google Analytics integration

Real user clickstream dataset

Logistic regression conversion modeling

Deployment as a Streamlit web app

👨‍💻 Author

Sobaan
Data Science Project
