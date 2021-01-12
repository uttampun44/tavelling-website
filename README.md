# tavelling-website
project made in html, css and javascript


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breathtaking Journey</title>
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <linkrel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.7.2/css/all.css"
      integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr"
      crossorigin="anonymous"/>
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="travel.css">
    <script src="travel.js"></script>
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
</head>
<body>
    <section>
    <nav>
        <div class="logo">
            <h1><a href="">EXPLORE</a></h1>
        </div>
    <div class="container">
        <ul>
            <li><a href="#"><i class="fa fa-home">HOME</i></a></li>
            <li><a href="#"><i class="fa fa-automobile">SERVICES</i>
            <ul id="cons">
                <li><a href="#">Accomodation</a></li>
                <li><a href="#">Taxi</a></li>
                <li><a href="#">Airport Picking</a></li>
            </ul>
        </li>
            <li><a href="#"><i class="fa fa-plane">Destination</i></a>
                <ul>
                    <li><a href="#">Norway</a></li>
                    <li><a href="#">Switzerland</a></li>
                    <li><a href="#">Uk</a></li>
                </ul>
            </li>
            <li><a href="#"><i class="fa fa-phone-square">Contact Us</i></a></li>
        </ul>
  </div>
</nav>
</section>
   <!--Main Page-->
   <div class="mainpage" data-aos="fade-down"  data-aos-delay="150" data-aos-duration="1000" data-aos-easing="ease-in-out"  data-aos-mirror="true">
       <div class="main" >
        <h2>Life Time Experience</h2>
        <br>
        <h3>JOURNEY</h3>
        <button><a href="#">START</a></button>
    </div>    
</div>
<!--Places-->
    <div class="places">
      <h4><u>Places</u></h4>
        <div class="image1">
            <img src="swiss.jpg">
            <p>Switzerland is a mountainous Central European country, home to numerous lakes, villages and the high peaks of the Alps.
            </p>
            <button>Book Now</button>
           </div>
           <div class="image2">
            <img src="lavender.jpg">
            <p>New Zealand currently makes up 9% of the country’s gross domestic product largest export sector.
            </p>
           <button>Book Now</button>
           </div>
           <div class="image3">
            <img src="norway.jpg">
            <p>Norway is a Scandinavian country encompassing mountains, glaciers and deep coastal fjords.
            </p>
            <button>Book Now</button>
           </div>
           <div class="image4">
            <img src="nature.jpg">
            <p>Sweden officially the Kingdom of Sweden is a Nordic country in Northern Europe.
            </p>
            <button>Book Now</button>
           </div>
           <div class="image5">
            <img src="landscape.jpg">
            <p>Finland is a Northern European nation bordering Sweden, Norway and Russia
            </p>
            <button>Book Now</button>
           </div>
           <div class="image6">
            <img src="h.jpg">
            <p>Canada is a country in the northern part of North America.
            </p>
            <button>Book Now</button>
        </div>
    </div>
    <div class="information">
             <h5>About Us</h5>
            <p1>Oyo Rooms (stylised as OYO), also known as Oyo Hotels & Homes, <br>is an Indian hospitality chain of leased and franchised hotels, <br>
                homes and living spaces.<br>
 Founded in 2013 by Ritesh Agarwal, OYO initially consisted mainly of budget hotels. <br>The startup expanded globally with thousands of hotels, <br>
 vacation homes and millions of rooms in India, Malaysia, UAE, Nepal, China, Brazil, Mexico,<br>
  UK, Philippines, Japan, Saudi Arabia, Sri Lanka, Indonesia, Vietnam, the United States and more.<br>
  The company's investors include SoftBank Group, Greenoaks Capital, Sequoia India, 
  <br>Lightspeed India, Hero Enterprise, Airbnb and China Lodging Group.
