Rstakeout
=========

Ruby script to execute an arbitrary command whenever a file changes.

Forked from github.com/edvardm/rstakeout, which was forked from topfunkyv

Installation
------------

    gem install sinefunc-rstakeout
    # Mac users: install `growlnotify` from the Growl DWG to get notifications

Common usage
------------

    # Execute a test everytime any file changes
    rstakeout 'rake test' **/*
    
    # Regenerate some LessCSS files whenever needed
    rstakeout 'lessc %s' **/*.less

Copyright
---------

License: MIT

