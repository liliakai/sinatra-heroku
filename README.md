# Getting started with [Heroku](http://heroku.com).

* Create an acount at [Heroku](http://heroku.com/signup).
* Install the gem `sudo gem install heroku`.
* If you do not have an SSH key you'll need to [generate one](http://heroku.com/docs/index.html#_setting_up_ssh_public_keys) and [tell Heroku about it](http://heroku.com/docs/index.html#_manage_keys_on_heroku)

# Deploying

```
git clone https://github.com/liliakai/sinatra-heroku.git
cd sinatra-heroku.git
heroku create
git push heroku master
heroku ps:scale web=1
```
