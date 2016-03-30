# Backend styles

Http Status Codes
--------------

Status codes for common escenarious:

* Social Login:
	- `424 Failed Dependency`: If the social access token is for a valid user but the user doesn't exist on the db.
	- `200`: If the user exists in the db, should return the session token.

* Force update:
    - `412`: If the user have an app version that should be updated.    