# cakeme

"cakeme" is a really simple Linux shell script to shorten the command for creating a new CakePHP project.

Normally, to make a new CakePHP project, you enter:

> composer create-project --prefer-dist cakephp/app myproject

(where "myproject" is the name of your new CakePHP app.)

"cakeme" turns the process into:

> cakeme myproject

## Install and Configure

1. Download cakeme.
2. Change the permissions to allow executing as a script:
> sudo chmod a+x cakeme
3. Move file with:
> sudo mv cakeme /usr/local/bin/cakeme

And you're done.

