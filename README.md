Rstakeout
=========

Ruby script to execute an arbitrary command whenever a file changes.

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

Authors
-------

This project has been forked from github.com/edvardm/rstakeout, which was forked from topfunky. The original author is Mike Clark.

Sinefunc has forked this project to:

 - Make this project a gem (easily installable with gem install)
 - New icons
 - Small feature additions

Copyright
---------

Icons from http://gakuseisean.deviantart.com/art/OSE-PNGs-53752770

License: MIT

