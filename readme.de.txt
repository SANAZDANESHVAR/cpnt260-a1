<body>
  <main>
  <div>
    <h1>Green tobacco</h1>
    <p>"experince our full line of cigaret and cigar  accessories" </p>
    
    
    <figure class="card">
      
      <figcaption>
        " WELCOM TO GREEN TOBACCO "
        <br>
          PLEASE VARIFY YOUR AGE TO ENTER:
        
      </figcaption>
   <button>
     <a href="https://picsum.photos/"> "I am not a minor" </a>

    </button>
        
     </figure>
  </div>
</main>
</body>
splash.markdown
splash
A Pen by SANAZDANESHVAR on CodePen.

License.

style.css

* body{
  margin: 0;
}

div{
  width: 100vh;
  height: 100vh;
}
  h1{
  font-size : 50px;
  font-variant: small-caps;
  font-family: 'Raleway', sans-serif;
  font-weight: 180;
  Background-color: hsla(30, 72%, 18%, 0.75);
  background-position: center;
  color: white;
}


p {
  font-size :30px;
  background-position: center;
  font-family: 'Pacifico', cursive;
  font-variant: small-caps;  
  background-color: hsla(360, 100%, 100%, 0.68);
  margin: 0;
  color:black;
}


  main {
  display: flex;
  align-items: center;
  justify-content: center;
   margin: 0;  
  background-size: cover;
  background-position: center;
  background-image:
   
linear-gradient(180deg,hsla(30, 100%, 21%, 0.41)40%,transparent),

linear-gradient(300deg,hsla(80, 100%, 50%, 0.17)10%, transparent), 
url('https://static.politico.com/dims4/default/f4cf2c1/2147483647/resize/1160x%3E/quality/90/?url=https%3A%2F%2Fstatic.politico.com%2Fa3%2F9c%2F2cf9c39f479a8dfe5f7857f97913%2F200214-tobacco-ap-773.jpg');
}



.card {
  min-width: 25ch;
  max-width: 45ch;
  border: 3px  solid black;
  border-radius: 0.3em;
  background-color: white;
  text-align: center;
  margin:1em 1em; 
  card-position: center; 
  pannel: 2em;
}
button{     
  display: block;   
  background-color: hsla(93, 100%, 15%, 1);
  border: 2px  solid black;
  border-radius: 0.2em;
  margin: 1em auto;
  font-size: 25px;  
}

a{        
  display: block; 
  font-family: 'Montserrat', sans-serif; 
  letter-spacing: 0.2em;
  border-radius: 0.02em;
  margin: auto;
  color: white;  
}


 a:hover{
  background-color: orange;
  color: black;
  text-decoration: underline;
}

a:active {
  background-color: hsla(13, 100%, 33%, 1); 
  color: white;
}

  


    @media screen (max-width: 400px) {
 
      body {
        font-size: 35px;
      }
    }
  
  
    @media screen (max-width: 800px) {

      body {font-size: 38px;
        
      }
    }
  
  
 @media screen (max-width: 1200px) {
      body {  font-size: 50px;
       
      }
    }   