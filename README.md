# Script to create a new PHP pool
This is a bash script to create a new user, vhost and PHP pool. This has been designed to work with PHP7.0-fpm with Nginx on an Ubuntu 16 box for sites using WordPress. It can be made to work with other versions of PHP if you know the PHP path.
It may work with other boxes but I haven't tested yet.

# Prerequisites

* Nginx
* PHP7.0-FPM

# Instructions

Simply upload this to your server, CD into the directory and run:

<pre>bash create_php_site.sh domain.com</pre>
Obviously changing domain.com to the domain you are using. 

Do not add www. as this is automatically put into place within the vhost!

# Want to improve this script?

If there is anything that I have missed then please submit a PR!

Of course, I accept no reponsibility if this messes up your server/sites etc. Use this at your own risk or not at all if you don't know what you are doing! 
