-- Bootstrap Documentation

#1 Go to startbootsrap Website after you download

#2 you can copy the folder like assets/css/js to your folder so u can use it wheter some framework wheter u are in offline

#3 then in your IDE to arrange properly create a  admin folder  then paste  this assets/css/js and add a folder includes then create something like this 
footer.php / header.php / navbar.php / sidebar.php

#4 Then u can go back to the template u download u can copy the header which is more on link 
ex:
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
        <meta name="description" content="" />
        <meta name="author" content="" />
        <title>Dashboard - Antiquina</title>
        <link href="https://cdn.jsdelivr.net/npm/simple-datatables@7.1.2/dist/style.min.css" rel="stylesheet" />
        <link href="css/styles.css" rel="stylesheet" />
        <script src="https://use.fontawesome.com/releases/v6.3.0/js/all.js" crossorigin="anonymous"></script>
    </head>


#5 then in your index.php you can call other file to combine using this 
<?php 
include('includes/header.php');
include('includes/navbar-top.php');
?>

other wise 

in your header.php you can combine them both the navbar-top.php so you can call only one in index.php 

#6 

 
