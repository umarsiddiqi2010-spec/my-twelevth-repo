# my-twelevth-repo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Salt n Pepper - Links</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <header>
      <h1>Salt <span>&amp;</span> Pepper</h1>
      <p>Your go-to links</p>
    </header>

    <nav class="links">
      <ul>
        <li><a href="https://saltnpepper.com.pk/about">About Us</a></li>
        <li><a href="https://saltnpepper.com.pk/menu">Menu</a></li>
        <li><a href="https://saltnpepper.com.pk/contact">Contact</a></li>
        <li><a href="https://saltnpepper.com.pk/order">Order Online</a></li>
        <li><a href="https://saltnpepper.com.pk/careers">Careers</a></li>
        <li><a href="https://saltnpepper.com.pk/blog">Blog</a></li>
      </ul>
    </nav>

    <footer>
      <p>&copy; 2025 Salt n Pepper. All rights reserved.</p>
    </footer>
  </div>
</body>
</html>

/* Basic reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Body style */
body {
  font-family: Arial, Helvetica, sans-serif;
  background-color: #f9f9f9;
  color: #333;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}

/* Container to center content */
.container {
  background: white;
  padding: 40px;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  width: 90%;
  max-width: 400px;
  text-align: center;
}

/* Header styles */
header h1 {
  font-size: 2em;
  margin-bottom: 10px;
}

header h1 span {
  color: #e63946; /* accent color for & */
}

header p {
  color: #666;
  margin-bottom: 30px;
}

/* Links list */
nav.links ul {
  list-style: none;
}

nav.links li {
  margin: 15px 0;
}

nav.links a {
  text-decoration: none;
  color: #1d3557;
  font-size: 1.1em;
  transition: color 0.2s;
}

nav.links a:hover {
  color: #e63946;
}

/* Footer style */
footer {
  margin-top: 40px;
  font-size: 0.9em;
  color: #999;
}
