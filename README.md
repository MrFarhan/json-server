# json-server

json-server is a node module, and hence can be installed globally by typing the following at the command prompt:

npm install json-server -g
     
Configuring the Server:
At any convenient location on your computer, create a new folder named json-server, and move to this folder.
Download the db.json file provided above to this folder.
Move to this folder in your terminal window, and type the following at the command prompt to start the server

json-server --watch db.json -p 3001 -d 2000
     
This should start up a server at port number 3001 on your machine.
The data from this server can be accessed by typing the following addresses into your browser address bar:

http://localhost:3001/dishes
http://localhost:3001/promotions
http://localhost:3001/leaders
http://localhost:3001/feedback

Type these addresses into the browser address and see the JSON data being served up by the server. This data is obtained from the db.json file
The json-server also provides a static web server. Any resources that you put in a folder named public in the json-server folder above, will be served by the server at the following address:

  http://localhost:3001/
