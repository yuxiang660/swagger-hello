# GitHub Pages for Swagger Restful API Docs
## Resource
* Static contents
  - ./docs
* Workflow
  - ./.github/workflow/static.yml
## Workflow Setting
* Create "ACTIONS_DEPLOY_KEY" or "PERSONAL_TOKEN"
  - "ACTIONS_DEPLOY_KEY", refer to [the configuration](https://github.com/marketplace/actions/github-pages-action#1-add-ssh-deploy-key)
  - "PERSONAL_TOKEN", refer to [the configuration](https://github.com/marketplace/actions/github-pages-action#%EF%B8%8F-personal_token)
* Set Action Event
  - Refer to [push request on path](https://help.github.com/en/actions/automating-your-workflow-with-github-actions/workflow-syntax-for-github-actions#onpushpull_requestpaths)
