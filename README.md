# Working-of-Side-bars
Detailed working of Side bars in HTML&amp;CSS 
<!DOCTYPE html>
<html>
    <head>
        <style>
            #head{
                background-color: aquamarine;
                height:75px;
                margin:10px;
            }
            #nav{
                background-color: aquamarine;
                height:40px;
                margin:10px;
                
            }
            .main{
                color:black;
                font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                font-size: medium;
                border-color:black;
                border-width:4px;
                background-color:aquamarine;
                padding:20px 20px 20px 20px;
                width:1000px;
                margin-bottom:10px;
                height:270px;
                margin-right:10px;
                
                
            }
            .main:hover{
                opacity:0.7;
                transition:opacity 1s ease-in-out;
            }
            
            .rightside{
                font-family: Arial, Helvetica, sans-serif;
                padding:15px 15px 15px 15px;
                float:right;
                width:350px;
                background-color: aquamarine;
                color:black;
                margin:10px;
                height:275px;
                margin-top:0px;
            }
            .rightside:hover{
                opacity:0.5;
            }
            .imageright{
                float:right;
                width:400px;
                margin-left:10px;
                
            }
            .imageright:hover{
                opacity:0.5;
                transition:opacity 1s ease-in-out;
            }
            body{
                background:linear-gradient(pink,yellow);
            }
            #nav ul{
                text-align: center;
                
            }
            #nav li{
                display:inline;
                margin:130px;

            
            }
            #nav li a{
                list-style-type:none;
                text-decoration:none;
                color:black;
                background-color: blue;


            }
            a:hover{
                background-color:whitesmoke;
            }
            #head{
                text-align: center;
                margin-top:0px;
                font-size: larger;
                font-weight: bold;
                position:inherit;
            }
            .footer{
                background-color: aquamarine;
                height:50px;
                clear:both;
                text-align: center;
            }

        </style>
    </head>
    <body>
        <div id="head">
            <h1>Sundar's Bio</h1>

        </div>
        <div id="nav">
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">About Us</a></li>
                <li><a href="">Support</a></li>
                <li><a href="">Contact US</a></li>

            </ul>

        </div>
        <div class="rightside">
            <h2>Lecture Timings:---</h2>
            <p>1st Lecture:11:30Am</p>
            <p>2nd Lecture:11:30Am</p>
            <p>3rd Lecture:11:30Am</p>
            <p>4th Lecture:11:30Am</p>
        </div>
        <div class="main">
            <h2>The CEO of Google...</h2>
            <p>Sundar Pichai, in full Pichai Sundararajan, (born June 10, 1972, Madras [now Chennai], Tamil Nadu, India), Indian-born American executive who was CEO of both Google, Inc. (2015– ), and its holding company, Alphabet Inc. (2019– ).

                As a boy growing up in Madras, Pichai slept with his brother in the living room of the cramped family home, but his father, an electrical engineer at the British multinational GEC, saw that the boys received a good education. At an early age Pichai displayed an interest in technology and an extraordinary memory, especially for telephone numbers. After earning a degree in metallurgy (B.Tech., 1993) and a silver medal at the Indian Institute of Technology Kharagpur, he was awarded a scholarship to study at Stanford University (M.S. in engineering and materials science, 1995). He remained in the United States thereafter, working briefly for Applied Materials (a supplier of semiconductor materials) and then earning an M.B.A. (2002) from the Wharton School of the University of Pennsylvania.</p>
          
        </div>
        <div class="imageright">
            <img src="sundar.jpg">
        </div>
        
        <div class="main">
            <h2>The CEO of Google...</h2>
            <p>Sundar Pichai, in full Pichai Sundararajan, (born June 10, 1972, Madras [now Chennai], Tamil Nadu, India), Indian-born American executive who was CEO of both Google, Inc. (2015– ), and its holding company, Alphabet Inc. (2019– ).

                As a boy growing up in Madras, Pichai slept with his brother in the living room of the cramped family home, but his father, an electrical engineer at the British multinational GEC, saw that the boys received a good education. At an early age Pichai displayed an interest in technology and an extraordinary memory, especially for telephone numbers. After earning a degree in metallurgy (B.Tech., 1993) and a silver medal at the Indian Institute of Technology Kharagpur, he was awarded a scholarship to study at Stanford University (M.S. in engineering and materials science, 1995). He remained in the United States thereafter, working briefly for Applied Materials (a supplier of semiconductor materials) and then earning an M.B.A. (2002) from the Wharton School of the University of Pennsylvania.</p>
          
        </div>
        <div class="footer">
            &c;Sundar.ac.in All rights reserved

        </div>
        
        

    </body>
</html>
