# How to Install and Set Up Git on Windows

**Step 1: Download Git for Windows**

1. Visit the [Official Git Website](https://git-scm.com/).
2. **Click** on Download for Windows. The website should detect your OS version and provide the correct installer.

**Step 2: Run the Git Installer**

1. **Open** the downloaded .exe file.
2. **Click** Next to begin the installation process.

**Step 3: Configure Installation Options**

During the installation, you will be prompted to select various options:

- Select Components: Keep the default options selected. Ensure Git Bash, Git GUI, and Git LFS are checked.
- Choosing the Default Editor: Select your preferred text editor (e.g., Vim, Nano, Notepad++, or VS Code).
- Adjusting the PATH Environment: Choose Git from the command line and also from 3rd-party software (recommended).
- HTTPS Transport Backend: Select Use the OpenSSL library.
- Line Ending Conversions: Choose Checkout Windows-style, commit Unix-style line endings (recommended for cross-platform projects).
- Configuring the Terminal Emulator: Choose Use MinTTY (default).

**Click** _Install_ and wait for the process to complete.

**Step 4: Verify Installation**

1. **Open** Command Prompt.

```sh
# Verify Installation
git --version
```

If Git is installed correctly, it will return the version number.

**Step 5: Configure Git**

Set up your username and email (these will be used for commits):
