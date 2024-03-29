# Python-Flask-RESTful-API

Dive right into developing complete, solid, production-ready REST APIs using Flask and popular extensions Flask-RESTful, Flask-JWT, and Flask-SQLAlchemy.

* Create resource-based, production-ready REST APIs using Flask and popular extensions;
* Using SQLAlchemy to easily and efficiently store resources to a database; 
* Handle seamless user authentication with advanced features like token refresh
* Handle log-outs and prevent abuse in your REST APIs with JWT blacklisting
* Understand the complex intricacies of deployments and performance of REST APIs.

## Changes

* Added `UserLogout` resource in `user.py`;
    * Imported and added to `app.py`
* Modified blacklist loader so it checks the JWT's `'jti'` key instead of the `'identity'`.
* Made `BLACKLIST` initially an empty set.


__init__.py 使一个folder变成package。在Python2是必须的

同一个file中的method之间空一行，同一个file中的class之间空两行（不强制，但是是conversion）

**data是传入一个dict的简化写法