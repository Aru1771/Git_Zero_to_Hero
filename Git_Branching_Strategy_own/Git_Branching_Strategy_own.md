“Initially, we clone the repository and create a feature branch from the main branch. All required code, infrastructure, or pipeline changes are implemented in the feature branch.

After completing the changes, we commit the code locally and push the feature branch to GitHub.

Then we raise a Pull Request against the main branch. Once the PR is created, the CI pipeline is automatically triggered through GitHub webhooks and Jenkins.

The CI pipeline performs validations such as:

Build validation
Unit testing
SonarQube analysis
Docker image build
Security scanning
Kubernetes/Terraform validation

After all CI checks pass successfully, peer reviewers verify both the code changes and pipeline status before approving the PR.

Once the PR is approved and merged into the main branch, the CD pipeline gets triggered automatically and deploys the application to development and staging environments.”
