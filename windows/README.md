# Windows Dotfiles

This repository contains my personal configuration files (dotfiles) for setting up and customizing my Windows development environment.

## 📌 What's Included

Wezterm Configuration

Neovim Configuration 

Chocolatey package lists

VS Code Settings (settings.json, keybindings.json)

## 🚀 Setup Instructions

Clone the repository:

git clone https://github.com/your-username/windows-dotfiles.git
cd windows-dotfiles

Backup existing config files (optional but recommended).

Symlink dotfiles (or copy them manually):

New-Item -ItemType SymbolicLink -Path $PROFILE -Target "$PWD\powershell\Microsoft.PowerShell_profile.ps1"

Install dependencies (if applicable):

choco install <package>

## 📌 To-Do