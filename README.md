This is a bash script to create a new user, vhost and PHP pool. This has been designed to work with PHP7.0-fpm with Nginx on an Ubuntu 16 box for sites using WordPress. It may work with other boxes but I haven't tested yet.

Simply upload this to your server, CD into the directory and run:

<pre>bash create_php_site.sh domain.com</pre>
Obviously changing domain.com to the domain you are using. 

Do not add www. as this is automatically put into place within the vhost!

If there is anything that I have missed then please submit a PR!
