
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    
        
}
body{
    background-color: hsl(241, 100%, 89%);
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh; 
    text-align: center;

   }
   
    

.container{
    background: hsl(252, 100%, 48%);
    padding: 30px;
    color: white;
    border-radius: 20px 20px;
    width:240px;
    height: 350px;
position:  relative ;
left: 20px;

}
    .your{
    border-radius: 2px;
}
.yourresult{
    font-size: 20px;
    color: hsl(220, 23%, 95%);
    opacity: 0.8;
}
.score{
    background-color: hsl(241, 81%, 36%);
border-radius: 50%;
width: 130px;
height: 140px;
margin: 33px;
color: wheat;
}
.nambre{
    font-weight: bold;
    color: rgb(255, 255, 255);
    font-size: 50px;
    text-align: center;
    padding-top: 30px;

}


.of{
font-weight: bold;
font-size: 10px;
    opacity: 0.4;

}

.Great{
    font-weight: bold;
font-size: 20px;
height: 20px;
line-height: 3px;


}

.you{
    font-size: 10px;
    word-spacing: 1px;
    width: 200px;
    opacity: 0.4;

}
.containerscorebord{
    background-color: hsl(221, 100%, 96%);
    width:240px;
    height: 350px;
    border-radius: 0px 20px 20px 0px;
    font-weight: bold;
margin-right: 20px;
    
}
.summary{
    text-transform: capitalize;
text-align: left;
padding-left: 50px;
padding-top: 30px;
font-size: 20px;

}
.Reaction{
    background-color: hsla(256, 72%, 93%, 1);
    display: flex;
    border-radius: 10px;
    margin-top: 10px;
    margin-left: 30px;
    align-items:center;
    width: 200px;
    height: 40px;
    padding-left: 10px;
    color: hsl(0, 100%, 67%);

}
.Memory{
    background-color: hsla(256, 72%, 93%, 1);
    display: flex;
    border-radius: 10px;
    margin-top: 10px;
    margin-left: 30px;
    align-items:center;
    width: 200px;
    height: 40px;
    padding-left: 10px;
    color: hsl(39, 100%, 56%);

}

.Verbal{
    background-color: hsla(256, 72%, 93%, 1);
display: flex;
border-radius: 10px;
margin-top: 10px;
margin-left: 30px;
align-items:center;
width: 200px;
height: 40px;
padding-left: 10px;
color: hsl(166, 100%, 37%);

}
.Visual{
    background-color: hsla(256, 72%, 93%, 1);
display: flex;
border-radius: 10px;
margin-top: 10px;
margin-left: 30px;
align-items:center;
width: 200px;
height: 40px;
padding-left: 10px;
color: hsl(234, 85%, 45%);
}

.Continue{
background-color:hsla(256, 72%, 46%, 1);
width: 180px;
height: 35px;
margin-top: 25px;
margin-left: 30px;
border-radius: 20px;
font-size: 15px;
color:wheat;
}


@media screen and (max-width: 768px) {
    body {
        flex-direction: column; /* يجعل العناصر الأب تحت بعض */
        align-items: center; /* توسيط العناصر */
        width: 90%;
    }
  .containerscorebord{
    margin-left: 60px;
    border-radius: 0px 0px 20px 20px;

  }
  .container{
z-index: 1;
    margin: -20px; 

margin-top: 40px;
}
.Reaction{
    margin-left: 25px;
}
.Memory{
    margin-left: 25px;

}
.Verbal{
    margin-left: 25px;

}
.Visual{
    margin-left: 25px;
 
}
.Continue{
    margin-left: 25px;

}
.score{
    margin-left: 25px;

}
.summary{
    margin-left: -20px;

}
}

