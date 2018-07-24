### nginx templates
This repo has some templates that can be used to set up nginx web servers.

File | Description
--- | ---
`nginx.conf` | Main nginx configuration file
`generate_self_signed_certificate` | Bash script for creating the PKI for SSL
`modsecurity_module_install` | Bash script for installing the ModSecurity module by SpiderLabs
`conf.d/blog.example.com.conf` | Configuration for a wordpress blog using fastcgi
`conf.d/default.conf` | Configuration for a basic server utilizing HTTPS
`conf.d/example.com.conf` | Configuration for a very basic web server
`conf.d/notes.example.com.conf` | Configuration for a python web app using uwsgi
`conf.d/photos.example.com.conf` | Configuration for a js photo app using nginx as a reverse proxy
