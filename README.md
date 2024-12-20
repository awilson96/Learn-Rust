# Learn-Rust
This is a repository for learning how to program in rust

## Downloading Rust

1. Download and Install Rustup
2. Open your browser and go to https://rustup.rs/.
3. Click "Install Rust" to download the Rustup installer.
4. Run the installer.
5. Follow Installation Prompts. During installation, Rustup will:
Install the Rust compiler (rustc) and package manager (cargo). Set up the environment paths automatically. Ensure you have the necessary build tools (if not, it will prompt you to install them).
6. Install Required Build Tools. Rust uses the MSVC (Microsoft C++) toolchain by default on Windows. If you don’t have the build tools, the Rust installer will ask to install them: Click "Yes" to download the Visual Studio Build Tools. Select the "C++ build tools" workload during installation.
7. Verify Installation
After installation, restart your terminal or command prompt and run:

```bash
rustc --version
cargo --version
```
You should see version numbers if the installation was successful.

8. Set Up a Code Editor. Recommended: Visual Studio Code (VS Code)
Download and install VS Code from https://code.visualstudio.com/.
9. Install the Rust Analyzer extension: Open VS Code. Go to Extensions (Ctrl+Shift+X). Search for Rust Analyzer and click Install.

## Cloning the project
The repository is public and available to anyone who wants to learn Rust. to clone the project:

### In Windows:
1. If you have not already, install Git Bash
2. Open Git Bash in the directory you wish to clone the project in (right click in the file explorer and select Git Bash Here)
3. In the terminal, run the command `git clone https://github.com/awilson96/Learn-Rust.git` to clone using the HTTPS protocol (recommended). If you have issues clone with HTTPS then you can try cloning using SSH by running the command `git clone git@github.com:awilson96/Learn-Rust.git`. If you are having issues with both of these commands then you will probably need to add your SSH key in GitHub for cloning via SSH. **If you are not having issues you are done, but to add SSH keys continue with the following steps**.
4. Click on your profile
5. Then select settings
6. Select SSH and GBD keys
7. Add your SSH key from the .ssh/ folder in a file called id_rsa.pub. Copy the contents of this file and paste it into the SSH keys section of GitHub
8. try recloning via SSH.

### In Linux
1. In the terminal, run the command `git clone https://github.com/awilson96/Learn-Rust.git` in the directory where you want to clone the repository if you prefer using the HTTPS protocol (recommended). If you have issues clone with HTTPS then you can try cloning using SSH by running the command `git clone git@github.com:awilson96/Learn-Rust.git`. If you are having issues with both of these commands then you will probably need to add your SSH key in GitHub for cloning via SSH. **If you are not having issues you are done, but to add SSH keys continue with the following steps**.
2. Click on your profile
3. Then select settings
4. Select SSH and GBD keys
5. Add your SSH key from the .ssh/ folder in a file called id_rsa.pub. Copy the contents of this file and paste it into the SSH keys section of GitHub
6. try recloning via SSH.


## Getting started (hello-world)
1. To create a new project, run `cargo new <project name>`
2. Change directories to the newly create project name `cd <project name>` 
3. Run the command `cargo run` in this directory to compile and run the code.

