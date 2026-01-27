# GitHub Actions CI Pipeline

## 📌 Overview
This repository demonstrates a basic **Continuous Integration (CI) pipeline** using **GitHub Actions** for a static HTML project.  
The pipeline automatically validates the project whenever code is pushed or a pull request is created.

---

## 🛠️ Project Structure


---

## ⚙️ CI Pipeline Configuration
- **CI Tool:** GitHub Actions
- **Runner:** Ubuntu (ubuntu-latest)
- **Trigger Events:**
  - Push to `main` branch
  - Pull request to `main` branch

---

## 🔄 Workflow Steps
1. Checkout source code from the repository  
2. Validate that `index.html` file exists  
3. Mark workflow as failed if validation fails  

---

## 🔐 Environment Variables & Secrets
- Environment variables can be defined inside the workflow YAML.
- Sensitive data (tokens, passwords) should be stored securely using **GitHub Secrets**.

---

## ❌ Failure Handling
The workflow was intentionally tested by breaking validation conditions to observe failure logs.  
After fixing the issue, the pipeline successfully passed, ensuring correct CI behavior.

---

## 📚 Learning Outcomes
- Understanding GitHub Actions workflow structure  
- Automating CI on push and pull requests  
- Debugging failed pipelines using logs  
- Secure handling of configuration and secrets  

---

## 🚀 Tools & Technologies Used
- GitHub Actions  
- YAML  
- Ubuntu Linux  
- Git & GitHub  

---

## 📸 Screenshots
Screenshots of workflow execution and logs are added to demonstrate successful CI runs.

---

## ✅ Conclusion
This project confirms a working CI pipeline that ensures basic validation and automation, following DevOps best practices.
