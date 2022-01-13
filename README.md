# Web Page for Mathematical Calculations

## AIM:

To design a static website with validation to perform mathematical calculations in client side.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Write javascript to perform the calculations.

### Step 4:

Include regularexpression based input validation.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
~~~

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Volume and Area</title>
    <style>
   
        .container1{
            background-size: 700px 500px ;
            width: 700px;
            height: 400px;
            text-align: center;
            border-style: solid;
            border-color: white;
            margin-left: 300px;
            display: inline-block;
            
            
        }
        .container2{
            
            width:700px;
            height:400px;
            text-align:center;
            border-style: solid;
            border-color: white;
            margin-left: 300px;
            margin-top: 10px;
        }
        body{
            /*background-image: url("https://i.pinimg.com/564x/55/73/57/55735706337f12b8125b73af8abe8302.jpg");*/
            background-image: url("https://www.helloscholar.in/wp-content/uploads/2020/10/chalk-rubbed-out-blackboard_34170-30.jpg");
            background-repeat: no-repeat;
            background-size: cover;
            
        }
        .intext{
            color:white;
            font-size: medium;
            font-family: sans-serif;
        }
        .img1{
            width:400px;
            height:200px;
            padding-right:100px;
            padding-top:10px;
        }
        .inele{
            margin-top: 5px;
            margin-bottom: 5px;
        }
        .inele1{
            margin-top: 2px;
            margin-bottom: 2px;
        }
        .labeltext{
            font-size: 20px;
            font-weight: 700;
        }
        .button{
            font-size: 15px;
            font-weight: 700;
        }
        h2{
            font-weight: 700;
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        h1{
            font-size: 50px;
            margin-left: 400px;
            font-weight: 700;
            text-decoration: underline;
            color: white;
            
        }
        .img2{
            width:400px;
            height:150px;
            padding-right:100px;
            padding-top:10px;

        }
        .foot{
              
            width:400px;
            height:50px;
            text-align:center;
            
            margin-left: 720px;
            margin-top: -30px;
            color: white;
        }
 
        

    </style>
</head>
<body>
    <h1>MatheMatical Calculator</h1>
        <div class="container1">
            <div class="intext">
                <h2><u>Volume of a Pyramid Calculator</u></h2>

                <form>
                    <div class="inele">
                    <label class="labeltext">Base:</label>
                    <input type="number" id="base1">
                    <label class="labeltext">Centimeters</label><br>
                    </div>
                    <div class="inele">
                    <label class="labeltext">Height:</label>
                    <input type="number" id="height1">
                    <label class="labeltext">Centimeters</label><br>
                    </div>
                    <div class="inele">
                    <input class ="button "type="button" id="button1" value="calculate Volume"><br>
                    </div>
                    <div class="inele">
                    <label class="labeltext">Volume:</label>
                    <input type="number" id="Pvolume" readonly>
                    <label class="labeltext">Centimeters<sup>3</sup></label>
                    </div>
                </form>
                <img class="img1" src="https://res.cloudinary.com/dk-find-out/image/upload/q_70,c_pad,w_1200,h_630,f_auto/pyramid_icon_takzpx.jpg">
            </div>

        
        </div>
        <div class="container2">
            <div class="intext">
                <h2><u>Volume of a Cone Calculator</u></h2>
                <form>
                    <div class="inele">
                    <label class="labeltext">Radius:</label>
                    <input type="number" id="Cradius">
                    <label class="labeltext">Centimeters</label><br>
                    </div>
                    <div class="inele">
                    <label class="labeltext">Height:</label>
                    <input type="number" id="cheight">
                    <label class="labeltext">Centimeters</label><br>
                    </div>
                    <div class="inele">
                    <input class="button" type="button" id="button2" value="Calculate Volume"><br>
                    </div>
                    <div class="inele">
                    <label class="labeltext">Volume:</label>
                    <input type="number" id="Cvolume" readonly>
                    <label class="labeltext">Centimeters<sup>3</sup></label>
                    </div>
                </form>
                <img class="img1" src="https://lh5.googleusercontent.com/rg1O0RO923cafYg30FdeNYZuSnbTvAhjc-FpPcrr0MsJKD2SaL--vRvCK_WT1lRdaUppekBPWyuvRbyrxVGtzBc=w1280">
            
            </div>

        </div>
        <div class="container2">
            <div class="intext">
            <form>
                <h2><u>Volume of Prism Calculator</u></h2>
                <div class="inele1">
                    <label class="labeltext">Base Area:</label>
                    <input type="number" id="basearea">
                    <label class="labeltext">Centimeters<sup>3</sup></label><br>
                </div>
                <div class="inele1">
                    <label class="labeltext">Height:</label>
                    <input type="number" id="Prheight">
                    <label class="labeltext">Centimeters<sup>3</sup></label><br>
                </div>
                <div class ="inele1">
                    <label class="labeltext">Length:</label>
                    <input type="number" id="length">
                    <label class="labeltext">Centimeters<sup>3</sup></label><br>
                </div>
                <div class="inele1">
                    <input class="button" type="button" id="Pbutton" value="Calculat Volume"><br>
                </div>
                <div  class="inele1">
                    <label class="labeltext">Volume:</label>
                    <input type="number" id="Prvolume" readonly>
                    <label class="labeltext">Centimeters<sup>3</sup></label>
                </div>

            </form>
            <img class="img2" src="https://res.cloudinary.com/dk-find-out/image/upload/q_70,c_pad,w_1200,h_630,f_auto/prism_icon_mgjkm4.jpg">
        </div>
        <div class="foot">
        
           <h3> Developed by Koduru Sanath Kumar Reddy</h3>
       
        </div>
        
    <script type="text/javascript">
        document.querySelector("#button1").addEventListener("click",function(){
            var base,height,pvolume;
            base = document.querySelector("#base1");
            height = document.querySelector("#height1");
            pvolume = document.querySelector("#Pvolume");
            var basevalue = base.value;
            var heightvalue = height.value;
            regbase = base.value.match("^[.]?[0-9]+[.]?[0-9]*$");
            regheight = height.value.match("^[.]?[0-9]+[.]?[0-9]*$");
            resultbase = base.value.match(regbase);
            resultheight = height.value.match(regheight);
            if(resultbase==null){
                alert("Invalid Pyramid Base value!!");
            }else if(resultheight==null){
                alert("Invalid Pyramid Height value!!")
            }else{
                pvolume.value = 1/3*basevalue*heightvalue;
            }           
        })
        document.querySelector("#button2").addEventListener("click",function(){
            var radius1,height1,volume1;
            radius1 = document.querySelector("#Cradius");
            cheight = document.querySelector("#cheight");
            volume1 = document.querySelector("#Cvolume");
            var radius1value = parseInt(radius1.value);
            var cheightvalue = parseInt(cheight.value);
            radius1match = radius1.value.match("^[.]?[0-9]+[.]?[0-9]*$");
            cheightmatch = cheight.value.match("^[.]?[0-9]+[.]?[0-9]*$");
            radius1result = radius1.value.match(radius1match);
            height1result = cheight.value.match(cheightmatch );


            if(radius1result==null){
                alert("Invalid Cone Radius value!!");
            }else if(height1result==null){
                alert("Invalid Cone Height value!!")
            }else{
                volume1.value= 3.14*radius1.value*radius1.value*cheight.value/3;
            }    

        })
        document.querySelector("#Pbutton").addEventListener("click",function(){
            var basearea, prheight,prvolume,length;
            basearea = document.querySelector("#basearea");
            prheight = document.querySelector("#Prheight");
            prvolume = document.querySelector("#Prvolume");
            length = document.querySelector("#length");
            var baseareavalue = parseInt(basearea.value);
            var prheightvalue = parseInt(prheight.value);
            var lengthvalue = parseInt(length.value);
            lengthmatch = length.value.match("^[.]?[0-9]+[.]?[0-9]*$");
            basematch = basearea.value.match("^[.]?[0-9]+[.]?[0-9]*$");
            heightmatch = prheight.value.match("^[.]?[0-9]+[.]?[0-9]*$");
            baseresult = basearea.value.match(basematch);
            heightresult = prheight.value.match(heightmatch);
            lengthresult = length.value.match(lengthmatch);
            if(baseresult==null){
                alert("Invalid Prism Base value!!")
            }else if(heightresult==null){
                alert("Invalid Prism Height value!!")
            }else if(lengthresult==null){
                alert("Invalid Prism Length value!!")
            }else{
                prvolume.value = 1/2*baseareavalue*prheightvalue*lengthvalue;
            }

        })
    </script>

    
</body>
</html>
~~~
## OUTPUT:
![output1](math1.png)
![output2](math2.png)

## Result:

Thus a website is designed to perform mathematical calculations in the client side.
