# Display-and-Positioning-Project

INDEX.HTML

``` markdown

<!DOCTYPE html>
<html>
  
  <head>
    <link href='https://fonts.googleapis.com/css?family=Raleway:400, 600' rel='stylesheet' type='text/css'>
    <link href='style.css' rel='stylesheet' type='text/css'/>
  </head>

  <body>
    
    <header>
        <nav>
          <ul>
            <li> About </li> <li> Work </li> <li> Team </li> <li> Contact </li>
          </ul>
        </nav>
    </header>

    <main>
      <div class="jumbotron">
        <div class="container">  
          <h1>We are Broadway</h1>
          <a href="#" class="btn-main"> Get Started </a>
        </div>
      </div>
    </main>

    <section class="supporting">
      <div class="container">
        
        <div class="col">
          <img src="https://s3.amazonaws.com/codecademy-content/projects/broadway/design.svg">
          <h2>Design</h2>
          <p>Make your projects look great and interact beautifully.</p>
          <a href="#"> Learn More</a><br>
        </div>
        
        <div class="col">
          <img src="https://s3.amazonaws.com/codecademy-content/projects/broadway/develop.svg">
          <h2>Develop</h2>
          <p>Use modern tools to turn your design into a web site</p>
          <a href="#"> Learn More</a><br>
        </div>
        
        <div class="col">
          <img src="https://s3.amazonaws.com/codecademy-content/projects/broadway/deploy.svg">
          <h2>Deploy</h2>
          <p>Use modern tools to turn your design into a web site</p>
          <a href="#"> Learn More</a><br>
        </div>
        
      </div>
    </section>

    <footer>
      <div class="container">
        <p>&copy; Broadway 2017</p>
      </div>
    </footer>
    
  </body>
</html>

```

STYLE.CSS

``` markdown

html, body {
  margin: 0;
  padding: 0;
}

header {
  background-color: #333333;
  position: fixed;
  width: 100%;
  z-index: 1;
}

nav {
  margin: 0;
  padding: 20px 0;
}

nav li {
  color: #fff;
  font-family: 'Raleway', sans-serif;
  font-weight: 600;
  font-size: 12px;
  display: inline-block;
  width: 80px;
}

main {
  text-align: center;
  position: relative; 
  top: 80px;
}

main h1 {
  color: #333;
  font-family: 'Raleway', sans-serif;
  font-weight: 600;
  font-size: 70px;
  margin-top: 0px;
  padding-top: 80px;
  margin-bottom: 80px;
  text-transform: uppercase;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 30px 0;  
  position: fixed;
  width: 100%;
  height: 30px;
  z-index: 1;
  bottom: 0;
}

footer p {
  font-family: 'Raleway', sans-serif;
  text-transform: uppercase;
  font-size: 11px;
}

.container {
  max-width: 940px;
  margin: 0 auto;
  padding: 0 10px;
  text-align: center;
}

.jumbotron {
  height: 800px;
  background-image: url("http://s3.amazonaws.com/codecademy-content/projects/broadway/bg.jpg");
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

.btn-main {
  background-color: #333;
  color: #fff;
  font-family: 'Raleway', sans-serif;
  font-weight: 600;
  font-size: 18px;
  letter-spacing: 1.3px;
  padding: 16px 40px;
  text-decoration: none;
  text-transform: uppercase;
}

.btn-default {
  font-family: 'Raleway', sans-serif;
  font-weight: 600;
  font-size: 10px;
  letter-spacing: 1.3px;
  padding: 10px 20px;
  text-decoration: none;
  text-transform: uppercase;  
  margin-bottom: 20px;      
}

.supporting {
  padding-top: 80px;
  padding-bottom: 100px;
}

.supporting .col {
  font-family: 'Raleway', sans-serif;
  text-align: center;
  display: inline-block;
  width: 200px;
  height: 200px;
}

.supporting img {
  height: 32px;
}

.supporting h2 {
  font-weight: 600;
  font-size: 23px;
  text-transform: uppercase;
}

.supporting p {
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  padding: 0 20px;
  margin-bottom: 20px;
}

.supporting a {
  background-color: white;
  color: #333333;
  font-family: 'Raleway', sans-serif;
  font-weight: 600;
  font-size: 12px;
  letter-spacing: 1.3px;
  text-decoration: none;
  text-transform: uppercase;
  padding: 10px;
  margin-bottom: 10px;
  border: 2px solid #333333; 
}

@media (max-width: 500px) {
  main h1 {
    font-size: 50px;
    padding: 0 40px;
  }

  .supporting .col {
    width: 100%;
  }
}

```
