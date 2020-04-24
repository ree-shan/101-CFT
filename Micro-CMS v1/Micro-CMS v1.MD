# Micro-CMS v1
### Flag 0
* Create a new page
* Check Url http://34.94.3.143/40cc016d42/page/12  
* Try chaging page numbers at the end (3,4, etc..) response  Page not found.
* http://34.94.3.143/40cc016d42/page/7 gives Forbidden
* Use the edit append 7 http://34.94.3.143/40cc016d42/page/edit/7
* Falg found

### Flag 1
* Try SQL injection in add post
* Create a new page. Enter '<>:;" in both input boxes. 
* The flag would be displayed as a pop up.

### Flag 2
* Add onclick event handler to button in Marktown Test.
* On clicking the JS code is executed.
* View page source to get the Flag.

### Flag 3
* Try SQLi in the URL
* Add ' to edit page URL for any post to get the flag.
