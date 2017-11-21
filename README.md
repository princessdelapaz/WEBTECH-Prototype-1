# WEBTECH-Prototype-1
Submitted by Group SADTECH
Patrisha Cabigas
Rafael Pangan
Princess Dela Paz
Hj Bumanlag 

-------------
Instruction
***Note: This is made through php, Xampp server is required to run the system

1.Set up Database through MYSQL, open model and forward engineer it
2. Check file "mysql_connect.php" and change the default "p@ssword" to your MYSQL Password
  Code: 
  
      <?php
      $dbc=mysqli_connect('localhost','root','[INSERT MY SQL PASSWORD HERE]');

      MYSQLI_SELECT_DB($dbc, "jeep-p-s");

      if (!$dbc) {
          die('Could not connect: '.mysql_error());
       }
      ?>
      
3. after, database set up, copy file folder, and paste it to your main drive > xampp > htdocs
4. run "index.php" to your localhost. 
              a. go to any internet browser (maker sure you started your xampp server) 
              b. type in the address bar : localhost/Jeep-P-S/WEBTECH/WEBTECH-UI/index.php



** Check the documentaion inside for further instructions
