# Installation

```
git clone https://github.com/paulfurley/twitter-realtime
mkdir venv
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

# Authenticating Twitter

Copy the file ``run.sh.example`` to ``run.sh``. In it you will see default
values for authentication credentials you'll need from Twitter. To create
these, you need to register a new Twitter app by doing the following:

- Log in to https://twitter.com with the account of your choice
- Visit [https://dev.twitter.com/apps/new](https://dev.twitter.com/apps/new)
- Create a new App
- Create an Access Token.
- Copy the value of the four fields into ``run.sh``
