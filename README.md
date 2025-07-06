
# powerbi-stackoverflow-survey-2024
Visualizing the results of the Stack Overflow Survey 2024 with Power BI

<p align="center">
  <img src="image0(1).png" alt="Power BI Dashboard Banner" width="100%">
</p>

<p align="center">
  <img src="image0(2).png" alt="Logo" width="100" />
</p>

# 🌍 Stack Overflow Developer Trends 2024 – Power BI Dashboard

This Power BI project visualizes the global results of the **Stack Overflow Developer Survey 2024**. It provides interactive insights into technologies, tools, and the demographics of the global developer community.

---

## 🔍 Overview

The dashboard answers key questions such as:

- What are the most popular **programming languages**, **databases**, and **web frameworks** worldwide?
- How widely are **AI tools** (such as ChatGPT, Copilot, etc.) used in software development?
- Which operating systems and embedded platforms are used most frequently?
- How do **salary structures**, **age distributions**, and **technological preferences** vary by region or profession?
- What correlations exist between experience, technology usage, and income?

---

## 📊 Features

- 🌐 **Global filters**: by region, profession, age, etc.
- 📈 **KPIs & charts**: distribution, trends, rankings
- 🗺️ **Interactive maps**: technology usage by country
- 🔄 **Comparison & correlations**: e.g. AI usage vs. experience
- 💬 **Visual storytelling elements**

---

## 🧩 Technology & Data

- 📌 **Power BI Desktop (.pbix)**
- 📁 **Data source**: [Stack Overflow Survey 2024 (CSV)](https://insights.stackoverflow.com/survey)
- 🧠 **Built with**: Power Query, DAX, map visuals, correlation analysis

---

## 📸 Preview

![Screenshot 1](screenshot1.png)  
![Screenshot 2](screenshot2.png)  
![Screenshot 3](screenshot3.png)  
![Screenshot 4](screenshot4.png)

---

> ⚠️ **IMPORTANT: Update Parameters in Power Query**

Before using the dashboard, please adjust the **three parameters** in the Power Query Editor:

1. **`SurveyCSVPath`** – the local file path to the Stack Overflow Survey 2024 results CSV  
2. **`CountryContinentPath`** – the path to the Country-Continent mapping CSV  
3. **`FilterToOneCountry`** – set this to `0` to load **all countries**  
   (default is `1` due to GitHub file size limitations; only one country is initially loaded)

➡️ You can access these parameters in **Power BI** under:
**Transform Data → Manage Parameters**

Make sure the CSV files are extracted and accessible locally, and adjust the paths accordingly.

---

## 🗂️ Repository Contents

| File | Description |
|------|-------------|
| `stackoverflowsurvey2024.pdf` | Power BI report as PDF|
| `stack-overflow-developer-survey-2024.zip` | Raw data |
| `README.md` | Project description |
| `screenshot1.png`, `screenshot2.png`, `screenshot3.png`, `screenshot4.png` | Preview images |
| `image0(2).png` | Project logo |
| `image0(1).png` | Title image |

---

## 👥 Target Audience

This project is intended for:
- Software developers & data analysts
- Anyone interested in technology trends
- HR, tech strategists & educational institutions
- Use in IT/data job applications or portfolios

---

## 🔗 Further Links

- [Official survey website](https://survey.stackoverflow.co/2024/)
- [Download the data (Stack Overflow)](https://survey.stackoverflow.co/2024/#download)

---

## 📄 License

This project is based on publicly available survey data. All visualizations and analyses were independently created. The rights to the raw data remain with Stack Overflow.  
This repository is licensed under the [MIT License](LICENSE).

---

## 🤝 Contact

For questions or feedback:  
**Markus Elstermann**  
📧 elstermannmarkus@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/)
