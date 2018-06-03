# INFO

Software    : WebKit

Platform    : Darwin

Architecture: arm64

Description : WebKit on Darwin: Crash by String.prototype.repeat() with location.href. 

Solution    : Check length of a String, before placing it in location.href. 

# WRITEUP

A bug exists in location.href, where an unusual string (an INCREDIBLY long string) exists; where a website can crash WebKit by placing a large string inside of location.href. 

# DOWNLOAD

[DOWNLOAD](https://drive.google.com/open?id=1hGfZf9FLD4yL-nsi5hxsqOOUsTDsjdsE)
