# Making Your First Commit!

Welcome to the IEEE: Computer Society!

This is your first-ever GitHub repository! Ever heard of hazing? Well, this is it... but way more fun. By the end of this workshop, you'll have successfully created your first commit on GitHub. Let's get started!

---

## Step 1: Install Git and GitHub CLI

Before you begin, you need to install Git and the GitHub CLI. Follow the instructions below based on your operating system.

### **Mac**
#### Install Git:
1. Open **Terminal**.
2. Run the following command to check if Git is already installed:
   ```bash
   git --version
   ```
3. If Git is not installed, install it via Homebrew:
   ```bash
   brew install git
   ```
4. Verify the installation:
   ```bash
   git --version
   ```

#### Install GitHub CLI:
1. Install GitHub CLI using Homebrew:
   ```bash
   brew install gh
   ```
2. Verify the installation:
   ```bash
   gh --version
   ```

### **Windows**
#### Install Git:
1. Download the Git installer from [here](https://git-scm.com/download/win).
2. Run the installer and follow the default setup.
3. Open **Command Prompt** or **PowerShell**, and verify the installation:
   ```bash
   git --version
   ```

#### Install GitHub CLI:
1. Download the GitHub CLI installer from [here](https://github.com/cli/cli/releases/latest).
2. Install it and restart your terminal.
3. Verify the installation:
   ```bash
   gh --version
   ```

### **Linux**
#### Install Git:
1. Open a terminal and install Git based on your distribution:
   ```bash
   sudo apt install git       # Debian/Ubuntu
   sudo dnf install git       # Fedora
   sudo pacman -S git         # Arch
   ```
2. Verify the installation:
   ```bash
   git --version
   ```

#### Install GitHub CLI:
1. Follow the installation guide for your distro from [GitHub CLI](https://github.com/cli/cli/blob/trunk/docs/install_linux.md).
2. Verify the installation:
   ```bash
   gh --version
   ```

---

## Step 2: Clone the Repository

Open your terminal and navigate to the directory where you want to clone the repository. Then, run:
```bash
git clone https://github.com/Computer-Society-EWU/Hello-World.git
```
This will create a local copy of the project on your machine.

---

## Step 3: Create a New Branch

Navigate into the cloned repository:
```bash
cd Hello-World
```
Then, create a new branch:
```bash
git checkout -b your-new-branch-name
```
Replace `your-new-branch-name` with a relevant name for your contribution.

---

## Step 4: Create Your "Hello, World" Program

Create a new file in your preferred programming language that prints "Hello, World". Example for Python:
```python
print("Hello, World")
```
Save this file inside the `Hello-World` directory.

---

## Step 5: Commit Your Changes

Add your changes:
```bash
git add .
```
Commit your changes with a meaningful message:
```bash
git commit -m "Added my Hello, World program"
```

---

## Step 6: Push Your Changes to GitHub

Push your changes to GitHub:
```bash
git push origin your-new-branch-name
```
Replace `your-new-branch-name` with the name of the branch you created earlier.

---

## Step 7: Create a Pull Request

1. Go to the [GitHub repository](https://github.com/Computer-Society-EWU/Hello-World).
2. Switch to your branch.
3. Click on "Pull Request" and fill in the details.
4. Submit your pull request!

Congratulations! 🎉 You've made your first contribution to a GitHub project!

---

## Step 8: Merge Your Changes

After your pull request has been reviewed and approved, you can merge your changes into the main branch. Follow these steps:

1. Switch to the main branch:
   ```bash
   git checkout main
   ```
2. Pull the latest updates from the main branch:
   ```bash
   git pull origin main
   ```
3. Merge your branch into the main branch:
   ```bash
   git merge your-new-branch-name
   ```
4. Push your changes to the main branch:
   ```bash
   git push origin main
   ```

---

## Step 9: Switch Branches

To switch to another branch, use:
```bash
git checkout another-branch-name
```
Replace `another-branch-name` with the branch you want to switch to.

---

## Step 10: Advanced Git Features

Explore advanced Git features such as:
- **Rebasing**: Integrate changes from another branch cleanly.
- **Cherry-picking**: Apply specific commits from one branch to another.
- **Handling merge conflicts**: Resolve conflicts when merging branches.

Check the [Git documentation](https://git-scm.com/doc) or other online resources to deepen your understanding.

---

If you get stuck, don't hesitate to ask for help. 

**Bonus AI-generated joke:**
> Why don’t programmers like nature? It has too many bugs! 🐛

