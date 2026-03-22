<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Donut Lovers</title>
  <style>
    html {
      scroll-behavior: smooth; 
    }
  </style>
</head>
<body>
  <header>
    <h1>Donut Lovers</h1>
    <p>Life is better with fillings</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#flavors">Flavors</a>
  </nav>

<section id="home">
  <h2>Home</h2>
  <p><strong>Welcome Donut Lovers!</strong></p>
  <p><strong>Your sweet journey starts here!</strong></p>
        <p><strong>Fun fact: did you know?</strong></p>
        <p>
          Donuts actually have a fascinating history — the ring shape we all know today was popularized in the mid‑1800s by a sailor named Hanson Gregory, who claimed he cut a hole in the middle so the dough would cook evenly. Since then, donuts have become a global treat, with countless variations from the American glazed classic to Japan’s matcha‑flavored creations. In fact, donuts are so beloved that the United States celebrates National Donut Day every June, a tradition that started in 1938 to honor volunteers who served donuts to soldiers during World War I.
        </p>
        <p>
          Welcome to Donut Lovers — your sweet escape into the world of donuts! From the timeless charm of a classic glazed to the rich indulgence of chocolate‑filled and the unique twist of gourmet matcha, every bite is a circle of joy. Our mission is simple: to share tips, guides, and flavors that brighten your day and bring donut enthusiasts together. Whether you’re here to explore, learn, or simply enjoy, Donut Lovers is your home for all things deliciously round.
        </p>
        <p>
         Explore different kinds of donuts from around the world.
        </p>

</section>


  <section id="flavors">
    <h2>Flavors</h2>
    <p><strong>There are a lot of fillings and toppings you can add to your donut. Just select one and then submit it!</strong></p>
    <form action="/submit-flavor" method="post">
      <label for="flavor">Choose your flavor:</label>
      <select id="flavor" name="flavor">
        <option value="chocolate">Chocolate</option>
        <option value="strawberry">Strawberry</option>
        <option value="vanilla">Vanilla</option>
        <option value="blueberry">Blueberry</option>
      </select>
      <br><br>
      <button type="submit">Submit Flavor</button>
    </form>
  </section>

  <footer>
    <p> 2026 — All donuts are yours!</p>
  </footer>
</body>
</html>
