<!DOCTYPE html>
<html>
    <head>
        <title>fill form</title>
        <style>
            body{
                background-color: black; 
            }
            .one{
                display: flex;
                flex-direction:column;
                justify-content: space-evenly;
                align-items: center;
                font-size: 15px;
                vertical-align: middle;
                background-color: rgb(25, 24, 24);
                border-radius: 15px;
                padding-top: 10px;
                padding-bottom: 20px;
                background-position: center;
                margin-left: 500px;
                max-width: 600px;
                
            }
            .two{
                display: flex;
                flex-direction: column;
                justify-content: space-evenly;
                align-items: center;
                gap: 20px;
                font-size: 10px;
                color: white;
            }

            input{
                display: flex;
                justify-content: center;
                align-items: center;
                padding-top: 13px;
                padding-bottom: 13px;
                padding-left: 90px;
                font-size: 20px;
                border-radius: 10px ;
                background-color:rgba(0, 0, 0, 0.036);   
            }
        
            #three{
                width: 150px;
                height: auto;
                border-radius: 67px;
            }
            h1{
                color: white;
            }
            h4{
                color: green;
                font-size: 20px;
            }
            #four{
                color: white;
                font-size: 17;
            }
            input::placeholder{
                color: white;
            }
        </style>
    </head>
<body>
    <div class="one">
        <img id="three" src="image 444.jpg" alt="" >
        <h1>QUEEN SOLOMON</h1>
        <h4>London, United Kingdom</h4>
        <p id="four">"front-end developer and avid reader"</p>
        <div class="two">
            <input type="" placeholder="GITHUB">
            <input type="" placeholder="FRONT-END MENTOR">
            <input type="" placeholder="LinkedIn">
            <input type="" placeholder="Twitter">
            <input type="" placeholder="INSTAGRAM">
        </div>
    </div>
</body>





</html>
