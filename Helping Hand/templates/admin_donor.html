<?php

if(isset($_POST['search'])){
    $search=$_POST['value'];
    $query="select * from donate where CONCAT(name,email,address,phone,donatingitem,quantity) LIKE '%".$search."%'";
    $search_res= filterTable($query);
}else{
    $query="select * from donate";
    $search_res=filtertable($query);
}
function filterTable($query)
{
    require 'db.php';    
    $filter_Result = mysqli_query($conn, $query);
    return $filter_Result;

}

?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        th ,tr{
       padding: 12px;
       font-size: 16px;
       border:1px solid black;
      }
    td{
      padding: 8px;
      font-size: 15px;
      border:1px solid black;
    
    }
   

    tr:hover{
      background-color: #ddd;
    }
    .profile1{
            background: yellow;
            width:150px;
            height: 10px;
            position: absolute;
            top: 20px;
            display: none;
            padding:120px;
            margin:120px 0 0 450px;
            justify-content: center;
            align-items: center;
            animation:pop 0.8s;
            
        }
       
        .popup{
        color:black;
        text-transform:uppercase;
        top:30px;
    }
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

<h1 align="center"><u>DONORS</u></h1>


    <form action="admin_donor.php" method="POST">
    <input type="text" name="value" placeholder=" Search here?"  >&nbsp;&nbsp;&nbsp;&nbsp;
            <input type="submit"  name="search" value="Search">

<table width="100%" border="2">
<thead  style="color:white;background-color: grey;">
        <th>Name</th><th>Email</th><th>Address</th><th>Phone</th><th>Food</th><th>Quantity</th><th>send</th>
</thead>
<tbody>
             <?php while($row=mysqli_fetch_array($search_res)):?>

                <tr align="center">
                <td height="28"><?php echo $name=$row['name']; ?></td>
                <td><?php echo $email=$row['email']; ?></td>
                <td><?php echo $address=$row['address']; ?></td>
                <td><?php echo $phone=$row['phone']; ?></td>
                <td><?php echo $food=$row['donatingitem']; ?></td>
                <td><?php echo $quantity=$row['quantity']; ?></td>
                <td><a href="rr.php?id=<?php echo $row['id'] ?>" id="send" name="send">SEND</a></td>

     </tr>
     <?php endwhile;?>  
       
           </tbody>
</table>
             </form>
             
 
            
</body>
</html>
