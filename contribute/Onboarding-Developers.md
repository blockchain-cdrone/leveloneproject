# Onboarding Developers
The [Level One Project](https://leveloneproject.org/) site describes what we're accomplishing.

We use a [standard developer code of conduct](https://www.contributor-covenant.org/version/1/4/code-of-conduct.html)

## External Developer Tools 
(See [Tools Choices](https://github.com/LevelOneProject/Docs/wiki/Tools,-technology,-and-process-choices) for a longer list that includes the reasoning behind each)
* Shipping docs and code are in GitHub at https://github.com/orgs/LevelOneProject.
* [GitHub Wiki search bar](https://chrome.google.com/webstore/detail/wiki-search-for-github/gdifdhnjmjaidbajhapmbcbnoocoeooc) This is a Chrome extension that adds a search for the GitHub Wiki. Not a required tool, but useful.
* Continuous Integration is via [CircleCI](https://circleci.com/gh/LevelOneProject)<sup>[1](#Crosslake)</sup>
* Hosting is via AWS, using and AWS VPC. See [test machine info](https://github.com/LevelOneProject/Docs/blob/master/AWS/Infrastructure/machines.md)
* Docker is used for packaging and deployment and hosts the registry of docker packages. Typically using an [Alpine Linux base image](https://alpinelinux.org/)
* JFrog hosts [Artifactory](https://github.com/LevelOneProject/Docs/blob/master/Artifactory/README.md) - a private Docker, Maven, and NodeJS repositories. We're in the process of moving NodeJS to NPM at https://www.npmjs.com/org/leveloneproject, and the Docker packages to Docker. 

## Internal Developer Tools
* Download Zenhub for project management https://www.zenhub.com/. Requires Chrome or Firefox browser. 
* Developer chat is on https://leveloneproject.slack.com
* Video conferencing: each company just uses their own

## Previous versions of the Level One Project
* Walk-through of the last version: [Prototype Demo - Phase 3 - 01-29-2016.pptx](./Prototype%20Demo%20-%20Phase%203%20-%2001-29-2016.pptx)
* Working software showing last version demo [V3 demo site](https://india-ist.open-dfs.org/ut/main.html)
Note: User, Pwd is Admin, 123
* Financial information for countries with low infrastructure: [FSPMaps](http://fspmaps.org). You can click on individual dots to see pictures.

## How do I start working with Mojaloop
1)	Review the Readme.md, contributor.md and FAQ.md guides in GitHub 
•	The Docs repository in GitHub includes the overall architecture, component design, message flow, and an overview of the Mojaloop software
•	Individual repositories within the GitHub project each describe component-specific details including source and APIs
2)	Before you start working with Mojaloop it is recommend that you review the details under the \contribute folder with specific emphasis on the roadmap.md
3)	Once you are ready to contribute to Mojaloop it is recommended that you follow GitHub fundamentals:

* Setup a local clone of the project locally; To perform a local setup, follow the setup instructions using Vagrant on your local environment in the [readme.md](https://github.com/LevelOneProject/interop-devops/blob/master/README.md) in the interop-devops repository. 

* Do some work; Fix a bug, pick up an issue; Remember to write good commit messages

* Create the pull request in GitHub; At this point someone from the maintainers team will review and approve or push back on your request

---
<a name="Crosslake">1</a>: Request access from Crosslake Technologies
