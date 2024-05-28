<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta http-equiv="author" content="Saumey mani" />
  <meta http-equiv="pragma" content="cache" />
  <title>Fitness Star Gym | Home Page </title>
  <!-- Favicons -->
  <link href="images/fitness_logo.png" rel="icon">
  <link href="images/fitness_logo.png" rel="touch-icon">

  <!-- Links Of External Css -->
  <link rel="stylesheet" href="style/desktop-view.css" type="text/css">
  <link rel="stylesheet" href="style/mobile-view.css" type="text/css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
  <div class="overlay-container">
    <!--Navbar Begins Here-->
    <header>
      <section class="navigation">
        <div class="nav-container">
          <div class="brand">
            <a href="#"><img src="images/logo.png" alt="Fitness Star Gym Logo"></a>
          </div>
          <nav>
            <div class="nav-mobile"><a id="navbar-toggle" href="#!" aria-label="Toggle navigation"><span></span></a>
            </div>
            <ul class="nav-list">
              <li class="home-btn">
                <a href="#">Home</a>
              </li>
              <li>
                <a href="class.html">Classes</a>
              </li>
              <li>
                <a href="products.html">Products</a>
              </li>
              <li>
                <a href="blogs.html">Blogs</a>
              </li>
              <li>
                <button type="button" class="join-btn" >Join Us</button>
              </li>
            </ul>
          </nav>
        </div>
      </section>   
    </header>


  <!-- Register Form -->
  <form>
    <div id="registerForm">
      <h2>SUBSCRIPTION PLAN</h2>
      <label for="fullname">Full Name:</label>
      <input class="form-input" type="text" name="fullname" id="fullname" placeholder="📛 Enter Your Name" required />

      <label for="email">Email:</label>
      <input class="form-input" type="email" name="email" id="email" placeholder="📧 xxxxx@gmail.com" required />

      <label for="mobile">Mobile Number:</label>
      <input class="form-input" type="text" name="mobile" id="mobile" placeholder="📲 xxxxxxxxxx" required />

      <legend>Duration:</legend>
      <label class="duration">
        <input type="radio" name="duration" value="monthly" /> Monthly
        <input type="radio" name="duration" value="yearly" style="margin-left: 22px;"/> Yearly
      </label>

      <legend>Mode Of Payment:</legend>
      <label class="payment">
        <input type="radio" name="payment" value="cash" /> Cash
        <input type="radio" name="payment" value="online" style="margin-left: 45px;" /> Online
      </label>

      <legend class="personal-training">Personal Training: <b>*free with yearly plan</b></legend>
      <label class="training">
        <input type="radio" name="personal-training" value="required" /> Required
      <br>
        <input type="radio" name="personal-training" value="not-required" /> Not required
      </label>
      
      <label for="sign-me" class="sign-me">
      <input type="checkbox" name="sign-me" value="sign-me" checked> 
      I accept all terms and conditions provided in this form.
      </label>
      
      <button>Submit</button>
      <button>Close</button>
    </div>
  </form>

  
    <!--Fitness Plans & Nutritions Code Begins Here-->
    <div class="main-content">
      <div class="hero-image">
        <div class="hero-card">
          <h1>Revitalize <br />your body</h1>
          <p>Fall in love with taking care of yourself: <br />mind, body, and spirit.</p>
          <button class="hero-btn1" type="button">Get Started</button >
          <button class="hero-btn2" type="button">Free Trial &#10132;</button>
        </div>
      </div>

      <div class="social-icons">
        <div class="font-awesome">
          <a href="https://www.whatsapp.com/" target="_blank"><i class="fa-brands fa-whatsapp"></i></a>
          <a href="https://www.facebook.com/" target="_blank"><i class="fa-brands fa-facebook"></i></a>
          <a href="https://www.youtube.com/" target="_blank"><i class="fa-brands fa-youtube"></i></a>
        </div>
      </div>

      <div class="plans">
        <h1>Fitness Plans & Nutritions</h1>
        <div class="plans-item">
          <div class="plans-card">
            <img src="images/weight-pound.png" alt="Symbol Of Weight Pound">
            <h5>Weight Loss</h5>
          </div>
          <div class="plans-border1"></div>
          
          <div class="plans-card">
            <img src="images/yoga.png" alt="Symbol Of Classic Yoga">
            <h5>Classic Yoga</h5>
          </div>
          <div class="plans-border2"></div>
          <div class="plans-card">
            <img src="images/cycling.png" alt="Symbol Of Cycling">
            <h5>Cycling</h5>
          </div>
          <div class="plans-border3"></div>

          <div class="plans-card">
            <img src="images/biceps.png" alt="Symbol Of Body Building">
            <h5>Body Building</h5>
          </div>
          <div class="plans-card">
            <img src="images/hypertrophy.png" alt="Symbol Of Hypertrophy">
            <h5>Hypertrophy</h5>
          </div>
          <div class="plans-card">
            <img src="images/running.png" alt="Symbol Of Running">
            <h5>Running</h5>
          </div>
        </div>
      </div>
    </div>

    
    <!--Subscription Plans Code Begins Here-->
    <div class="subscription">
      <h1>Subscription Plans</h1>
      <div class="subscription-cards">
        <div class="subscription-card">
          <div class="sub-text">
            <h4>Basic</h4>
            <p>for 12 months</p>
          </div>
          <div class="sub-text">
            <h4>800/month</h4>
            <p>for streaming</p>
          </div>
          <button type="menu" class="hero-btn2 subscription-btn">Select Plan</button>
        </div>

        <div class="subscription-card">
          <div class="sub-text">
            <h4>Intermediate</h4>
            <p>for 12 months</p>
          </div>
          <div class="sub-text">
            <h4>1000/month</h4>
            <p>for streaming</p>
          </div>
          <button type="menu" class="hero-btn2 subscription-btn">Select Plan</button>
        </div>

        <div class="subscription-card">
          <div class="sub-text">
            <h4>Advanced</h4>
            <p>for 12 months</p>
          </div>
          <div class="sub-text">
            <h4>1500/month</h4>
            <p>for streaming</p>
          </div>
          <button type="menu" class="hero-btn2 subscription-btn">Select Plan</button>
        </div>
      </div>
    </div>



    <!--Html Code Begins Here For Fitness Club-->
    <div class="fitness-club">
      <div class="club-img"></div>
      <div class="club-items">
        <div class="club-item">
          <img src="images/gm.png" alt="Image Of Good Management">
          <h4>Good Management</h4>
          <p>What hurts today makes you stronger tomorrow.</p>
        </div>

        <div class="club-item">
          <img src="images/pg.jpeg" alt="Image Of Practice Sessions">
          <h4>Practice Sessions</h4>
          <p>Motivation is what gets you started.</p>
        </div>

        <div class="club-item">
          <img src="images/ft.png" alt="Image Of Personal Trainers">
          <h4>Personal Trainers</h4>
          <p>If it doesn't challenge you, it won't change you.</p>
        </div>
      </div>
    </div>
    


    <!--Html Code Begins Here For Success Stories-->
    <div class="success-stories">
      <h1>Success Stories</h1>
      <div class="stories-collection">
        <div class="stories-card">
          <img src="images/james.jpeg" alt="Image Of James with his stories">
          <p>Working out regularly I lose 
            some of my extra pounds which 
            helped in my modelling career.</p>
        </div>

        <div class="bruce-mars">   
        <div class="stories-card">
          <img src="images/bruce-mars.jpeg" alt="Image Of Bruce Mars with her stories">
          <p>Yoga and Pilates helped 
            me get back in shape 
            and raised my confidence.</p>
        </div>
      </div>    

        <div class="stories-card">
          <img src="images/mark-adriane.jpeg" alt="Image Of Mark Adriane with her stories">
          <p>Personal Trainer diet plan 
            helpedin increasing 
            strength and endurance.</p>
        </div>
      </div>
    </div>


    <!--Html Code Begins Here For Footer-->
    <footer class="footer">
      <div class="foot-container">
      <div class="foot-logo">
        <img src="images/logo1.png" alt="Logo of Fitness Star Gym">
        <h3>Prioritize Your Fitness Goals
          with our world class services</h3>
      </div>
      <div class="company foot-card">
        <h3>COMPANY</h3>
        <ul>
          <li><a href="#">About</a></li>
          <li><a href="#">Careers</a></li>
          <li><a href="#">Blogs</a></li>
          <li><a href="#">Terms & Conditions</a></li>
        </ul>
      </div>
      <div class="contact foot-card">
          <h3>CONTACT</h3>
          <ul>
            <li><a href="#">Help/FAQs</a></li>
            <li><a href="#">Press</a></li>
            <li><a href="#">Mobile</a></li>
          </ul>
      </div>
      <div class="more foot-card">
        <h3>MORE</h3>
          <ul>
            <li><a href="#">Program</a></li>
            <li><a href="#">Plans</a></li>
            <li><a href="#">Method</a></li>
          </ul>
      </div>
      <div class="foot-tags foot-card">
        <h3>Popular Tags</h3>
        <button type="button" class="tags-btn-color1">ABS</button>
        <button type="button" class="tags-btn-color1">Workout</button>
        
        <button type="button" class="tags-btn-color2">Nutrition</button>
        <button type="button" class="tags-btn-color1">Fitness</button>
        
        <button type="button" class="tags-btn-color1">Boxing</button>
        <button type="button" class="tags-btn-color2">Trainers</button>
        
        <button type="button" class="tags-btn-color2">Facilities</button>
    </div>
    </div>    
    </footer>
    <div class="copyright">
      <h3>CopyRight  All  Rights  Reserved</h3>
    </div>

  </div>

  <script src="script/index.js"></script>

  <!-- Links Of External Js -->

  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
 
  <script src="https://kit.fontawesome.com/8a4fbb7cf2.js" crossorigin="anonymous"></script>
</body>
</html>
