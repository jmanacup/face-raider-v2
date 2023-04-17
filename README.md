# Face Raider V2

A React web application that uses MXFACE facial recognition API for classroom attendance. Built using React, Express, TailwindCSS.

This is a forked from **Face Raider** hackathon proposed project with additional features such as implementing *TailwindCSS* and adding *swagger* documentation.
 
## Requirements to Run

* create an `.env` file after cloning the repo. This should require the following:

```js
SUPABASE_KEY = ...
PORT = 5000
MXFACE_KEY = ...
MXFACE_REQ_URL = "https://faceapi.mxface.ai/api/v3/face/verify"
```
Details:

| **Field**      | **Description**                                  
|----------------|--------------------------------------------------
| SUPABASE_KEY   | Represents the Supabase API Public Key           
| PORT           | Port for the Express.js                          
| MXFACE_KEY     | API key of the MXFACE API                        
| MXFACE_REQ_URL | This is a constant url that refers to MXFACE API 

### Running the Program

1. To run application, you need to run the server by navigating to *backend* then running the following command,
```
npm run dev
```
2. Then run the react app by navigating to *frontend* and entering,
```
nodemon
```


To request for a demo, please reach out to [me](mailto:john.manacup@gmail.com).
