Jekyll Boilerplate
=============================

A starter project including full setup for Jekyll, GulpJS, SASS, AutoPrefixer &amp; BrowserSync

#### Install Node.js
1.  Install [HomeBrew](http://brew.sh/)
1. `brew install nvm`
1. `nvm install v6.9.4`

#### Setting up the Project
1. Install Jekyll `$ gem install jekyll`
2. Install gulp: `$ npm install -g gulp`
3. Install dependencies: `$ npm install`
4. Serve for dev server: `$ gulp serve`
5. Build for prod: `$ gulp build`

#### Alfred Workflow
*For those who use Alfred Workflows, I made a workflow to quickly spin up a new Jekyll project:*
* [Download Alfred Workflow](https://github.com/BertHaine/tools-workflows/blob/master/alfred/Create%20Jekyll%20Project.alfredworkflow) - trigger the workflow by typing the command Create Jekyll ***YourProjectName***

What This Workflow Does:
1. Creates a new directory **sites** in your Documents directory.
2. Clones this repo and a gitignore into the sites folder titled ***YourProjectName***.
3. Removes the boiler README & git file and creates a fresh git repo. 
4. Opens the project in Iterm & Sublime Text

*If you would like to edit any of the commands, the workflow is a simple bash script.*


## Acknowledgments

Hat tip to

* [Shane Osbourne](https://github.com/shakyShane) for his jekyll boilerplate I built off of for this template.
* [Urban Influence](http://urbaninfluence.com/2016/08/a-flexy-little-grid-system/) for their Flex Grid Mixin used here.