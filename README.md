# FlipkartReviewScrapper
This is Flipkart review scrapper web app which will works only for Flipkart using Flask API and deployed on Heroku

steps for use in your local system:

1. fork the repo
2. clone in your local pc
3. make a seperate environment 
4. install requirements.txt (pip install -r requirements.txt)
5. Run the app.py 

steps for Deployment on Heroku:
https://reviewscrapperflipkart8.herokuapp.com/

1. download heroku cli first from this link https://devcenter.heroku.com/articles/heroku-cli
2. check heroku is installed in our system do open 'Anaconda prompt' or 'Terminal' and just type 'heroku' in there for confirmation.
3. type "heroku login"
4. login on heroku or do sign up
5. go to your heroku dashboard and create a new app and give name
6. in your conda terminal create a new environment "conda create -n <name> python=3.6"  put your environment name in place of <name>
7. go to the file location
8. 'git init'
9. 'heroku git:remote -a <name of your app>  check on your dashboard 
10. 'git add .'
11. git commit -am "first-commit"
12. 'git push heroku master'

you will get the link on the terminal of your deployed app
