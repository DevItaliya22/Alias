# Terminal Productivity Setup: Windows (PowerShell) & macOS (ZSH)

This guide documents terminal aliases and functions to speed up development on both Windows and macOS. It includes Git helpers, npm shortcuts, tunneling tools, and common quality-of-life utilities.

---

## 🪟 Windows Terminal Setup (PowerShell)

Use the contents of alias.txt and add it to your PowerShell profile.

To open and edit your PowerShell profile:

```powershell
notepad $PROFILE
```

Then paste the content of alias.txt into the file and save it.

Make sure to enable script execution:

```powershell
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```

---

## 🍎 macOS ZSH Setup

Use the contents of mac.xttx and paste it into your \~/.zshrc file.

To open the file:

```zsh
nano ~/.zshrc
```

Paste the contents of mac.xttx, save, and reload your shell with:

```zsh
source ~/.zshrc
```

---

Now your terminal on both Windows and macOS is ready for rapid development ✨

Feel free to customize further!
