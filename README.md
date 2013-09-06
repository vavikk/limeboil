Limeboil
========
Lightweight and responsive css grid system.

<h2>Usage:</h2>

Add the link to your html file: 
        `<link rel="stylesheet" type="text/css" href="limeboil.css"> `

Adding content:
---------------------
    <div class="box">       
     <div class="col-2">Some content</div>   
     <div class="col-2">Some content</div>  
    </div>    

will create 2 columns, each column will have a 50% width
Also
--------------------
`.container` - 1200px wide container  
`.w980` - width:980px  
`.w960` - hm, for some project I use 960px, can't remember why   
`.right` - will float right  
`.resp `- will make the image responsive   
`.disabled` - will disable the element  

Responsive Video (Using Iframe)
------------------------------------
`.video` - responsive video using iframe  
Use the ifrme inside the video class :          
          `<div class="video">`   
                   `<iframe src="//player.vimeo.com/video/36103466"></iframe>`     
           `</div>`   


Example:
---------------------
[Example1](http://vitaliejerebnii.com/experiments/limeboil/)  

Thanks:
---------------------
Inspired by Lemonade grid system.
https://github.com/dope/lemonade
