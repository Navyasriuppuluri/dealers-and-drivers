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
