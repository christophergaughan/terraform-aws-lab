# Terraform AWS Lab

This repository is a **sample public Terraform lab setup**, created for demonstration and public viewing purposes.

The main goal is to show a **clean, professional infrastructure-as-code (IaC) workflow** using Terraform, including:

- A basic example AWS S3 bucket configuration (`main.tf`)
- Version constraints and provider requirements (`versions.tf`)
- Proper `.gitignore` usage to exclude local `.terraform` directories and avoid pushing provider binaries
- A sample GitHub Actions workflow (`.github/workflows/terraform.yml`) to validate Terraform code automatically

---

## Why public?

I also maintain private Terraform repositories that include more advanced modules and production-level configurations. This public repo serves as a simplified, open example to share best practices without exposing sensitive or proprietary infrastructure details.

---

## Key points

- **Modular and version-controlled:** Demonstrates foundational structure you’d use in larger Terraform setups
- **CI/CD ready:** Integrated GitHub Actions pipeline to run `terraform fmt`, `validate`, and `plan`
- **No credentials included:** No actual AWS keys or sensitive data; fully safe to fork or inspect

---

## Why Terraform?

While there are many strong infrastructure-as-code (IaC) tools out there (like Pulumi and AWS CDK), Terraform was chosen here because:

- **Maturity & ecosystem:** Terraform has a large community and extensive module ecosystem, making it easy to reuse and maintain infrastructure code.
- **Cloud-agnostic flexibility:** Supports multiple cloud providers, so you can design for AWS and keep options open for hybrid or multi-cloud setups.
- **Compliance familiarity:** In highly regulated industries (like clinical research and pharma), Terraform is widely adopted and auditors are comfortable reviewing its state and change history.
- **Strong CI/CD integration:** Pairs well with PR-based workflows and GitHub Actions for automated validation and planning.

This example repo demonstrates these advantages in a simple, transparent way.


### Next steps

Feel free to explore, fork, or use as a starting point to build your own IaC practice setups!

---

**Built for demonstration. For real deployments, always review security, state management, and compliance considerations.**
