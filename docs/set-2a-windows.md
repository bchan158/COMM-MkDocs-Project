# How to Install and Set Up Git on Windows

**Step 1: Download Git for Windows**

1. Visit the [Official Git Website](https://git-scm.com/).
2. **Click** on Download for Windows. The website should detect your OS version and provide the correct installer.

**Step 2: Run the Git Installer**

- Follow the on-screen instruction to begin the installation.

**Step 3: Configure Installation Options**

During the installation, you will be prompted to select various options:

- Select Components: Keep the default options selected. Ensure Git Bash, Git GUI, and Git LFS are checked.
- Choosing the Default Editor: Select your preferred text editor (e.g., Vim, Nano, Notepad++, or VS Code).
- Adjusting the PATH Environment: Choose Git from the command line and also from 3rd-party software (recommended).
- HTTPS Transport Backend: Select Use the OpenSSL library.
- Line Ending Conversions: Choose Checkout Windows-style, commit Unix-style line endings (recommended for cross-platform projects).
- Configuring the Terminal Emulator: Choose Use MinTTY (default).

**Step 4: Verify Installation**

- **Open** Command Prompt.

```powershell
git --version
```

!!! success "Success!"

    ```powershell
    git version 2.x.x
    ```

## Step 2: Configure Git

After installing Git, you need to configure your user details.

1 - Set your name:

```powershell
git config --global user.name "Your Name"
```

---

2 - Set your email:

```powershell
git config --global user.email "your-email@example.com"
```

---

3 - Verify the configuration:

```powershell
git config --list
```

!!! example "Example"

    ```powershell
    user.name=John Doe
    user.email=john.doe@email.com
    ```
