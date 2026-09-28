<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D0D0D,45:8A2BE2,100:FF2E97&height=190&section=header&text=Ash-MLDev&fontSize=62&fontColor=00F0FF&animation=fadeIn&fontAlignY=34&desc=Finance%20analytics%20%E2%86%92%20Data%20Science%20and%20Machine%20Learning&descSize=17&descAlignY=54" width="100%" alt="banner" />

<a href="https://github.com/Ash-MLDev">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=3200&pause=900&color=00F0FF&center=true&vCenter=true&width=780&height=64&lines=FP%26A+Analyst+at+a+5G+telecom+operator;Credit+risk+%C2%B7+Churn+%C2%B7+Fraud+modeling;Open+to+Data+Science+%2F+ML+roles" alt="typing" />
</a>

<br/>

<a href="mailto:ashotpalyants@gmail.com"><img src="badges/email.svg" alt="Email" /></a>
<a href="https://www.linkedin.com/in/ashotp"><img src="badges/linkedin.svg" alt="LinkedIn" /></a>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,50:8A2BE2,100:FF2E97&height=3&section=header" width="100%" alt="divider" />

</div>

## About

I'm an FP&A specialist at a 5G / fixed-wireless telecom operator in Tashkent — budgeting,
cash flow forecasting, variance analysis and lender covenant reporting. Before that I spent two
years at EY in business analysis and advisory. I'm moving that work into data science and
machine learning: same problems, better tools.

My ML background comes from a six-month Data Science program plus self-study, not from a job yet.
What I took from it is the full workflow rather than just calling `.fit()`: cleaning real data,
splitting it properly, tuning with cross-validation, checking for over- and underfitting, and
putting the finished model behind an interface someone can actually use.

- **Open to Data Scientist, Credit Risk / ML modeling and ML Engineer roles** — on-site in Tashkent, hybrid, remote or relocation
- Focus domains: **credit risk**, **customer churn** and **fraud / transaction data** — the places where finance and ML overlap
- Bring a finance lens: I know what a model output has to turn into for a CFO, a risk committee or a lender
- Working languages: **English** and **Russian** (fluent)

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2E97,50:8A2BE2,100:00F0FF&height=3&section=header" width="100%" alt="divider" />
</div>

## Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,sqlite,postgres,sklearn,tensorflow,flask,git,github,vscode&theme=dark&perline=9" alt="stack" />

</div>

**Languages**
<br/>
<img src="badges/python.svg" alt="Python" /> <img src="badges/sql.svg" alt="SQL" /> <img src="badges/tsql.svg" alt="T-SQL" />

**Data & Analysis**
<br/>
<img src="badges/pandas.svg" alt="pandas" /> <img src="badges/numpy.svg" alt="NumPy" /> <img src="badges/scipy.svg" alt="SciPy" /> <img src="badges/matplotlib.svg" alt="Matplotlib" /> <img src="badges/seaborn.svg" alt="Seaborn" /> <img src="badges/powerbi.svg" alt="Power BI" />

**Machine Learning**
<br/>
<img src="badges/sklearn.svg" alt="scikit-learn" /> <img src="badges/tensorflow.svg" alt="TensorFlow / Keras" /> <img src="badges/nltk.svg" alt="NLTK" /> <img src="badges/lime.svg" alt="LIME" /> <img src="badges/pyspark.svg" alt="PySpark" />

