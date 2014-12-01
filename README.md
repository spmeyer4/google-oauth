Requirements:
-Apache with PHP
-php.ini file configured as below

****PHP.INI****
change the line include_path line so that the path variable contains:
include_path=include_path = ".:/path/to/google-api-php-client-master/src:/path/to/google-api-php-client-master"

****installation****
-copy the google-api-client-master folder to a known location and update the php.ini file
-copy the htdocs/example folder into apache's root web folder directory
-go to http://localhost/examples/user-example.php
-everything should work
-if not, make sure line 21 on user-example.php is able to find the autoload.php file. It should be in the google-api-client-master folder

