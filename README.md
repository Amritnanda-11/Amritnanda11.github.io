# Amritnanda11.github.io
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Barbil City Explorer - By Amrit Nanda of Jindal School Class 9B</title>
  <style>
    /* Reset & Neon theme */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      transition: all 0.3s ease-in-out;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0d0d0d;
      color: #e0eaff;
      min-height: 100vh;
      overflow-x: hidden;
      padding: 1.5rem;
    }

    a {
      color: #39ff14;
    }

    .neon-text {
      color: #39ff14;
      text-shadow: 0 0 5px #39ff14, 0 0 10px #39ff14, 0 0 20px #39ff14,
        0 0 40px #00ff00;
    }

    h1,
    h2 {
      text-align: center;
      margin-bottom: 1rem;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 0;
    }

    .author-name {
      font-size: 1.3rem;
      color: #a0fbbf;
      margin: 0 0 1.5rem 0;
      text-align: center;
      text-shadow: 0 0 5px #17ff4e;
      font-weight: 600;
    }

    h2 {
      font-size: 2.3rem;
      border-bottom: 2px solid #39ff14;
      display: inline-block;
      padding-bottom: 0.3rem;
      margin-bottom: 2rem;
      color: #39ff14;
      text-shadow: 0 0 6px #39ff14;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 1rem;
      margin-bottom: 2rem;
      flex-wrap: wrap;
    }

    nav button {
      background: none;
      border: 2px solid #39ff14;
      color: #39ff14;
      padding: 0.5rem 1.2rem;
      border-radius: 30px;
      cursor: pointer;
      font-weight: 700;
      font-size: 1.1rem;
      transition: all 0.3s ease;
    }

    nav button:hover,
    nav button.active {
      background-color: #39ff14;
      color: #0d0d0d;
      box-shadow: 0 0 15px #39ff14, 0 0 40px #00ff00;
    }

    section.category {
      display: none;
      max-width: 1000px;
      margin: 0 auto 3rem;
      background: #121217;
      padding: 1.5rem 2rem;
      border-radius: 15px;
      box-shadow: 0 0 20px #39ff1422, inset 0 0 20px #00ff0044;
      color: #aafdb3;
    }

    section.category.active {
      display: block;
    }

    ul.shop-list {
      list-style: none;
      font-size: 1.1rem;
      margin-bottom: 1rem;
      padding-left: 1rem;
    }

    ul.shop-list li {
      margin-bottom: 12px;
    }

    img.place-img {
      width: 45%;
      height: 200px;
      object-fit: cover;
      border: 3px solid #39ff14;
      border-radius: 12px;
      margin: 0.5rem;
      box-shadow: 0 0 15px #39ff1466;
    }

    div.img-container {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin-bottom: 1rem;
    }

    iframe.map {
      display: block;
      margin: 1rem auto;
      width: 95%;
      height: 300px;
      border: 3px solid #39ff14;
      border-radius: 12px;
      box-shadow: 0 0 15px #39ff14bb;
    }

    #weather-info {
      color: #aafdb3;
      font-weight: 700;
      font-size: 1.2rem;
      text-align: center;
      margin-top: 20px;
      text-shadow: 0 0 7px #39ff14bb;
    }

    footer {
      text-align: center;
      padding: 1rem;
      color: #39ff14;
      font-weight: 700;
      border-top: 2px solid #39ff14;
      margin-top: 3rem;
      font-size: 1rem;
      text-shadow: 0 0 6px #39ff14bb;
    }
  </style>
</head>

