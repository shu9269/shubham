# shubham
<!DOCTYPE html>
<html>
<title>Assignment</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body{
height: 100%;
color:blue;
    
}
html {
  height: 100%;
 
}

.bgimg {
  background-position: center;
  background-size: cover;
  background-image: url("https://media-cdn.tripadvisor.com/media/photo-s/04/29/3e/30/eden-pavilion-restaurant.jpg");
  min-height: 75%;
}

.menu {
  display: none;
}

header {
   color:red;
   font-size:40px;
}
.w3-top h1{
   background-color:gray;
   padding:30px 30px;
}

w3-col s3{
  
   padding:20px 20px;
   barder:10px 10px;
}

footer{
 background-color:gray;
 padding:30px;
 color:red;
 }

</style>
<body>


<div class="w3-top"  >
    <h1 style="float:left">
      <a href="#" >HOME</a>
     </h1>
     <h1 style="float:left">
      <a href="#about" >ABOUT</a>
     </h1>
     <h1 style="float:left">
      <a href="#menu" >MENU</a>
     </h1>
     <h1 >
      <a href="#where" >WHERE</a>
     </h1>
</div>


<header class="bgimg " id="home">
   
  <h1>My<br>Cafe</h1>
  
</header>

    <h5><span style="color:red" "font-size:40">ABOUT THE CAFE</span></h5>
    <p>A café is a type of restaurant which typically serves coffee and tea, in                 addition  to light refreshments such as baked goods or snacks. The term "café"         comes from the French word meaning "coffee".</p>

    <p>A café setting is known as a casual social environment where you can find people        reading newspapers and magazines, playing board games, studying or chatting with          others about current events. It is known also regarded as a place where                information can be exchanged..</p>
    <p>In addition to our full espresso and brew bar menu, we serve fresh made-to-order           breakfast and lunch sandwiches, as well as a selection of sides and salads             and other good stuff.</p>
    
    <p><i>"Use products from nature for what it's worth - but never too early, nor             too late." Fresh is the new sweet.</i></p>
     
      </div>
    <img src="https://media-cdn.tripadvisor.com/media/photo-s/18/55/29/64/j-c-s-star-cafe.jpg" style="width:70%;max-width:700px" class="w3-margin-top">
    <img src="https://www.thelalit.com/wp-content/uploads/2020/09/IRD.jpg"style="width:70%;max-width:700px" class="w3-margin-top">
    <p><strong>Opening hours:</strong> Everyday from 6am to 10pm.</p>
    <p><strong>Address:</strong> 15 food street Shahpura, 501</p>
  </div>

<!-- Menu Container -->
<div class="container" id="menu">
  <div class="content" style="max-width:700px">
 
    <h1 style="color:green"> THE MENU</h1>
  
    <div style="color:red">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Eat');" id="myLink">
        <div class="w3-col s6 tablink">Eat</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Drinks');">
        <div class="w3-col s6 tablink">Drink</div>
      </a>
    </div>

    <div id="Eat" >
      <h2>Bread Basket</h2>
      <p>Assortment of fresh baked fruit breads and muffins Rs.50</p><br>
    
      <h2>Honey Almond Granola with Fruits</h2>
      <p>Natural cereal of honey toasted oats, raisins, almonds and dates Rs.70</p><br>
    
      <h2>Belgian Waffle</h2>
      <p>Vanilla flavored batter with malted flour Rs.100</p><br>
    
      <h2>Scrambled eggs</h2>
      <p>Scrambled eggs, roasted red pepper and garlic, with green onions Rs.120</p><br>
    
      <h2>Blueberry Pancakes</h2>
      <p class="w3-text-grey">With syrup, butter and lots of berries Rs.150</p>
    </div>

    <div >
      <h2>Coffee</h2>
      <p>Regular coffee Rs.50</p><br>
    
      <h2>Chocolato</h2>
      <p>Chocolate espresso with milk Rs.40</p><br>
    
      <h2>Corretto</h2>
      <p>Whiskey and coffee Rs.55</p><br>
    
      <h2>Iced tea</h2>
      <p>Hot tea, except not hot Rs.45</p><br>
    
      <h2>Soda</h2>
      <p>Coke, Sprite, Fanta, etc. Rs.20</p>
    
</div>
<div>
    <img src="http://hungrylobbyist.com/wp-content/uploads/2018/05/587559ecf10a9a1d008b7c0f-960-720-960x500.jpg">
  </div>
<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
  <div class="w3-content" style="max-width:700px">
    <h1 style="background-color:red">WHERE TO FIND US</h1>
    <p><b>Find us at some address at some place.</b></p>
    <img src="https://previews.123rf.com/images/karpenyuk/karpenyuk1602/karpenyuk160200696/53241609-cartoon-map-seamless-pattern-roads-cars-and-houses-.jpg"  style="width:100%">
    <p><span class="w3-tag">FYI!</span> We offer full-service catering for any event, large or small. We understand your needs and we will cater the food to satisfy the biggerst criteria of them all, both look and taste.</p>
    <p><strong>Reserve</strong> a table, ask for today's special or just send us a message:</p>
    <form>
      <p><input type="text" placeholder="Name" required name="Name"></p>
      <p><input  type="number" placeholder="How many people" required name="People"></p>
      <p><input  type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
      <p><input  type="text" placeholder="Message \ Special requirements" required name="Message"></p>
      <p><button type="submit">SEND MESSAGE</button></p>
    </form>
  </div>
</div>

</div>

<footer  >
  <h4>Contact us</h4>
     <ul><strong>phone no:</strong>8756498757,9758346427</ul>
     <ul><p><strong>Address:</strong> 15 food street, Shahpura Bhopal</p></ul>
</footer>

<script>

function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
    }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" ", "");
   }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
