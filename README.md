# chat-applicaton - A React JS Chat Application
![image](https://github.com/rushi-12320/chat-applicaton/assets/55217679/7be158c6-42b7-4921-aade-63afd4e455ee)
⚠️ Before you start
Make sure Git and NodeJS is installed
Yarn is faster than Npm. So use Yarn.
Create .env file in both public and server folder.
server/.env
PORT=5000
MONGO_URL=xxxxxxxxxxxxxx
MESSAGE_ALGORITHM="aes-256-ctr"

MESSAGE_SECRET_KEY="xxxxxxxxxxxxxxxxxx"
CLIENT_URL="http://localhost:3000"
public/.env
REACT_APP_CHAT_APP_USER="xxxxxxxxxxxxxxxxxxxxxx"
REACT_APP_MULTIAVATAR_API_KEY="xxxxxxxxxxxxxxxxx"
REACT_APP_SERVER_URI="http://localhost:5000"
In most cases localhost is set to port 3000 and 5000 in client and server side respectively. But if there is any issue in connection you can change these values.
Make sure Mango Db and Mongo Db Compass is installed on your local system. If it's not, you can follow this guide.
Now copy your mongo db url as shown below:
![image](https://github.com/rushi-12320/chat-applicaton/assets/55217679/a1d35d45-0385-429d-8dca-3eb3491a1a3b)

NOTE: Both MESSAGE_SECRET_KEY and REACT_APP_CHAT_APP_USER are just different random strings. You can generate them using a password generator. Make sure their length is of decent amount like 16 or 32.

To setup Avatar, Create an account in Multiavatar API
On app dashboard, copy your key as shown below and paste them in .env file in public folder. 
![image](https://github.com/rushi-12320/chat-applicaton/assets/55217679/4ad59038-dafc-4338-88cd-3a6bb309b142)

NOTE: You can use Multiavatar API without account but API requests are limited to 10/min that's why, I didn't recommend doing it in that way. Make sure you don't share them publicly



Snappy is a Realtime React JS Chat Application using Socket.io and MongoDb
Type and Run yarn install

Run yarn start to start back end server

Now, check console. If it says, Server is running! and Database connection successfull. Then it means that everything is working fine!
![image](https://github.com/rushi-12320/chat-applicaton/assets/55217679/d548883d-82ac-442b-b488-f5eb9efde6b0)
Now, nodejs server is configured and started. Next, we need to setup Client side server.

Open a new Terminal and run yarn install. Make sure you are in public folder.

Once packages are installed, type and run yarn start

Now client side server will be started and you can start using this app 👍

![image](https://github.com/rushi-12320/chat-applicaton/assets/55217679/6b3bdb3b-6e5f-4efa-a125-01896ec7ca33)

