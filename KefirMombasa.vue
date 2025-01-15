<template>
  <div id="app">
    <!-- Navbar -->
    <nav class="navbar">
      <h1>Kefir Mombasa</h1>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>

    <!-- Home Section -->
    <section id="home" class="home">
      <h2>Welcome to Kefir Mombasa</h2>
      <p>
        Discover the healthiest and tastiest fermented milk drink in Mombasa.
        Perfect for your gut health!
      </p>
      <div class="product">
        <img src="https://via.placeholder.com/300" alt="Kefir" />
        <h3>500ml Kefir</h3>
        <p>Price: KES 2,000</p>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
      <h2>Contact Us</h2>
      <p>Have any questions? Reach out to us:</p>
      <ul>
        <li>Email: info@kefirmombasa.com</li>
        <li>Phone: +254 700 123456</li>
        <li>Location: Mombasa, Kenya</li>
      </ul>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <p>&copy; 2025 Kefir Mombasa. All rights reserved.</p>
      <p>
        Follow us:
        <a href="#" target="_blank">Facebook</a> |
        <a href="#" target="_blank">Instagram</a> |
        <a href="#" target="_blank">Twitter</a>
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "KefirMombasa",
};
</script>

<style>
/* General Styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #f5f5f5;
}
#app {
  text-align: center;
}

/* Navbar Styles */
.navbar {
  background-color: #fff3e0;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.navbar h1 {
  font-size: 24px;
  color: #e65100;
}
.navbar ul {
  list-style: none;
  display: flex;
  gap: 20px;
}
.navbar a {
  text-decoration: none;
  color: #ff6f00;
  font-weight: bold;
}

/* Home Section Styles */
.home {
  padding: 20px;
  background-color: #fffde7;
}
.home p {
  margin: 10px 0;
}
.product {
  margin-top: 20px;
  padding: 10px;
  background-color: #ffecb3;
  border-radius: 5px;
}
.product img {
  width: 300px;
  border-radius: 10px;
}

/* Contact Section Styles */
.contact {
  padding: 20px;
  background-color: #fff3e0;
}
.contact ul {
  list-style: none;
  padding: 0;
}
.contact li {
  margin: 10px 0;
  font-size: 18px;
}

/* Footer Styles */
.footer {
  background-color: #ffe0b2;
  text-align: center;
  padding: 15px;
  position: fixed;
  bottom: 0;
  width: 100%;
}
.footer a {
  color: #e65100;
  margin: 0 5px;
}
</style>
