<h1 align="center">
  <img src="https://github.com/Olament/MycologyBot/blob/master/img/mushroom.png" alt="Mushroom logo" width="100">
  <br>
    <a href="https://www.reddit.com/r/mycology/">/r/Mycology</a> Bot
  <br>
</h1>

MycologyBot is a Reddit bot that dedicated to identify mushroom images from [/r/Mycology](https://www.reddit.com/r/mycology/) by using the [DeepMushroom API](https://github.com/Olament/DeepMushroom-docker). 

##  Getting Started
Setup your ```praw.ini``` configuration file inside app directory
```ini
[mycology]
client_id=CLIENT_ID
client_secret=CLIENT_SECRET
password=PASSWORD
username=USERNAME
```
Build and run the docker
```cmd
docker build && docker run
```
