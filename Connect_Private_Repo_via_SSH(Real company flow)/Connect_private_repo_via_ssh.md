🔐 Connecting to a Private GitHub Repository Using SSH – A Simple but Essential DevOps Skill
When I first started working with Linux servers, I used HTTPS to clone GitHub repositories. 
In most real-world DevOps environments, the preferred approach is SSH authentication because it's secure, passwordless, and ideal for automation.

The basic workflow is straightforward:
✅ Check whether an SSH key already exists
✅ Generate a new SSH key (if required)
✅ Start the SSH agent
✅ Add the private key to the agent
✅ Copy the public key
✅ Add the public key to your GitHub account
✅ Test the SSH connection
✅ Clone the repository using the SSH URL
Once configured, you can clone, pull, and push code without entering your username and password every time.

This becomes especially valuable when working with:
🚀 CI/CD Pipelines
☸️ Kubernetes Deployments
🐳 Docker-based Applications
☁️ AWS EC2 Instances
⚙️ Jenkins & GitHub Actions
🤖 Deployment Automation Scripts
