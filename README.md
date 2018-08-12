Notes: 
Code is deployed from gh-pages branch and is a projectsite. usersite can only be deployed from the master branch. I am using kickster/Circle CI to build because github-pages doesnt support google-maps jekyll gem I am using. 

To update,
git add, commit,push
bin/deploy
rebuild gh-pages branch in circleCI if it was skipped.
