# Git Setup

This section guides you through installing and configuring Git to prepare for version control.

## Installing Git
Git is available for Windows, macOS, and Linux. Follow these steps to install it:

- **Windows**:
  - Download the installer from [git-scm.com](https://git-scm.com).
  - Run the installer, accepting default settings unless specific customization is needed.
  - Verify installation by opening a terminal (e.g., Command Prompt or PowerShell) and typing `git --version`.
- **macOS**:
  - Install via Homebrew: `brew install git` (requires Homebrew installed).
  - Alternatively, download the installer from [git-scm.com](https://git-scm.com).
  - Verify with `git --version` in Terminal.
- **Linux**:
  - Install via package manager (e.g., `sudo apt install git` for Ubuntu/Debian or `sudo yum install git` for CentOS).
  - Verify with `git --version`.

## Configuring Git
Configure Git with your identity to associate commits with your name and email:

- Set your name: `git config --global user.name "Your Name"`
- Set your email: `git config --global user.email "your.email@example.com"`
- Optional: Configure a default text editor (e.g., `git config --global core.editor "nano"` for Nano).
- View configurations: `git config --list`

## Verifying Setup
Ensure Git is ready for use:

- Check the version: `git --version` (should display the installed Git version, e.g., `git version 2.39.2`).
- Verify configuration: `git config --global user.name` and `git config --global user.email` to confirm your settings.
- Test initialization: Create a directory, run `git init`, and check for a `.git` folder to confirm repository creation.

With Git installed and configured, you're ready to explore its core concepts in the next section.