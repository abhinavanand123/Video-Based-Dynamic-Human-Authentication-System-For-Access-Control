Running the project 

1)To run the project execute the firstpage.py file .
2)you will be getting the user interface section after execution .
3)Enter the proper credentials to login and wait for some time to pop up the main page of program.(username- admin, pass- admin)
4)You will be logged to the main page of the program. There you can have multiple options to interact with the system .
5) You can register by giving the name of the person and by clicking on the  take image button.


Note:- make sure while registration all the orientation of the face are captured I.e. 360⁰ degree rotation of the face. 

6) After that you have to train the system by clicking on the train image button. ( a message will appear in the dialog box "images trained" conforming the training process)
7) Finally you can track or recognize by clicking on track image button. 
8)The user log will be displayed in the dialog box of the identified person. 

We have also used database as SQLite for viewing of database you should install DB browser for SQLite:-
	->Open DB browser for SQLite and select option open database
	->Now select database.db file 
	->Later select option browse data under which we will have dropdown consisting images, userinfo, userlog
	->we have used BLOB(Binary Large Object) for images to view.
