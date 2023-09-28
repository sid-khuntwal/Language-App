# Language-App

#Backend Setup

```
npm i

```

After installing the dependencies create a ".env" file in the root directory and add the following varibles to it

```
ATLAS_URI = mongodb+srv://sidlyf:1234@cluster0.qbfn02m.mongodb.net/?retryWrites=true&w=majority
PORT = 5000

```

This will connect to Database, After this run the following command to start the server

```
npm start
```

Now you must see "Database connected" on console, this means server has started.

#After this you need to start the client

Keeping the server running in the other terminal run the following commands -

```
npm i \\ to install the dependencies

```

after this create a ".env" file in the "client" root and add the following -

```
REACT_APP_SERVER_HOSTNAME = "http://localhost:5000"
```

Now start the client

```
npm start
```

Your app should be up and running
