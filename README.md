HelloWorld
===========

This repository will allow you to build your first professional Java
project, including unit and acceptance tests, using Gradle as the
build tool.

After you have cloned the repository, you should be able to navigate
to the directory containing the gradle.build file. There, you can
build the project by running the command

`gradle build`

You can then run the acceptance tests. First, you will need to modify
the "runacceptance.bat" (Windows) or "acceptance/runacceptance.sh" 
(Linux/OSX) file. You will need to edit it so that the path to the 
Robot Framework jar files matches where they're located on your machine.
After that, you can run either

`runacceptance.bat`  (on Windows) 

or go into the "acceptance" directory and run 

`./runacceptance.sh` (on Linux/OSX) 

Note: You will probably need to make the "runacceptance.sh" script 
executable by saying 

`chmod a+x runacceptance.sh`

before running it the first time.

Parker Hardin
