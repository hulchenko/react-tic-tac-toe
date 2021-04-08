npx create-react-app my-app

npm start (need to cd to my-app folder)

GitHub deployment:

1.  create-react-app app-name
2.  cd app-name
3.  npm install app-name --save-dev
4.  in package.json - http://{username}.github.io/{repo-name}
5.  in package.json - "predeploy": "npm run build", "deploy": "gh-pages -d build"
6.  npm run deploy
7.  git push origin main
8.  indicate gh-page branch if pushed to it
