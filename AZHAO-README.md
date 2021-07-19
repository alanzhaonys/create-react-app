To keep create-react-app up to date:
git remote add upstream git@github.com:facebook/create-react-app.git
git fetch upstream
git pull upstream main


- Fork Facebook https://github.com/facebook/create-react-app
- Clone the repo(now that it's in my own account)
- Make changes
  - packages/react-scripts/config/webpack.config.js
  - packages/react-scripts/package.json - change name to alanzhao-react-scripts
- Commit
- Go into packages/react-scripts, run `npm publish`
