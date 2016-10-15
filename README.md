--------------------------------------------------------------
Disclaimer
--------------------------------------------------------------
I did not coded this emulator.

Read the following for more information.

Last update: 

--------------------------------------------------------------
Building
--------------------------------------------------------------
Go to root directory and run:
```
$ apt-get install build-essential
$ apt-get install zlib1g-dev
$ make
$ cc -o setupwizard setupwizard.c
$ cc -o adduser adduser.c
$ ./setupwizard
$ ./alpha-start start
$ ./alpha-start stop
```

To add users:
```
$ ./adduser
```
--------------------------------------------------------------
Alpha Taulin Build Readme
--------------------------------------------------------------

Firstly I would like to thank you for downloading this server
software.
It is designed for the Ragnarok Online Alpha client that can 
be obtained from:
	http://www.castledragmire.com/ragnarok/downloads.php

Please be sure to read the other Readme.txt file first before
operating this software.

I have placed an itemnametable.txt file in the db directory,
this file contains item names matching those in the server 
database. This file should be offered to players to place in a
data directory in their RO client directory.

--------------------------------------------------------------
Disclaimer
--------------------------------------------------------------

This software is not my original work, and only a small amount
of it has actually be added by me originally. This amount will
grow as I try to bring the server software to completion.

I will not claim any credit for the work done AppleGirl and
others with her to get the software to the point it was at for
the revision 159 release, what I am trying to achieve is to
now bring the server software to a point where it is fully
playable and, hopefully, as close to the original alpha server
as possible.


--------------------------------------------------------------
Compiling
--------------------------------------------------------------

I have discovered that some Linux distributions do not like to
compile the grfio.c file, I do not know why but mine does just
fine.
Therefore I have included the grfio.o file in the source
packages so that it wont need to be compiled, if you do a make
clean it will be deleted as well though, so use make clean at
your own risk.


--------------------------------------------------------------
Releases
--------------------------------------------------------------

My releases of this software will be as follows:
* With every new version I will release a package with all 
files, except the server executables, with all the changed
files back to the revision 159 release. This will be denoted
as the "trail" release.
* A second package will contain all but the original files
that are in the "trail" release.
* All releases after the v1.1.0 release will also have a
package that contains only the files changed since the last
release.

The versioning is as follows:
* The first number denotes a major version. Odd numbers are
testing/beta releases while even will be stable.
* The second number counts the number of major releases.
* The third number is for a minor release.

Releasing changes to the database would count as a minor
release, for example v1.1.1
Then releasing a code change would be a major release and
would be released as v1.2.0

I am hoping that at v1.2.0 or v1.3.0 I will have the majority
of bugs fixed server side, with the v2.X.0 release coming
once most of the unnecessary server code has been removed.

--------------------------------------------------------------
--------------------------------------------------------------
Dev Taulin Nakima
--------------------------------------------------------------