
# JavaScript Server-Side Login Template

A super basic Server-Side Login System. 

The server is based on express and uses a MongoDB database. 
The client uses vite and react and has a basic ui 


# Server

Server node modules:     
- bcrypt
- express
- express-flash
- express-session
- JWT
- mongoose
- nodemon
- cors
- dotenv
- ejs

## Setup Server: 


#### The server uses a `.env` so u have to set it up:
<sub>In the Server directory<sub>

Linux:
```bash
touch .env
```

Windows:
```bash
echo. > .env
```

VSCode:
```bash
code .env
```

#### Set your port in the `.env`

The client uses the port `2020` but you can change the baseurl value for the client  in `./app/src/utils/services.js`
```.env
PORT="2020"
```

than run:
```bash
npm i
```

#### now you only need to [setup the Database](#Database) and you should be good to go


#### Run server in dev mode:
```bash
npm run dev
```

# Client

#### client node modules: 
* react
* react-bootstrap
* react-dom
* react-router-dom

#### ``Get vite``



#### Than run
<sub>In the Client directory<sub>
```bash
npm i
```


#### Run client in dev mode:
```bash
npm run dev
```

# Database

#### Create a MongoDB Cluster

and link it in the `.env` file of the server like this: 

```.env
DBURI="YOURCLUSTERSTING"
```
