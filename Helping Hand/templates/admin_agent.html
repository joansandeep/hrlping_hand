<?php

if(isset($_POST['search'])){
    $search=$_POST['value'];
    $query="select * from agent where CONCAT(agent_id,name,address,phone) LIKE '%".$search."%'";
    $search_res= filterTable($query);
}else{
    $query="select * from agent";
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
        </style>
</head>
<body>
<h1 align="center"><u>AGENT</u></h1>
    <form action="admin_agent.php" method="POST">
    <input type="text" name="value" placeholder=" Search here?"  >&nbsp;&nbsp;&nbsp;&nbsp;
            <input type="submit"  name="search" value="Search">

<table width="100%" border="2">
<thead  style="color:white;background-color: grey;">
        <th>NAME</th><th>Address</th><th>Phone</th>
</thead>
<tbody>
             <?php while($row=mysqli_fetch_array($search_res)):?>

                <tr align="center">
                <td height="28"><?php echo $name=$row['name']; ?></td>
                <td><?php echo $address=$row['address']; ?></td>
                <td><?php echo $phone=$row['phone']; ?></td>
              
     </tr>
     <?php endwhile;?>  
       
           </tbody>
</table>
             </form>
</body>
</html>

