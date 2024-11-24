# Learning Codacy

This repository is dedicated to learning about the code review automation tool **Codacy**, which helps improve code quality by analyzing codebases and providing actionable feedback.

<p align="center">
<a href="https://app.codacy.com/gh/madhurimarawat/Learning-Codacy/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade">
    <img src="https://app.codacy.com/project/badge/Grade/c96266ba8f6d4386b486a474c429a5c4" alt="Codacy Badge">
</a> &nbsp; &nbsp;
<a href="https://github.com/madhurimarawat/Learning-Codacy">
    <img src="https://img.shields.io/github/repo-size/madhurimarawat/Learning-Codacy" alt="GitHub repo size">
</a>
</p>

---

## **Introduction**

**Codacy** is an automated code review tool that integrates seamlessly with GitHub and other version control platforms. It performs static code analysis, identifies code smells, and enforces best practices to streamline development workflows.

## **Steps to Set Up Codacy**

### **1. Create an Account**
1. Visit [Codacy](https://www.codacy.com/) and sign up using your **GitHub** account.
   - Grant the necessary permissions for Codacy to access your repositories.
2. After authorization, you will be redirected to the Codacy dashboard.

<img src="https://github.com/user-attachments/assets/2bde1014-7316-44f0-a58b-375f9caa4cea" width="100%">

---

### **2. Add Your Repository**
1. On the Codacy dashboard, click **"Add a repository"**.
2. Select the repository (**Learning-Codacy**) you want Codacy to analyze.
   - Ensure Codacy has the required access permissions.
3. Codacy will perform an initial scan and generate a baseline report.

<img src="https://github.com/user-attachments/assets/e558db92-74e4-4b78-9068-4dea1ffe3155" width="100%">

---

### **3. Test with Deliberate Code Issues**
To test Codacy’s capabilities, include intentional errors in your code, such as naming inconsistencies, duplication, or missing error handling. Observe how Codacy detects and reports these issues.

<img src="https://github.com/user-attachments/assets/35182bbf-50ca-4d33-a357-954d25d341c5" width="100%">

---

### **4. Integrate Codacy with GitHub**
1. Enable GitHub integration in Codacy:
   - Go to **Settings > Integrations** in your Codacy dashboard.
   - Activate **GitHub Status Checks** to view analysis results directly in your pull requests.
2. Once integrated, Codacy will provide feedback automatically during your development process.

<img src="https://github.com/user-attachments/assets/b3926f11-5f87-459b-b42a-03bf427802cd" width="100%">

---

## Analysis and Evaluation

### **Benefits of Integration**

- **Automatic Code Reviews**: Save time by automating style and complexity checks.
- **Feedback in Pull Requests**: View issues directly in GitHub pull requests.
- **Customizable Rules**: Focus on the metrics that matter most for your project.
- **Improved Code Quality**: Maintain consistent standards across your team.

### **Example Workflow**

1. Developer submits a pull request.
2. CodeFactor/Codacy analyzes the code changes.
3. Issues and suggestions are displayed directly in the pull request.
4. Developer resolves the issues before merging.

### **Troubleshooting**

- **Analysis Not Triggering**: Ensure the repository is public or that the service has access to your private repository.
  
---

## Directory Structure

```
📂 Learning-Codacy
├── 📁 Codes
│   ├── 📄 sample_code_corrected.py               # Testing script for the corrected workflow, ensuring proper functionality of the Streamlit app.
│   ├── 📄 sample_code_with_errors.py             # Script demonstrating the erroneous workflow for analysis and debugging.
│   ├── 📄 sample_code_with_errors_codefactor.py  # Script showcasing the error-prone workflow updated for CodeFactor review and improvements.
│
├── 📁 Documentation Files
│   ├── 📄 Code Review Automation.md              # Sprint planning document outlining the development process and project timeline.
│   ├── 📄 Code Review Automation.pdf             # A formatted PDF report summarizing project outputs and features for sharing and printing.
│
├── 📁 Output
│   ├── 📄 Experiment 9 Output.docx               # Word document explaining the experiment's results in detail.
│   ├── 📄 Experiment 9 Output.pdf                # PDF version of the experiment's outputs for easy distribution.
│
├── 📄 README.md                                  # Overview of the project, including purpose, setup instructions, and key features.
├── 📄 LICENSE.md                                 # License information governing the usage, distribution, and modification of the project.
```

---

## Thanks for Visiting 😄

- Drop a 🌟 if you find this repository useful.<br><br>
- If you have any doubts or suggestions, feel free to reach me.<br><br>
📫 How to reach me:  &nbsp; [![Linkedin Badge](https://img.shields.io/badge/-madhurima-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/madhurima-rawat/) &nbsp; &nbsp;
<a href ="mailto:rawatmadhurima@gmail.com"><img src="https://github.com/madhurimarawat/Machine-Learning-Using-Python/assets/105432776/b6a0873a-e961-42c0-8fbf-ab65828c961a" height=35 width=30 title="Mail Illustration" alt="Mail Illustration📫" > </a><br><br>
- **Contribute and Discuss:** Feel free to open <a href= "https://github.com/madhurimarawat/Learning-Codacy/issues">issues 🐛</a>, submit <a href = "https://github.com/madhurimarawat/Learning-Codacy/pulls">pull requests 🛠️</a>, or start <a href = "https://github.com/madhurimarawat/Learning-Codacy/discussions">discussions 💬</a> to help improve this repository!
