# GitHubActionsLab-Viktoriya

---

## Workflow 1: Job Dependencies

Demonstrates how to define job dependencies using the 'needs' keyword. The sequence is build -> test -> deploy.

Key Concepts
- needs: controls job execution order
- runs-on: specifies the OS runner 
- steps: simulate build, test, and deploy phases


---

## Workflow 2: Environment Variables and Secrets

Shows the use of environment variables at different levels and securely accesses AWS credentials using GitHub Secrets we created

Key Concepts
- env: Defines environment variables at workflow, job, and step levels
- secrets: securely injects AWS credentials only showing names
- workflow_dispatch: enables manual triggering

---

## Workflow 3: Multi-Platform Testing

Runs three independent jobs in parallel across different OS

Key Concepts
- runs-on: executes jobs on ubuntu-latest, windows-latest, and macos-latest
- actions/checkout@v4: checks out the repository
- OS-specific commands: uname -a, systeminfo show OS-specific behavior


---

## Challenges & Resolutions

Didn't meet any challenges, since most of this similliar to in-class exercises



