There are:
	1. Website source code
	2. Docker file for nginx image base on debian
	3. Docker file for gunicorn, django and python3
	4. Docker file for database

For depoltment, you should build image of nginx as static content server and reverse porxy, gunicorn iamge as app server, database image as data server.

Then mount the source code to web seriver. 
