<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;300;400;500;900&family=Ubuntu:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div class="header">
        <nav>
            <img src="images/logo.png" alt="" class="logo">
            <div>
                <button class="lang-btn">English <img src="images/down-icon.png" alt=""></button>
                <button>Sign In</button>
            </div>
        </nav>

        <div class="header-content">
            <h1>Unlimited movies, TV shows and more!!.</h1>
            <h3>Watch anywhere. Cancel anytime</h3>
            <p>Ready to watch? Enter  your email to create or restart your membership</p>

            <form class="email-signup">
                <input type="email" placeholder="enter email" required>
                <button type="submit">Get started</button>
            </form>
        </div>
    </div>
    

    <div class="features">
        <div class="row">
            <div class="text-col">
                <h2>Enjoy on your TV.</h2>
                <p>Watch on Smart TVs, Playstation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</p>
            </div> 
            <div class="img-col">
                <img src="images/feature-1.png" alt="">
            </div>
        </div>
        <div class="row">

            <div class="img-col">
                <img src="images/feature-2.png" alt="">
            </div>
            <div class="text-col">
                <h2>Download your shows to watch offline</h2>
                <p>Save your favorites easily and always have something to watch</p>
            </div> 
           
        </div>
        <div class="row">
            <div class="text-col">
                <h2>Watch everywhere</h2>
                <p>Stream unlimited movies and TV shows on your phones,TV's,tablet,laptop,PC</p>
            </div> 
            <div class="img-col">
                <img src="images/feature-3.png" alt="">
            </div>
        </div>
         <div class="row">
            <div class="img-col">
                <img src="images/feature-4.png" alt="">
            </div>
            <div class="text-col">
                <h2>Create profiles for children.</h2>
                <p>Send children on adventure with their favorite characters in space made just for them -free with your membership.</p>
            </div> 
            
        </div>
    </div>

    <div class="faq">
        <h2>Frequently Asked Question</h2>
        <ul class="accordian">
            <li>
                <input type="radio" name="accordian" id="first">
                <label for="first">What is AMAZON PRIME?</label>
                <div class="content">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint ut eligendi delectus soluta quod a vitae nam, debitis natus deleniti?
                </div>
            </li>
            <li>
                <input type="radio" name="accordian" id="second">
                <label for="second">How much does netflix cost?</label>
                <div class="content">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint ut eligendi delectus soluta quod a vitae nam, debitis natus deleniti?
                </div>
            </li>
            <li>
                <input type="radio" name="accordian" id="third">
                <label for="third">Where can i watch?</label>
                <div class="content">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint ut eligendi delectus soluta quod a vitae nam, debitis natus deleniti?
                </div>
            </li>
            <li>
                <input type="radio" name="accordian" id="fourth">
                <label for="fourth">How do i cancel?</label>
                <div class="content">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint ut eligendi delectus soluta quod a vitae nam, debitis natus deleniti?
                </div>
            </li>
            <li>
                <input type="radio" name="accordian" id="fifth">
                <label for="fifth">What can i watch in Netflix?</label>
                <div class="content">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint ut eligendi delectus soluta quod a vitae nam, debitis natus deleniti?
                </div>
            </li>
            <li>
                <input type="radio" name="accordian" id="sixth">
                <label for="sixth">Is AMAZON PRIME good for kids?</label>
                <div class="content">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint ut eligendi delectus soluta quod a vitae nam, debitis natus deleniti?
                </div>
            </li>
        </ul>
        <small>Ready to watch? Enter you email to to start or reset your membership</small>
        <form class="email-signup">
            <input type="email" placeholder="enter email" required>
            <button type="submit">Get started</button>
        </form>
    </div>


    <div class="footer">
        <h2>Question?  call- 000-000-000</h2>
        <div class="row">
            <div class="col">
                <a href="#">faq</a>
                <a href="">Investor Relations</a>
                <a href="">Privacy</a>
                <a href="">Speed Test</a>
            </div>
            <div class="col">
                <a href="#">Help Center</a>
                <a href="">Jobs</a>
                <a href="">Cookies Preferences</a>
                <a href="">Legal Notice</a>
            </div>
            <div class="col">
                <a href="#">Account</a>
                <a href="">Ways to Watch</a>
                <a href="">Corporate Information</a>
                <a href="">Only on AMAZONE PRIME</a>
            </div>
            <div class="col">
                <a href="#">Media Center</a>
                <a href="">Terms of use</a>
                <a href="">Contact US</a>
            </div>
        </div>
        <button class="lang-btn">English <img src="images/down-icon.png" alt=""></button>
        <p class="copyright-text">AMAZON India</p>
                
    </div>
</body>
</html>
