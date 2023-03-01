# XenonStack_Technical-round-Task



Welcome to caR selling website! We are a platform that connects car buyers and sellers in a convenient and hassle-free way. Our goal is to make the car buying and selling experience as smooth as possible for everyone involved.

******How it Works*****
Post your car: Sellers can post their cars for sale on our platform, including the make and model, year, mileage, and any other relevant details.
Search for cars: Buyers can search for cars on our platform, using filters such as make and model, price range, and location.
Connect with sellers: Once a buyer finds a car they are interested in, they can connect with the seller through our platform to ask questions and schedule a test drive.
Complete the sale: If the buyer decides to purchase the car, they can complete the sale through our platform, which includes secure payment processing and transfer of ownership documents.
Benefits for Car Sellers
Wide audience: Our platform connects car sellers with a wide audience of potential buyers, increasing their chances of selling their car quickly.
Convenience: Posting a car for sale on our platform is easy and convenient, and sellers can manage their listing and communicate with potential buyers all in one place.
Secure transactions: Our platform offers secure payment processing and transfer of ownership documents to protect both the seller and the buyer.
Benefits for Car Buyers
Easy search: Our platform makes it easy for car buyers to search for cars using filters such as make and model, price range, and location.
Transparent information: Car buyers can access all relevant information about the car, including its history and any damage or repairs, so they can make an informed decision.
Secure transactions: Our platform offers secure payment processing and transfer of ownership documents to protect both the seller and the buyer.
How to Get Started
Create an account: Car sellers and buyers can create an account on our platform to get started.
Post a car for sale or search for cars: Car sellers can post their cars for sale, and car buyers can search for cars on our platform.
Connect and complete the sale: Once a buyer finds a car they are interested in, they can connect with the seller through our platform to ask questions and schedule a test drive. If they decide to purchase the car, they can complete the sale through our platform.
Thank you for choosing our caR selling website. If you have any questions or concerns, please don't hesitate to contact us.











--------------------------------HTML CODE------------------------------

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website with Login & Registration</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <h2 class = "BuyourfirstCar"> BuyourfirstCar</h2>
        <nav class = "navigation">
            <a href = "#">Home</a>
            <a href = "#">About</a>
            <a href = "#">Service</a>
            <a href = "contact.html">Contact</a>
            <button class = "btnLogin-popup">Login</button>
        </nav>
    </header>



    <div class = "wrapper">
        <span class="icon-close"><ion-icon name="close-circle-sharp"></ion-icon></span>


        <div class = "form-box login">
            <h2>Login</h2>
            <form action="#">
                <div class = "input-box">
                    <span class = "icon"><ion-icon name="mail-sharp"></ion-icon>
                    </span>
                    <input type="email" required>
                    <label> Email</label>

                </div>

                <div class = "input-box">
                    <span class = "icon"><ion-icon name="lock-closed-sharp"></ion-icon></span>
                    <input type="password" required>
                    <label>Password</label>

                </div>


                <div class = "remember-forgot">
                    <label>
                        <input type="checkbox">
                        Remember me
                    </label>
                    <a href="#">Forgot Password?</a>
                
                </div>

                <button type="submit" class="btn">Login</button>

                <div class="login-register">
                    <p>Don't have an account?<a href="#" class="register-link">Register</a></p>
                </div>

            </form>

        </div>

        <div class = "form-box register">
            <h2>Registration</h2>
            <form action="#">

                <div class = "input-box">
                    <span class = "icon"><ion-icon name="person-sharp"></ion-icon>
                    </span>
                    <input type="text" required>
                    <label>Username</label>

                </div>

                <div class = "input-box">
                    <span class = "icon"><ion-icon name="mail-sharp"></ion-icon>
                    </span>
                    <input type="email" required>
                    <label> Email</label>

                </div>
