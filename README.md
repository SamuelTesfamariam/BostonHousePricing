This repo is still under development!
# BostonHousePricing
In this project I follow a tutorial by [Krish Naik](https://www.youtube.com/watch?v=MJ1vWb1rGwM) to familiarize myself with the end to end project excution process. From this project I learned some important topics: the CI/CD pipeline process and methods of deploying models, as well as testing APIs using the Postman app.  

### Software and Tools requirements:

1. [GitHub Account](https://github.com)
2. [Render Account](https://render.com/) --> Since Heroku discontinued the free tier, I opted to use Render free web services offering.
3. [VSCode IDE](https://code.visualstudio.com/)
4. [GIT CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line) or [GitHub Desktop](https://desktop.github.com/)
5. [Postman App](https://www.postman.com/downloads/)

Create new environment for project
``` 
conda create -p venv python==3.7 -y

```
<<<<<<< HEAD
### Data, EDA, Modeling
1. I use the Boston Housing data offered by sklearn
2. Performed some light exploratory data analysis
3. Used mutivariate linear regression to fit the model for prediction

### Pickling files
I used python's "Pickle" library to load the model and standarized input data files to my web application

### Web app
I used python's flask framework to build my application. I used the Postman app to test my prediction api (locally and on the Render server, after deployment).

### Front-end application
I used Krish's html file to build the front end application, since I do not know how to write html (yet!). 
