# What Kind of Tools Should I Use?

![IMG_5716.jpeg](pictures/IMG_5716.jpeg)

https://landscape.cncf.io/

When it comes to choosing the right tools for your automation project, it is essential to consider the specific
requirements of your organization, the complexity of your infrastructure, and the skills of your team members.

---

## What do you need to get started?

### Version Control System (VCS)

A git repository is a good place to start. You can use GitHub, GitLab, or Bitbucket to store your code and collaborate
with your team. These platforms provide version control, issue tracking, and pull request workflows that are essential
for managing your automation codebase.

### Infrastructure as Code (IaC) Tool

An IaC tool like Terraform, AWS CloudFormation, or Azure Resource Manager can help you define and provision your
infrastructure using code.

### Pipeline Orchestration Tool

A CI/CD tool like GitHub Actions, Gitlab or Jenkins can help you automate the build, test, and deployment
processes of your infrastructure code.

---

## What's next?

### Monitoring and Logging

Tools like Prometheus, Grafana, and ELK stack can help you monitor the health and performance of your infrastructure.

### Security and Compliance

Tools like AWS Config, Azure Policy, and HashiCorp Vault can help you enforce security policies and ensure compliance

### Collaboration and Communication

Tools like Slack, Microsoft Teams, or Zoom can help you collaborate with your team and communicate effectively.

### Automated Testing

Tools like Terratest, Pester, and Postman can help you automate testing of your infrastructure code.

---

## Development environment

When it comes to automation, the first and most important application you'll need is a development environment.
In my opinion, there are two tools that you should look into. Each has unique advantages, disadvantages and use cases:

### Visual Studio Code

Visual Studio Code is a lightweight, open-source code editor that is highly extensible and customizable.
It has a rich ecosystem of extensions that can help you write, test, and debug your code more efficiently.

It lacks stable support for Terraform and other IaC tools, but it is a great choice for general-purpose coding. It is
also a good choice for PowerShell DSC-related coding. Git integration is not so stable as in Jet Brains Intellij IDEA.

### Jet Brains Intellij IDEA

Jet Brains Intellij IDEA is a powerful, feature-rich IDE well-suited for Java, Python, and other languages.

It has excellent support for Terraform and other IaC tools, but it is not as lightweight as Visual Studio Code. It is
also a good choice for Terraform-related coding. Git integration is more stable than in Visual Studio Code.

### GitHub CoPilot

Github CoPilot will significantly boost the speed of coding with code completion and help with

### ChatGPT

For the unlikely possibility that you're lost and don't know how to start writing code, just ask ChatGPT.
It helped me on a lot of occasions – even when our developers were unable to do so. However, don't expect too much;
the solutions often don't work completely, and they need some tweaking. Sometimes, Google provides better examples.
