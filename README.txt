This application receives a subscription order for a client who wants to attend different gym classes.
That order is automatically registrated into a database.
The client-server communication is realised using sockets.
To run this application, the user has to create a database named "Abonamente", for this specifications:
String url="jdbc:derby://localhost:1527/Abonamente";
String username="Carina";
String password  = "stud";
This database has to contain one table: “INREGITRARE_ABONAMENTE”.
SQL script used to create the table with the right columns:
CREATE TABLE INREGISTRARE_ABONAMENTE
(NUME VARCHAR(50),
SEX VARCHAR(2),
ZI_INCEPERE VARCHAR(2),
LUNA_INCEPERE VARCHAR(2),
AN_INCEPERE VARCHAR(4), 
ZI_EXPIRARE VARCHAR(2), 
LUNA_EXPIRARE VARCHAR(2), 
AN_EXPIRARE VARCHAR(4), 
TIP_ABONAMENT VARCHAR(300) );

