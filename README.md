SCAUZFAPI
=========
An API that can get some message from scau's zhengfang system.

The class has been packaged.User can use the public function--init with it's id,password and operation to get information you need.

In getLessonTable, people can get the class table which has been dealed with.
If user haven't login before,system will get table from the scau system and store it into database.Otherwise,system will get table from database.
