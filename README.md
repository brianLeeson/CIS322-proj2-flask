# proj2-flask

Instructions for use:
## In your workspace

Make sure pyvenv is installed.

'bash ./configure' should create appropriate configuration files on
most Unix files.   If you are using Windows, some additional editing
of configuration files may be necessary.  You might have to edit the
Makefile to find the right version of 
pyvenv.

If you can run flask applications in your development environment, the
application would might be run by
`   python3 syllabus.py`
and then reached with url
`   http://localhost:5000`

`make run` will launch the debugging server built into flask.  It
provides the best support for tracking down bugs in your server, but
it's not suitable for use by many users or over a long period.  `make
service` starts a Green Unicorn (gunicorn) server; you may note the extra
lime sparkles all around you.  Green Unicorn can be used for servers
that run over a longer period (e.g., if you want to leave a web
service running on your Pi).   
