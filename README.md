# pilot-project

A place where we can test out technologies before using in our actual project.

## Dependency

+ python3

```
sudo apt-get install python3
```

+ venv
```
python3 -m pip install virtualenv
```
optionally you can use the `--user` flag with pip, see [docs](https://virtualenv.pypa.io/en/latest/installation/)

Now to setup the virtualenv run:
```
virtualenv venv
```

+ flask

We would like to install flask within the virtualenv instead of a system wide install.

Go to the root folder for the project and activate the virtual enviorment with the following:
```
source venv/bin/activate
```
in your teminal you should see `(venv)` before the prompt. Now you can install flask with
```
python3 -m pip install Flask
```

You are now set-up to use the project.

## Running
Make sure that you've activated the virtualenv, you should see `(venv)` in your terminal prompt.

Some thing like:
```
(venv) user@laptop: ~/hcp-pilot-project$
```

Now run the following, it should serve the page to localhost on some free port.
```
python3 app.py
```
