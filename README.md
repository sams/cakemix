# cakemix

"cakemix" is a really simple Linux shell script to run CakePHP commands.


Usage:

> cakemix

Issuing the "CakeMix" command with no parameters will attempt to start the
CakePHP development server on the default port (9876).


> cakemix nnnn

Starts the CakePHP development server on port 'nnnn'.


> cakemix xxxx

Create a new Cake project skeleton named 'xxxx'.


> cakemix -p

Sets the default permissions on the '/tmp' and '/logs' directories.


> cakemix -h

Diplays the help text.


## Install and Configure

Download cakemix.

Change the permissions to allow executing as a script:
> sudo chmod a+x cakemix

Move file with:
> sudo mv cakemix /usr/local/bin/cakemix

And you're done.

(P.S. This only works on Linux.)
