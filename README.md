# FreeCodeCamp-Survey-Form

/* HTML at the top and CSS is underneath it */

<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>

<!DOCTYPE html>
<html>
<header>
  <div id="header">
    <img id="header-img" src="https://www.adidas.co.uk/glass/react/ffb3fe8/assets/img/icon-adidas-logo.svg" alt="Adidas Logo" width="225px" height="auto">
    
    <nav id="nav-bar">
     &nbsp; &nbsp; &nbsp; <a class="nav-link" href="#features"><b>Features</b></a> &nbsp; &nbsp; &nbsp;

      <a class="nav-link" href="#shoe-performance-review"><b>Shoe Performance Review</b></a> &nbsp; &nbsp; &nbsp;
      
      <a class="nav-link" href="#video-review"> <b>Video Review</b></a>
      
      <style>
@import url('https://fonts.googleapis.com/css2?family=Padauk&family=Poppins:wght@200&display=swap');
</style>
      
    </nav>
</header>

<body>
 
 <form id="form" action="https://www.freecodecamp.com/email-submit">
  
   <label for="email" id="email-label"> Email:</label>
<input id="email" type="email" name="email" placeholder="example123@gmail.com" class="form-inputs" required> </input>
  <input id="submit" type="submit" value="Submit">

  </form>
  
  <br> <br> <section id="features"> <b><u>Features</u></b><br>Cras sem tellus, lobortis volutpat semper a, accumsan sit amet tellus. Integer auctor neque sem, id gravida nisl imperdiet vitae. Nam ac leo sed dolor finibus tincidunt. Quisque diam sem, tempor quis sapien a, faucibus egestas urna. Nam elementum orci a sapien porttitor, sed malesuada orci vulputate. Maecenas eu risus sapien. Ut pretium sem vel ligula accumsan, a ullamcorper massa mattis. Interdum et malesuada fames ac ante ipsum primis in faucibus. Quisque et elit sed magna ultricies pellentesque eu in lacus. Ut id leo at orci interdum semper a et quam. Donec pretium sapien vitae odio dignissim, vitae tempus felis rhoncus. Praesent metus metus, dictum quis nisi nec, bibendum elementum sapien. Sed finibus ligula sapien, ut ornare nunc commodo vel. Suspendisse nec neque lacus. Vivamus malesuada eu dui sed porttitor.
  </section> <br> <br>
  
  <section id="shoe-performance-review"> <b><u>Shoe Performance Review</u></b><br>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer condimentum faucibus ligula, non ultricies mauris egestas vel. Aliquam a enim augue. Nam feugiat ex vel turpis elementum suscipit. Etiam porta ipsum id nisl euismod, et ullamcorper tellus consectetur. Quisque facilisis velit id lectus ornare, et elementum nibh dictum. Aenean lacinia venenatis massa, a maximus elit egestas sit amet. Mauris libero neque, euismod et sagittis vitae, pretium vitae urna. Suspendisse vel sagittis orci. Morbi imperdiet nec lacus eu molestie. Suspendisse tempus consequat urna in pharetra.
  </section> <br> <br>
  
  <section id="video-review"> <b><u>Video Review</u></b>
     <br> <iframe id="video" width="600" height="350" src="https://www.youtube-nocookie.com/embed/yvUHT746ImE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </section>
 
  <br>
   <br>
   <br>

  <div class="end-images">
  <div class="row">
  <div class="column">
    <img src="https://i.pinimg.com/originals/fe/aa/23/feaa23488a3727995d1e7ba59c6131b1.jpg" alt="Bostons Photo" style="width:100%">
  </div>
  <div class="column">
    <img src="https://i.pinimg.com/originals/77/8a/87/778a87822809f99eeb2f761947f67ecb.jpg" alt="Image of the Original Bostons Dating All The Way Back To 1981!" style="width:100%">
  </div>
  <div class="column">
    <img src="https://i0.wp.com/www.afoodiestaysfit.com/wp-content/uploads/2019/08/AFSFMarch-64.jpg?resize=1067%2C1600&ssl=1" alt="Marybeth Wells Showing of a Pair of Black Boston 9's" style="width:100%">
  </div>
</div>
  </div>
  
 
  </body>
      </html>
      
      /* CSS for the Survey Form */
      
      @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200&display=swap');

body {
  font-family:'Poppins';
  line-height: 1.4;
  width: 600px;
  margin: auto;
}

.submit-button {
  width: 100%;
  padding: 0.75rem;
  background: blue;
  color: white;
  border-radius: 90px;
  cursor: pointer;
  opacity: 0.55
}

.input-headings {
  margins: 0 auto 1.25rem auto;
  padding: 0.25rem;
}

.form-inputs {
  display: inline-block;
  width: 90%;
  height: 2rem;
  padding: 0.25rem 0.75rem;
  background-color: #fff;
  border: 1px solid #ced4dn;
  border-radius: 0.25rem;
}

form {
  
}

h1 {
  text-align: center;
  color: orange;
}

p {
  text-align: center;
  color: orange;
  font-size: 20px;
}

form {
  color: orange;
  font-size: 18px;
  opacity: 1;
}
body {
    background-image: url("https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.mintlogix.com%2Fwp-content%2Fuploads%2F2014%2F09%2Fbackground_23.jpg&f=1&nofb=1");
 
}

body {
  text-align: center;
 
}

<!--This ".survey" CSS changes everything in the html to make it easier to style all elements.-->

.survey {
  color: white;
}

.end-p {
  font-size: 18px;
}
  
