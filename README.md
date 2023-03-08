# BostonHousePricing
In this project I follow a tutorial by [Krish Naik](https://www.youtube.com/watch?v=MJ1vWb1rGwM) to familiarize myself with the end to end project excution process. From this project I learned some important topics: the CI/CD pipeline process and methods of deploying models. 

### Software and Tools requirements:

1. [GitHub Account](https://github.com)
2. [RenderAccount](https://render.com/) --> Since Heroku discontinued the free tier, I opted to use Render free web services offering.
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GITCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line) or [GitHub Desktop](https://desktop.github.com/)

Create new environment for project
``` 
conda create -p venv python==3.7 -y

```
### Data, EDA, Modeling
1. I use the Boston Housing data offered by sklearn
2. Performed some light exploratory data analysis
3. Used mutivariate linear regression to fit the model for prediction

### Pickling files
I used python's "Pickle" library to load the model and standarized input data files to my web application

### Web app
I used python's flask framework to build my application

### Front-end application
I used Krish's html file to build the front end application, since I don't know how to write html (yet!). 