<br> In 2012, Ritesh Agarwal launched Oravel Stays to enable listing and booking of budget accommodations. <br>
After undertaking months of research and staying in various bed and breakfast homes, <br>guest houses,and small hotels across India, 
<br>he pivoted Oravel to OYO in 2013
<br>
<br> OYO partners with hotels to give similar guest experience across cities. <br>
Shortly after launching Oravel Stays <br>
Ritesh Agarwal received a grant of $100,000 as part of the Thiel Fellowship from Peter Thiel.<br>
 OYO currently has over 17,000 employees globally, of which approximately 8000 are in India and South Asia. <br>
 OYO Hotels & Homes is a full-fledged hotel chain that leases and franchises assets. <br>
 The company invests in capex, hires GMs to oversee operations and customer experience <br>
 as well as generating around a million job opportunities in India and South Asia alone. <br>
 OYO has also set up 26 training institutes for hospitality enthusiasts across</p>   
 <!--form-->         
 <div class="form-control">
        <form class="form">
            <h6>Login</h6>
            <label>UserName: </label>
            <input type="text" placeholder="Enter your Username">
            <br>
            <br>
            <label>Password:</label>
            <input type="password" placeholder="Enter your Password">
             <br>
             <br>
            <button>Login In</button>
        </form>
        <div class="detail">
             <p>Don't Have Any Account?</p>
             <p1><a href="register.html">Sign Up</a></p1>
             <div class="forgot-password">
                <h><a href="#">Forgot Your Password</a></h>
             </div>
        </div>
        <div class="searching">
            <p>Can't find what you're lookign for? Use the search form below to search the site!</p>
            <input type="text" placeholder="Search the site here." id="searchinput" onkeyup="search()">
            <button>Search</button>
        </div>
    </div>
    <div class="last-information">
        <div class="travel-tips">
            <h>TRAVEL TIPS</h>
            <ul>
            <li><a href="#">Start Here</a></li>
            <li><a href="#">Travel Blog</a></li>
            <li><a href="#">Destination Guide</a></li>
            <li><a href="#">Teaching Overseas</a></li>
            <li><a href="#">Guide Books</a></li>
            </ul>
        </div>

        <div class="community">
            <h>COMMUNITY</h>
            <ul>
            <li><a href="#">Forums & Events</a></li>
            <li><a href="#">Book Club</a></li>
            <li><a href="#">Patreon</a></li>
            <li><a href="#">FLYTE</a></li>
            <li><a href="#">Blogging Course</a></li>
            </ul>
        </div>

        <div class="book-trip">
            <h>BOOK YOUR TRIP</h>
            <ul>
            <li><a href="#">Accomodation</a></li>
            <li><a href="#">Cheap Flights</a></li>
            <li><a href="#">Travel Insurance</a></li>
            <li><a href="#">Travel Credit Cards</a></li>
            <li><a href="#">Favourite Company</a></li>
            </ul>
        </div>

        <div class="follow">
            <h>FOLLOW ME ON:</h>
            <a href="#"><i class="	fa fa-facebook-square"></i></a>
            <div class="instagram">
                <a href="#"><i class="fa fa-instagram"></i></a>
            </div>
            <div class="twitter">
                <a href="#"><i class="	fa fa-twitter"></i></a>
            </div>
        </div>
        
        <!--Conpyrights-->
        <div class="copyright">
           <p>Copyright@2020.NepalTravel Site</p>
           <hr>
           <p>AN ELITE TravelMedia PUBLISHER</p>
        </div>
    </div>
    <script>
        AOS.init();
        function search() {
            
        }
    </script>
</body>
</html>


Register Page
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css">
    <title>Register </title>
    <script src="travel.js"></script>
    <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
</head>
<style>
    *{
        padding: 0%;
        margin: 0%;
        box-sizing: border-box;
    }
 body{
     background-image: url("nature.jpg");
     background-repeat: no-repeat;
     background-size: cover;
     overflow-x: hidden;
 }  
