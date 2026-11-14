Hi, I'm Arman 👋

🎓 Final-year Computer Science (Data Science) Student @ Auckland University of Technology
📍 Auckland, New Zealand

## 🧠 About Me

I'm a data science student who likes building practical things: machine learning models, SQL analysis, dashboards, and, through my capstone, an LLM agent that controls a robot. I care about honest evaluation: checking for leakage, explaining what the numbers really mean, and writing up the bugs I find.

## 🔧 Skills

* **Programming:** Python, SQL · coursework in R, Java and C
* **Libraries:** pandas, NumPy, scikit-learn, Matplotlib, Seaborn
* **Machine Learning:** Logistic Regression, MLP neural networks, KNN, Decision Trees · cross-validation, ROC/AUC, leakage-safe preprocessing
* **Applied AI:** LLM agents with tool calling (capstone), AI coding assistants in a pull-request review workflow
* **Data & BI:** Power BI (DAX, Power Query, star-schema modelling), exploratory data analysis
* **Databases:** SQL (joins, window functions, CTEs), SQLite, Firebase / Firestore
* **Tools:** Git & GitHub, Linux, Jupyter · learning Streamlit

## 🤖 Applied AI Capstone: LLM Agents for Robots

Team project at AUT with an industry client (code is private). A fine-tuned language model, served locally through Ollama, turns typed or spoken commands into a fixed set of validated tool calls for a Unitree Go2 quadruped robot. A safety executor enforces speed, distance and turn limits, so the model never sends raw motor commands. The system is developed in a MuJoCo simulation before running on the real robot.

**My part:**
* **Scrum Master:** ran sprints and meetings, the risk register and status reports, and communication with our supervisor and the client
* **Feedback store:** built the feature that copies user-flagged agent replies to Firebase Firestore (Python module, security rules and tests)
* **Simulation setup:** got the MuJoCo simulation and walking policy running on Windows and Linux for the team
* **AI-assisted development:** directed Claude Code to build person-following and ledge/stall protection, reviewed the output and took it through teammate code review

## 🚀 Featured Projects

### 📊 Automobile Market Dashboard (Power BI)
Interactive two-page Power BI report on price, performance and fuel efficiency of 205 cars.
* Star-schema data model with 13 documented DAX measures, including a Pearson correlation calculated in DAX
* Power Query cleaning with a parameterised data source, saved in PBIP format so every measure is readable on GitHub
👉 [View Project](https://github.com/AremonNZ/automobile-market-dashboard)

### 🍄 Mushroom Classification
Machine learning project comparing KNN and Decision Tree models on 61K samples.
* Achieved 99.93% test accuracy using KNN, confirmed by 5-fold cross-validation (99.89%)
* Found and fixed a data-ordering bug that made cross-validation look like 52%
* Focused on feature importance and model comparison
👉 [View Project](https://github.com/AremonNZ/mushroom-classification)

### 🎗️ Breast Cancer Classification
Classification of tumors using Logistic Regression and MLP neural networks.
* Both models reached 97.66% test accuracy (98% in 10-fold cross-validation), so the simpler Logistic Regression was preferred
* Focused on medical risk: analysed the false negatives (missed malignant tumours) rather than accuracy alone
👉 [View Project](https://github.com/AremonNZ/breast-cancer-ml-classification)

### 🏥 Medical Appointment No-Shows (SQL)
SQL-based analysis of 110,527 real patient appointments to identify what predicts no-shows.
* Used GROUP BY, CASE WHEN, window functions, and CTEs
* Found that waiting time is the strongest predictor (5% no-shows same day vs 33% at 30+ days), and showed the apparent SMS-reminder effect is confounded by wait time
👉 [View Project](https://github.com/AremonNZ/medical-appointment-noshow-sql)

### 🚗 Car Market Data Exploration (EDA)
Exploratory data analysis on car market data to uncover pricing trends and patterns.
* Applied data cleaning, outlier detection, and correlation analysis
* Produced visual insights to support data-driven conclusions
👉 [View Project](https://github.com/AremonNZ/Automobile-Data-Analysis-EDA-)

## 📈 Currently Working On

* Building end-to-end machine learning projects
* Developing deployable apps using Streamlit
* Strengthening SQL skills for real-world data analysis

## 🎯 Goals

* Secure a Data Science / Data Analyst internship or graduate role
* Build production-ready data projects
* Improve real-world problem solving with data

## 📫 Contact

* LinkedIn: [arman-arabkhani](https://www.linkedin.com/in/arman-arabkhani-95903a384/)
* GitHub: [AremonNZ](https://github.com/AremonNZ)
* Email: [armanarabkhani.nz@yahoo.com](mailto:armanarabkhani.nz@yahoo.com)
