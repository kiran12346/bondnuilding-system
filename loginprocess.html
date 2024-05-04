<?php
$hostname='localhost';
$username='root';
$password='';
$databasename='bbs';

$mysqli=mysqli_connect($hostname,$username,$password,$databasename);
session_start();

if(isset($_POST['email']) && isset($_POST['password'])){
$email=($_POST['email']);
$password=($_POST['password']);

if(empty($email)){
header("Location:login.php?error=User email is required");
exit();
}
else if(empty($password)){
header("Location:login.php?error=User password is required");
exit();
}
else{
$sql="SELECT * FROM users WHERE email='$email' AND password='$password' ";
$result=mysqli_query($mysqli,$sql);
if(mysqli_num_rows($result)){
$row=mysqli_fetch_assoc($result);
if($row['email']===$email && $row['password']===$password){
$_SESSION['email']=$row['email'];
$_SESSION['id']=$row['id'];
header("Location:homepage.php");
exit();
}

}
else{
header("Location:login.php?error=Please fill both of user email and password");
exit();
}
}
}


?>