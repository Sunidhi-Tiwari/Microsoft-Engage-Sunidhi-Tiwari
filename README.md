
# PopcornFlix

PopcornFlix is a movie recommendation website.




## Flask Server

Link to flask server:

https://github.com/Sunidhi-Tiwari/FlaskServer

## Features

- Fully Responsive
- Sign in/ Sign up
- Recommend Similar movies
- Shows details about a particular movie
- Toggle actor view as well
- Users can create a favourite list of movies
- Users can add and remove from favourite list
- Users can like/dislike a particular movie
- Users can share opinion about a specific movie



## Tech Stack

React.js is used for Frontend.

Flask and Node.js in backend. 

Scikit Learn Count - Vectorizer is used for preperation of the Recommendation system. The Cosine Similarity parameter is used for finding the closest neighbours. The top movies with closest similarity  score are selected.

TMDB is used to fetch the attribute information and image data of movies.
## Run Locally

To deploy this project clone the repo or download it then unzip it.
Open the project direcotry.

Clone:

```bash
  git clone https://github.com/Sunidhi-Tiwari/Microsoft-Engage-Sunidhi-Tiwari
```
Go to the project direcotry
```bash
  cd my-project
```

Install dependencies:

Run

```bash
  npm install
```

Navigate to the client folder and run

```bash
  npm install
```

To connect it with flask server, clone the flask repository(link provided above)
Run the flask server separately. 

Instruction for flask server:
First clone it and then run the command given below in separate terminal to install all dependencies
Clone:

```bash
  git clone https://github.com/Sunidhi-Tiwari/FlaskServer
```
Go to the project direcotry
```bash
  cd my-project

```bash
  pip install -r requirements.txt
```
To start the app in the development server, run the command

```bash
  python app.py
```
To connect the flask server with MERN app (main webapp)

Copy the local host address of flask server and paste that inside the path client -> src -> components -> views -> content -> Recommendation.js (in const MovieRecommendations inside async function getAllData())

After connecting flask server 

Run client and server separately

In root folder run

```bash
   npm start
```

Navigate to client folder and run

```bash
   npm start
```

Requirements:

To run MERN app, Node Js and MongoDB should be pre installed.

Inside server-> config -> dev.js, MongoDB database is connected with my username and password, you can change it.


```bash
   MongoDB ceredentials: 
   username: sudhi
   password: abcd12345
```


## Website Gallery

Screenshots from webapp

https://docs.google.com/document/d/1CBuvMZkdhwJz16SCQ4oq296Wyud3uZR_yBHcWL5E1ao/edit?usp=sharing