
# PopcornFlix

PopcornFlix is a movie recommendation website.




## Appendix

Link to flask server:

https://github.com/Sunidhi-Tiwari/FlaskServer

## Deployment

To deploy this project clone the repo or download it then unzip it.
Open the project direcotry.

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


## Documentation

[Documentation](https://linktodocumentation)

