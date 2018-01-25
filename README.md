## ecosystemly

Is where we do the things.
 
 ### Assumptions
 
* Any issue/pr on a project board is ignored
* Every team has their own App
* App posts to only one slack channel for every ping
* App doesn't directly ping Slack users 
* Single project board
* Halp not supported

 ### What to do

1. Listen for Webhook events and parse comment/body for `Team @mention`
    * Issue/Pull create
    * Issue/Pull comment
    * Review Added 
1. Is Issue/Pull on Project Board
    1. put an Issue/Pull Request on triage on board of Projects
        - only unique 
    1. mention to room

### What do you triage
 
#### Pull Requests
* [PR] Put on project board 
   - across GitHub
   - Pull Request from other repositories
* [PR] (general case) - 
* [Issues] - post the comment to slack
* [Issues] - final result - effort - impact
* [Issues/PR] - Labels - type of request

* Do you need to resolve 
* Requested to reviewers
* Comments post reply 
   * Update on ticket w/ @mention
   
* Weekly roundup of triage - this exists in Project
