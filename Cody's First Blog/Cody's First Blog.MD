# Cody's First Blog
## Flag 1
* "http://35.227.24.107/94bfca32eb/" on the comment box try XXS script alert (didn’t work)
* Try inserting "?php phpinfo() ?" in add comment box
* Flag 1 appears

## Flag 2
* Inspect the source code of the page 
* <!--<a href="?page=admin.auth.inc">Admin login</a>-->
* http://35.227.24.107/94bfca32eb/?page=admin.auth.inc use this to access the hidden page
* Removing .auth bypasses the login 
* Flag 2 appears in the page
