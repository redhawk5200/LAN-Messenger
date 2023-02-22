# LAN-Messenger
![image](https://user-images.githubusercontent.com/59371949/220443578-0d324f76-dd0e-490f-80eb-7cf22cfeb256.png)

                Assignment 1 for the course "Computer Networks CS 3001".
Assignment document uploaded in the files above.

The folder `src` contains the files for both `server` and the `client`.
This assignment was created using the java and for the GUI, a java GUI toolkit called `Swing` was used.

<hr>
Interface for `server.java`:<br><br>
      <img src="server.png" alt="server screen">


The textfield on the top left constains the ip address and the port number in the format `ipaddress:portnumber`. The port number is extracted from the text field by the following `code`:<br><br>
![image](https://user-images.githubusercontent.com/59371949/220646205-5b33109f-0555-4c72-8765-216193dc11b5.png)

<hr>
Interface for `server.java`:<br><br>
      <img src="client.png" alt="client screen">
      
The textfield on the top right contains the port number, where the port number is extracted by the following `code`:<br><br>
      ![clietncode](https://user-images.githubusercontent.com/59371949/220655629-0e438fb1-c0bf-49e2-8c5b-b4da54550e02.png)




In both the files, the ip address is static. However, you can make it dynamic by making a push request.
