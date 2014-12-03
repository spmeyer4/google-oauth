Requirements:<br>
-Apache with PHP<br>
-php.ini file configured as below<br>
<br>
****PHP.INI****<br>
change the line include_path line so that the path variable contains:<br>
include_path=include_path = ".:/path/to/google-api-php-client-master/src:/path/to/google-api-php-client-master"<br>
<br>
****installation****<br>
-copy the google-api-client-master folder to a known location and update the php.ini file<br>
-copy the htdocs/example folder into apache's root web folder directory<br>
-go to http://localhost/examples/user-example.php<br>
-everything should work<br>
-if not, make sure line 21 on user-example.php is able to find the autoload.php file. It should be in the google-api-client-master folder<br>

To run the example go to<br>
http://localhost/examples/user-example.php<br>
