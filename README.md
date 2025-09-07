# civic-resistance-toolkit
Open, nonpartisan toolkit to help communities resist authoritarian drift, defend democracy, and protect vulnerable groups. Includes step-by-step action plans, printable resources, and an accessible website for civic engagement.
# Deploy Scripts

Two one-click deployment scripts for the Civic Resistance Toolkit (Vite + React).

## Prerequisites
- GitHub account
- git
- Node.js / npm
- Optional: GitHub CLI (`gh`) for automatic repo creation

## macOS/Linux
```bash
# Inside your project folder (the unzipped toolkit)
chmod +x deploy.sh
GITHUB_USER=YOUR-USERNAME REPO_NAME=civic-resistance-toolkit ./deploy.sh
```

## Windows (PowerShell)
```powershell
# Inside your project folder (the unzipped toolkit)
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
./deploy.ps1 -GitHubUser YOUR-USERNAME -RepoName civic-resistance-toolkit
```

After it runs:
1) Go to Settings â†’ Pages in your repo.
2) Select source: `gh-pages` branch, root `/`.
3) Open: `https://YOUR-USERNAME.github.io/civic-resistance-toolkit/`
