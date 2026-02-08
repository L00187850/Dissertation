# \# Generative AI IaC compliant with Compliance Standard



\## Project Overview



This repository contains the Infrastructure as Code (IaC) and CI/CD pipelines for a highly secure, AWS-based environment. The architecture is designed to meet ISO 27001 Annex A controls.



\### The following scripts are found in this repository.

&nbsp;- "Enable Nested Virtualisation (if using virtual machine).ps1" = This script enables nested virtualisation for docker if required. Note that the VM name must be adjusted in the script.

&nbsp;- Initial Prompt = This is the prompt developed to prepare the LLM environment

&nbsp;- "Install Jenkins Container.bat" = This bat file installs the Jenkins container used in Docker.

&nbsp;- "install python and checkov.bat" = This command installs both Python and Checkov for the Jenkins image.

&nbsp;- "verify checkov functionality.bat" = This command verifies if checkov is installed before proceeding.

&nbsp;- "Remediation Loop Logs.zip" = Text files displaying logs obtained per Jenkins build. Each log displays the progress from the previous iteration.



