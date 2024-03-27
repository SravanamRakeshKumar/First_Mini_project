# Rakeshu
<html> 
 <head> 
  <title>login page</title> 
  <style>
    body
    {
      width:auto;
      height:auto;
      display:flex;
      justify-content:center;
      align-items:center;
      color:white;
      background:linear-gradient(45deg,green,blue,red,yellow);
      overflow:auto;
    }
    #one
    {
      width:100%;
      height:100%;
      display:none;
      background-color:white;
      border:20px black solid;
      overflow:auto;
    }
    .i
    {
      width:90%;
      height:70px;
      font-size:50px;
      outline:none;
      background-color:white;
      border-left:none;
      border-top:none;
      border-right:none;
      caret-color:blue;
      color:black;
    }
    span
    {
      font-size:30px;
    }
     #h
     {
       width:auto;
       height:100px;
       color:white;
       font-size:50px;
       text-align:center;
       background-color:navy;
       padding-top:20px;
       position:sticky;
       top:0px;
       z-index:10;
     }
     #n ul
     {
       display:flex;
       margin-top:0px;
       padding:0px;
       width:auto;
       height:auto;
       background-color:silver;
       border:5px black solid;
       border-left-color:transparent;
       border-right-color:transparent;
     }
     nav
     {
      position:sticky;
      top:100px;
      z-index:10;
     }
     #n ul li
     {
       list-style-type:none;
       margin-right:30px;
       font-size:70px;
      }
      #n ul li:last-child
      {
       position:absolute;
       right:0px;
       margin-right:0px;
      }
      li a
      {
        text-decoration:none;
        color:black;
      }
      li a:hover
      {
        background-color:green;
        color:white;
        width:100%;
        height:100%;
      }
      .xxx
      {
        width:auto;
        height:auto;
        display:none;
        background-color:white;
        color:black;
      }
      #x p::first-line
      {
        position: absolute;
        top:30px;
        font-size:130px;
        color:green;
        font-family:italic;
      }
      :target
      {
        display:block;
      }
      #inside
      {
        display:none;
      }
      #n ul li:hover #inside
      {
        display:block;
        position:absolute;
        margin:0px;
      }
      #n ul li:hover #inside ul
      {
        display:block;
        margin:0px;
      }
      #n ul li:hover #inside ul li
      {
        width:100%;
        padding:30px;
        left:0px;
        border-bottom:5px solid blue;
        border-radius:0;
        background-color:green
      }
      #x .daa
      {
        width:100%;
        height:auto;
        margin:10px;
        display:block;
      }
      #cal
      {
        width:500px;
        height:800px;
        background-color:red;
        position:relative;
        border:5px black solid;
        z-index:2;
        display:flex;
        flex-wrap:wrap;
      }
      #cal p
      {
        width:100px;
        height:100px;
        background-color:blue;
        margin-left:20px;
        font-size:25px;
        display:flex;
        color:white;
        justify-content:center;
        align-items:center;

      }
  #in
{
  width:550px;
  height:550px;
  background-color:black;
  display:grid;
  grid-template-columns:repeat(3,auto);
  gap:2px;
}
.out
{
width:170px;
height:170px;
display:grid;
grid-template-columns:repeat(3,auto);
gap:1px;
background-color:white;
border:5px black solid;
}
.oo
{
width:55px;
height:55px;
display:flex;
font-size:30px;
justify-content:center;
align-items:center;
border:2px black solid;
background-color:white;
}
#tic
{
width:600px;
height:600px;
background-color:red;
display:grid;
grid-template-columns:repeat(3,auto);
}
.toc
{
width:200px;
height:200px;
display:grid;
grid-template-columns:repeat(3,auto);
border:5px white solid;
background-color:black;
color:white;
display:flex;
justify-content:center;
align-items:center;
font-size:50px;
}
#tt{
  border-collapse: collapse;
  width: 100%;
}

