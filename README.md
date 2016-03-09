# urlshortner
URL Shortner Sample Application
==============

How to use it
--------------

*Get a short URL*
	Send a POST request http://localhost:8080/{LoNG_URL_HERE}
	Example POST request to this URL  http://localhost:8080/http://hellasdirect.gr
	In Response you will get a short URL, Obviously you need to change the host information in the code when running on particular domain for example hd.gr
	Short URl will consist of ID which will help convert Short URL to Long URL

*How the short URL will be resolve to the long URl*
	Whenever a user send a GET request to this application with the the short URL ID
	For example http://localhost:8080//3d9ae0f3 will resolve to http://hellasdirect.gr