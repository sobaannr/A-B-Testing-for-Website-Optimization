# A/B Testing Simulation for Internee.pk Homepage

## Objective
The goal of this project is to **design and analyze A/B tests** for better user experience on the Internee.pk homepage. Since we cannot access real user analytics, we simulate A/B testing using **scraped homepage data** and **modeled user engagement metrics**.

---

## Data Source
- Scraped from [Internee.pk](https://www.internee.pk) homepage.
- Metrics extracted:
  - Number of links
  - Number of buttons
  - Number of internship cards
  - Page size (HTML length)
---

## Tools & Libraries
- Python 3
- `numpy`, `pandas`, `matplotlib`
- `scipy` for statistical testing
- `beautifulsoup4` and `requests` for web scraping
- `ipywidgets` for interactive dashboard

---

## Project Steps

1. **Web Scraping**: Extract homepage features.
2. **Feature Engineering**: Count buttons, links, cards, and page size.
3. **Design Variations**:
   - Design A: Original homepage
   - Design B: Improved homepage with more CTAs, links, and cards
4. **Simulate User Engagement**: Engagement scores generated using a linear model with noise.
5. **Statistical Testing**: Independent t-test to identify if Design B is significantly better.
6. **Visualization**: Histograms of engagement scores.
7. **Interactive Dashboard**: Adjust buttons, links, and cards to see engagement changes.

---

## How to Run

1. Open `A-B-Testing-InterneePK.ipynb` in **Google Colab** or **Jupyter Notebook**.
2. Run all cells sequentially.
3. Use the interactive sliders to explore how homepage changes affect engagement.

Optional: Run `ab_testing_simulation.py` as a script (plots will appear in a separate window).

---

## Results
- Design B shows **higher simulated engagement scores** compared to Design A.
- Statistical test confirms **significant improvement** (p-value < 0.05).
- Interactive dashboard allows exploration of different design feature combinations.

---

