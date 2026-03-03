# 🚀 A/B Testing Simulation for Internee.pk Homepage

## 📊 Data Science Project | UX Optimization | Statistical Analysis

---

## 🎯 Project Objective

This project simulates an A/B test to evaluate how homepage design changes can improve user engagement.

Since real analytics access was unavailable, the project:

- Extracts homepage structural features using web scraping  
- Creates two homepage design variations (A & B)  
- Simulates user engagement  
- Performs statistical hypothesis testing  
- Visualizes engagement distributions  

---

## 🌐 Data Source

Public homepage HTML data from Internee.pk.

Extracted metrics:

- Number of links  
- Number of buttons  
- Number of internship cards  
- Page size (HTML length)  

---

## 🧠 A/B Design Variations

### 🅰 Design A — Original Layout

- Minimal call-to-action buttons  
- Limited visible internships  
- Lower interaction density  

### 🅱 Design B — Improved UX Version

- Increased CTA buttons  
- Featured internship cards  
- Enhanced navigation structure  

**Hypothesis:** Design B improves engagement.

---

## 🧪 Statistical Framework

### Null Hypothesis (H0)

There is no significant difference in engagement between Design A and Design B.

### Alternative Hypothesis (H1)

Design B results in higher engagement.

### Method Used

- Independent Two-Sample T-Test  
- Significance Level: 0.05  

---

## 📊 Interactive Features

- Engagement score simulation  
- Adjustable UX variables (buttons, links, cards)  
- Real-time histogram visualization  
- Statistical significance output  

---

## 🛠 Tech Stack

- Python  
- NumPy  
- Pandas  
- SciPy  
- Matplotlib  
- BeautifulSoup  
- Requests  
- ipywidgets  

---

## 📂 Project Structure

A-B-Testing-InterneePK/

- A-B-Testing-InterneePK.ipynb  
- ab_testing_simulation.py  
- README.md  
- data/  

---

## ▶️ How to Run

### Run in Notebook (Recommended)

1. Open the notebook in Jupyter or Google Colab  
2. Run all cells sequentially  
3. Use sliders to test engagement changes  

### Run as Script

Install dependencies:

pip install -r requirements.txt  

Run:

python ab_testing_simulation.py  

---

## 📈 Results

- Design B shows higher simulated engagement  
- Statistical testing confirms significance (p < 0.05)  
- UX improvements positively affect modeled user behavior  

---

## 📌 Key Learnings

- Practical A/B testing implementation  
- UX experimentation using structural web features  
- Statistical validation of design decisions  
- Engagement modeling without direct analytics  

---

## 👨‍💻 Author

Sobaan  
Data Science Project  
