## Frontend React:
  - package manager: __Yarn__
  - install dependencies: `yarn install`
  - start project: `yarn start`
  - add dependecie: `yarn add <package-name>`
  - delete dependecie: `yarn remove <package-name>`
  - build react app: `yarn build`
  
## Backend Node.JS Express: 
  - package manager: __NPM__
  - install dependencies: `npm install`
  - start project: `npm start`
  - add dependecie: `npm install <package-name>`
  - delete dependecie: `npm uninstall <package-name>`
  - for secret data like **aws keys, DB password, etc** use `.env` file
  
  ## Github Commit Workflow:
  - `git checkout main.`
  - `git pull origin main`
  - `git checkout -b SUMR-123` (use JIRA task name eg. SUMR-123)
  - __Do work__
  - __Work is done__
  - `git add .`
  - `git commit -m "commit message"`
  - `git checkout main`
  - `git pull origin main`
  - `git checkout SUMR-123`
  - `git rebase main`
  - `git push origin SUMR-123`
  - __Than create pull request__
