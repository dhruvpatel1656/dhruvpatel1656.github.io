# Deploy your portfolio on GitHub Pages (Windows)

1. Open PowerShell and go to this folder:
   cd $HOME\Downloads\portfolio-site\portfolio-site   (adjust if your unzip created a single folder)
2. Publish it as a repo named exactly dhruvpatel1656.github.io:
   git init -b main
   git add .
   git commit -m "Initial commit: portfolio website"
   gh repo create dhruvpatel1656.github.io --public --source=. --remote=origin --push
3. On GitHub open the repo > Settings > Pages. Under "Build and deployment" set Source to
   "Deploy from a branch", Branch to main and folder to / (root), then Save.
4. After 1-2 minutes your site is live at https://dhruvpatel1656.github.io
5. Add that link to your GitHub profile (Edit profile > Website), to LinkedIn, and to each repo's Website field.
