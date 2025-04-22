# ⚙ .dotfiles

## 📦 Prerequisites

These dotfiles are configured to be used with:
- [Bash](https://www.gnu.org/software/bash/)
- [Stow](https://www.gnu.org/software/stow/)
- [Git](https://git-scm.com/)

## 🚀 Setup

1. Clone this repository to your home directory:

```bash
cd ~
git clone https://github.com/Studsministern/.dotfiles.git
```

2. Change directory to the `.dotfiles` directory:

```bash
cd .dotfiles
```

3. Fill [.gitconfig](/.gitconfig) with your own information.

4. Run the following command to symlink the dotfiles to your home directory:

```bash
stow .
```
