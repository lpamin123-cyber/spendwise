# SpendWise — Personal Finance & Expense Tracker

## Project Description
SpendWise is a responsive web application built to help users record daily expenses, categorize spending, monitor budgets, and visualize personal financial habits in real time. Deploying from a local workspace to Netlify makes the application accessible on the web with automatic continuous deployment from GitHub.

## Technologies Used
- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Version Control & CLI:** Git, Git Bash, GitHub
- **Deployment & CI/CD:** Netlify

## GitHub Repository Information
- **Repository Name:** `spendwise`
- **Repository URL:** `https://github.com/lpamin123-cyber/spendwise`
- **Branch:** `main`
- **Visibility:** Public

## Live Netlify Website URL
- **Live URL:** `https://actual-netlify-subdomain.netlify.app`

## Deployment Process Summary
1. **Deployment Readiness:** Verified project files inside `~/spendwise` and prepared `.gitignore`.
2. **GitHub Repository:** Pushed the project to a public GitHub repository (`https://github.com/lpamin123-cyber/spendwise`) on the `main` branch.
3. **Netlify Deployment:** Connected the GitHub repository to Netlify, deployed the site, and updated the subdomain to a custom SpendWise site name.
4. **Continuous Deployment & Testing:** Made a visible update, pushed to `main`, verified automatic Netlify builds, and tested pages, styles, scripts, and assets on the live URL.

## Challenges Encountered During Deployment
- **Heredoc & Directory Prompts in Git Bash:** Resolved unclosed `cat << 'EOF'` prompts with `Ctrl + C` and ensured commands ran inside `~/spendwise` with `EOF` on its own line.
- **Remote URL & Asset Verification:** Updated `origin` to `https://github.com/lpamin123-cyber/spendwise.git` and checked browser DevTools (`Console` and `Network`) on the live site for `404` or script errors.

## Lessons Learned
- Always verify `pwd` and `git remote -v` before committing or pushing changes.
- Linking GitHub to Netlify automates builds and updates on every push to `main`.
- Testing the live Netlify site in the browser catches path or asset issues early.
