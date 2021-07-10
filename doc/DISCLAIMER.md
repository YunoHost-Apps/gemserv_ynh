* Other infos that people should be aware of, such as:
    * Redirect TCP/1965 port to the server
    * To add a gemini capsule, create a /etc/gemserv/config.d/example.toml 

```
[[server]]
hostname = "youdomain.org"
dir = "/path/to/serv/"
key = "/etc/yunohost/certs/youdomain.org/key.pem"
cert = "/etc/yunohost/certs/youdomain.org/crt.pem"
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
# usrdir is optional. it'll look in /home/usr/public_gemini
usrdir = true
# proxy is optional
# path is what comes after the hostname e.g. example.com/path
proxy = { path = "localhost:1966" }
# proxy_all is optional
# It will send all requests to the specified server. It also supports streamming.
proxy_all = localhost:1967
# redirect is optional
redirect = { "/redirect" = "/", "/newdomain" = "gemini://example.net" }
```