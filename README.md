# API chat project and text sentiment analysis
 
In this project we want to communicate an API with a chat service for team members of a company. With this project we want to create users, chat rooms, add text messages, etc.
 
In addition, another task for the project is to analyze the sentiment of the chat messages in order to make sure that the workers of the company are happy.
 
To do so, I worked with the following tools to complete this challenge:
- `FLASK` - An API creation tool for python.
- `NLTK` - A python library to conduct Natural Language Processing.
 
In addition I used `MySQL` to handle the chat database, and I communicated it with the python code using `sqlalchemy` and `pymysql`.
 
## API functions
 

`/chat/create/<name>`

`/user/create/<username>`

`/chat/adduser/`

`/chat/addmessage/`

`/chat/list/<chat_id>`

`/user/list/<user_id>`

`/chat/sentiment/<chat_id>`

`/user/sentiment/<user_id>`


 
## MySQL Database Creation
 
In the following figure I show a very simplistic database schema to handle the chat app.
 
![CHAT SHEMA](images/sql_schema.png)
 
I created a series of users and chat names to create the table and I assigned a random set of users for each chat. Lastly, I listed a series of random mensajes, so I made each user in each chat post some of them in a random order.
 
## Text sentiment analysis
 
Words
 
## Final thoughts
 
words
