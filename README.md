# css-grid-for-responsive
this code is for making a responsive website
<!--
RESPONSIVE BY CSS 

-->

<html>
    <style>
        .container{
            display: grid;
            grid-gap: 1rem;
            /*grid-template-columns: 200px 100px 150px;*/
            /*justify-content: center;*/
            /*align-items: center;*/
            grid-template-columns: repeat(auto-fit , minmax(400px ,1fr))
            
        }
        .box{
            /*text-align: center;*/
            background-color: pink;
            border: 2px solid black;
            padding: 10px;
        }
    </style>
<body>
<div class="container">
    <div class="box">box1</div>
    <div class="box">box2</div>
    <div class="box">box3</div>
    <div class="box">box4</div>
    <div class="box">box5</div>
    <div class="box">box6</div>
    <div class="box">box7</div>
    <div class="box">box8</div>
    <div class="box">box9</div>
    <div class="box">box10</div>
    <div class="box">box11</div>
    <div class="box">box12</div>
    <div class="box">box13</div>
    <div class="box">box14</div>
    
    <div class="box">box14</div>
    
</div>
</body>
</html>
