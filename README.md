// using html



<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta http-equiv="X-UA-Compatible" content="IE=edge">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title> login page</title>

<link rel="stylesheet" href="style.css">

</head>

  



<body class="bg-img">

  

<div class="nature">

  <input type="Name" required><input type="Name" required>

</div>

  

  <div class="center">

     <h2> Book a call</h2>

     <h5> Book a call slot  and our reprentive will call yoy within 1hr of selected time</h5>

     <form method="post">

<div class="txt_field">

  <span></span>

  <lable> Name</lable>

  <br>

  <input type="Name" required>

  <br>

</div> 

<div class="txt_field">

  <span></span>

  <lable> Email</lable>

  <br>

  <input type="Email" required>

  

  

</br>

</div>

<div class="txt_field">

  <span></span> 

  <lable> Phone</lable>

  <br>

  <input type="Phone" required>

</br>



</div>





<div>

  <div class="pass"></div>



   Time for Call:

   <br>

   <div class="value">

     <!-- <span></span> -->

   <input type="date"><input type="time">

</div>

<div>

  

  <input type="submit" value= "Get a Call">



</div>

     </form>

  </div>

</div>

<div class="logo">

<img src="logo.png" alt="">

</div>

</body>

 

 

</html>





// using  css



.bg-img{

background-image: url(tanu.jpg);

}



.nature input{

    width:100px;

    padding: 0 5px;

    height:20px;

    font-size: 16px;

    border-color: orange;   



}

body{

    margin: 0;

    padding: 0;

    font-family: monterserrat;

    background: linear-gradient(120deg, #2980b9, hsl(282, 44%, 47%));

     height:250vh;

     overflow:hidden;

     border-color: darkorange;

     text-align:right;

}

.center{

    position:absolute;

    top: 35%;

    left: 44%;

    text-align: top;

    transform:translate(-50%,-50%);

    width:600px;

    background:whitesmoke;

     border-radius: 10px;

     border-color:gold;

     border-bottom-left-radius:orange;

     border-top-right-radius:red;

}



.center h2{

    text-align: center;

    /* padding: 0 0 20px 0; */

   color: tomato;



}

.center h5{

    text-align: center;

    padding: 0 0 20px 0;

    border-bottom: 1px solid silver ;

}

.center form{

    padding: 0 40px;

    box-sizing:border-box;



}

form .txt_field{

    position:relative;

    border-bottom:1px solid #adadad;

    margin: 10px 0;



}

.txt_field input{

    width:500px;

    padding: 0 5px;

    height:20px;

    font-size: 16px;

    /* border:none; */

     /* background:none; */

      outline:none;



}



.txt_field lable{

    position:absolute;

     top: 20%;

     left:5px;

     color:dimgrey;

      transform: translateY(-50%);

      font-size:16px ;

      pointer-events: none;



}



.txt_field span::before{

    content:'';

    position:absolute;

    top:40px;

    left:0;

    width:100%;

    height: 2px;

    

}

 .txt_field input:focus ~ lable,

 .txt_field input:valid ~  lable{

     top:-5px;

     color: #2980b9;

 }

 

 .pass{

    margin: -5px 0 20px 5px;

    color: #a6a6a6;

    cursor:pointer;



 }

 .pass:hover{

    text-decoration: underline;



 }



 .value input{

    width:242px;

    padding: 0 5px;

    height:20px;

    font-size: 16px;

 }



 



  input[type="submit"]{

    width:100%;

    height:30px;

    border:1px solid;

    background: orange;

     border-radius: 3px;

 font-size: 10px;

 color:white;

 font-weight: 700;

 cursor:pointer;

 outline:none;

 margin:  30px 0;

    text-align: center;

  }

  input[type="submit"]:a{

    color: #2691d9;

  }



  input[type="submit"] a:hover{

   border-color: #262626;

    transition: .5s;

    text-decoration: underline;

  }

 .logo{

    display:flex;

    align-items: center;

 }

 .logo img{

    width: 88px;

  padding: 0 25;



 }
