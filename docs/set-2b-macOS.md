# How to Install and Set Up Git on macOS

Git is a popular version control system that allows developers to track changes in their code efficiently. This guide provides step-by-step instructions on installing and configuring Git on macOS.

## Step 1: Install Git on macOS

1 - **Open** a terminal by **typing** "Terminal" in _Spotlight_:

![macOS Terminal](assets/images/open-terminal-macos.png)

---

2 - Install Homebrew:

```bash title="Bash"
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

---

3 - Install Git via Homebrew:

```bash title="Bash"
brew install git
```

---

4 - Verfiy the installation:

```bash title="Bash"
git --version
```

!!! success "Success!"

    ```bash title="Bash"
    git version 2.x.x
    ```

## Step 2: Configure Git

After installing Git, you need to configure your user details.

1 - Set your name:

```bash title="Bash"
git config --global user.name "Your Name"
```

---

2 - Set your email:

```bash title="Bash"
git config --global user.email "your-email@example.com"
```

---

3 - Verify the configuration:

```bash title="Bash"
git config --list
```

!!! success "Success: You should see something like this"

    ```bash title="Bash"
    user.name=John Doe
    user.email=john.doe@email.com
    ```
