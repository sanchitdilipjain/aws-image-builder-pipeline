## Container Image pipeline using AWS EC2 Image Builder

**Introduction**
- EC2 Image Builder is a completely managed AWS service that simplify the process to automate the creation, management, and deployment of tailored, secure, and up-to-date server images that are pre-installed and pre-configured with software and settings to match specific IT standards.
- Features of EC2 Image Builder

  - Greater productivity and reduce operations for building compliant and up-to-date images
  - Greater service uptime
  - Improved the security standard for deployments
  - Centralized enforcement and lineage tracking
  - Simplified sharing of resources across AWS accounts

**How EC2 Image Builder works?**
- When you use the EC2 Image Builder pipeline console setup to create a custom image, a wizard guides you through the following steps.

  - **Provide pipeline details**: Enter details about your pipeline, such as a name, description, tags, and a schedule to run automated builds.
  - **Select recipe**: Select from building an AMI, or building a container image.
  - **Provide infrastructure configuration**: Image Builder launches EC2 instances in your account to customize images and run validation tests.
  - **Provide distribution settings**: Select the AWS Regions to distribute your image to after the build is complete and has passed all its tests
