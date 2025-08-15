<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
            background-color:hsl(358, 100%, 68%);
            text-align: center;
            color: aliceblue;
            height: 53px;
            padding-top: 15px;
        }
        .food-item img {
          width: 100%;
          height: 180px;
          object-fit: cover;
          border-radius: 8px;
        }
        .food-item {
            background-color: white;
          padding: 20px;
          border-radius: 8px;
          width: 250px;
          margin: 20px;
         box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
         text-align: center;
         float: left;
        }
        .food-item:hover{
            box-shadow: 0 0 20px;
        }

.btn{
    background-color:hsl(358, 100%, 68%);
    border-radius: 6px;
    height: 45px;
    color: aliceblue;
    box-shadow: 0 0 rgba(0, 0, 0, 0.1);
  
} 
.btn:hover{
    box-shadow: 0 0 rgba(0, 0, 0, 0.1);
}
body{
    margin-inline: 90px;
}
 /* footer {
    text-align: center;
    padding: 10px;
    background-color: #efdedf;
    color: rgb(18, 12, 12); 
 } */
.food-items-container {
    display: flex;
    flex-wrap: wrap; 
    justify-content: space-between;
    margin: 70px auto;
    width: 100%;
}
nav{
    width: 100px;
}
.button{
    border-radius: 15px;
    width: 400px;
    height: 36px;
    text-align: center;
    float: right ;
}
.button:hover{
    box-shadow: 0 0 rgba(0, 0, 0, 0.1);
}
.cost{
    font-size: large;
}
span{
    color: blue;
}
label{
    font-size:xx-large;
}
select{
    width: 250px;;
    height:30px;
}
nav{
    float:inline-start;
    /* background-color:hsl(358, 100%, 68%); */
            text-align:center;
            font-variant:inherit ;
            color:color-mix(in srgb, color percentage, color percentage);
            height: 15px;
            padding-top: 25px;
            font-size:larger;
          text-shadow: 0 0 rgba(13, 5, 5, 0.1); 
            /* background-color:hsl(358, 100%, 68%); */
            
        }

   
    </style>
</head>
<body>
    
    <header>
        <h1>FOOD_DELIVERY</h1>
    </header>
    <header class="nav"><nav>Home</nav>
    <nav>Tracking</nav>
    <nav>Order details</nav></header><br><br>
    <br><label for="search"><b>search:</b></label>
   <select name="Search bar" id="search bar" size="1" placeholder="jagadeesh" > 
     <option value="chicken items" >chicken item</option>
     <option value="mutton item">mutton item</option>
     <option value="veg item">veg item</option>



</select> 

    <div class="food-items-container">
    <div class="food-item">
        <img src="https://i.pinimg.com/736x/1b/a7/e7/1ba7e7bc23cc8aeb92fdd5a693418cc6.jpg" alt="Gobi manchuriyan">
        <h2>Gobi manchuriyan</h2>
        <p>Delicious cheese gobi with fresh toppings.</p>
        <p class="cost">  Rs 60/-</p>
        <!-- <h3></h3> -->
        <button class="btn" onclick="ClipboardItem">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSjhvD5rm7FVaZIvotDitBQ6JxJNJmAZSWuvg&s" alt="chicken 65">
        <h3>CHICKEN 65</h3>
        <p>Delicious chicken 65 with fresh toppings.</p>
        <p class="cost">  Rs 120/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://3.bp.blogspot.com/-f_XfCZAc9FY/UzRmFGoVLbI/AAAAAAAAGmM/o77Mp9kbFcc/s1600/IMG_0021.JPG" alt="chicken 65">
        <h3> CHICKEN KABAB</h3>
        <p>Delicious chicken kabab with fresh toppings.</p>
        <p class="cost">  Rs 100/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRK8RPOoKeHDTB0f4t6UP9CEmgDst-KTb_g4w&s" alt="chicken 65">
        <h4>Mutton Kima</h4>
        <p>Delicious mutton kima with fresh toppings.</p>
        <p class="cost">  Rs 350/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkBW7ZVabVYl8ufaKyphLM7KOELL4qQ9GpXA&s" alt="chicken 65">
        <h5>Fish Karachi</h5>
        <p>Delicious Fish karachi with fresh toppings.</p>
        <p class="cost">  Rs 190/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://img.onmanorama.com/content/dam/mm/en/food/in-season/Ramzan/Images/hyderabadi-dum-biryani.jpg.transform/576x300/image.jpg" alt="chicken 65">
        <h3>Chicken Biriyani</h3>
        <p>Delicious Chicken Biriyani with fresh toppings.</p>
        <p class="cost">  Rs 130/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://www.egginfo.co.uk/sites/default/files/styles/amp_1200x1200_1_1/public/2018/10/salmon-egg-wraps500x333.jpg?itok=8F4zeyU-" alt="chicken 65">
        <h3>EGG ROLE</h3>
        <p>Delicious egg role with fresh toppings.</p>
        <p class="cost">  Rs 55/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://c.ndtvimg.com/2022-05/pl007fjo_egg-curry_625x300_04_May_22.jpg?im=FeatureCrop,algorithm=dnn,width=620,height=350" alt="chicken 65">
        <h3>EGG CURRY</h3>
        <p>Delicious egg curry with fresh toppings.</p>
        <p class="cost">  Rs 80/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQojXLZX5nYWghAkLJosSSkaFh8_fzXrkoZqA&s" alt="chicken 65">
        <h3>Paneer Curry</h3>
        <p>Delicious Paneer Curry with fresh toppings.</p>
        <p class="cost">  Rs 155/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://cookingfromheart.com/wp-content/uploads/2017/02/Tandoori-Mushroom-Tikka-5.jpg" alt="chicken 65">
        <h3>Mushroom Tikka</h3>
        <p>Delicious Mushroom Tikka with fresh toppings.</p>
        <p class="cost">  Rs 100/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQpFq_xgoXXEHLsyR0ofvuvfMlXSqXYGAsJBQ&s" alt="chicken 65">
        <h3>Chicken Tikka</h3>
        <p>Delicious Chicken Tikka with fresh toppings.</p>
        <p class="cost">  Rs 120/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
    <div class="food-item">
        <img src="https://www.hyderabadiruchulu.com/wp-content/uploads/2020/06/Keema-Balls-Recipe-1.jpg" alt="chicken 65">
        <h3>Kima Balls</h3>
        <p>Delicious egg role with fresh toppings.</p>
        <p class="cost">  Rs 140/-</p>
        <button class="btn">ORDER NOW</button>
    </div>
     <footer>
        <p>&copy; 2024 Zomato</p>
       <p>Contact: <a href="9390868837">9390868837</a></p>



    </footer> 
    
   
</div>
</body>
</html>
