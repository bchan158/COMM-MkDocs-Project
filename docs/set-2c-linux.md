# How to Install and Set Up Git on Linux

Git is a widely used version control system that allows developers to track changes in their code efficiently. This guide provides step-by-step instructions on how to install and configure Git on Linux.

## Step 1: Install Git on Linux

1 - **Open** a terminal using a keyboard shortcut (Ctrl + Alt + T):

![Linux Terminal](assets/images/open-terminal-linux.png)

---

2 - The installation process depends on your Linux distribution.

=== "Ubuntu / Debian"

    1 - Update the package list:

    ```bash title="Bash"
    sudo apt update
    ```

    ---

    2 - Install Git:

    ```bash title="Bash"
    sudo apt install git -y
    ```

    ---

    3 - Verify the installation:

    ```bash title="Bash"
    git --version
    ```

    !!! success "Success!"

        ```bash title="Bash"
        git version 2.x.x
        ```

=== "Fedora"

    1 - Install Git using DNF:

    ```bash title="Bash"
    sudo dnf install git -y
    ```

    ---

    2 - Verify the installation:

    ```bash title="Bash"
    git --version
    ```

    !!! success "Success!"

        ```bash title="Bash"
        git version 2.x.x
        ```

=== "Arch Linux"

    1 - Install Git using pacman:

    ```bash title="Bash"
    sudo pacman -S git
    ```

    ---

    2 - Verify the installation:

    ```bash title="Bash"
    git --version
    ```

    !!! success "Success!"

        ```bash title="Bash"
        git version 2.x.x
        ```

=== "CentOS / RHEL"

    1 - Install Git using yum:

    ```bash title="Bash"
    sudo yum install git -y
    ```

    ---

    2 - Verify the installation:

    ```bash title="Bash"
    git --version
    ```

    !!! success "Success!"

        ```bash title="Bash"
        git version 2.x.x
        ```

=== "OpenSUSE"

    1 - Install Git using zypper:

    ```bash title="Bash"
    sudo zypper install git
    ```

    ---

    2 - Verify the installation:

    ```bash title="Bash"
    git --version
    ```

    !!! success "Success!"

        ```bash title="Bash"
        git version 2.x.x
        ```

## Step 2: Configure Git

After installing Git, set up your user information.

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
