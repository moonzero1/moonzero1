<!doctype>
<html>
    <head>
    <title>
        CHAT BUDDY
        </title>
        <style type="text/css">
            #round{background-color: aqua;border-bottom-left-radius: 100px;border-top-left-radius: 100px;border-top-right-radius: 100px;height: 200px;width: 200px;border-bottom-right-radius: 20px;}
                #i{
                    border-radius: 100px; height: 200px;width: 200px;
            }
            #body{background-color: bisque;margin-left: 100px;margin-right: 100px;height: auto;
            animation-name: example;
            animation-duration: 5s;animation-iteration-count: infinite;
            }
            
            #header{background-color: chocolate;height: 60px;padding-top: 3px;padding-left: 3px;}
            
            @keyframes example{
                from{background-color: red;}
                to{background-image: url(aa.jpg);}
                from{background-image: url(../Downloads/ah1.jpg);}
                to{background-image: url(../Downloads/ah2.png);background-position: right;}
                
            
                
            div{margin-top: 10px;margin-left: 10px;margin-top: 10px;margin-bottom: 10px;
            }
                
            .bar{background-color: black;width: 30px;height: 3px;
            padding-top: 3px;padding-left: 3px;border-radius: 3px;
            }
                
            .menu{height: 57px;width: 60px;background-color: aqua;padding-top: 3PX;}
            .menu:hover {background-color: azure;}
            .hid{display: none;}
            #an{animation-name: other;
            animation-duration: 5s;
            animation-iteration-count: infinite;}
                
        </style>
    </head>
    
    <body>
  <div id="header">
      <div class="menu"><div id="dot" ></div> <div id="dot" ></div> <div id="dot"></div>
</div>        </div>
        
    <div id="body">
        <div id="round">
            <img src="aa.jpg" id="i">
        </div>
        </div>
        
        <div id="an"></div>
        
    </body>
    
    </html>
