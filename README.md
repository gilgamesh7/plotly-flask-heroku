# plotly-flask-heroku

Code in <br>
https://blog.heptanalytics.com/flask-plotly-dashboard/ <br>

# On heroku
- Create staging app (plotly-flask-heroku-staging)
- Add to NEW pipeline (plotly-flask-heroku-staging-pipeline)
- Create production app in pipeline (plotly-flask-heroku)


## Instantiate remote GIT
(As of 28/04/2022 , the dashboard has been disabled for OAUTH - only CLI available) <br> <br>
heroku git:remote -a <b>plotly-flask-heroku-staging</b>
<br>
To Check : git remote -v
<br>

# Deploy to Staging
git push heroku main

# Deploy to production
Use Heroku dashboard to promote


