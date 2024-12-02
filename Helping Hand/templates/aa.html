
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      #send{
            text-decoration:none;
			border-radius:10px ;
			background: #D9FA81;
 	    	color: black;
 	    	padding: 8px 20px;
 	    	text-transform:uppercase;
			cursor:pointer;
			color:black;
			font-size:20px;
			height:40px;
			width:180px;
		}
      </style>
</head>
<body>
   <form method="post">
     
<input type="submit" name="ok" value="ok" id="send">
</form>
</body>
</html>

<?php
require 'db.php';
$id= $_GET['agent_id'];
$ide=$_GET['donor_id'];
$query = "select * from agent where agent_id = '$id' ";
$res=mysqli_query($conn,$query) or die('error');
if(isset($_POST['ok'])){

$query1="select * from donate where id='$ide'";
$res1=mysqli_query($conn,$query1) or die('error');
while($row=mysqli_fetch_array($res1)){
  $name=$row['name'];
      $address=$row['address'];
      $phone=$row['phone'];
      $item=$row['donatingitem'];
      $quan=$row['quantity'];
$sql="UPDATE agent SET message = '$name,$address,$phone,$item,$quan' WHERE agent_id = $id;";
$result=mysqli_query($conn,$sql);
    if($result){
       echo"<script>alert('successful')</script>";
    } 
    else{
      echo"no";
    }
}
}


?>