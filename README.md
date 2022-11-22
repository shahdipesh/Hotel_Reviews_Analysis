# This file contains instruction on how to run the program on a University Linux Lab Computer.

> Note: You must  be inside the src directory before following any instructions explained below.



## To run the project

- Open Terminal
- Change the directory to the project's src folder.
- Type `make run` in the terminal.
- Press enter.



# FAQs

1) How do I insert data in the tables?
> You can find 'insertQueries' object in the Main class. Please use the appropriate method of the object to insert data in the related tables.
> For eg: insertQueries.insertCoordinates(util.getConnectionUrl()) inserts data into the Coordinates table.

2) The GUI seems to be crammed up when the project runs.

> Please make the GUI full screen if they do not layout properly.


3) I am getting "could not find config file" error.

> We setup the project structure in a way so that this error does not occur, but If you are still seeing the error  please go to the Util.java file and set the 'filename'  variable to the path of the 'auth.cfg' file.



4) "make run" gives me 'driver not found exception.'

>In this case you can run the make file commands manually.
>1) Type `javac Main.java`
>2) Press enter.
>3) Type `java -cp .:[path_to the_MSSQL driver jar] Main`
>
> Note: If you are using windows type `java -cp .;[path_to the_MSSQL driver jar] Main`
>
>4) Press enter. The project should be running now.



The working demo of the project can be found [here](https://streamable.com/ghmbdx).
