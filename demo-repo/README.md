Yimifi Frontend Project Guide
====================
- - -

## Required Installation

1. Install Node
	- You can [download](https://nodejs.org/en/download/) it from here.
	- To check if installed or node, run command in terminal ``node -v``.
2. Install angular-cli globally.
	- Run this command in terminal. ``npm install -g @angular-cli``.
3. Install Yarn. [Dependency manager which we are using to manage project dependency instead of NPM.].
	- Check out this [document](https://yarnpkg.com/en/docs/install) for reference.
	- To check if installed or node, run ``yarn --version``.


## Project setup
1. Clone repo from bitbucket.
	- ``git clone https://chintanggor@bitbucket.org/yimify/frontend.git``
2. Open terminal and go to repo folder.
3. Install dependency using yarn. This will create node_modules folder.
	- Run command ``yarn``.

## Run Project on local PC in developement mode
1. Run command ``npm start``.
2. Go to browser and type url ``http://localhost:4200``.

## To create build for production mode / for server
1. Run command ``npm run build``
2. It will create dist folder in repo directory. You need to upload all files from dist folder to server to run this project.