<!--
                <div class = "input-box">
                    <span class = "icon"><ion-icon name="person-sharp"></ion-icon>
                    </span>
                    <input type="text" required>
                    <label>Username</label>

                </div>  -->

                <div class = "input-box">
                    <span class = "icon"><ion-icon name="lock-closed-sharp"></ion-icon></span>
                    <input type="password" required>
                    <label>Password</label>

                </div>


                <div class = "remember-forgot">
                    <label>
                        <input type="checkbox">
                        I agree to the term and conditions
                    </label>
                    <a href="#">Forgot Password?</a>
                
                </div>

                <button type="submit" class="btn">Register</button>

                <div class="login-register">
                    <p>Already have an account?<a href="#" class="login-link">Login</a></p>
                </div>

            </form>

        </div>
    </div>


    
    <script src ="script.js"></script>
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>


</body>
</html>



------------------------------------CONTACT PAGE-------------------------------------------------

<!DOCTYPE html>
<html>
<head>
	<title>Contact us</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link href="https://fonts.googleapis.com/css?family=Quicksand&display=swap" rel="stylesheet">
	<meta name="viewport" content="width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0">
</head>
<body>
	<div class="container">
		<div class="contact-box">
			<div class="left"></div>
			<div class="right">
				<h2>Contact Us</h2>
				<input type="text" class="field" placeholder="Your Name">
				<input type="text" class="field" placeholder="Your Email">
				<input type="text" class="field" placeholder="Phone">
				<textarea placeholder="Message" class="field"></textarea>
				<button class="btn">Send</button>
			</div>
		</div>
	</div>
</body>
</html>




------------------------------------------------CSS CODE--------------------------------------------------------------


*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}


body{
    display: flex;
    justify-content: center;
    align-items: top; /* <---------------align-items: center*/
    align-content: center;
    min-height: 100vh;
    background-image: url('background.jpg');
    background-size: cover;
    background-position: center;

}



header{
    position: fixed;
    top:'0';
    left:'0';
    width: 100%;
    padding: 20px 100px;
    /*background: red;*/     
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 99; 
}

.logo{
    font-size: 2em;
    color: white;
    user-select: none;
}

.navigation a {
    position: relative;
    font-size: 1.1em;
    color: white;
    text-decoration: none;
    font-weight: 500;
    margin-left: 40px;
}


.navigation a::after {
    content: '';
    position: absolute;
    left: 0;
    bottom: -6px;
    width: 100%;
    height: 3px;
    background: #fff;
    border-radius: 5px;
    transform-origin: right;
    transform: scaleX(0);
    transition: transform .5s;

}

.navigation a:hover::after{
    transform-origin: left;
    transform: scaleX(1);

}


.navigation .btnLogin-popup{
    width: 130px;
    height: 50px;
    background: transparent;
    border: 2px solid #fff;
    outline: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1.1em;
    color: #fff;
    font-weight: 500;
    margin-left: 40px;
    transition: .5s;
}

.navigation .btnLogin-popup:hover{
    background: #fff;
    color: #162938;
}


.wrapper {
    position: relative;
    width: 400px;
    height: 440px;
    background: transparent;
    border: 2px solid rgba(255, 255, 255, .5);
    border-radius: 20px;
    backdrop-filter: blur(20px);
    box-shadow: 0 0 30px rgba(0, 0, 0, .5); 
    display: flex;
    justify-content: center;
    align-items: center;
    /*overflow: hidden; */
    transition: height .2s ease;
}



.wrapper.active{
    height:520px
}



/*
.wrapper .form-box{
    width: 100px;
    padding: 40px;
} */


.wrapper .form-box.login {
    transition: transform .18s ease;
    transform: translateX(0);
} 


.wrapper.active .form-box.login {
    transition: none;
    transform: translateX(-400px);
}


.wrapper .form-box.register {
    position: absolute;
    transition: none;
    transform: translateX(400px);
}

.wrapper.active .form-box.register {
    transition: transform .18s ease;
    transform: translateX(0);
} 



.wrapper .icon-close {
    position: absolute;
    top: 0;
    right: 0;
    width: 45px;
    height:45px;
    background:#162938;
    font-size: 2em;
    color:#fff;
    display: flex;
    justify-content: center;
    align-items: center;
    border-bottom-left-radius: 20px;
    cursor: pointer;
    z-index: 1;
    
}




.form-box h2{
    font-size: 2em;
    color:#162938;
    text-align: center;
}



.input-box{

    position: relative;
    width: 100%;
    height: 50px;
    border-bottom: 2px solid #162938;
    margin: 30px 0;
}


