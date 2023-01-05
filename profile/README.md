<div align="center"><h1>SueApp</h1></div>

## Frontend React:
  - package manager: yarn
  - install dependencies: yarn install
  - start project: yarn start
  - add dependecie: yarn add <package-name>
  - delete dependecie: yarn remove <package-name>
  - build react app: yarn build
  
## Backend Node.JS Express: 
  - package manager: npm
  - install dependencies: npm install
  - start project: npm start
  - add dependecie: npm install <package-name>
  - delete dependecie: npm uninstall <package-name>
  - for secret data like aws keys, DB password, etc use .env file
  
  ## Github Commit Workflow:
  - git checkout main.
  - git pull origin main.
  - git checkout -b SUMR-123.
  - Do work
  - Work is done
  - git add .
  - git commit -m "commit-name" (use JIRA task name eg. SUMR-123)
  - git checkout main.
  - git pull origin main.
  - git checkout SUMR-123.
  - git rebase main.
  - git push origin SUMR-123.
  - Than create pull request
