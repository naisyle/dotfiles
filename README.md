# Dotfiles

This repository contains my personal dotfiles for setting up and configuring my development environment across multiple systems.

## 📌 What's Included

Shell configurations (.bashrc, .zshrc, .aliases, .profile)

Editor settings (VS Code, Neovim, etc.)

Terminal settings (wezterm, kitty)

Wallpapers 

## 🚀 Setup Instructions

Clone the repository:

git clone https://github.com/naisyle/dotfiles.git
cd dotfiles

Backup existing config files (optional but recommended).

Symlink dotfiles (or copy them manually):

New-Item -ItemType SymbolicLink -Path $PROFILE -Target "$PWD\powershell\Microsoft.PowerShell_profile.ps1"

Install dependencies (if applicable):

choco install <package>

## 📌 To-Do