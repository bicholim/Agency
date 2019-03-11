<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
background-image: url("7.jpg");
}
/* Style the side navigation */
.sidenav {
  height: 100%;
  width: 200px;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: #111;
  overflow-x: hidden;
}


/* Side navigation links */
.sidenav a {
  color: white;
  padding: 16px;
   text-decoration: none;
  display: block;

}

/* Change color on hover */
.sidenav a:hover {
  background-color: #ddd;
  color: black;
}

/* Style the content */
.content {
  margin-left: 200px;
  padding-left: 20px;
}
</style>
</head>
<body>

<div class="sidenav">
  <a href="#Register">REGISTER</a>
  <a href="#login">LOG IN</a>
  <a href="#search">SEARCH</a>
</div>

<div class="content">
  
  <table align="center" border="2" >
                <tr>
                    <td colspan="2">
                        <center><font color="white" size="7" style="font-family:ALGERIAN">Register</font></center>
                    </td>
                </tr>
                <tr>
                    <td><font color="white" size="5"><b>User No</b></font></td><td><input type="text" name="user_no"></td>
                </tr>
                 <tr>
                    <td><font color="white" size="5"><b>User Name</b></font></td><td><input type="text" name="user_name"></td>
                </tr>
                 <tr>
                    <td><font color="white" size="5"><b>Address</b></font></td><td><input type="text" name="address"></td>
                </tr>
                <tr>
                    <td><font color="white" size="5"><b>Email</b></font></td><td><input type="text" name="email"></td>
                </tr>
                <tr>
                    <td><font color="white" size="5"><b>Phone No</b></font></td><td><input type="number" name="phone_no"></td>
                </tr>
                 <tr>
                    <td><font color="white" size="5"><b>Password</b></font></td><td><input type="password" name="upass"></td>
                </tr>
                <tr>
                    <td><font color="white" size="5"><b>confirm Password</b></font></td><td><input type="password" name="cpass"></td>
                </tr>
                <tr>
                    <td></td>
                    <td><input type="Submit" name="register" value="Register"></td>
                </tr>
            </table>
       
</div>

</body>
</html>
