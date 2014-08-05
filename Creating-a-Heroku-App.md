---
layout: module
title: Creating a Heroku App
---

## Create a new App

1. Create a new Play Framework + Java app with Activator:

        activator new hello-heroku play-java

    This creates a new application from the `play-java` template and puts it in a `hello-heroku` directory

2. Change to the new `hello-heroku` directory:

        cd hello-heroku

3. Run the app locally:

        activator ~run

4. Verify the app works locally by opening your browser to: [http://localhost:9000/](http://localhost:9000)


## Deploy the App on Heroku

1. Initialize a git repo in your project's root directory:

        git init

2. Stage the project files to be added to the repo:

        git add .

3. Commit your files:

        git commit -m init

4. Create a new app on Heroku:

        heroku create

5. Deploy the app:

        git push heroku master

    Note: This pushes your source code and then builds it from scratch on Heroku so it will take a few minutes.  Subsequent deploys are faster.

6. Verify the app works on Heroku:

        heroku open

    Note: The app will look different on Heroku because it is running in production mode.  To run locally in production mode use the `activator start` command.

<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="Creating-a-Salesforce1-App.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="Using-Heroku-Connect.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
