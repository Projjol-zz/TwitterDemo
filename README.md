TwitterDemo
===========

To try it out, install express, passport and passport-twitter.

Dependency Installation
------------------------
For Express:

`npm install -g express`

For Passport:

`npm install --save passport passport-twitter`

Additionally, the way Twitter apps work, a domain name is required, so under `/etc/hosts`, add :

`local.example.com 127.0.0.1`.

Also, the config.json file has been ignored on purpose, to ensure that the app works well, please do the following:

* Create a config.json file in the root directory
* The file in turn should in turn have the following:

>    { "consumerKey": "...",
       "consumerSecret": "..."
     }
* And that's it, with these in place, you should be up and running.
