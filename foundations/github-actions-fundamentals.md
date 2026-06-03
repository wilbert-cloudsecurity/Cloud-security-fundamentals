# GitHub Actions Fundamentals

## What GitHub Actions Are
GitHub Actions is a CI/CD automation tool that allows you to run workflows based on events in your repository.

## Why GitHub Actions Matter
They enable automation of testing, building, and deployment processes directly from GitHub, improving efficiency and reducing manual work.

---

# Core Concepts

## Workflow Structure
- **name** → Defines the workflow name  
- **on** → Event triggers (push, pull_request, workflow_dispatch)  
- **jobs** → Groups of tasks executed in the workflow  
- **steps** → Sequential execution of commands inside a job  

## Environment Variables (env)
- Used to inject dynamic values into workflows  
- Allow reuse of data like usernames or configurations  
- Help resolve runtime warnings (e.g., forcing Node.js versions)  

## Secrets
- Secure storage for sensitive data (API keys, tokens, passwords)  
- Managed via GitHub CLI or repository settings  
- Automatically masked in logs using ***  

## Triggers
- **main branch triggers** → Run workflows on production branch changes  
- **workflow_dispatch** → Manual execution using a “Run workflow” button  

## Debugging and Audit
- Identify YAML indentation errors  
- Detect missing triggers or misconfigured jobs  
- Analyze logs for logical or security issues  
- Ensure secrets are not exposed in outputs  

---

# What I Practiced

- Created GitHub Actions workflows using YAML structure  
- Configured environment variables for dynamic execution  
- Stored and tested secrets securely using GitHub CLI  
- Set up automated and manual workflow triggers  
- Debugged workflow errors related to syntax and execution order  
- Verified secure handling of sensitive credentials  

---

## Why It Matters
GitHub Actions is essential for automating software and cloud workflows, enabling CI/CD pipelines and improving operational efficiency in real-world engineering environments.
