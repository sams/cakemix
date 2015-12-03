# cakemix

"cakemix" is a really simple Linux shell script to shorten the command for creating a new CakePHP project.

Normally, to make a new CakePHP project, you enter:

> composer create-project --prefer-dist cakephp/app myproject

(where "myproject" is the name of your new CakePHP app.)

"cakemix" turns the process into:

> cakemix myproject

## Install and Configure

Download cakemix.

Change the permissions to allow executing as a script:
> sudo chmod a+x cakemix

Move file with:
> sudo mv cakemix /usr/local/bin/cakemix

And you're done.

(P.S. This only works on Linux.)

