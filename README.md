# Secrets-Auth-Security
A webiste named "Secret" where user can login and submit/post/view secret(text).
The login authentication is changed from level1 to level6 to make hacking the website harder with new methods as follows:

Different levels of security and authentication scenario:
Level1- 	user authentication via remote MongoDb
Level2- 	Database encryption/ env key
Level3- 	Simple password hashing (md5)
Level4-   Salting + Hashing password
Level5-	  Session + cookies authentication/ passport pkg
Level6-	  Google sign-in OAuth 2.0/ Facebook sign-in

Session/cookies remember login session.
Logout button ends it.