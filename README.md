<!DOCTYPE html>
<html lang="en">

<head>
  <title>Github pages</title>
  <style>
    .item1 {
      grid-area: header;
    }

    .item2 {
      grid-area: menu;
    }

    .item3 {
      grid-area: main;
    }

    .item4 {
      grid-area: right;
    }

    .item5 {
      grid-area: footer;
    }

    .grid-container {
      display: grid;
      grid-template-areas:
        'header header header header header header'
        'menu main main main right right'
        'menu footer footer footer footer footer';
      grid-gap: 10px;
      background-color: #2196F3;
      padding: 10px;
    }

    .grid-container>div {
      background-color: rgba(255, 255, 255, 0.8);
      text-align: center;
      padding: 20px 0;
      font-size: 30px;
    }
  </style>
</head>

<body>

  <h1>Likes and dislikes</h1>

  <p>Majority of the things that i like are edible. However, that does not mean i eat almost everything because i am
    also a picky eater:</p>

  <div class="grid-container">
    
    <div class="item2">Dislikes
      <ul>
        <li>Fish</li>
        <li>Eggs</li>
    </div>
    
    <div class="item1">Likes</div>
    <div class="item3">Cars<br>
      <p> I am a car fanatic. My favourite models are Chevrolet,Toyota, Dodge and Opel. When it comes to car size i pick
        SUVs over all other sizes.If you are contemplating on buying a car, i recommend using this website:
        <a href="https://www.cars.com/">Cars.com </a>
      </p>
    </div>
    <div class="item4">Images:<br>
      <img src="https://www.chevrolet.com/content/dam/chevrolet/na/us/english/index/vehicle-groups/suv/01-images/2021-suvs-blazer.jpg"
      alt="SUV">
    </div>
    <div class="item5">Author
      <p>Deliverance Right<br>
        email:deliveranceright@gmail.com</p>
    </div>
  </div>

</body>

</html>