**Deployment & Tooling**
<br/>
<img src="badges/flask.svg" alt="Flask" /> <img src="badges/aiogram.svg" alt="aiogram" /> <img src="badges/tkinter.svg" alt="Tkinter" /> <img src="badges/joblib.svg" alt="joblib" /> <img src="badges/jupyter.svg" alt="Jupyter" /> <img src="badges/git.svg" alt="Git" />

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,50:8A2BE2,100:FF2E97&height=3&section=header" width="100%" alt="divider" />
</div>

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [Home Credit Default Risk](https://github.com/Ash-MLDev/project2_home_credit_default_risk)

<img src="badges/python.svg" /> <img src="badges/pandas.svg" /> <img src="badges/in-progress.svg" />

Credit default prediction on the Home Credit dataset — feature engineering across several
related tables (bureau history, previous applications, installments), gradient-boosted models,
evaluated by ROC-AUC, with a scorecard-style view of what drives default.

<!-- EDIT: add your best CV / leaderboard ROC-AUC once you have one -->

</td>
<td width="50%" valign="top">

### Telecom Customer Churn

<img src="badges/python.svg" /> <img src="badges/sklearn.svg" /> <img src="badges/planned.svg" />

Churn model for a subscription telecom business — the domain I work in. Starts from the
questions that decide the model: what counts as churn, over what horizon, and which retention
action the prediction triggers. Evaluated on lift and expected retained revenue, not just accuracy.

<!-- EDIT: link the repo once it's public -->

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Transaction Fraud Detection

<img src="badges/python.svg" /> <img src="badges/sklearn.svg" /> <img src="badges/planned.svg" />

Fraud classifier on heavily imbalanced transaction data — time-based validation, resampling vs.
class weights, and a decision threshold chosen from the cost of a missed fraud versus a false alarm.

<!-- EDIT: link the repo once it's public -->

</td>
<td width="50%" valign="top">

### Phishing Website Detector

<img src="badges/python.svg" /> <img src="badges/sklearn.svg" /> <img src="badges/flask.svg" />

End-to-end classifier that flags phishing URLs from their feature set. EDA and cleaning,
a `GradientBoostingClassifier` tuned with `GridSearchCV` over `StratifiedKFold`, explicit
over- and underfitting checks, then persisted with joblib and served through a Flask app.

<!-- EDIT: push this repo and link it here -->
`repo: not yet published`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Spaceship Titanic — Neural Network Classifier

<img src="badges/python.svg" /> <img src="badges/tensorflow.svg" /> <img src="badges/flask.svg" />

Diploma project for the Data Science program. Binary classifier built in TensorFlow/Keras on
the Spaceship Titanic dataset, with cross-validation, two documented notebooks, and a Flask
web front end for live predictions.

<!-- EDIT: push this repo and link it here -->
`repo: not yet published`

</td>
<td width="50%" valign="top">

### SQL Analytics & BI Dashboard

<img src="badges/sql.svg" /> <img src="badges/powerbi.svg" />

Analytics over a relational TV-series database — joins, aggregation and subqueries driven
from Python, with the results presented in a Power BI dashboard.

<!-- EDIT: publish the notebook + .pbix if you want this one to count -->

</td>
</tr>
</table>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2E97,50:8A2BE2,100:00F0FF&height=3&section=header" width="100%" alt="divider" />
</div>

## Experience

**FP&A Specialist — Perfectum Mobile** (5G / FWA telecom operator) · 2025 – present
> Budgeting, cash flow forecasting (IAS 7 direct method) and variance analysis. Built a Power Query /
> Power Pivot pipeline for subscriber revenue reporting, and maintain loan portfolio actuals and
> DSCR covenant reporting for the company's lenders. Work daily with commercial, network, IT and
> the CFO — turning open-ended questions into models that answer them.

**Senior Specialist, Business Analysis & Advisory — EY** · 2023 – 2025
> Treasury operating model, liquidity policy and stress-testing methodology for a state bank;
> comparative analysis of international financial centres (DIFC, AIFC and others) for a regulatory
> sandbox concept; an Excel dashboard and asset classification tool for a government client.

**Finance & Accounting** · earlier
> Senior finance manager, and accounting lead for US trucking companies (US GAAP, QuickBooks) —
> where I first automated reporting with Google Sheets and Apps Script.

**Data Science program** — six months, project-based · 2026
> Python and OOP, Pandas/NumPy, SQL and BI, statistics and A/B testing, classical ML,
> neural networks, NLP and recommenders, and model deployment. Followed by self-study
> on real datasets.

**Education**
> BBA, Business Management with Finance — Westminster International University in Tashkent

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,50:8A2BE2,100:FF2E97&height=3&section=header" width="100%" alt="divider" />
</div>

## What I Can Do

| Area | Detail |
|:--|:--|
| **Supervised ML** | Linear and logistic regression, decision trees, random forest, gradient boosting, SVM (SVC + SVR) |
| **Unsupervised** | K-means, hierarchical clustering |
| **Model workflow** | Train/test splits, `GridSearchCV` with stratified k-fold, over/underfitting diagnostics |
| **Evaluation** | Classification reports, confusion matrices, ROC-AUC, regression error metrics |
| **Deep learning** | Dense networks, CNNs for images, RNN/LSTM for sequences |
| **Applied** | Time series, NLP text classification (TF-IDF + Naive Bayes), recommenders, LIME for interpretability |
| **Statistics** | Distributions, correlation, hypothesis testing, A/B test analysis |
| **Finance** | Cash flow forecasting, budgeting and variance analysis, credit covenants (DSCR), treasury and liquidity |
| **Shipping** | joblib persistence served through Flask, Tkinter, or an aiogram Telegram bot |

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2E97,50:8A2BE2,100:00F0FF&height=3&section=header" width="100%" alt="divider" />

## Contact

Open to Data Science, Credit Risk and ML roles — Tashkent, remote or relocation. Email is the fastest way to reach me.

<a href="mailto:ashotpalyants@gmail.com"><img src="badges/email-long.svg" alt="Email" /></a>
<a href="https://www.linkedin.com/in/ashotp"><img src="badges/linkedin.svg" alt="LinkedIn" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF2E97,55:8A2BE2,100:0D0D0D&height=140&section=footer" width="100%" alt="footer" />

</div>
