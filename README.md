<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="../styles/styles.css">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    


  @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100;200&display=swap');
 

 *{
     font-family: 'Outfit', sans-serif;
     margin: 0;
     padding:0;
 }
 .logo{
    color: #fbfbfb;
 }
 
 
     
 .main{
     width:100%; 
     height: 100vh;
     background-position: center;
     background-size: cover;
 }
 
 .navbar{
     display:flex;
     justify-content: space-between;
     align-items: center;
     width:1200px;
     height:75px;
     margin:auto;
 }
 
 .menu{
     width: 400px;
     float:left;
     height:70px;
 }
 
 ul{
     
     display:flex;
     justify-content: space-between;
     align-items: center;
 }
 
 ul li{
     transition: 0.3s ease;
     padding: 30px;
     padding-left: 50px;
     list-style: none;
 }
 
 ul li a:hover{
     color: aliceblue;
     translate: 0px -5px;
 }
 ul li:hover{
     color: rgb(176, 192, 206);
     translate: 0px -5px;
 }
 
 ul li a{
     transition: 0.3s ease;
     font-weight: bold;
     text-decoration: none;
     color: #d06767;
 }

 .search{
     width:330px;
     float:left;
     margin-left:270px;
 }
 
 .srch{
     width:200px;
     height:40px;
     background: transparent;
     border: 2px solid #274c77;
     margin-top:13px;
     color:#9b2929;
     padding:5px 5px;
     float:left;
     border-radius: 20px;
 }
 
 .btn1{
     width:100px;
     height:40px;
     background:#ada07f;
     color:#370fd7;
     font-size: 15px;
     padding: 10px;
     margin-top:13px;
     cursor:pointer;
     transition:0.3s ease;
     border: 2px solid #8e6b01;
     border-radius: 15px;
     margin-left: 15px;
 
 }
 
 .btn1:hover{
     background-color: #8e6b01 ;
     translate:0px -3px;
 }
 
 .srch:focus{
     outline: none;
 }
 
 .content{
     width:1200px;
     height:auto;
     margin:auto;
     color:#660909;
     position:relative;
 }
 
 .content h1{
     font-size: 50px;
     padding-left: 20px;
     margin-top: 10%;
     letter-spacing: 2px;
 }
 
 .content .par{
     color:rgb(103, 97, 90);
     padding-left: 20px;
     padding-bottom: 25px;
     letter-spacing: 1.2px;
     line-height: 30px;
     font-weight: bold;
 }
 
 .btnsubmit{
     width:150px;
     height:40px;
     background:#cd9a00;
     color:#fff;
     font-size: 15px;
     padding: 10px;
     margin-top:13px;
     cursor:pointer;
     transition:0.3s ease;
     border: 2px solid #8e6b01;
     border-radius: 15px;
     margin-right: 15px;
 }
 
 
 .btnsubmit1{
     width:150px;
     height:40px;
     background:#fbfbfb;
     color:#cd9a00;
     font-size: 15px;
     padding: 10px;
     margin-top:13px;
     cursor:pointer;
     transition:0.3s ease;
     border: 2px solid #cd9a00;
     border-radius: 15px;
 }
 
 .submit{
     padding-left: 20px;
 }
 
 .hint{
     padding-top: 10px;
 }
 
 .form{
     width:250px;
     height:370px;
     position:absolute;
     top: 150px;
     left: 800px;
     transform: translate(0%,-5%);
     color: #fce6a2;
     font-size:22px ;
     background-color: #32cb98;
     border-radius: 20px;
     padding: 15px;
     margin:5px;
 }
 
 .form h2{
     width:220px;
     text-align: center;
     color:#8c1919;
     font-size:22px;
     background-color: #fff;
     border-radius: 20px;
     padding: 8px;
     margin:2px;
 }
 
 .form input{
     width:240px;
     height:35px;
     background: transparent;
     border-radius: 10px;
     padding:3px;
     color: #fff;
     font-size:15px ;
     letter-spacing: 1px;
     margin-top:30px;
 
 }
 
 .form .link{
     font-size: 17px;
     padding-top: 20px;
     text-align: center;
 }
 
 .link a{
     text-decoration: none;
     font-size: 17px;
     color:#ba5151;
 }
 .link a:hover{
     color: #c97474;
 }
 .form .liw{
     font-size: 12px;
     padding-top: 10px;
     text-align: center;
     padding-bottom: 35px;
 }
 
 .icons a{
     text-decoration: none;
     color: #9a1717;
 }
 
 .icons ion-icon{
     color:#1b1a1a;
     font-size: 30px;
     padding-left: 14px;
     transition: 0.3s ease;
 }
 
 .icons ion-icon:hover{
     color: #565655;
 } 
 
 .btnn{
     background:#c99c9c;
     font-size: 15px;
     cursor:pointer;
     transition:0.3s ease;
     border: 1px solid #117cb9;
     border-radius: 15px;
     margin-top: 15px;
     margin-left: 70px;
     color: #1375b6;
 }
 
 .btnn:hover{
     background-color: #6e6f6f;
     translate:0px -3px;
     color: #fff;
 }
 
 .btnn>a{
     padding: 20px 25px ;
     text-decoration: none;
     color: #0e0f0f;
 }
 
 .btnn>a:hover{
     color: #fff;
 }
 
 ::placeholder{
     color:#fff;
 }
 

 
 .footer-elem{
     display:flex;
     justify-content: center;
     align-items: center;
 }
 
 .copyright{
     display:flex;
 justify-content: center;
 align-items: center;
 }
 
 .footer-elem ion-icon{
     color:#2e0842;
     font-size: 30px;
     padding-left: 14px;
     transition: 0.3s ease;
 }
 
 .footer-elem ion-icon:hover{
     color: #6c0faa;
 } 
 
 .follow-us{
     translate: 0px -10px;
     padding-bottom: 10px;
     color: #09cdeb;
 }
 .copyright{
    
     color: #09cdeb;

 }
 body{
     background-image: url("ruuu.jpeg") ;
    background-size: cover;
     
     
     
 }
     
 
