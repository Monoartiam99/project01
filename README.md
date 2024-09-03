<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Card Design</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Sevillana&display=swap');
        *{
            margin: 0;
            padding:0;
        }
        body{
            background-color: gray;
            padding: 45px;
            display: flex;

        }
        .card{
            background-color: white;
            width: 203px;
            height: 420px;
            border-radius: 15px;
            margin: 4px;
        }
        .card:nth-child(3){
            background-color: white;
            width: 180px;
            height: 420px;
            border-radius: 15px;
            margin: 4px;
        }
      
        .image{
            padding: 7px;
           
        }
        .image img{
            border-radius: 15px;
            display: flex;
            
        }
        .content{
            padding: 5px;
            font-family: 'poppins', sans-serif;
        }
        .content p {
            font-size: 13px;
            color: grey;

        }
        .capsules{
            padding: 4px;
            text-align: center;
        }
        .capsules span{
            border: 1px solid black;
            padding: 4px;
            border-radius: 7px;
            font-size: 12px;
            /* font-family: 'Sevillana', sans-serif; */
        }
        .button{
            text-align: center;
        }
        .button button{
            padding: 4px 13px;
            border-radius: 15px;
            background-color: rgb(194, 244, 234);
            color: rgb(63, 63, 206);
            font-size: 13px;
            margin-top: 4px;
            border: none;

            font-weight: bold;
        }
        h2{
            text-align: center;
        }
     </style>
</head>
<body>
    <div class="card">

        <div class="image">
         <img src="NEW.jpg" width="188" alt="">
    </div>
    <div class="capsules">
        <span>Nature</span>
        <span>Lake</span>
    </div>
    <div class="content">
        <h2>Monojit</h2>
        <p>I want to become a best engineer in world
            at first you should be a good human.
        </p>
    </div>
    <div class="button">
        <button>Read More</button>
    </div>
</div>

<div class="card">

    <div class="image">
     <img src="MONO SKETCH.jpg" width="188" alt="">
</div>
<div class="capsules">
    <span>Nature</span>
    <span>Lake</span>
</div>
<div class="content">
    <h2>Monojit</h2>
    <p>I want to become a best engineer in world
        at first you should be a good human.
    </p>
</div>
<div class="button">
    <button>Read More</button>
</div>
</div>

<div class="card">

    <div class="image">
     <img src="Mono11.jpg" width="165" alt="">
</div>
<div class="capsules">
    <span>Nature</span>
    <span>Lake</span>
</div>
<div class="content">
    <h2>Monojit</h2>
    <p>I want to become a best engineer in world
        at first you should be a good human.
    </p>
</div>
<div class="button">
    <button>Read More</button>
</div>
</div>
</body>
</html>