#t
 {  
        border: 5px solid green;   
        padding: 15px;  
    }
    #what,#insta,#you,#lin,#git
    {
      width:500px;
      height:200px;
      border:10px black solid;
      background-color:red;
      border-radius:30%;
      margin-left:17%;
      display:flex;
      justify-content:center;
      align-items:center;
      font-size:50px;
      color:white;
      box-shadow:10px 0px 0px 10px blue;
    }

  </style> 
 </head> 
 <body>
   <div id="fff">
   <table> 
    <tbody> 
     <tr> 
      <td><h1 style="padding:0px 0px 0px 50px;font-size:45;font-weight:bolder">Username</h1> </td> 
     </tr> 
     <tr> 
      <th style="padding:0px 0px 0px 30px"><input type="text" id="iii" class="i" required></th> 
     </tr> 
     <tr> 
      <td><h1 style="padding:50px 0px 0px 50px;font-size:45;font-weight:bolder">Password</h1> </td> 
     </tr> 
     <tr> 
      <th style="padding:0px 0px 0px 30px"><input type="password" class="i" id="ii" required><br></th> 
     </tr> 
     <tr> 
      <th style="padding:0px 0px 0px 300px"><input type="checkbox" id="c" onclick="fun()" style="width:50px;height:30px"><span>Show Password</span></th> 
     </tr> 
     <tr> 
      <th style="padding:150px 0px 0px 20px"><input  type="submit" value="LOGIN"  onclick="next()" style="width:500px;height:100px;font-size:60px;color:white;background-color:red;border-radius:40px"></th> 
     </tr> 
    </tbody> 
   </table> 
  </div>
  <div id="one"> 
   <header id="h">
      Portfolio website 
   </header> 
   <nav id="n"> 
    <ul> 
     <li class="active" style="background-color:green;color:white" onclick="ab()"><a href="#x">home</a></li> 
     <li><a href="#y">studies</a> 
      <div id="inside"> 
       <ul> 
        <li onclick="bc()"><a href="#p">achivements</a></li> 
        <li onclick="cd()"><a href="#q">about</a></li> 
        <li onclick="de()"><a href="#r">projects</a></li> 
       </ul> 
      </div> </li> 
     <li onclick="ef()"><a href="#z">contact</a></li> 
     <li onclick="zz()"><a href="#">logout</a></li> 
    </ul> 
   </nav> 
 <div id="x" style="display:block;color:black;margin:10px">
     <p style="font-size:40px">student website
     it is not a website.it is a feature successful platform of every student and it is helpful to what is you and what can u do in your carrier.<hr style="color:gray">
     <br><br>
     <b style="font-size:40px;margin:10px">now see some important topis on studies--></b>
    </p>
     <div id="d1" class="daa" style="background-color:red;padding-right:10px;padding-bottom:10px;padding-left:10px">
       <span style="color:white;font-size:40px">1.goal</span>
       <br>
       <h2>goal means for example you are a mutly skilled student and you have a good behaviour. but you have dont idea for the what you do, that's why you are not successful in your life.first you  decide one goal and do hardwork for it,the atomically your success.it is tha major roal of every student life.</h2>
     </div>
     <br>
     <div id="d2" class="daa" style="background-color:orange;padding-right:10px;padding-bottom:10px;padding-left:10px">
       <span style="color:white;font-size:40px">2.time</span>
       <br>
       <h2>goal means for example you are a mutly skilled student and you have a good behaviour. but you have dont idea for the what you do, that's why you are not successful in your life.first you  decide one goal and do hardwork for it,the atomically your success.it is tha major roal of every student life.</h2>
     </div>

     <br>
     <div id="d3" class="daa" style="background-color:MediumSeaGreen;padding-right:10px;padding-bottom:10px;padding-left:10px">
       <span style="color:white;font-size:40px">3.patence</span>
       <br>
       <h2>goal means for example you are a mutly skilled student and you have a good behaviour. but you have dont idea for the what you do, that's why you are not successful in your life.first you  decide one goal and do hardwork for it,the atomically your success.it is tha major roal of every student life.</h2>
     </div>

     <br>
     <div id="d4" class="daa" style="background-color:gray;padding-right:10px;padding-bottom:10px;padding-left:10px">
       <span style="color:white;font-size:40px">4.practice</span>
       <br>
       <h2>goal means for example you are a mutly skilled student and you have a good behaviour. but you have dont idea for the what you do, that's why you are not successful in your life.first you  decide one goal and do hardwork for it,the atomically your success.it is tha major roal of every student life.</h2>
     </div>

     <br>
     <div id="d5" class="daa" style="background-color:skyblue;padding-right:10px;padding-bottom:10px;padding-left:10px">
       <span style="color:white;font-size:40px">5.behaviour</span>
       <br>
       <h2>goal means for example you are a mutly skilled student and you have a good behaviour. but you have dont idea for the what you do, that's why you are not successful in your life.first you  decide one goal and do hardwork for it,the atomically your success.it is tha major roal of every student life.</h2>
     </div>

     
   </div> 
    <div id="z" class="xxx" style="margin:30px">
   <h1 style="font-size:60px"><u>Contact:-</u></h1>
     <p style="font-size:40px">project  means you are bulid an idea with some properties like tools that is the project.and first step is you do a plan for the project and desing it, after  all good result then you are do a one project.<br>

