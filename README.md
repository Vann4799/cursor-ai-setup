# Cursor AI Setup

Initial setup project for the 100Hires portfolio application process.

## Tools Installed

| Tool | Status | Notes |
|------|--------|-------|
| [Cursor IDE](https://cursor.com/) | Installed | Primary code editor used for this setup |
| Claude Code (Cursor extension) | Installed & logged in | AI coding assistant extension inside Cursor |
| Codex (Cursor extension) | Installed & logged in | AI coding assistant extension inside Cursor |
| Git | Installed | Version control for commit and push |
| GitHub | Account active | Public repository hosting |

## Steps Completed

1. **Downloaded and installed Cursor IDE** from [cursor.com](https://cursor.com/).
2. **Installed Claude Code add-on** in Cursor via the Extensions panel and signed in.
3. **Installed Codex add-on** in Cursor via the Extensions panel and signed in.
4. **Created a public GitHub repository** named `cursor-ai-setup` under account `Vann4799`.
   - Repository URL: https://github.com/Vann4799/cursor-ai-setup
5. **Opened the repository in Cursor IDE** and initialized the local Git repository.
6. **Created this `README.md`** documenting the tools, steps, and any issues encountered.
7. **Committed and pushed** this file to the `main` branch on GitHub.

## Issues Encountered & How They Were Solved

### 1. Connecting local folder to the empty GitHub repository

**Issue:** After creating the repo on GitHub, the local project folder had no remote configured and no commits yet.

**Solution:** Added the GitHub remote with `git remote add origin`, created the README, made the first commit, and pushed to `main` using:

```bash
git remote add origin https://github.com/Vann4799/cursor-ai-setup.git
git add README.md
git commit -m "Add README with setup documentation"
git branch -M main
git push -u origin main
```

### 2. Installing Cursor extensions (Claude Code & Codex)

**Issue:** Extensions are not bundled with Cursor by default and must be installed manually.

**Solution:** Opened the Extensions sidebar in Cursor (`Ctrl+Shift+X`), searched for "Claude Code" and "Codex", clicked Install on each, then followed the sign-in prompts to connect the accounts.

### 3. PowerShell command syntax

**Issue:** Chaining commands with `&&` failed in older PowerShell versions on Windows.

**Solution:** Used semicolons (`;`) to run multiple commands sequentially, or ran each command separately.

---

**Repository:** https://github.com/Vann4799/cursor-ai-setup  
**README link:** https://github.com/Vann4799/cursor-ai-setup/blob/main/README.md
