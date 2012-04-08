FPC_WIN
-------
Compile pascal source with win32 compiler using wine under Mac OS X.
Under Linux didn't test. Notify me if you did, please.

###Preinstallation:

* Install wine ([mac os x manual](http://www.davidbaumgold.com/tutorials/wine-mac))
* Install freepascal win32 compiler ([official web site](http://freepascal.org))

###Installation:

* Copy `fpc_win` to `/usr/local/bin`
* Set execute permissions on `/usr/local/bin/fpc_win`

###Usage:

* `fpc_win input_file.pas [-o<output_file>]`