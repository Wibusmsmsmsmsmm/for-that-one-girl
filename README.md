# For That One Girl

This repository is a library of tools, where each directory represents a unique, standalone project. Users can easily upload the contents of any directory to a new GitHub repository, set up a GitHub Actions workflow, and deploy it seamlessly.

## Features
- **Modular Design**: Each directory is self-contained and can function independently.
- **Effortless Deployment**: Deploy any tool by simply download the content inside the directory containing your desired tool, upload it to a new GitHub repository and configuring GitHub Actions.
- **Customizable**: Modify the files (HTML, CSS, JS) to tailor it to your specific needs.

---

## How to Use

Follow these steps to use and deploy a tool from this repository:

### 1. Clone the Repository
Begin by cloning this repository to access all available tools:
```bash
git clone https://github.com/techmoocher/for-that-one-girl.git
```

### 2. Choose your desired tool
Check what tools are avialable with
```bash
ls
```
Navigate to your desired tool (for example: good-night)
```bash
cd good-night
```

### 3. Upload to Github
First, you have to create a Github account. Once you've got your Github account, create a new repository (name it whatever your want). Then, upload all the content into your newly created repository.
Refer to this link to learn how to upload files: <a href="https://docs.github.com/en/repositories">https://docs.github.com/en/repositories</a>

### 4. Deploy with Github Actions
Go to <b>Settings</b>, head for <b>Pages</b>.
On <b>Pages</b>, right under the <b>Build and Deployment</b> title, click the dropdown menu, choose <b>Github Actions</b>. On the <b>Static HTML</b>, click <b>Configure</b>, then click <b>Commit changes...</b>. You will have to wait for around 1-2 minutes for the deployment to finish. After that go to your browser and start using the web with <i>{your_github_username}.github.io/{repository_name}</i>
