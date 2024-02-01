<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
         header {
            display: flex;
            background-color: #333;
            color: white;
            padding: 1em;
            width: 773px;
            margin-left: 350px;
            justify-content: center;
        }
        .main{
            border: 3px black solid;
            width: 800px;
            margin-left:  350px;
            background-color: yellow;
           padding-bottom: 15px;
        }
        .first,.six,.seven{
            display: flex;
            justify-content: center;
            text-decoration: underline;
        }
        h2{
            background-color: red;
            display: block;
            padding: 5px;
            color: black;
        }
        img{
            border: 2px solid black;
            border-radius: 50px;
        }
        .fifth{
            padding: 3px;
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
        }
        h3{
            padding: 10px;
        }
        .Bf,.m,.s{
           display: grid;
           grid-template-columns: repeat(3,1fr);
        }
    </style>
</head>
<body>
    <header>
        <h1>MENU CARD</h1>
    </header>
    <div class="main">   
    <div class="first">
        <h2> BREAKFASTS </h2>
    </div>
    <div class="Bf"> 
    <div class="fifth">
        <img src="https://m.economictimes.com/thumb/msid-99118050,width-1200,height-900,resizemode-4,imgsize-64776/idli_istock.jpg" alt="idly" height="100px" width="100px"/>
        <h3>Idly:40/-</h3>
    </div>
    <div class="fifth">
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Dosa_at_Sri_Ganesha_Restauran%2C_Bangkok_%2844570742744%29.jpg" alt="dosa" height="100px" width="100px"/>
        <h3>Dosa:50/-</h3>
    </div>
    <div class="fifth">
         <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQO95d9m6g5wKZzALaZTP8GD5-Bo6rw1XyLq2P1VJBppg&s" alt="puri" height="100px" width="100px"/>
         <h3>Puri:40/-</h3>
    </div>
    <div class="fifth">
        <img src="https://www.dwarakaorganic.com/wp-content/uploads/2022/04/Upma.jpg" alt="upma" height="100px" width="100px"/>
        <h3>Upma:30/-</h3>
    </div>
    <div class="fifth">
        <img src="https://bonmasala.com/wp-content/uploads/2022/12/medu-vada-recipe.webp" alt="vada" height="100px" width="100px"/>
        <h3>Vada:30/-</h3>
    </div>
    </div>
    <div class="six">
        <h2> STARTERS </h2>
    </div>
    <div class="s">
        <div class="fifth">
            <img src="https://cdn.tarladalal.com/members/9306/procstepimgs/corn-cheese-balls-(21)-11-187702.jpg" alt="idly" height="100px" width="100px"/>
            <h3>Corn Balls:80/-</h3>
        </div>
        <div class="fifth">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSYmjU-bR9IMVfptq7fS-vjFXw_C1322XXt6g&usqp=CAU" alt="dosa" height="100px" width="100px"/>
            <h3>Manchuria:60/-</h3>
        </div>
        <div class="fifth">
             <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2019/06/vegetable-soup-500x375.jpg" alt="puri" height="100px" width="100px"/>
             <h3>soup:90/-</h3>
        </div>
        <div class="fifth">
            <img src="https://thecozycook.com/wp-content/uploads/2020/02/Copycat-McDonalds-French-Fries-.jpg" alt="upma" height="100px" width="100px"/>
            <h3>Fries:100/-</h3>
        </div>
        <div class="fifth">
            <img src="https://www.cookwithmanali.com/wp-content/uploads/2015/07/Restaurant-Style-Recipe-Paneer-Tikka.jpg" alt="vada" height="100px" width="100px"/>
            <h3>Paneer Tikka:120/-</h3>
        </div>
        </div>
    <div class="seven">
        <h2> MEALS </h2>
    </div>
    <div class="m">
    <div class="fifth">
        <img src="https://www.indianveggiedelight.com/wp-content/uploads/2020/04/veg-biryani-instant-pot.jpg" alt="idly" height="100px" width="100px"/>
        <h3>Biryani:250/-</h3>
    </div>
    <div class="fifth">
        <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2020/12/fried-rice.jpg" alt="dosa" height="100px" width="100px"/>
        <h3>Fried Rice:250/-</h3>
    </div>
    <div class="fifth">
         <img src="https://3.bp.blogspot.com/-6KrKB-VtwGM/V3pl5bG1MNI/AAAAAAAAOA8/BjFtDQUpSH8z_m9qr2mjv7Zhx-9gnvrngCLcB/s1600/IMG_0229%2Bcopy.jpg" alt="puri" height="100px" width="100px"/>
         <h3>Pulihora:150/-</h3>
    </div>
    <div class="fifth">
        <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2022/02/curd-rice-thayir-sadam.jpg" alt="upma" height="100px" width="100px"/>
        <h3>Curd Rice:100/-</h3>
    </div>
    <div class="fifth">
        <img src="https://www.yummytummyaarthi.com/wp-content/uploads/2012/03/6885797918_9ec7ced19a_b.jpg" alt="vada" height="100px" width="100px"/>
        <h3>Pudina Rice:150/-</h3>
    </div>
    </div>
    </div>
</body>
</html>
