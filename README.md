# Python CI/CD Pipeline with GitHub Actions

This is a DevOps project that demonstrates how to set up a *CI/CD pipeline* for a simple Python application using *GitHub Actions*. It features automated testing with pytest that runs every time new code is pushed to the repository.

---

##  What This Project Does

-  Runs unit tests using pytest
-  Automatically triggers CI workflow via GitHub Actions
-  Demonstrates DevOps tools in action: Git, YAML, CI, testing

---

## Tech Stack

- *Language*: Python  
- *Testing Framework*: Pytest  
- *CI/CD*: GitHub Actions  
- *Config Language*: YAML  
- *Version Control*: Git, GitHub  
---
## How CI works 

- Whenever code is pushed into github:
1. The Github actions workflow(python-app.yml) is triggered.
2. All tests in test_main.py are executed using pytest.
3. Results can be viewed under the actions tab of the repo 
