<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Islamic Thoughts</title>
<link href="https://fonts.googleapis.com/css2?

family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
<script src="https://kit.fontawesome.com/a076d05399.js"></script>
<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #0f3d3e;
    color: white;
}

/* AUTH PAGE */
#authPage {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
.auth-box {
    background: #1e2a2f;
    padding: 40px;
    border-radius: 10px;
    width: 320px;
    text-align: center;
}
.auth-box h2 { color: #d4af37; }
.auth-box input { width: 90%; padding: 10px; margin: 10px 0; border-radius: 

5px; border: none; }
.auth-box button { background: #d4af37; border: none; padding: 10px 20px; 

border-radius: 5px; font-weight: bold; cursor: pointer; }
.auth-box a { color: #d4af37; cursor: pointer; display: block; margin-top: 

10px; }

/* MAIN SITE */
#mainSite { display: none; }
nav {
    background: #0f3d3e;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
nav h2 { color: #d4af37; }
.hero {
    height: 70vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: #123f40;
}
.hero h1 { font-size: 45px; color: #d4af37; }
section { padding: 50px 20px; text-align: center; }
.btn { background: #d4af37; padding: 10px 25px; color: #0f3d3e; text-

decoration: none; border-radius: 5px; font-weight: bold; margin: 5px; display: 

inline-block; }

/* QURAN SECTION */
#quran {
    background-color: #1e2a2f;
    padding: 50px 20px;
    color: #d4af37;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}
.quran-card {
    background: #2a2a2a;
    padding: 30px;
    width: 250px;
    border-radius: 10px;
    transition: 0.3s;
    text-align: center;
}
.quran-card:hover { transform: translateY(-10px); background: #0f3d3e; }
.quran-card a { color: #d4af37; text-decoration: none; font-weight: bold; }
.quran-card a:hover { color: #fff; }

/* SOCIAL MEDIA SECTIONS */
.social-section { background: #1e2a2f; margin: 30px auto; padding: 30px 

20px; max-width: 600px; border-radius: 10px; }
.social-section h3 { color: #d4af37; margin-bottom: 15px; }
.social-section a { display: inline-block; margin: 5px; }

/* STAR RATING */
.stars {
    font-size: 35px;
    cursor: pointer;
    color: gray;
    transition: color 0.2s;
}
.stars span.active,
.stars span:hover,
.stars span:hover ~ span { color: gold; }

/* FEEDBACK & REVIEWS */
#feedback textarea, #reviewText { width: 90%; height: 100px; border-radius: 

5px; padding: 10px; border: none; margin-top:10px; }
#reviewList { margin-top: 20px; text-align: left; max-width: 500px; margin-

left:auto; margin-right:auto; }

/* FOOTER */
footer { background: #111; padding: 20px; text-align: center; border-top: 

3px solid #d4af37; }
footer p { margin: 5px; }
.social-icons a { color: white; font-size: 28px; margin: 0 10px; }
.social-icons a:hover { color: #d4af37; }

@media (max-width:768px){
    .hero h1 { font-size: 28px; }
    .auth-box { width: 90%; }
    #quran { flex-direction: column; align-items: center; }
}
</style>
</head>
<body>

<!-- LOGIN & SIGNUP -->
<div id="authPage">
    <div class="auth-box" id="loginBox">
        <h2>Login</h2>
        <input type="text" id="loginName" placeholder="Enter Name">
        <input type="password" id="loginPass" placeholder="Enter 

Password">
        <label><input type="checkbox" id="showLoginPassword" 

onclick="togglePassword('login')"> Show Password</label><br><br>
        <button onclick="login()">Login</button>
        <a onclick="showSignup()">Create New Account</a>
        <a onclick="forgotPass()">Forgot Password?</a>
    </div>
    <div class="auth-box" id="signupBox" style="display: none;">
        <h2>Sign Up</h2>
        <input type="text" id="signupName" placeholder="Create Name">
        <input type="email" id="signupEmail" placeholder="Enter Email">
        <input type="password" id="signupPass" placeholder="Create 

Password">
        <label><input type="checkbox" id="showSignupPassword" 

onclick="togglePassword('signup')"> Show Password</label><br><br>
        <button onclick="signup()">Create Account</button>
        <a onclick="showLogin()">Back to Login</a>
    </div>
</div>

<!-- MAIN SITE -->
<div id="mainSite">
<nav>
    <h2>Islamic Thoughts</h2>
    <a href="https://wa.me/923447256084" class="btn" 

target="_blank">WhatsApp</a>
</nav>

<div class="hero">
    <div>
        <h1>Islamic Thoughts</h1>
        <p>Quran & Sunnah Guidance for Life</p>
    </div>
</div>

<!-- QURAN SECTION -->
<section id="quran">
    <div class="quran-card">
        <h3><a href="https://quran.com/" target="_blank">Quran 

Majeed</a></h3>
        <p>Read verses from the Holy Quran online.</p>
    </div>
    <div class="quran-card">
        <h3><a href="https://sunnah.com/" target="_blank">Hadith</a></h3>
        <p>Authentic sayings of Prophet Muhammad ﷺ.</p>
    </div>
    <div class="quran-card">
        <h3><a href="https://quran.com/ayaat" 

target="_blank">Ayyat</a></h3>
        <p>Inspiring Quranic Ayyat and verses.</p>
    </div>
    <div class="quran-card">
        <h3><a href="https://www.al-islam.org/seerah-ahlul-bayt" 

target="_blank">Seerat Ahl e Bait</a></h3>
        <p>Learn about the lives of Ahlul Bayt.</p>
    </div>
</section>

<!-- SOCIAL MEDIA SECTIONS -->
<section class="social-section">
<h3>YouTube Channel</h3>
<a href="https://www.youtube.com/@IslamicThoughts-of" class="btn" 

target="_blank">Visit YouTube</a>
</section>

<section class="social-section">
<h3>TikTok Account</h3>
<a href="https://www.tiktok.com/@imranshahs0" class="btn" 

target="_blank">Visit TikTok</a>
</section>

<section class="social-section">
<h3>Twitter Profile</h3>
<a href="https://twitter.com/IslamicThoughts" class="btn" 

target="_blank">Visit Twitter</a>
</section>

<section class="social-section">
<h3>Facebook Page</h3>
<a href="https://www.facebook.com/IslamicThoughts" class="btn" 

target="_blank">Visit Facebook</a>
</section>

<section class="social-section">
<h3>WhatsApp Chat</h3>
<a href="https://wa.me/923447256084" class="btn" 

target="_blank">Chat on WhatsApp</a>
</section>

<!-- STAR RATING WITH REVIEW -->
<section>
<h2 style="color:#d4af37;">Rate Our Website & Add Review</h2>
<div class="stars">
    <span data-value="1">★</span>
    <span data-value="2">★</span>
    <span data-value="3">★</span>
    <span data-value="4">★</span>
    <span data-value="5">★</span>
</div>
<p id="ratingResult"></p>
<textarea id="reviewText" placeholder="Write your review 

here..."></textarea><br>
<button class="btn" onclick="submitReview()">Submit Review</button>
<div id="reviewList"></div>
</section>

<!-- FEEDBACK -->
<section id="feedback">
<h2 style="color:#d4af37;">Send Feedback</h2>
<textarea id="feedbackText" placeholder="Write your 

feedback..."></textarea><br>
<button class="btn" onclick="submitFeedback()">Submit Feedback</button>
<p id="feedbackMsg"></p>
</section>

<!-- FOOTER / SOCIAL MEDIA -->
<footer>
<p>&copy 2026 Islamic Thoughts|All Right Reserved</p>
<div class="social-icons">
    <a href="https://www.youtube.com/@IslamicThoughts-o3f" 

target="_blank"><i class="fab fa-youtube"></i></a>
    <a href="https://www.tiktok.com/@imranshahs0" target="_blank"><i 

class="fab fa-tiktok"></i></a>
    <a href="https://twitter.com/IslamicThoughts" target="_blank"><i 

class="fab fa-twitter"></i></a>
    <a href="https://www.facebook.com/IslamicThoughts" 

target="_blank"><i class="fab fa-facebook"></i></a>
    <a href="https://wa.me/923447256084" target="_blank"><i class="fab 

fa-whatsapp"></i></a>
</div>
</footer>

<script>
// LOGIN / SIGNUP
function showSignup(){ loginBox.style.display="none"; 

signupBox.style.display="block"; }
function showLogin(){ signupBox.style.display="none"; 

loginBox.style.display="block"; }
function signup(){
    localStorage.setItem("name", signupName.value);
    localStorage.setItem("pass", signupPass.value);
    localStorage.setItem("email", signupEmail.value);
    alert("Account Created Successfully!");
    showLogin();
}
function login(){
    if(loginName.value===localStorage.getItem("name") && 

loginPass.value===localStorage.getItem("pass")){
        authPage.style.display="none"; mainSite.style.display="block";
    } else { alert("Wrong Name or Password!"); }
}
function forgotPass(){
    let email=prompt("Enter your registered email:");
    if(email===localStorage.getItem("email")){ alert("Your Password is: 

"+localStorage.getItem("pass")); }
    else { alert("Email not found!"); }
}
function togglePassword(type){
    let pass=document.getElementById

(type==='login'?'loginPass':'signupPass');
    let check=document.getElementById

(type==='login'?'showLoginPassword':'showSignupPassword');
    pass.type=check.checked?"text":"password";
}

// STAR RATING & REVIEW
const stars=document.querySelectorAll(".stars span");
let selectedRating=0;
stars.forEach(star=>{
    star.addEventListener("click",function(){
        selectedRating=parseInt(this.getAttribute("data-value"));
        stars.forEach(s=>s.classList.toggle("active", parseInt(s.getAttribute

("data-value"))<=selectedRating));
        document.getElementById("ratingResult").innerText="You rated 

"+selectedRating+" Star"+(selectedRating>1?'s':'')+" ⭐";
    });
});
function submitReview(){
    const reviewText=document.getElementById("reviewText").value.trim();
    if(selectedRating===0){ alert("Please select star rating!"); return; }
    if(reviewText===""){ alert("Please write review!"); return; }
    const list=document.getElementById("reviewList");
    const p=document.createElement("p");
    p.innerText="⭐".repeat(selectedRating)+" - "+reviewText;
    list.prepend(p);
    document.getElementById("reviewText").value="";
    selectedRating=0; stars.forEach(s=>s.classList.remove("active"));
    document.getElementById("ratingResult").innerText="";
}

// FEEDBACK
function submitFeedback(){
    let text=document.getElementById("feedbackText").value.trim();
    if(!text){ alert("Please write feedback first!"); return; }
    document.getElementById("feedbackMsg").innerText="Thank you for 

your feedback ❤️";
    document.getElementById("feedbackText").value="";
}
</script>

</body>
</html>
