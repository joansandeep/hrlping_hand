<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background:url(images/front.jpg);
            background-size:cover;
            background-attachment: fixed;
            background-position: center;
        }
        
        .btn-1{
 	    display: inline-block;
 	    background: #ff523b;
 	    color: #fff;
 	    padding: 8px 30px;
 	    border-radius: 15px;
 }
 .btn-1:hover{
 	background: #563434;

 }
 
 .apply{
    background: #fff;
	width: 300px;
	height: 200px;
	position: relative;
	text-align: center;
	padding: 20px 0;
	margin: auto;
	box-shadow: 0 0 20px 0px rgba(0,0,0,0.1); 
	overflow: hidden;
}
    .text-center{
	    text-align: center;
    }
    .text-center1{
	    text-align: center;
        font-size:20px;
        color:red;
    }
.login{
	width: 30%;
	border: 2px solid grey;
	margin: 10% auto;
	padding: 25px 0;
	background: radial-gradient(#fff,#ffd6d6);
}
 </style>
</head>
<body>
    <div class="login">
     <h2 class="text-center"><b>LOGIN<br>
    <?php
    session_start();
    if (isset($_SESSION['login'])) {
        echo $_SESSION['login'];
        unset($_SESSION['login']);
    }
    if (isset($_SESSION['no-login-message'])) {
        echo $_SESSION['no-login-message'];
        unset($_SESSION['no-login-message']);
    }
    ?>
     <br>
<div class="apply">
    <form action="donor.php" class="text-center" method="POST">
        
       <b>Username <br> <input type="text" name="name" required><br><br>
       <b>Password<br><input type="password" name="pass" required><br><br>
       <input type="submit" name="submit" class="btn-1">
       <a href="register.php"><input type="button"  value="signup" class="btn-1"></a>

</div>
</div>
</form>
</body>
</html>

<?php
require 'db.php';
if(isset($_POST['submit'])){
$name=$_POST['name'];
$Password=$_POST['pass']; 
$sql="select * from donor where username='$name' AND password='$Password'";
$result=mysqli_query($conn,$sql) or die('error');
if(mysqli_num_rows($result)==1){
    header("location:donor1.php");
}
else{
    $_SESSION['login']="<div class='text-center1'>Try Again Username And Password Is Incorrect!<br></div>";  
    header('location:donor.php');
}
}
?> 