</style>

<body>

    <div class="main">

        <div class="navbar">
            <div>
                <h2 class="logo">Website</h2>
            </div>
            <div class="menu">
                <ul>
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">ABOUT</a></li>
                    <li><a href="#">SERVICE</a></li>
                    <li><a href="#">DESIGN</a></li>
                    <li><a href="#">CONTACT</a></li>
                </ul>
            </div>

            <div class="search">
                <input class="srch" type="text" placeholder="Search Here">
                <a href="#"><button class="btn1">Search</button></a>
            </div>
        </div>

        <div class="content">

            <h1>PET SHELTER</h1>
            <p class="par">Adopt us we need your help.<br> Come join hands with
                us and take us to your shelter <br>Pets are non-judgemental and provide unconditional love,meaning, and joy to our lives !</p>
            <div class="submit">
                <button class="btnsubmit">SignUp</button>
                
             
            </div>
        </div>

        <div class="form">
            <h2>Login Here</h2>
            <input type="text" placeholder="Enter your Username :">
            <input type="password" placeholder="Enter your Password :">
            <button class="btnn"><a href="#">Login</a></button>

            <p class="link">Dont Have an Account? <a href="#">Sign Up</a></p>
            <p class="liw">Login With:</p>

            <div class="icons">
                <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
                <a href="#"><ion-icon name="logo-google"></ion-icon></a>
                <a href="#"><ion-icon name="logo-skype"></ion-icon></a>
            </div>

        </div>

    </div>

    <footer>
        <div>
            <ul>
                <li><a href="#">SERVICE</a></li>
                <li><a href="#">DESIGN</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>
            <div class="footer-elem">
                <p>
                    <span class="follow-us">You can follow us on</span>
                    <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                    <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
                    <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                </p>
            </div>
            <div class="copyright">
                <p>&copy; 2023 WebPage. All rights reserved.</p>
            </div>
        </div>
    </footer>
    <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js"></script>
</body>

</html>