.header{
    display: flex;
    justify-content: center;
    align-items: center;
    color: red;
}
 #form{
    border-radius: 2px;
    border-width: 2px;
    border-style: outset;
     border-color: black;
     background-color: #a60059;
     width: 700px;
     height: 500px;
    position: relative;
    left: 30%;
 }
 .form-control{
     display: flex;
     justify-content: center;
     align-items: center;
     padding: 5px;
 }
 .form-control input[type=text]{
   width: 470px;
   height: 30px;
   text-align: center;
 }
 .form-control input[type=Email]{
   width: 470px;
   height: 30px;
   text-align: center;
 }
 .form-control input[type=number]{
   width: 470px;
   height: 30px;
   text-align: center;
 }
 .form-control input[type=password]{
   width: 470px;
   height: 30px;
   text-align: center;
 }
 .form-control input[type=password]{
   width: 470px;
   height: 30px;
   text-align: center;
 }
 .form-control label{
     font-size: 20px;
     padding: 10px;
 }
 label{
   font-size: 3vh;
   padding: 8px;
   display: flex;
 }
 .btn{
   width: 250px;
   height: 30px;
   display: flex;
   justify-content: center;
   align-items: center;
   position: relative;
   left: 32%;
   background-color: seagreen;
   padding: 2px;
   font-size: 18px;
   color: white;
 }
 .btn a{
   text-decoration: none;
 }
 #user{
  display: flex;
   position: absolute;
   left: 18%;
   top: 15%;
   color: white;
 }
 #mail{
  display: flex;
   position: absolute;
   left: 18%;
   top: 31%;
   color: white;
 }
 #contact{
  display: flex;
   position: absolute;
   left: 18%;
   top: 47%;
   color: white;
 }
 #pass{
  display: flex;
   position: absolute;
   left: 18%;
   top: 63%;
   color: white;
 }
 #con{
   display: flex;
   position: absolute;
   left: 18%;
   color: white;
 }
</style>
<body>
    <div class="container">
       <div class="header">
    <h1>REGISTER FORM</h1>
       </div>
       <form class="form" id="form" action="travel.html" method="GET" onsubmit="return validation()">
        <label>UserName:</label>
           <div class="form-control">
        <input type="text" placeholder="Enter your username" required="" id="username" name="" autocomplete="off">
           </div>
           <span id="user"></span>
           <label>Email:</label>
           <div class="form-control">
            <input type="Email" placeholder="Enter your Email" required="" id="email" name="" autocomplete="off">    
          </div>
          <span id="mail"></span> 

               <label>PhoneNumber:</label>
               <div class="form-control">
                <input type="number" placeholder="Enter your number" required="" id="phone" name="" autocomplete="off">    
              </div>
              <span id="contact"></span> 
                   <label>Password:</label>
                   <div class="form-control">
                    <input type="password" placeholder="Enter password" required="" id="password" name="" autocomplete="off">   
                  </div>
                  <span id="pass"></span> 
                       <label>Confirm Password:</label>
                       <div class="form-control">
                        <input type="password" placeholder="Confirm Password" required="" id="confirm" name="" autocomplete="off">
                        <br>
                      </div>
                      <span id="con"></span>
                      <br>
                           <input type="submit" value="REGISTER" class="btn" value="" id="sub">
       </form>
    </div>
    <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
    <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/sweetalert/2.0.0/sweetalert.min.js"></script>
    <script type="text/javascript">

    let submit = document.getElementById('sub');

    submit.addEventListener('click', () =>{
        swal({
        title: "Login Successfully!",
        icon: "success",
        timer: 10000,
    showConfirmButton: false
        });
           });    
    </script>
</body>
</html>

Javascript Code
function validation() {

    const username = document.getElementById("username").value;
    const email = document.getElementById("email").value;
    const phone = document.getElementById("phone").value;
    const password = document.getElementById("password").value;
    const confirm = document.getElementById("confirm").value;
 
    

    if(username==null || username=="") {
          document.getElementById("user").innerHTML = "username cannot be blank."
          return false;
    } 
    if(email==null || email==""){
        document.getElementById("mail").innerHTML = "Email box cannot be empty."
        return false;
    }
    if(phone==null || phone==""){
        document.getElementById("contact").innerHTML = "Phone number cannot be blank."
    } 
    if(password.length>1 && password.length<8) {
        document.getElementById("pass").innerHTML = "Password must be between 6 to 8 character long."
        return false;
    } if(confirm==password) {
        return true;
    } else if(confirm!==password){
          document.getElementById("con").innerHTML = "Password not matching."
          return false;
    }
}

