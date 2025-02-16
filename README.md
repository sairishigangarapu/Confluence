# Confluence
This is a project that makes playlists via an interactive interface


<h1>To perform this project -</h1> 

<h2>Setting up the framework </h2>

1) go to the required directory and create a virtual env by python -m venv venv
2) Then cd venv , Scripts/activate
3) Run pip install flask
4) Go to the URL "http://127.0.0.1:5000/" To check if the server is up and running

<h2>Setting up of the backend(ml.py) and frontend(templates)</h2>

<h3>Dependenices installation</h3>

1)Redirect to the venv <br/>
2)Run "pip install flask openai spotipy dotenv oAuth logging" after activation of the workspace to install all the required dependencies <br/>

<h3>.env file</h3>
1) Create a spotify dev account , then user_profile -> setting <br/>
2) Copy paste your client id and secret into the respective fields<br/>
3) Go to aiml.com and make an account<br/>
4) Go to Get API -> generate apikey and paste this in your .env file<br/>
5) In the dev account make sure to put your redirecting URL "http://localhost:5000/callback" <br/>

Follow this exact file tree while performing tasks on the files

<img width="252" alt="Screenshot 2025-02-16 134003" src="https://github.com/user-attachments/assets/cf859752-98c8-4988-a2b7-a1a97f8ff7a7" />

<b>(Note - All this must be done only while the venv is activated) </b>

<h2>Running the application</h2>
1) In the command prompt type in python ml.py <br/>
2) Copy the URL shown (It will be this http://127.0.0.1:5000/) </br>
3) Now enjoy the app /n
