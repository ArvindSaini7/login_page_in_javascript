# login_page_in_javascript
login page 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Facebook</title>
    <style>
        .a{ 
            
            
            width: 100%;
            height: 500px;
            background-color: #F2F4F7;
        }
        .b{
            width: 100%;
            height: 400px;
            background-color: white;
            
        }
        .aa{
            
            width: 400px;
            height: 400px;
            background-color: white;
        }
        .ab{
            width: 400px;
            height: 100px;
            background-color: #F2F4F7;
        }
    </style>
</head>
<body>
    <div class="a">
        <center>
        <div class="aa"><center>
           <div class="ab"> <h1 style="font-style: italic; color: #166FE5; font-size:52px;">Facebook</h1></div>
            <h5>Log in to Facebook</h5></center>
            <center>
            <input type="email" id="email" style="width: 300px; height: 40px; margin-top: 30px;" >
            <input type="password" id="password" style="width: 300px; height: 40px; margin-top: 30px;" >
                <button  onclick="login()" type="Login" style="width: 300px; height: 40px; background-color: #166FE5;  margin-top: 30px;">Login</button>
        </center></center>
        </div>

    </div>
    <div class="b"><center><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique autem esse veritatis, facere quibusdam laboriosam temporibus nisi in ex culpa?<br>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae ratione quod cum deleniti distinctio </p></center></div>
</body>
</html>
<script>
    let login = () =>{
        let emailvalue = document.getElementById("email").value
        let passwordvalue = document.getElementById("password").value

        if(emailvalue=="a@gmail.com"&& passwordvalue=="12345"){
            window.location.assign("https://www.youtube.com/")
        }

        else if(emailvalue=="" && passwordvalue=="12345"){
                alert("enter email")
            }
            
            else if(emailvalue=="" && passwordvalue==""){
                alert("enter data")
            }
            else if(emailvalue!="a@gmail.com" && passwordvalue=="12345"){
                alert("invalid email")
            }
            else if(emailvalue=="a@gmail.com" && passwordvalue!="12345"){
                alert("invalid password")
            }
            else{
                alert("invalid data")
            }
    };

    
</script>
