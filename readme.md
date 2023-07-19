 <h1 align="center">task-2<h1>

### 
To make an API to fetch latest videos sorted in reverse chronological order of their
publishing date-time from YouTube for a given tag/search query in a paginated
response.

<h2 align="center">Backend<h2>

### Backend-Link:-
    https://hack2skilltask-2.onrender.com

## Installation

1. Clone the repository:
   git clone https://github.com/your-username/library-app.git
   
## Pre - requisites
Before running the application, make sure you have the following installed:

* Node.js
* MongoDB

## Install the dependencies:
```
npm install
```

     "dependencies": {
    "cors": "^2.8.5",
    "dotenv": "^16.3.1",
    "express": "^4.18.2",
    "googleapis": "^122.0.0",
    "mongoose": "^7.3.4",
    "nodemon": "^3.0.1"
  },
       

## Start the server:

     npm run start
The server will start running on the specified port.

## API Endpoint

  1. to get all data regarding cricket

    * method : GET
    * Endpoint : /videos

   
    * Response:
      200 OK: all available data of cricket.
      500 Internal Server Error: Error fetching latest videos
      
  2. to get all paginated data regarding cricket

    * method : GET
    * Endpoint : /videos?page=<pageno.>&limit=<limitno.>

   
    * Response:
      200 OK: paginated available data of football.
      500 Internal Server Error: Error fetching latest videos

   3. to get all data regarding cricket by search with title and description

    * method : GET
    * Endpoint : /search?q=<title or description>

   
    * Response:
      200 OK: all available data of cricket according to search.
      500 Internal Server Error: Error fetching latest videos

## Tech Stacks

<h4 align="center ">Backend</h4>
<div display:"flex" align="center">
<img src="https://camo.githubusercontent.com/a1eae878fdd3d1c1b687992ca74e5cac85f4b68e60a6efaa7bc8dc9883b71229/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e6f64652e6a732d3333393933333f7374796c653d666f722d7468652d6261646765266c6f676f3d6e6f6465646f746a73266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/7f73136d92799b19be179d1ed87b461120c35ed917c7d5ab59a7606209da7bd3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f457870726573732e6a732d3030303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d65787072657373266c6f676f436f6c6f723d7768697465">
<img src="https://camo.githubusercontent.com/72e92f69f36703548704a9eeda2a9889c2756b5e08f01a9aec6e658c148d014e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6f6e676f44422d3445413934423f7374796c653d666f722d7468652d6261646765266c6f676f3d6d6f6e676f6462266c6f676f436f6c6f723d7768697465">
</div>

<br/>
<br/>

## Environment Variables


`mongoURL`

`port`

`key1`

`key2`

