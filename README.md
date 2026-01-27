## CI Pipeline Configuration
This project uses GitHub Actions to run a basic CI pipeline.

- CI tool: GitHub Actions  
- Runner: Ubuntu (ubuntu-latest)  
- The pipeline runs automatically:
  - When code is pushed to the main branch
  - When a pull request is created for the main branch  

---

## Workflow Steps
1. The workflow first downloads (checks out) the project code.  
2. It checks whether the `index.html` file exists in the repository.  
3. If the file is missing, the workflow fails and shows an error in the logs.  

---

## Environment Variables and Secrets
- Normal configuration values can be added as environment variables in the workflow file.  
- Sensitive data like tokens or passwords should be stored using GitHub Secrets for security.  

---

## Failure Handling
To understand how CI failures work, the workflow was intentionally broken by changing the validation step.  
After checking the error logs, the issue was fixed and the pipeline ran successfully again.  

---

## Learning Outcomes
- Learned how to create a GitHub Actions workflow.  
- Understood how CI pipelines trigger automatically on push and pull requests.  
- Learned how to read logs to debug CI failures.  
- Understood the importance of keeping secrets secure.  

---

## Tools and Technologies Used
- GitHub Actions  
- YAML  
- Ubuntu Linux  
- Git and GitHub  

---

## Screenshots
Screenshots of the successful workflow run and logs are included to show the working CI pipeline.  

---

## Conclusion
This project helped me understand the basics of CI using GitHub Actions and how automation helps maintain code quality.
