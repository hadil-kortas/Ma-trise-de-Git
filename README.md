# DevOps Practical Work - Git Mastery
This practical work aims to familiarize you with Git, a widely-used decentralized version control system. The practical work covers the following aspects:
## Part 1: Setting up the Git Environment
  1. **SSH Key Generation:**
     - Generating SSH key: `ssh-keygen -t rsa -b 4096 -C kortashadil27@example.com`
     - Adding the SSH public key to the remote repository.
---
  2. **Git Configuration:**
     - Configuring the username: `git config --global user.name "Hadil kortas"`
     - Configuring the email address: `git config --global user.email kortashadil27@gmail.com`
---
  3. **SSH Connection to Remote Repositories:**
     - Testing SSH connection: `ssh -T git@github.com`
---
## Part 2: Creating a New Project
  1. **Creating the Project on GitHub:**
     - Creating a new project with appropriate options.
     - Cloning the project locally: `git clone git@github.com:hadil-kortas/Maitrise-de-Git.git`
     - `cd Maitrise-de-Git`
---
## Part 3: Basic Git Concepts
  1. **Working with Files:**
     - Create a file named index.html: `touch index.html`
     - `echo 'My index.html Content' > index.html `
     - Using the following commands to add the file to the index and commitmy first change: `git add index.html`
     - `git commit -m "First commit: added index.html" `
  2. ** Commit History:**








