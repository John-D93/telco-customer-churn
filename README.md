# Telco Customer Churn — Machine Learning Group Project

This repository contains our group's machine learning project analyzing the Kaggle Telco Customer Churn dataset.

## Repository Files
* `M6_Telco_CustomerChurn_GroupProject.ipynb` — Main project notebook for final submission.
* `WA_Fn-UseC_-Telco-Customer-Churn.csv` — Telco Customer Churn dataset.

---

## How to Contribute using GitHub Codespaces(Recommendation)

You don't need to install Git, Python, or Jupyter on your computer to work on this project. We are using **GitHub Codespaces**, which gives everyone the exact same coding environment right in the browser.

### 1. Open a Codespace
1. Click the green **`<> Code`** button near the top of this page.
2. Select the **Codespaces** tab.
3. Click **Create codespace on main**. *(Wait a minute for the browser-based VS Code environment to load.)*

### 2. Create Your Own Branch
Never make changes directly on the `main` branch.
1. Click **`main`** in the very bottom-left corner of the Codespace window.
2. Select **`+ Create new branch...`** at the top of the screen.
3. Give it a short, descriptive name (e.g., `eda-alex` or `logistic-regression`) and press **Enter**.

### 3. Make Your Changes
> **Important tip for Jupyter Notebooks:** If two people edit the exact same `.ipynb` file at the same time, it causes messy merge conflicts. To avoid this, **create your own working notebook** (e.g., `work_yourname.ipynb`) for your experiments and code. We will merge the finalized sections into `M6_Telco_CustomerChurn_GroupProject.ipynb` once reviewed.

### 4. Save, Commit, and Push
1. Save your files (`Ctrl + S` or `Cmd + S`).
2. Click the **Source Control** icon (the branching icon, third down on the far-left sidebar).
3. Type a brief message describing what you did in the text box (e.g., *"Added feature engineering and correlation matrix"*).
4. Click **Commit** (if prompted to stage all changes, click **Yes**).
5. Click **Publish Branch** (or **Sync Changes**) to send your branch to GitHub.

### 5. Open a Pull Request (PR)
1. Once published, click the **Create Pull Request** pop-up in the bottom-right corner—or come back to this GitHub repo page and click the yellow **Compare & pull request** button.
2. Add a quick summary of your work and click **Create pull request**.
3. Let the group know so we can review and merge it into `main`!

---

## Option 2: Working Locally (Using Git)

If you already have Git and Python/Jupyter installed locally and prefer your own setup:

### 1. Clone the Repository
```bash
git clone [https://github.com/basicallysteve/telco-customer-churn.git](https://github.com/basicallysteve/telco-customer-churn.git)
cd telco-customer-churn

```

### 2. Create Your Own Branch
```bash
git checkout -b your-branch-name
```

### 3. Stage, Commit, and Push
```bash
git add .
git commit -m "Brief description of your changes"
git push -u origin your-branch-name
```

### 4. Open a Pull Request

Go to the repository on GitHub, click the yellow Compare & pull request button, add a short summary, and click Create pull request.

---

## Quick Reminders
* **Always pull the latest changes** before starting new work by switching to `main`, clicking the sync icon (bottom-left), and then creating a fresh branch.
* **Close your Codespace tab** when you're done—GitHub automatically pauses it after 30 minutes of inactivity so it won't eat up your free monthly hours.
