# dealers-and-drivers
#login code
<!DOCTYPE html>   
<html>   
<head>  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<title> Login Page </title>  
<style>   
Body {  
  font-family: Calibri, Helvetica, sans-serif;   
}  
button {   
       background-color: #c1e9c2;   
       width: 100%;  
        color: rgb(36, 35, 35);   
        padding: 15px;   
        margin: 10px 0px;   
        border: none;   
        cursor: pointer;   
         }   
 form {   
        border: 3px solid #f1f1f1;   
    }   
 input[type=text], input[type=password] {   
        width: 100%;   
        margin: 8px 0;  
        padding: 12px 20px;   
        display: inline-block;   
        border: 2px solid rgb(8, 12, 8);   
        box-sizing: border-box;   
    }  
 button:hover {   
        opacity: 0.7;   
    }   
  .cancelbtn {   
        width: auto;   
        padding: 10px 18px;  
        margin: 10px 5px;  
    }   
        
     
 .container {   
        padding: 25px;   
        background-color: lightblue;  
    }   
</style>   
</head>    
<body>    
    <Body background="https://i.pinimg.com/564x/aa/45/e9/aa45e96d5866da44cee3df14a559579e.jpg"></Body>
    <center> <h1  style="color:rgb(15, 0, 0);font-size:40px;"> LOGIN </h1> </center>   
    <form>  
    <div class="container">   
            <label>Username : </label>   
            <input type="text" placeholder="Enter Username" name="username" required>  
            <label>Password : </label>   
            <input type="password" placeholder="Enter Password" name="password" required>  
            <button type="submit">Login</button>   
            <input type="checkbox" checked="checked"> Remember me   
            <button type="button" class="cancelbtn"> Cancel</button>   
            Forgot <a href="#"> password? </a>
            <p></p>
      New user?<a href=driver.html>REGISTER AS DRIVER</a>
      <p></p>
      <a href=registrsdealers.html>REGISTER AS DEALER</a>
        </div>   
    </form>     
</body>     
</html>


#signup code for drivers
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">  
        <title> Login Page </title>  
        <style>   
        Body {  
          font-family: Calibri, Helvetica, sans-serif;  
          background-color: rgb(223, 190, 196);  
        }  
        button {   
               background-color: #c1e9c2;   
               width: 100%;  
                color: rgb(36, 35, 35);   
                padding: 15px;   
                margin: 10px 0px;   
                border: none;   
                cursor: pointer;   
                 }   
         form {   
                border: 3px solid #f1f1f1;   
            }   
         input[type=text], input[type=password] {   
                width: 100%;   
                margin: 8px 0;  
                padding: 12px 20px;   
                display: inline-block;   
                border: 2px solid rgb(8, 12, 8);   
                box-sizing: border-box;   
            }  
         button:hover {   
                opacity: 0.7;   
            }   
          .cancelbtn {   
                width: auto;   
                padding: 10px 18px;  
                margin: 10px 5px;  
            }   
                
             
         .container {   
                padding: 25px;   
                background-color: lightblue;  
            }   
        </style>  
    <center><h1 style="color:rgb(15, 0, 0);font-size:40px;"> WELCOME DRIVERS </h1></center>
    <center><p style="color:rgb(2, 2, 14);font-size:18px;"> Create an new account </p></center>
</head>
<body>
    <Body background="https://i.pinimg.com/564x/aa/45/e9/aa45e96d5866da44cee3df14a559579e.jpg"></Body>
<form>
    <center><table></center>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Name:</td><td><input type=”text” placeholder=”Name” name=””></td></tr>  
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Age:</td><td><input type=”digit” placeholder=”Age” name=””></td></tr>
                        <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Truck no:</td><td><input type=”text” placeholder=”Trucknumber” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Email Address:</td><td><input type=”mail”  placeholder=”Email” name=””></td></tr>
                        <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Password:</td><td><input type=”Password” placeholder=”Password” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Re-enter Password:</td><td><input type=”Password” placeholder=”Password” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Truck capacity:</td><td><input type=”digit” placeholder=”Capacity” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Experience:</td><td><input type=”digit” placeholder=”DrivingExperience” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Mobile no:</td><td><input type=”tel” placeholder=”phone” name=””></td></tr>
                        <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Preffered Route1:</td><td><input type=”text” placeholder=”cityFrom” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Route1:</td><td><input type=”text” placeholder=”cityTo” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Preffered Route2:</td><td><input type=”text” placeholder=”cityFrom” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Route2:</td><td><input type=”text” placeholder=”cityTo” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Preffered Route3:</td><td><input type=”text” placeholder=”cityFrom” name=””></td></tr>
            <tr><td style="color:rgb(2, 2, 14);font-size:18px;">Route3:</td><td><input type=”text” placeholder=”cityTo” name=””></td></tr>

    </table>

</form> 
</body>
</html>
#sign up code for dealers

<!DOCTYPE html>
<html>
<head>  
        <meta name="viewport" content="width=device-width, initial-scale=1">  
        <title> Login Page </title>  
        <style>   
        Body {  
          font-family: Calibri, Helvetica, sans-serif;  
          background-color: rgb(223, 190, 196);  
        }  
        button {   
               background-color: #c1e9c2;   
               width: 100%;  
                color: rgb(36, 35, 35);   
                padding: 15px;   
                margin: 10px 0px;   
                border: none;   
                cursor: pointer;   
                 }   
         form {   
                border: 3px solid #f1f1f1;   
            }   
         input[type=text], input[type=password] {   
                width: 100%;   
                margin: 8px 0;  
                padding: 12px 20px;   
                display: inline-block;   
                border: 2px solid rgb(8, 12, 8);   
                box-sizing: border-box;   
            }  
         button:hover {   
                opacity: 0.7;   
            }   
          .cancelbtn {   
                width: auto;   
                padding: 10px 18px;  
                margin: 10px 5px;  
            }   
                
             
         .container {   
                padding: 25px;   
                background-color: lightblue;  
            }   
        </style>      
    <center><h1 style="color:rgb(15, 0, 0);font-size:40px;">WELCOME DEALERS</h1></center>
    <center><p style="color:rgb(2, 2, 14);font-size:18px;">Create an account and start enjoying the service</p></center>
</head>
<body>  
    <Body background="https://i.pinimg.com/564x/aa/45/e9/aa45e96d5866da44cee3df14a559579e.jpg"></Body>
<form>
    <center><table></center>
        <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">Name:</td><td><input type=”text” placeholder=”Enter your name” name=””></td></tr></center>
            <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">Email Address:</td><td><input type=”mail”  placeholder=”Email” name=””></td></tr></center>
            <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">Password:</td><td><input type=”Password” placeholder=”Password” name=””></td></tr></center>
                <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">Re-enter Password:</td><td><input type=”Password” placeholder=”Password” name=””></td></tr></center>
                    <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">Nature of material:</td><td><input type=”text” placeholder=”Material type” name=””></td></tr></center>
                        <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">Quantity:</td><td><input type=”digit” placeholder=”amount of material” name=””></td></tr></center>
                            <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">Weight:</td><td><input type=”text” placeholder=”weight of material” name=””></td></tr></center>
                                <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">Mobile no:</td><td><input type=”tel” placeholder=”phone” name=””></td></tr></center>
                                    <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">city:</td><td><input type=”text” placeholder=”Ex(vizag..)” name=””></td></tr></center>
                                        <center><tr><td style="color:rgb(2, 2, 14);font-size:18px;">State:</td><td><input type=”text” placeholder=”state” name=””></td></tr></center>
    <center></table></center>
</form> 
</body>
</html>
