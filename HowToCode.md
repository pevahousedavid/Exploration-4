﻿# Exploration-4
 
 These are the steps and code I used to figure out how to use LESS
 
 first I had to install LESS on my machine and server, using this line npm install -g less
 
 Then the compilier ahd to be called using the line lessc styles.less when I have added things.
 
 To test I added  .box {
        color: #fe33ac;
        border-color: #fdcdea;
    }
    .box div {
        -webkit-box-shadow: 0 0 100px rgba(0, 0, 0, 0.3);
        box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);
  
  as well as adding this line to make sure it worked <link rel="stylesheet/less" type="text/css" href="styles.less" />
  
  Though I could not get the compilier to tell me I did something wrong, I could not get the css to show up using less