<body>
  <header>
    <h1 class="neon-text">Barbil City Explorer</h1>
    <div class="author-name">By Amrit Nanda of Jindal School Class 9B</div>
    <p style="text-align:center; margin-bottom:2rem;">
      Discover Barbil’s best tourist spots and essential markets, all in one place!
    </p>
    <nav>
      <button class="active" onclick="showCategory('tourist')">Tourist Places</button>
      <button onclick="showCategory('grocery')">Grocery & Supermarkets</button>
      <button onclick="showCategory('apparel')">Apparel Shops</button>
      <button onclick="showCategory('electronics')">Electronics</button>
      <button onclick="showCategory('restaurants')">Restaurants</button>
      <button onclick="showCategory('beauty')">Beauty Parlours</button>
      <button onclick="showCategory('others')">Other Shops</button>
    </nav>
  </header>

  <section id="tourist" class="category active" tabindex="0">
    <h2>Top Tourist Places Around Barbil</h2>

    <article>
      <h3>Murga Mahadev Waterfalls</h3>
      <div class="img-container">
        <img src="[translate:https://upload.wikimedia.org/wikipedia/commons/b/bf/Shiva_Temple_at_Barbil_Odisha.jpg]" alt="Murga Mahadev Temple" class="place-img" />
        <img src="[translate:https://upload.wikimedia.org/wikipedia/commons/f/f7/Shiv_Temple_Barbil.jpg]" alt="Murga Mahadev Waterfall" class="place-img" />
      </div>
      <p>A blend of nature and spirituality, located amidst forests with twin waterfalls from Thakurani Hills.</p>
      <iframe class="map" title="Murga Mahadev Waterfalls" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.691762023033!2d85.59583121533484!3d22.080139342198834!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a2720a0a8e2377b%3A0x2cdd2cec07dd539f!2sMurga%20Mahadev%20Temple!5e0!3m2!1sen!2sin!4v1698087400000!5m2!1sen!2sin"></iframe>
    </article>

    <article>
      <h3>Khandadhar Waterfalls</h3>
      <div class="img-container">
        <img src="[translate:https://upload.wikimedia.org/wikipedia/commons/6/63/Khandadhar_Falls.jpg]" alt="Khandadhar Waterfalls" class="place-img" />
        <img src="[translate:https://upload.wikimedia.org/wikipedia/commons/5/5f/Khandadhar_Falls_closeup.jpg]" alt="Khandadhar Waterfalls Closeup" class="place-img" />
      </div>
      <p>One of Odisha’s tallest waterfalls, surrounded by lush forests, 10 km from Barbil.</p>
      <iframe class="map" title="Khandadhar Waterfalls" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.763144382173!2d85.57999311533481!3d22.0691919422624!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a2720a9f301bd21%3A0x12221a5c9f661e4e!2sKhandadhar%20Waterfall!5e0!3m2!1sen!2sin!4v1698087200000!5m2!1sen!2sin"></iframe>
    </article>

    <article>
      <h3>Sanaghagara Waterfalls</h3>
      <div class="img-container">
        <img src="[translate:https://upload.wikimedia.org/wikipedia/commons/3/3a/Sanaghagara_Falls.jpg]" alt="Sanaghagara Waterfalls" class="place-img" />
        <img src="[translate:https://upload.wikimedia.org/wikipedia/commons/8/87/Sanaghagara_waterfall_2.jpg]" alt="Sanaghagara Falls Surrounding" class="place-img" />
      </div>
      <p>Beautiful waterfall in the hills surrounding Barbil, ideal for trekking enthusiasts.</p>
      <iframe class="map" title="Sanaghagara Waterfalls" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.753903857823!2d85.56603321533478!3d22.07191844228236!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a2720ac7e5f69e3%3A0xcb0ad62ec591b48d!2sSanaghagara%20Waterfalls!5e0!3m2!1sen!2sin!4v1698090000000!5m2!1sen!2sin"></iframe>
    </article>
  </section>

  <section id="grocery" class="category" tabindex="0">
    <h2>Grocery & Supermarkets</h2>
    <ul class="shop-list">
      <li>Binodini Grocery Shop - Phuljhar - Contact: 06767-654321</li>
      <li>Chandan Grocery Ltd - Anandapur Road - Contact: 06767-789012</li>
      <li>Patanjali Arogya Kendra - Ground Floor, Basti Road - Contact: 09437496936</li>
    </ul>
    <iframe class="map" title="Grocery Market Barbil" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.568367790549!2d85.59934965194091!3d22.113835557146004!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a27211e9f72d0b9%3A0x5bc6b20c2e14a8d6!2sBarbil%20Market!5e0!3m2!1sen!2sin!4v1698089000000!5m2!1sen!2sin"></iframe>
  </section>

  <section id="apparel" class="category" tabindex="0">
    <h2>Apparel & Clothing Shops</h2>
    <ul class="shop-list">
      <li>Shivaji Cloth Store - Main Road - Contact: 06767-234567</li>
      <li>Rahul Tailors - Market Road - Contact: 06767-987654</li>
      <li>Nandini Ethnic Wear - Bamebari - Contact: 06767-321098</li>
    </ul>
    <iframe class="map" title="Apparel Market Barbil" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.560123027028!2d85.59848915072152!3d22.114179357118212!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a27211e6c08d073%3A0xd3e9d605e6c0086e!2sApparel%20Market%20Barbil!5e0!3m2!1sen!2sin!4v1698089100000!5m2!1sen!2sin"></iframe>
  </section>

  <section id="electronics" class="category" tabindex="0">
    <h2>Electronics & Appliances</h2>
    <ul class="shop-list">
      <li>Barbil Electronics - Station Road - Contact: 06767-345678</li>
      <li>New Age Mobiles - Market Square - Contact: 06767-876543</li>
      <li>Soumyajit Electricals - Kalinga Nagar - Contact: 06767-432109</li>
    </ul>
    <iframe class="map" title="Electronics Market Barbil" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.5623459082958!2d85.5989996877114!3d22.11406054283483!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a27211e406eae0f%3A0xf67e5c5ecfa289ab!2sElectronics%20Market%20Barbil!5e0!3m2!1sen!2sin!4v1698089200000!5m2!1sen!2sin"></iframe>
  </section>

  <section id="restaurants" class="category" tabindex="0">
    <h2>Restaurants & Eateries</h2>
    <ul class="shop-list">
      <li>Dawat Restaurant - Main Road - Contact: 06767-123789</li>
      <li>Food Junction - Bamebari - Contact: 06767-987321</li>
      <li>Spice Villa - Anandapur Road - Contact: 06767-456123</li>
    </ul>
    <iframe class="map" title="Restaurant Area Barbil" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.551234777543!2d85.5978761518208!3d22.11455742645062!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a27211e234abdfd%3A0x3cfc4aad317ba064!2sRestaurant%20Area%20Barbil!5e0!3m2!1sen!2sin!4v1698089300000!5m2!1sen!2sin"></iframe>
  </section>

  <section id="beauty" class="category" tabindex="0">
    <h2>Beauty Parlours & Salons</h2>
    <ul class="shop-list">
      <li>Twinkle Beauty Parlour - Main Road - Contact: 06767-564789</li>
      <li>Allure Spa & Salon - Phuljhar - Contact: 06767-876987</li>
    </ul>
    <iframe class="map" title="Beauty Parlour Area Barbil" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.565489800123!2d85.5999876871102!3d22.114010838263724!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a27211e1a0a8b9f%3A0xf63eb0d4c34f1efa!2sBeauty%20Parlour!5e0!3m2!1sen!2sin!4v1698089400000!5m2!1sen!2sin"></iframe>
  </section>

  <section id="others" class="category" tabindex="0">
    <h2>Other Shops & Services</h2>
    <ul class="shop-list">
      <li>Ravi Stationery Shop - Market Road - Contact: 06767-321456</li>
      <li>Gift Gallery - Anandapur Road - Contact: 06767-654789</li>
      <li>Indane Gas Agency - Keonjhar Road - Contact: 06767-480377</li>
    </ul>
    <iframe class="map" title="Other Markets Barbil" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3782.5523312972907!2d85.59751278469943!3d22.114556937392142!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a27211e63f1244b%3A0xbf7741a7a8ab772c!2sMarket%20Barbil!5e0!3m2!1sen!2sin!4v1698089500000!5m2!1sen!2sin"></iframe>
  </section>

  <section class="category active" tabindex="0" style="max-width: 900px; margin: 2rem auto 4rem; background: #121217; padding: 1.5rem; border-radius: 15px; box-shadow: 0 0 25px #39ff14cc;">
    <h2 class="neon-text" style="margin-bottom: 1rem;">Current Weather in Barbil</h2>
    <div id="weather-info">Loading weather...</div>
  </section>

  <footer>
    <p>© 2025 Barbil City Explorer | Developed with care by Amrit Nanda of Jindal School Class 9B</p>
  </footer>

  <script>
    // Show/hide categories based on button click
    const buttons = document.querySelectorAll("nav button");
    const categories = document.querySelectorAll("section.category");

    buttons.forEach((button) =>
      button.addEventListener("click", () => {
        const target = button.textContent.toLowerCase().split(" ")[0];
        categories.forEach((section) => {
          if (section.id === target) {
            section.classList.add("active");
            section.style.display = "block";
          } else {
            section.classList.remove("active");
            section.style.display = "none";
          }
        });
        buttons.forEach((btn) => btn.classList.remove("active"));
        button.classList.add("active");
      })
    );

    // OpenWeatherMap API key for weather
    const apiKey = "51e26e71c3132ab16fd55c16127c0363";
    const weatherDiv = document.getElementById("weather-info");

    async function fetchWeather() {
      try {
        const response = await fetch(
          `https://api.openweathermap.org/data/2.5/weather?q=Barbil,IN&units=metric&appid=${apiKey}`
        );
        if (!response.ok) throw new Error("Weather data not available");
        const data = await response.json();

        weatherDiv.innerHTML = `
          <p><strong>${data.name}, ${data.sys.country}</strong></p>
          <p>Temperature: ${data.main.temp}°C</p>
          <p>Weather: ${data.weather[0].description}</p>
          <p>Humidity: ${data.main.humidity}%</p>
          <p>Wind Speed: ${data.wind.speed} m/s</p>
        `;
      } catch {
        weatherDiv.innerHTML = `<p>Error fetching weather data.</p>`;
      }
    }
    fetchWeather();
  </script>
</body>

</html>
