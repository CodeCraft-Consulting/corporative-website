<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="hero">
        <!-- <img src="hero-image.jpg" alt="CodeCraft Consulting" /> -->
        <h1>Welcome to CodeCraft Consulting</h1>
        <p>We offer consulting services for websites and applications.</p>
      </section>
      <section id="services">
        <h2>Our Services</h2>
        <!-- <img src="services-image.jpg" alt="Our services" /> -->
        <!-- List your services here -->
      </section>
      <section id="about">
        <h2>About Us (Phillip, Vic, Rux)</h2>
        <!-- Write about your company here -->
      </section>
    </main>
    <footer>
      <!-- Footer content goes here -->
    </footer>
  </div>
</template>

<style scoped>
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background: #f4f4f4;
}

#app {
  max-width: 1200px;
  margin: 0 auto;
}

header {
  background-color: #333;
  color: white;
  padding: 20px 0;
  position: sticky;
  top: 0;
  z-index: 10;
}

nav ul {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: space-around;
}

nav a {
  color: white;
  text-decoration: none;
}

#hero {
  background-color: white;
  padding: 50px 20px;
  text-align: center;
  box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.1);
}

#services,
#about {
  padding: 50px 20px;
  text-align: center;
}

h1,
h2 {
  color: #333;
}

img {
  max-width: 100%;
  height: auto;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px 0;
  position: sticky;
  bottom: 0;
}
</style>
