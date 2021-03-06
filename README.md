### Project is unmaintained (archived)
Petition for archival is a process in 
which a projects state is altered to the "archival" state. In the "archival" state
no organization member shall accept any pull
request or address any issues related to the
repository. A project can be set to the archival state after a period of six months with no pull requests you must however have two organization members or a club officer petition for this. the project can be restored to an active state by an approved appeal to the developers guild president.

# Daze

**How to Install**

1. If you don't have Node.js, download it at [http://nodejs.org/](http://nodejs.org/) and install it.
2. Clone the repo.
3. Navigate to the 'daze-frontend' folder in terminal/cmd/bash.
4. Run *npm install*. This will install all the packages used in the website.
8. Go back to your first terminal/cmd/bash and run *npm start* to start up the server.
9. Open [http://localhost:3000/](http://localhost:3000/) and you should be at the site.

**Other Info**

- HTML templates go in the "views" folder
- Untemplated HTML files go in the "wip-views" folder
- CSS, Non-Node JS, and IMG files go in the "public" folder in their respective folders
- Avoid pushing directly to master; instead, work on branches and make pull requests!

**Node Packages Used**

- Async
- Body-Parser - Parse body elements in POST requests
- Cookie-Parser - Handle cookies
- Express - Node Framework
- Nunjucks - Render HTML templates
- Request - Make calls to Backend API
- Validator - Validate user input

**Handy Git Commands**

- *git clone [remote repo]* - Get the project repo for the first time
- *git pull origin [branch name]* - Update a branch
- *git status* - Show the files that you have changed.
- *git add --all* - Stage all the files that you have changed for a commit
- *git commit -m [commit message]* - Commit your staged files to your local repo
- *git push origin [branch name]* - Push your local commits from your branch to the remote repo
- *git stash* - Stash your changed files
- *git stash apply* - Apply your stash
- *git branch [branch name]* - Create and checkout a new branch
- *git checkout [branch name]* - Checkout a branch
- *git merge master* - Merge your current branch with master
- *git rebase master* - Rebase your current branch on top of master

**Coding Style**

We'll be using [Airbnb's ES5 Javascript Style Guide](https://github.com/airbnb/javascript/tree/master/es5)

**Good Links to Check Out**

- [Express' Website](http://expressjs.com/)
- [npm's Website](https://www.npmjs.com/)
- [Dead Simple Guide to Node.js, Express, and MongoDB](http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/)
- [ES5 Javascript Style Guide](https://github.com/airbnb/javascript/tree/master/es5)

**License**

Code is licensed under MIT. See the LICENSE file for details.
