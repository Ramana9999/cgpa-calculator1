# cgpa-calculator1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #left
        {
margin-left: -650px;


        }
        #right{
            margin-top: -325px;

margin-right: -600px;

        }

        #start{
            font-size: 60px;
            background-color:black;
            color:rgb(42, 165, 138);



        }
        .center {
            background-color: rgb(42, 165, 138);
            /* margin:250px; */
            /* margin-top: 0px; */
            /* margin-bottom: 0px; */
            /* margin-left: 300px; */
            /* margin-right:300px ; */
            padding:30px;
            
            font-size: 40px;
        }

.port{
    font-size: 25px;
    padding-top: 25px;
    margin:10px;
}
#view
{
    color:darkgreen;
    padding:10px;
    margin-left: 10px;
    align-items: center;
    padding-left:40px;
  /* margin-top: -50px; */
font-size: 40px;
}

body{
    background-color: rgb(205, 245, 255);
}





        




        </style>
</head>
<body >
    <div id=start>
    <center>JNTU CGPA CALCULATOR</div><br><br><br>
    </center>
    <div class=center>
        <center>
            <div id=left>
   SEMISTER 1-1 <input type=number class=port id=sem1><br>
   SEMISTER 1-2 <input type=number class=port id=sem2><br>
   SEMISTER 2-1 <input type=number class=port id=sem3><br>
   SEMISTER 2-2 <input class=port  type=number id=sem4><br>
   </div>
   <div id=right>
   SEMISTER 3-1 <input class=port type=number id=sem5><br>
   SEMISTER 3-2 <input class=port type=number id=sem6><br>
   SEMISTER 4-1 <input class=port type=number id=sem7><br>
   SEMISTER 4-2 <input class=port type=number id=sem8><br></div> </center></div><br>
 <center><button class=btn type=button onclick=done() ><h1>SUBMIT</h1></button></center>><br><br><br>
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
 <font SIZE=40>TOTAL CGPA:</font>  <input  id=view VALUE=RESULT>
<br><br><br><br><br>

   <script>
       function done()
       {
       var a,b,c,d,e,f,g,h;
       var final,total;
    // //    if(a,b,c,d,e,f,g,h==number)

       
      
       a=Number(document.getElementById("sem1").value);
       b=Number(document.getElementById("sem2").value);
       c=Number(document.getElementById("sem3").value);
       d=Number(document.getElementById("sem4").value);
       e=Number(document.getElementById("sem5").value);
       f=Number(document.getElementById("sem6").value);
       g=Number(document.getElementById("sem7").value);
       h=Number(document.getElementById("sem8").value);
       if(a,b,c,d,e,f,g,h<10)
       {
       total=a+b+c+d+e+f+g+h;
       final=total/8;
       document.getElementById("view").value=final;


       }
       else {
        alert( " please check your inputs once");
       }
    // else
    // {
    // alert("check your inputs");
    // }  
       
       
       
    //    if(final>10)
    //    {
    //    alert("please check your input wheather they are correct inputs"); 
    //    }
    //    else
    //    {
    //    document.getElementById("view").value=final;
    //    }
   }


       </script>
    
</body>
</html>
