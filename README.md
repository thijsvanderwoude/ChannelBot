# 7/6/2018 DMY, fixing it because it gave me issues with PHP7+ so it doesn't suck a fat cock

# ChannelBot
ChannelBot is a simple bot that posts the latest videos from a certain set of channels to a certain set of subreddits.
What's special about it is that **most of it's configuration goes through reddit's PM system.**
## Setup
1. Install PHP, on debian/ubuntu:  ```sudo apt-get install php5-cli curl libcurl3 libcurl3-dev php5-curl```  
On other distributions/platforms: google is your friend.  
2. Install composer:  ```curl -sS https://getcomposer.org/installer | php```  
3. ```composer install```
4. Copy config.default.yaml to config.yaml
5. Enter your settings.
A API key to the Youtube Data API can be retrieved at [Google's Developer Console](http://console.developers.google.com)
Choose 'server key' and enter your current IP address.
Make sure to enable 'Youtube Data API'
6. Done. Start the bot with:
```
./bot
```
[And read the docs on how to configure it's channels here](http://www.reddit.com/r/ChannelBot/wiki/api)


  
![Screenshot](http://i.imgur.com/iOcVf7E.png)
  
