# Action Cable Chat

This is a simple chat program created with Ruby on Rails using WebSockets via Action Cable.

The deployed version of the app can be found at [https://peaceful-garden-98889.herokuapp.com](https://peaceful-garden-98889.herokuapp.com).

This was created following the tutorial [*Learn Enough Action Cable to Be Dangerous*](https://www.learnenough.com/action-cable-tutorial) by Michael Hartl.

To get started, fork the repo and clone it to your local machine, then run the following commands:

To run Action Cable Chat locally...

1. Clone the repo: 
```
$ git clone https://github.com/jsheridanwells/action_cable_chat_app.git
```

2. Open the directory:
```
$ cd action_cable_chat
```

3. Install the gems and set up the database:
```
$ bundle install
$ rails db:migrate
$ rails db:seed
```

4. Run the server:
```
$ rails server
```

5. Navigate to the local server in your browser:
```
http://localhost:3000
```

## Using Action Cable Chat

There are two sample users already available from the data seed. You can login in one browser as `username: alice, password: wonderland`, then login in another browser as `username: bob, password: asdfasdf`.  When one "user" sends a message to another, it will appear in the other browser via a websocket connection. 