.input-box label{
    position: absolute;
    top: 80%;
    left: 2px;
    transform: translateY(-50%);
    font-size: 1em;
    color: #162938;
    font-weight: 500;
    pointer-events: none;
    transition: .5s;

}


/*
.input-box input:focus~label,
.input-box input:valid~label {
    top: -5;
}   */ 

.input-box input{
    
    width: 100%;
    height: 50%; 
    background: transparent;
    border:none;
    outline: auto;
    font-size: 0.9em;
    color: #162938;
    font-weight: 600;
}

.input-box .icon{
    position: absolute;
    top: 10px;
    right: 8px;
    font-size: 1em;
    color: #162938;
    line-height: 57px;
}


.remember-forgot {
    font-size: 0.7em;
    color: #162938;
    font-weight: 500;
    margin: -15px 0 15px;
    display: flex;
    justify-content: space-between;

}

.remember-forgot label input{
    accent-color: #162938;
    margin-right: 3px;
}

.remember-forgot a {
    color: #162938;
    text-decoration: none;   
}

.remember-forgot a:hover {
    text-decoration: underline;
}

.btn {
    width: 100%;
    height: 45px;
    background: #162938;
    outline: none;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1em;
    color: #fff;
    font-weight: 500;
}

.login-register {
    font-size: .9em;
    color: #162938;
    text-align: center;
    font-weight: 500;
    margin: 25px 0 10px;


}

.login-register p a {
    color: #162938;
    text-decoration: none;
    font-size: 1em;
    font-weight: 600;
}    

.login-register p a:hover{
    text-decoration: underline;
}





/*contact page*/
.container{
	position: relative;
	width: 100%;
	height: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
	padding: 20px 100px;
}

.container:after{
	content: '';
	position: absolute;
	width: 100%;
	height: 100%;
	left: 0;
	top: 0;
	background: url("img/bg.jpg") no-repeat center;
	background-size: cover;
	filter: blur(50px);
	z-index: -1;
}
.contact-box{
	max-width: 850px;
	display: grid;
	grid-template-columns: repeat(2, 1fr);
	justify-content: center;
	align-items: center;
	text-align: center;
	background-color: #fff;
	box-shadow: 0px 0px 19px 5px rgba(0,0,0,0.19);
}

.left{
	background: url("img/bg.jpg") no-repeat center;
	background-size: cover;
	height: 100%;
}

.right{
	padding: 25px 40px;
}

h2{
	position: relative;
	padding: 0 0 10px;
	margin-bottom: 10px;
}

h2:after{
	content: '';
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
    height: 4px;
    width: 50px;
    border-radius: 2px;
    background-color: #2ecc71;
}

.field{
	width: 100%;
	border: 2px solid rgba(0, 0, 0, 0);
	outline: none;
	background-color: rgba(230, 230, 230, 0.6);
	padding: 0.5rem 1rem;
	font-size: 1.1rem;
	margin-bottom: 22px;
	transition: .3s;
}

.field:hover{
	background-color: rgba(0, 0, 0, 0.1);
}

textarea{
	min-height: 150px;
}

.btn{
	width: 100%;
	padding: 0.5rem 1rem;
	background-color: #2ecc71;
	color: #fff;
	font-size: 1.1rem;
	border: none;
	outline: none;
	cursor: pointer;
	transition: .3s;
}

.btn:hover{
    background-color: #27ae60;
}

.field:focus{
    border: 2px solid rgba(30,85,250,0.47);
    background-color: #fff;
}

@media screen and (max-width: 880px){
	.contact-box{
		grid-template-columns: 1fr;
	}
	.left{
		height: 200px;
	}
}






----------------------------------------------------JAVASCRIPT CODE------------------------------------------------

const wrapper = document.querySelector('.wrapper');
const loginLink = document.querySelector('.login-link');
const registerLink = document.querySelector('.register-link');

registerLink.addEventListener('click', ()=>{
    wrapper.classList.add(active);

});

loginLink.addEventListener('click', ()=>{
    wrapper.classList.remove(active);
    

});





-------------------------------------------OUTPUT---------------------------------------------------------



