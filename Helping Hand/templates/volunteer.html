<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
<title>Document</title>
<style>
body{
margin:0;
padding:0;
background:url(images/volunteer.jpg);
background-size:cover;
background-attachment: fixed;
background-position: center;
}
#title{
text-align:center;
text-shadow: 2px 2px #FF0000;
}
.apply{
width: 500px;
height: 750px;
background: rgba(0, 0, 0, 0.3);
color: white;
top: 70%;
left: 50%;
position: absolute;
transform: translate(-50%,-50%);
box-sizing: border-box;
padding:  30px;
border-radius: 20px;
}
.field{
height: 20px;
font-size: 15px;
margin:20px 0 20px 0;
width: 250px;
border:2px solid #ffffb3;  
}
.imagprev{
height: 180px;
width: 180px;
border-radius: 70%;
}
.rad{
color:black;
font-weight:bold;
padding:10px;
font-size:15px;
text-transform:uppercase;
}
.btn-1{
display: inline-block;
background: black;
color: #fff;
padding: 8px 30px;
margin: 2px 0;
border-radius: 20px;
}
.profile{
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
@keyframes pop{
0% {
transform: scale(0) ;
}
60% {
transform: scale(1) ;
}
100% {
transform: scale(1);
}
}        
</style>
</head>
<body>
<h1 id="title"><u>VOLUNTEER<u></h1>
<div class="apply">
<div id="prev">
<form action="" method="POST" enctype="multipart/form-data">
<img src="images/person.jpg" alt="img" class="imagprev"   width="200px">
<span class="image"></span><br>
<input type="file" id="inpfile" name="image"  accept="image/*">
</div>
<div class="login">  
<b>Name <br><input type="text" name="name" class="field" required><br>
<b>Age <br><input type="number" name="age" class="field" min="18" required><br>
<b>Gender<br><input type="radio" name="req" id="rad1" required><label for="rad1" class="rad">male</label>
<input type="radio" name="req" id="rad2" required><label for="rad2" class="rad">female</label><br>
<b>Address <br><input type="text" name="add" class="field" required><br>
<b>Contactno<br> <input type="text" name="phone" class="field" required><br>
<b>Password<br><input type="password" name="password" class="field" required><br>
<input type="submit" name="submit" class="btn-1" value="NEXT">
</form>
</div>
</div>
<script>
const inpfile=document.getElementById("inpfile");
const prev=document.getElementById("prev");
const imgprev=prev.querySelector(".imagprev");
const imgprevdef=prev.querySelector(".image");
inpfile.addEventListener("change",function(){
const file=this.files[0]
if(file){
const reader=new FileReader();
imgprevdef.style.display="none";
imgprev.style.diplay="none";
reader.addEventListener("load",function(){
imgprev.setAttribute("src",this.result)
});
reader.readAsDataURL(file);
}
})
</script>
</body>
</html>
<?php
require 'db.php';
if(isset($_POST['submit'])){
$file=$_FILES["image"]["name"];
$username=$_POST['name'];
$age=$_POST['age'];
$phone=$_POST['phone'];
$address=$_POST['add'];
$password=$_POST['password'];
$sql="INSERT INTO volunteer(image,name,age,phone,address,password)VALUES('$file','$username','$age','$phone','$address','$password')";
$result=mysqli_query($conn,$sql);
if($result){
echo"<script>alert('Your account request is now pending for approval. Please wait for confirmation. Thank you.')</script>";
}     
}
?>
