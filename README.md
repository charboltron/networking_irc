# Chat Box 

![Image of Chat Box Demo](/img/chat_irc_demo.jpg)

### About

Created in May/June 2019 with Evan DePosit. An experiment in internetworking protocols, the 'Chat Box' is an asynchronous client/server chat application which supports multiple clients, chat room creation, deletion, joining, switching, leaving, broadcasting, as well as other functions relating to connections and disconnections. See the RFC.pdf (Request For Comments) for much more detailed information on the protocol and how the application works. All chimes and sounds within the application created by Charles Bolton in Python. 

### Running 

To run the application, first navigate to the /src dirctory. Begin by starting the server module:

python3 server.py

Then, make a number of duplicate terminal windows within the same /src folder. In each of the other windows start a single client: 

python3 client.py 

The clients will then be able to communicate with each other via the shared server, create and join rooms, etc. 

### Python Modules 

* playsound from playsound (for sound effects)
* asyncio (for asynchronous I/O)
* ast (abstract syntax trees)
* sys 