<br>
<br>
<div id="what">
  <p>whatsap</p>
</div>
<br>
<div id="insta">
  <p>instagram</p>
</div>
<br>
<div id="you">
  <p>you tube</p>
</div>
<br>
<div id="lin">
  <p>Linkedin</p>
</div>
<br>
<div id="git">
  <p>Github</p>
</div>

</div>
   <div id="p" class="xxx" style="margin:30px;">
     <h1 style="font-size:60px"><u>achievements:-</u></h1>
     <p style="font-size:40px">achievements means what you achive in you are life for your carrier.and how to use that achivements to lead a life that is main concept of the achivemes.not only academics, you are achieved one in any domain that is one of the your achievement.<br>
     <hr>
        <br>
     <span style="color:green;font-size:50px"><b>let us look some achivements in my acadamic carrier</b></span><br>
     <p style="font-size:60px;color:#ff00ff">-->in my 10<sup>th</sup> class</p>
     <p style="font-size:40px;margin-left:30px">
     <span style="font-size:70px">I</span>n 10th class i am archive many gift,awords,price money as per acodimics and games. now i share my achievements with us, i am so happy to this .my first award is ₹100 cash price in matametics due to i am the class first in that subject i am so happy.then after i achieve many price moneys and many gifts as per the academic s</p><br>
      <p style="font-size:60px;color:#ff00ff">-->in my inter</p>
      <p style="font-size:40px;margin-left:30px">
      <span style="font-size:70px">I</span>n 10th class i am archive many gift,awords,price money as per acodimics and games. now i share my achievements with us, i am so happy to this .my first award is ₹100 cash price in matametics due to i am the class first in that subject i am so happy.then after i achieve many price moneys and many gifts as per the academic s
          </p>
     <p style="font-size:60px;color:#ff00ff">-->in my betech</p>
     <p style="font-size:40px;margin-left:30px">
     <span style="font-size:70px">I</span>n 10th class i am archive many gift,awords,price money as per acodimics and games. now i share my achievements with us, i am so happy to this .my first award is ₹100 cash price in matametics due to i am the class first in that subject i am so happy.then after i achieve many price moneys and many gifts as per the academic s
       </p>
     </p>
   </div> 
      
  <div id="r" class="xxx" style="margin:30px">
     <h1 style="font-size:60px"><u>projects:-</u></h1>
     <p style="font-size:40px">project  means you are bulid an idea with some properties like tools that is the project.and first step is you do a plan for the project and desing it, after  all good result then you are do a one project.<br>
       <hr>
       <br>
       <span style="color:blue;font-size:50px"><b>My projects are:- </b></span><br>
     <p style="font-size:60px;color:#ff00ff">>>>Calculator</p>
     <p style="font-size:40px;margin-left:30px">
       <span style="font-size:70px">I</span>n 10th class i am archive many gift,awords,price money as per acodimics and games. now i share my achievements with us, i am so happy to this .my first award is ₹100 cash price in matametics due to i am the class first in that subject i am so happy.then after i achieve many price moneys and many gifts as per the academic s
     </p>
     <div id="cal">
       <p style="width:90%; height:100px;border:5px black solid; background-color:white"></p>
       <p>1</p>
       <p>2</p>
       <p>3</p>
       <p>4</p>
       <p>5</p>
       <p>6</p>
       <p>7</p>
       <p>8</p>
       <p>9</p>
       <p>0</p>
       <p>+</p>
       <p>-</p>
       <p>*</p>
       <p>%</p>
       <p>c</p>
       <p>r</p>

     </div>
     <br>
     <p style="font-size:60px;color:#ff00ff">>>>Sudoco</p>
     <p style="font-size:40px;margin-left:30px">
       <span style="font-size:70px">I</span>n 10th class i am archive many gift,awords,price money as per acodimics and games. now i share my achievements with us, i am so happy to this .my first award is ₹100 cash price in matametics due to i am the class first in that subject i am so happy.then after i achieve many price moneys and many gifts as per the academic s
     </p>
     <div id="in">
       <div class="out">
         <div class="oo">1</div>
         <div class="oo">6</div>
         <div class="oo">8</div>
         <div class="oo">3</div>
         <div class="oo">5</div>
         <div class="oo">4</div>
         <div class="oo">2</div>
         <div class="oo">7</div>
         <div class="oo">9</div>
       </div>
       <div class="out">
         <div class="oo">9</div>
         <div class="oo">5</div>
         <div class="oo">3</div>
         <div class="oo">6</div>
         <div class="oo">2</div>
         <div class="oo">4</div>
         <div class="oo">8</div>
         <div class="oo">7</div>
         <div class="oo">1</div>

       </div>
       <div class="out">
        <div class="oo">6</div>
         <div class="oo">3</div>
         <div class="oo">1</div>
         <div class="oo">9</div>
         <div class="oo">2</div>
         <div class="oo">7</div>
         <div class="oo">8</div>
         <div class="oo">5</div>
         <div class="oo">4</div>

       </div>
       <div class="out">
         <div class="oo">8</div>
         <div class="oo">3</div>
         <div class="oo">2</div>
         <div class="oo">4</div>
         <div class="oo">6</div>
         <div class="oo">9</div>
         <div class="oo">5</div>
         <div class="oo">7</div>
         <div class="oo">1</div>

       </div>
       <div class="out">
         <div class="oo">5</div>
         <div class="oo">2</div>
         <div class="oo">4</div>
         <div class="oo">1</div>
         <div class="oo">7</div>
         <div class="oo">6</div>
         <div class="oo">3</div>
         <div class="oo">8</div>
         <div class="oo">9</div>

       </div>
       <div class="out">
         <div class="oo">4</div>
         <div class="oo">1</div>
         <div class="oo">6</div>
         <div class="oo">8</div>
         <div class="oo">5</div>
         <div class="oo">3</div>
         <div class="oo">9</div>
         <div class="oo">7</div>
         <div class="oo">2</div>

       </div>
       <div class="out">
         <div class="oo">3</div>
         <div class="oo">9</div>
         <div class="oo">5</div>
         <div class="oo">1</div>
         <div class="oo">3</div>
         <div class="oo">8</div>
         <div class="oo">6</div>
         <div class="oo">2</div>
         <div class="oo">7</div>

       </div>
       <div class="out">
         <div class="oo">2</div>
         <div class="oo">8</div>
         <div class="oo">2</div>
         <div class="oo">4</div>
         <div class="oo">9</div>
         <div class="oo">7</div>
         <div class="oo">6</div>
         <div class="oo">3</div>
         <div class="oo">5</div>

       </div>
       <div class="out">
         <div class="oo">7</div>
         <div class="oo">1</div>
         <div class="oo">5</div>
         <div class="oo">3</div>
         <div class="oo">7</div>
         <div class="oo">2</div>
         <div class="oo">8</div>
         <div class="oo">6</div>
         <div class="oo">4</div>

       </div>
     </div>
     <br>
     <p style="font-size:60px;color:#ff00ff">>>>Tic-toc-tic</p>
     <p style="font-size:40px;margin-left:30px">
       <span style="font-size:70px">I</span>n 10th class i am archive many gift,awords,price money as per acodimics and games. now i share my achievements with us, i am so happy to this .my first award is ₹100 cash price in matametics due to i am the class first in that subject i am so happy.then after i achieve many price moneys and many gifts as per the academic s
     </p>
     
    <div id="tic">
      <div class="toc">X</div>
      <div class="toc">O</div>
      <div class="toc">X</div>
      <div class="toc">O</div>
      <div class="toc">X</div>
      <div class="toc">O</div>
      <div class="toc">X</div>
      <div class="toc">O</div>
      <div class="toc">X</div>
    </div>
   </div>      
      
   <div id="q" class="xxx" style="margin:30px">
   <h1 style="font-size:60px"><u>about:-</u></h1>
     <p style="font-size:40px">project  means you are bulid an idea with some properties like tools that is the project.and first step is you do a plan for the project and desing it, after  all good result then you are do a one project.<br>
       <hr>
       <br>
       <br>
       <br>
       <div style="width:300px; height:300px; background-color:white;border:5px black solid;position: relative;float:right">
         <div style="width:150px; height:150px;background-color:lightgray;margin-left:22%;border-radius:50%"></div>
         
       <div style="width:100%; height:150px;background-color:lightgray;position:absolute;border-top-left-radius:50%;
       border-top-right-radius: 50%"></div>
       </div>
    <div>
    <p style="font-size:50px;margin-bottom:10px;">
    <b>Name</b>:S.Rakesh Kumar<br>
    <b>Date Of Birth</b>:06-02-2004<br>
    <b>State</b>: Andhra Pradesh<br>
   <b> District</b>: Krishna<br>
   </div>
   <div style="margin-top:150px">
    <table border="20px" id="tt">
        <tr style="color:red;font-size:40px">
         <th id="t">Class</th>
         <th id="t">grade</th>
         <th id="t">Completion Year</th>
       </tr> 
      <tr style="color:black;font-size:30px">
         <td id="t">10th</td>
         <td id="t">9.7</td>
         <td id="t">2019</td>
       </tr> 
        <tr style="color:black;font-size:30px">
         <td id="t">Inter</td>
         <td id="t">8.7</td>
         <td id="t">2021</td>
       </tr> 
        <tr style="color:black;font-size:30px">
         <td id="t">Btech</td>
         <td id="t">7.8</td>
         <td id="t">2025</td>
       </tr> 

     </table>
 </div>
  </div> 
  <script>
  var a=document.getElementById("ii");
  var b=document.getElementById("c");
  var c=document.getElementById("iii");

    function fun()
  {
    if(b.checked)
    {
      a.type="text";
    }
    else
    {
    a.type="password";
    }
  }
  function next()
    {
      fff.style.display="none";
      one.style.display="block";
      x.style.display="block";
      p.style.display="none";
      q.style.display="none";
      r.style.display="none";
      z.style.display="none";


      a.value="";
      c.value="";
    }
      function ab()
    {
      x.style.display="block";
      p.style.display="none";
      q.style.display="none";
      r.style.display="none";
      z.style.display="none";
      
    }
    function bc()
    {
      x.style.display="none";
      p.style.display="block";
      q.style.display="none";
      r.style.display="none";
      z.style.display="none";
    }
    function zz()
    {
      fff.style.display="block";
      one.style.display="none";
    }
    function cd()
    {
      p.style.display="none";
      r.style.display="none";
      q.style.display="block";
      z.style.display="none";
      x.style.display="none";

      
    }
    function de()
    {
      p.style.display="none";
      q.style.display="none";
      r.style.display="block";
      z.style.display="none";
      x.style.display="none";


    }
    function ef()
    {
      x.style.display="none";
      z.style.display="block";
      p.style.display="none";
      q.style.display="none";
      r.style.display="none";
    }
    
    

  </script> 
 </body>
</html>
