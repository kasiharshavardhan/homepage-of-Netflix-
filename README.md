# homepage-of-Netflix-
homepage of Netflix by using HTML and CSS

HTML :
<!DOCTYPE html>
<html>
<head>
  <title>Netflix</title>
  <style>
    body {
      font-family: sans-serif;
      background-color: black;
      color: white;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
    }

    .logo {
      font-size: 2em;
    }

    .menu {
      display: flex;
      justify-content: space-around;
      align-items: center;
    }

    .menu-item {
      font-size: 1.2em;
      padding: 10px;
    }

    .main-content {
      padding: 20px;
    }

    .hero-image {
      width: 100%;
      height: 500px;
      background-image: url(https://i.imgur.com/example.jpg);
      background-position: center;
      background-size: cover;
    }

    .hero-text {
      font-size: 2em;
      padding: 20px;
    }

    .browse-content {
      padding: 20px;
    }

    .browse-title {
      font-size: 1.5em;
      padding: 20px;
    }

    .browse-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }

    .browse-item {
      width: 200px;
      height: 300px;
      margin: 10px;
      background-image: url(https://i.imgur.com/example.jpg);
      background-position: center;
      background-size: cover;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      Netflix
    </div>

    <div class="menu">
      <div class="menu-item">Home</div>
      <div class="menu-item">Browse</div>
      <div class="menu-item">My List</div>
    </div>
  </header>

  <main class="main-content">
    <div class="hero-image">
      <div class="hero-text">
        <h1>Watch TV shows and movies online</h1>
        <p>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
        <a href="#">Start your free trial</a>
      </div>
    </div>

    <div class="browse-content">
      <h2 class="browse-title">Browse popular titles</h2>

      <div class="browse-list">
        <div class="browse-item"></div>
        <div class="browse-item"></div>
        <div class="browse-item"></div>
        <div class="browse-item"></div>
        <div class="browse-item"></div>
        <div class="browse-item"></div>
      </div>
    </div>
  </main>

  <footer>
    <p>Copyright &copy; 2023 Netflix</p>
  </footer>
</body>
</html>

CSS :

body {
  font-family: sans-serif;
  background-color: black;
  color: white;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
}

.logo {
  font-size: 2em;
}

.menu {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.menu-item {
  font-size: 1.2em;
  padding: 10px;
}

.main-content {
  padding: 20px;
}

.hero-image {
  width: 100%;
  height: 500px;
  background-image: url(https://i.imgur.com/

