# Infrastructure as Code (IaC) with Terraform:  (terraform-docker-demo)
  Getting Started Clone the repository: git clone https://github.com/asmat72/terraform-docker-demo.git  Navigate to the project directory:
📌 Objective : 
      - Provision a “local Docker container” using “Terraform”, demonstrating how infrastructure can be defined and managed as code.
🛠 Tools Used :
      - “Terraform”:  Infrastructure as Code tool for automating resource provisioning.
      - “Docker”: Containerization platform used to run lightweight, isolated applications.
 📁 Files Included :
      - main.tf`: Terraform configuration file that defines the Docker image and container.
      - “Execution logs”: Execution logs from Terraform commands (“init”, “plan”, “apply”, “state”,     “destroy”).
🚀 Working Process :
   1. Environment Setup :
      - Installed Terraform and Docker on an AWS EC2 instance (Ubuntu).
      - Verified installations using “terraform –version” and “docker –version”.
   2. Terraform Configuration :
      - Created a “main.tf” file with the following components:
         • Docker provider block
         • Docker image resource (“nginx : latest”)
         • Docker container resource exposing port 8080
   3. Terraform Workflow :
      - Executed the following commands step-by-step:
         a. Initialize Terraform
         b. Preview Infrastructure Plan.  (Shows what Terraform will create.)
         c. Apply Configuration.    (Creates the Docker container.)
         d. Check Terraform State.   (Displays managed resources.)
         e. Destroy Infrastructure.    (Removes the container and cleans up.)
   4. Outcome :
      - Successfully provisioned and destroyed a Docker container using Terraform. Gained hands-on experience with:
         • Docker provider usage
         • Terraform resource definitions
         • Managing infrastructure lifecycle via CLI
