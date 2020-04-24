# Postbook
## Flag 1
* Go to sign-up page and singup with a user name and password
* next proceed to sign in page
* Note Author: user and Author: admin
* Sing out and try the username cited earlier and common passwords
* User name: user and password: password worked
* flag 1 found

## Flag 2
* Go to write a newpost 
* Inspect the page
* note <input type="hidden" name="user_id" value="2">
* Change value ="1" press create
* Flag found on the next page

## Flag 3
* Inspect the the create button in the index page
* For my own eyes only check it 
* Inspect page
* a href="index.php?page=view.php&amp;id=8"<2a>
* change  href="index.php?page=view.php&amp;id=2"></a>
* Click the link you get the flag 

## Flag 4
* Inspect the delete
* a style="color: red;" href="index.php?page=delete.php&amp;id=eccbc87e4b5ce2fe28308fd9f2a7baf3">delete</a>
* Check the id=eccbc87e4b5ce2fe28308fd9f2a7baf3 equals to MD5 hash value of 3
* Send c4ca4238a0b923820dcc509a6f75849b which is MD5 Value for 1 to delete the post
* you would find flag 4

## Flag 5
* I beleive I found one earlier for viewing someone elses post
* not sure how I ended up with that.

