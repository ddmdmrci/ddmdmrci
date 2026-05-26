# Hi, I'm Didem 👋

### Business Analytics | Research | Finance | Data Analytics

I am currently pursuing a Master of Research at Western Sydney University.

My background combines business analytics, accounting, and research with an interest in turning data into meaningful insights and evidence-based decisions.

---

## 🎓 Education

- Master of Research — Western Sydney University (Current)
- Master of Business Analytics — Macquarie University
- MBA — Yildiz Technical University
- Bachelor’s Degree — International Trade & Business — Eastern Mediterrenean University

---

## 🛠 Technical Skills

### Analytics
Python • SQL • Statistics • Machine Learning

### Data & Visualisation
Power BI • Tableau • Excel

### Finance & Business
Financial Analysis • Procurement • Odoo • Xero •SAP

---

# 🚀 Analytics Portfolio

## 📂 Featured Projects

| 📌 Project | 🧠 Description | 🎯 Focus Area | 📊 Status |
|------------|---------------|--------------|-----------|
| COVID-19 Financial Impact Analysis | Financial performance and business analysis of Mavi during the COVID-19 period using Python and analytical modelling | Financial Analytics | 🟢 Completed |
| Big Data Processing with MapReduce | Distributed data processing and large-scale analytics implementation using MapReduce techniques | Big Data Analytics | 🟢 Completed |
| Customer Shopping Behaviour Analysis | Exploratory and predictive analysis of customer purchasing behaviour and shopping patterns | Consumer Analytics | 🟢 Completed |

---

## 🔧 Tools & Technologies

Python • Jupyter Notebook • Data Analysis • Machine Learning • Financial Modelling

---

## 🎯 Areas of Interest

📈 Business Analytics  
💰 Financial Analytics  
🛍 Consumer Behaviour  
📊 Data Visualisation  
🔬 Research & Data Science

## 🚀 Projects

### 📊 Financial Analytics
Business reporting and dashboard development

### 📈 Data Analytics
Predictive modelling and business insights

### 🔬 Research
Applied research and statistical analysis

---

## 📫 Connect

LinkedIn: https://www.linkedin.com/in/didemdemirci

Email: demirci_didem@yahoo.com

---

✨ Turning data into insights and research into decisions.

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:           A preset of color, one of [github, github-dark, github-light]
    #  - color_snake:       Color of the snake
    #  - color_dots:        Coma separated list of dots color.
    #                       The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                       Exactly 5 colors are expected.
    #  - color_background:  Color of the background (for gif only)
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9&color_background=#aaaaaa
