# spis16-webapps-oauth-and-pymongo-v1


On Heroku at: http://spis16-oauth-and-pymongo.herokuapp.com/

Requires:

```
pip install --user Flask-OAuthlib
pip install --user PyGithub
pip install --user pymongo
```

The `--user` is only for ACMS accounts: leave off the `--user` if running on your own PC.

look at http://flask-pymongo.readthedocs.io/en/latest/

```
 PyMongo.save_file(filename, fileobj, base='fs', content_type=None)

    Save the file-like object to GridFS using the given filename. Returns None.
```
