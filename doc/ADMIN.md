Please note that Gemserv uses the TCP port 1965, so you can't use it for anything else.

To add a gemini capsule, create a `/etc/gemserv/config.d/example.toml` file as following:

Minimal version : 

``` toml
[[server]]
hostname = "yourdomain.org"
dir = "/opt/yunohost/gemserv"
key = "/etc/yunohost/certs/yourdomain.org/key.pem"
cert = "/etc/yunohost/certs/yourdomain.org/crt.pem"
```
Extended version :
``` toml
[[server]]
hostname = "yourdomain.org"
dir = "/opt/yunohost/gemserv"
key = "/etc/yunohost/certs/yourdomain.org/key.pem"
cert = "/etc/yunohost/certs/yourdomain.org/crt.pem"
# index is optional but defaults to index.gemini. The server will serve files
# ending in gemini or gmi.
index = "index.gmi"
# lang is optional
lang = "en"
# cgi is optional bool
cgi = true
# cgipath is optional and only checked if cgi is true. It restricts cgi to only
# this directory.
cgipath = "/path/to/cgi-bin/"
# scgi is optional
scgi = { "/scgi" = "localhost:4000" }
# cgienv is optional
cgienv = { "GIT_PROJECT_ROOT" = "/srv/git" }
# usrdir is optional. it'll look in each user's ~/public_gemini
usrdir = true
# proxy is optional
# path is what comes after the hostname e.g. example.com/path
proxy = { path = "localhost:1966" }
# proxy_all is optional
# It will send all requests to the specified server. It also supports streamming.
proxy_all = "localhost:1967"
# redirect is optional
redirect = { "/redirect" = "/", "/newdomain" = "gemini://example.net" }
```

And then create the folder `/opt/yunohost/gemserv` and put your files in that folder.