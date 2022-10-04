# Spotify-Recommendation-System
- We will have 3 tasks to finish our Spotify Recommendation System Project with deploying it <br>
- Tasks:
    - Task1: Feature Engineering
    - Task2: Building ML Model
    - Task3: Deploying ML Model
<hr>
<center> <h1> Task 1: Feature Engineering</h1> </center>

<hr>

## Task Details 
- Deadline Date: 9/14/2022 <br>
- Deadline Time: 9:00 AM EG, 12:30 AM IST

- Dataset Link:
    - https://drive.google.com/file/d/1QB1suGX6SiyJpDZ9afpnfoRYJTwPyQMQ/view?usp=sharing

- You are required to add at minimum two modifications to the feature engineering of this dataset
    - Feel free to check your notebook regarding this task and add any modification which was not done in this example notebook
    - Feel free to contact your team leader if you want to ask about anything

- Recommendations
    - You may use `boxcox technique` to handle the skewness of the numerical data (but remember it only accepts positive data)
    - You may use `PCA technique` in different manner rather than dimensionality reduction
    - You may use different way than `correlation technique` to get the best features from the dataset
    - You may use `one hot encoding technique` regarding categorical features (yes, no) rather than (1, 0)
    - You may use one/many of the `object` columns and convert them into category `int` using `label encoding technique`



<center> <h1> Task 2: Spotify Collaborative Filtering Model Building</h1> </center>

<hr>

## Task Details 
- Deadline Date: 9/16/2022 <br>
- Deadline Time: 11:59 PM EG, 03:30 AM IST

- Dataset:
    - There are two datasets and we will try to train our model on both and then check the accuracy and compare
        - This is supposed to be made to gain visualization about the importance of PCA
        - The datsets are `model_normal_dataset.csv` and `model_pca_dataset.csv` 
    - Link
        - https://drive.google.com/drive/folders/104scYexDFCHGSWE8pw3sXTmieWwZZUpH?usp=sharing

We are going to build Recommendation System using `Collaborative Filtering` 


<center> <h1> Task 3: Build Basic Website </h1> </center>
<hr>

## Task Details 
- Deadline Date: 9/22/2022 <br>
- Deadline Time: 11:59 PM EG, 03:30 AM IST (9/23/2022)

- You are supposed to build a website using <a href = "https://streamlit.io/" > Streamlit </a>
- The website should contain of minimum one page with:
    - Welcome Title and description of what our website does 
    - Input box where I input the name of the song
    - Output Table where I can control how many rows it should display
    - The output table should contain the track's 
        - Name
        - Album
        - Track Uri
    - Footer which wrote in it, your credit as name, etc.
    - Just do the task with no ML Model explained, just make the user interface and functionalities
    - A BONUS for designing the best user interface

## Website project Files (Flask)
[Website project Repo](https://github.com/engmohamedmostafa2021/Spotify-Recommendation-System-Website

## Deployment
you can access our app by following this link [Spotify-Recommendation-System-Website](https://spotifyrecsys.herokuapp.com/)
### Heroku
We deploy our flask app to [Heroku.com](https://www.heroku.com/). In this way, we can share our app on the internet with others. 
We prepared the needed files to deploy our app successfully:
- Procfile: contains run statements for app file and setup.sh.
- requirements.txt: contains the libraries must be downloaded by Heroku to run app file (app.py)  successfully 
- model.py: contains the python code of the recommendation system algorithm.
### Flask 
We also create our app by using flask , then deployed it to Heroku . The files of this part are located into (Spotify-Recommendation-System-Website) folder. You can access the app by following this link : [Spotify-Recommendation-System-Website](https://spotifyrecsys.herokuapp.com/)