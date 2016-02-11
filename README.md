# cakemix

"cakemix" is a really simple Linux shell script to run CakePHP commands.

Usage:

> cakemix -p [project-name]

Creates a new project.


> cakemix -s [port]

Starts the CakePHP development server (on "port" if specified).


> cakemix -x

Sets default permissions on /tmp and /logs folders.


## Install and Configure

Download cakemix.

Change the permissions to allow executing as a script:
> sudo chmod a+x cakemix

Move file with:
> sudo mv cakemix /usr/local/bin/cakemix

And you're done.

(P.S. This only works on Linux.)

