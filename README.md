<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Ankitha Konakanchi Portfolio</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    
  <link href="https://fonts.googleapis.com/css?family=Poppins:100,200,300,400,500,600,700,800,900" rel="stylesheet">

  <link rel="stylesheet" href="css/open-iconic-bootstrap.min.css">
    <link rel="stylesheet" href="css/animate.css">
    
  <link rel="stylesheet" href="css/owl.carousel.min.css">
    <link rel="stylesheet" href="css/owl.theme.default.min.css">
    <link rel="stylesheet" href="css/magnific-popup.css">

  <link rel="stylesheet" href="css/aos.css">

  <link rel="stylesheet" href="css/ionicons.min.css">
    
  <link rel="stylesheet" href="css/flaticon.css">
    <link rel="stylesheet" href="css/icomoon.css">
    <link rel="stylesheet" href="css/style.css">



<style>

/*======================================
//--//-->   ABOUT
======================================*/

.about-mf .box-shadow-full {
  padding-top: 4rem;
  padding-bottom: 4rem;
}

.about-mf .about-img {
  margin-bottom: 2rem;
}

.about-mf .about-img img {
  margin-left: 10px;
}


.skill-mf .progress {
  /* background-color: #cde1f8; */
  margin: .5rem 0 1.2rem 0;
  border-radius: 0;
  height: .7rem;
}

.skill-mf .progress .progress-bar {
  height: .7rem;
  background-color: #ffbd39;
}


/* Animation styles */
#typing-animation {
  position: relative;
  font-size: 30px;
  font-weight: bold;
  color: rgb(255, 255, 255);
  overflow: hidden;
  white-space: nowrap;
  animation: typing 3s steps(20, end) infinite;
}

#typing-animation:before {
  content: "";
  /* position: absolute; */
  top: 0;
  left: 0;
  width: 0;
  height: 100%;
  background-color: #ccc;
  animation: typing-cursor 0.5s ease-in-out infinite;
}

@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

@keyframes typing-cursor {
  from {
    width: 5px;
  }
  to {
    width: 0;
  }
}


/* project image zoom effect */

.zoom-effect {
  overflow: hidden;
  transition: transform 0.3s ease-out;
}

.zoom-effect:hover {
  transform: scale(1.1);
}


</style>


  </head>
  <body data-spy="scroll" data-target=".site-navbar-target" data-offset="300">
	  
	  
  <nav class="navbar navbar-expand-lg navbar-dark ftco_navbar ftco-navbar-light site-navbar-target" id="ftco-navbar">
	    <div class="container">
	      <a class="navbar-brand" href="index.html">Ankitha Konakanchi</a>
	      <button class="navbar-toggler js-fh5co-nav-toggle fh5co-nav-toggle" type="button" data-toggle="collapse" data-target="#ftco-nav" aria-controls="ftco-nav" aria-expanded="false" aria-label="Toggle navigation">
	        <span class="oi oi-menu"></span> Menu
	      </button>

<div class="collapse navbar-collapse" id="ftco-nav">
	        <ul class="navbar-nav nav ml-auto">
	          <li class="nav-item"><a href="#home-section" class="nav-link"><span>Home</span></a></li>
	          <li class="nav-item"><a href="#about-section" class="nav-link"><span>About</span></a></li>
	          <li class="nav-item"><a href="#resume-section" class="nav-link"><span>Resume</span></a></li>
	          <!-- <li class="nav-item"><a href="#project-section" class="nav-link"><span>Projects</span></a></li> -->
	          <li class="nav-item"><a href="#contact-section" class="nav-link"><span>Contact</span></a></li>
	        </ul>
	      </div>
	    </div>
	  </nav>
	  <section id="home-section" class="hero">
		  <div class="home-slider  owl-carousel">
	       <div class="slider-item ">
	      	<div class="overlay"></div>
	         <div class="container">
	          <div class="row d-md-flex no-gutters slider-text align-items-end justify-content-end" data-scrollax-parent="true">
	          	<div class="one-third js-fullheight order-md-last img" style="background-image:url(C:\Users\akona\OneDrive\Desktop);">
	          	 <div class="overlay"></div>
	          	</div>
		          <div class="one-forth d-flex  align-items-center ftco-animate" data-scrollax=" properties: { translateY: '70%' }">
		          	<div class="text">
		          		<span class="subheading">Hello!</span>
			            <h1 class="mb-4 mt-3">I'm <span>Ankitha Konakanchi</span></h1>
<!-- Element to contain animated typing -->
						<span id="typing-animation"></span>

<script>

						// Initialize the typing animation
						const typingAnimationElement = document.getElementById('typing-animation');

						// Create an array of typing text
						const typingTexts = [
						'Full Stack Java Developer  ',
												];

						// Create a function to display the typing animation for a given text
						function playTypingAnimation(text) {
						// Loop through each character and add it to the element
						for (let i = 0; i < text.length; i++) {
							setTimeout(() => {
							typingAnimationElement.textContent += text[i];
							}, i * 200); // Increase the delay to slow down the typing animation
						}

						// Once the animation is complete, reset the text and start over
						setTimeout(() => {
							typingAnimationElement.textContent = '';
							playTypingAnimation(typingTexts[(typingTexts.indexOf(text) + 1) % typingTexts.length]);
						}, text.length * 200);
						}

						// Start the typing animation loop
						playTypingAnimation(typingTexts[0]);

						</script>

<br>
						<br>
      <!-- <h2 class="d-flex" style="margin-bottom: 0">With over 5 years of experience</h2> -->
      <!-- <br> -->
			            <p><a href="https://www.linkedin.com/in/ankitha-konakanchi-7b93302b1" class="btn btn-primary py-3 px-4">linkedin</a> 
             <!-- <a href="https://github.com/rishabhnmishra" class="btn btn-white btn-outline-white py-3 px-4">My works</a></p> -->
		            </div>
		          </div>
	        	</div>
	        </div>
	      </div>
		</div>
    </section>



  <section class="ftco-about img ftco-section ftco-no-pb" id="about-section">
    	<div class="container">
			<div class="row">
				<div class="row d-flex align-items-stretch">
				<!-- <div class="row d-flex"> -->
					<div class="col-md-6 col-lg-5 d-flex">
						<div class="img-about img d-flex align-items-stretch">
							<div class="overlay">
								<div class="row">
									<div class="col-sm-6 col-md-5">
									  <div class="about-img">
										<img src="images/aboutmeDeepak.jpeg" class="img-fluid rounded b-shadow-a" alt="">
									  </div>
									</div>
									<!-- Details next to profile image -->
									<div class="col-sm-6 col-md-7">
									  <div class="about-info">
										<p><span class="title-s">Name: </span> <span>Ankitha Konakanchi</span></p>
										<p><span class="title-s">Job Role: </span> <span>Full Stack Java Developer</span></p>
										<p><span class="title-s">Experience: </span> <span>5+ Years</span></p>
										<p><span class="title-s">Address: </span> <span>Texas</span></p>
									  </div>
									</div>
								  </div>

<div class="skill-mf">
									<p class="title-s">Skills</p>
									<span>Frontend Developer</span> <span class="pull-right">95%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 75%;" aria-valuenow="80" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
									
<span>Backend Developer</span> <span class="pull-right">85%</span>
									<div class="progress">
										<div class="progress-bar" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0"
											aria-valuemax="100"></div>
									</div>
								</div>
							</div>
						</div>
					</div>
					
<div class="col-md-6 col-lg-7 pl-lg-5 pb-5">
						<div class="row justify-content-start pb-3">
							<div class="col-md-12 heading-section ftco-animate">
								
<h1 class="big">About</h1>
								<h2 class="mb-4">About Me</h2>
								
<p>I am a proficient Python Full Stack Developer with 5 years of experience in building scalable and efficient web applications. I specialize in Java and Spring Boot for back-end development, creating RESTful APIs, and implementing microservices architectures. On the front-end, I work with technologies like React.js, Angular, HTML5, CSS3, and JavaScript to deliver responsive and user-friendly interfaces.I have expertise in databases such as MySQL, PostgreSQL, and MongoDB, along with experience in deploying applications using AWS and Azure cloud platforms. My skillset includes setting up CI/CD pipelines using Jenkins, Docker, and Kubernetes, ensuring seamless integration and deployment.I follow Agile methodologies and emphasize writing clean, maintainable code. Passionate about solving problems and optimizing performance, I thrive in collaborative environments to deliver impactful, business-focused solutions.</p>
								<ul class="about-info mt-4 px-md-0 px-2">
									<li class="d-flex"><span>Profile:</span> <span>Full Stack Java Developer </span></li>
									<li class="d-flex"><span>Education:</span> <span>M.S. in Information Technology Management</span></li>
									<li class="d-flex"><span>Language:</span> <span>English, Telugu</span></li>
									<li class="d-flex"><span>Interest:</span> <span>Traveling, Music</span></li>
								</ul>
							</div>
						</div>


<div class="counter-wrap ftco-animate d-flex mt-md-3">
							<div class="text">
								<p><a href="https://www.linkedin.com/in/ankitha-konakanchi-7b93302b1/" class="btn btn-primary py-3 px-3">LinkedIn</a></p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
    </section>



	
  <section class="ftco-section ftco-no-pb" id="resume-section">
    	<div class="container">
    		<div class="row justify-content-center pb-5">
          <div class="col-md-10 heading-section text-center ftco-animate">
          	<h1 class="big big-2">Resume</h1>
            <h2 class="mb-4">Resume</h2>
            <p>I am a skilled Python Full Stack Developer with expertise in Spring Boot, React.js, and microservices architecture, specializing in building scalable and user-friendly web applications. I have experience with databases like MySQL and MongoDB, cloud platforms such as AWS and Azure, and CI/CD tools like Jenkins and Docker. Passionate about clean code and collaboration, I deliver impactful solutions aligned with business goals.</p>
          </div>
        </div>

<div class="row">
			<h1 class="big-4">Experience</h1>
			<div class="underline"></div>
		</div>
		<br>
		
<div class="row">
				<div class="col-md-6">
					<div class="Micron">
						<span class="date">Sep 2023-present</span>
						<h2>Full Stack developer</h2>
						<span class="position"></span>
						<p class="mt-4">Ensuring quality and uptime of joining equipment, along with making improvements and engineering changes in joining process by analyzing faults and data and finding solutions for the issues. 
							<ul>
								<li>Provide support to production line to solve issues and increase equipment efficiency.</li>
								<li>working on providing solutions on defect tracking system .</li>
								
</ul>
						</p>
					</div>

</div>

<div class="col-md-6">
					<div class="resume-wrap ftco-animate">
						<span class="date">october 2021- August 2023</span>
						<h2>Developer</h2>
						<span class="position">Aarete Chicago,IL</span>
						<p class="mt-4">Identifying savings opportunities in supply chain, procurement, and organizational processes.. 
							<ul>
								<li>Helping organizations leverage modern technologies to streamline operations.
Providing solutions like AI, machine learning, and automation for enhanced productivity..</li>
								
</ul>
						</p>
					</div>

</div>
			</div>

<br>
		<br>
<div class="row">
			<h1 class="big-4">Education</h1>
			<div class="underline"></div>
		</div>
		<br>
		
<div class="row">
    			<div class="col-md-6">
    				<div class="resume-wrap ftco-animate">
    					<span class="date">2012-2016</span>
    					<h2>Bachelor of Engineering</h2>
    					<span class="position">Computer Science Engineering</span>
    					<p class="mt-4">GPA : 3.48</p>
    				</div>
    			</div>

  <div class="col-md-6">
    				<div class="resume-wrap ftco-animate">
    					<span class="date">2023-2024</span>
    					<h2>Master of Science</h2>
    					<span class="position">Information Technology Management</span>
    					<p class="mt-4">GPA : 3.2</p>
    				</div>
				</div>
    		</div>
<!-- <
<section class="ftco-section ftco-no-pt ftco-no-pb ftco-counter img" id="section-counter"
<div class="container">
		<div class="row d-md-flex align-items-center">
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="20">0</strong>
                <span>Achievements</span>
              </div>
            </div>
          </div>
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="30">0</strong>
                <span>Projects</span>
              </div>
            </div>
          </div>
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="1000">0</strong>
                <span>Mentored Students</span>
              </div>
            </div>
          </div>
          <div class="col-md d-flex justify-content-center counter-wrap ftco-animate">
            <div class="block-18">
              <div class="text">
                <strong class="number" data-number="500">0</strong>
                <span>Cups of coffee</span>
              </div>
            </div>
          </div>
        </div>
      </div>
	
	  <div class="ftco-section ftco-hireme img margin-top" style="background-image: url(images/bg_1.jpg)">
			<!-- <div class="container"> -->
				<!-- <div class="row justify-content-center">
					<div class="col-md-7 ftco-animate text-center">
						<h2>More projects on<span> Github  </span> </h2>
						<div class="heading"> <h4> I love to solve business problems &amp; uncover hidden data stories </h4>
						<br>
						<p><a href="https://github.com/rishabhnmishra" class="btn btn-primary py-3 px-5">GitHub</a></p>
						</div>
					</div> -->
				</div>
			<!-- </div> -->
		</div>
	</section>



    <section class="ftco-section contact-section ftco-no-pb" id="contact-section">
      <div class="container">
      	<div class="row justify-content-center mb-5 pb-3">
          <div class="col-md-7 heading-section text-center ftco-animate">
            <h1 class="big big-2">Contact</h1>
            <h2 class="mb-4">Contact Me</h2>
            <p>Below are the details to reach out to me!</p>
          </div>
        </div>

        <div class="row d-flex contact-info mb-5">
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-map-signs"></span>
          		</div>
          		<h3 class="mb-4">Address</h3>
	            <p>1708 12th St S,Birmingham, AL 35205</p>
	          </div>
          </div>
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-phone2"></span>
          		</div>
          		<h3 class="mb-4">Contact Number</h3>
	            <p><a href="tel://6592538780">+1 (659)253-8780</a></p>
	          </div>
          </div>
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-paper-plane"></span>
          		</div>
          		<h3 class="mb-4">Email Address</h3>
	            <p><a href="deepak.kuruva@gmail.com">deepak.kuruva@gmail.com</a></p>
	          </div>
          </div>
          <div class="col-md-6 col-lg-3 d-flex ftco-animate">
          	<div class="align-self-stretch box p-4 text-center">
          		<div class="icon d-flex align-items-center justify-content-center">
          			<span class="icon-globe"></span>
          		</div>
          		<h3 class="mb-4">Download Resume</h3>
	            <p><a href="https://drive.google.com/file/d/1iqNCAQ7nIvtQrCiSGcijEjkp7VeTe151/view?usp=sharing">Resumelink</a></p>
	          </div>
          </div>

		  <div class="container">
			<br>
			<br>
			<div class="row justify-content-center">
				<div class="col-md-7 ftco-animate text-center">
					<h2>Have a<span> Question?  </span> <a href="" class="btn btn-primary py-3 px-5">Click Here</a> </h2>
				</div>
			</div>
				<br>
					<ul class="ftco-footer-social list-unstyled d-flex justify-content-center align-items-center mb-0">
					  <li class="ftco-animate normal-txt">Find me on  </li>
					  <!-- <li class="ftco-animate"><a href="https://www.youtube.com/@RishabhMishraOfficial"><span class="icon-youtube"></span></a></li> -->
					  <li class="ftco-animate"><a href="http://linkedin.com/in/deepak-kuruva-78353b246"><span class="icon-linkedin"></span></a></li>  
				</ul>
				<br>
		   </div>
   </div>
 </section>


 
	
<footer class="ftco-footer ftco-section">
		<div class="container">
		  <div class="row">
			<div class="col-md-12 text-center">
  <p><!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved | This template is made with <i class="icon-heart color-danger" aria-hidden="true"></i> by <a href="https://colorlib.com" target="_blank">Colorlib</a>
	  <!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. --></p>
			</div>
		  </div>
		</div>
	  </footer>


  <!-- loader -->
  <div id="ftco-loader" class="show fullscreen"><svg class="circular" width="48px" height="48px"><circle class="path-bg" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke="#eeeeee"/><circle class="path" cx="24" cy="24" r="22" fill="none" stroke-width="4" stroke-miterlimit="10" stroke="#F96D00"/></svg></div>


  <script src="js/jquery.min.js"></script>
  <script src="js/jquery-migrate-3.0.1.min.js"></script>
  <script src="js/popper.min.js"></script>
  <script src="js/bootstrap.min.js"></script>
  <script src="js/jquery.easing.1.3.js"></script>
  <script src="js/jquery.waypoints.min.js"></script>
  <script src="js/jquery.stellar.min.js"></script>
  <script src="js/owl.carousel.min.js"></script>
  <script src="js/jquery.magnific-popup.min.js"></script>
  <script src="js/aos.js"></script>
  <script src="js/jquery.animateNumber.min.js"></script>
  <script src="js/scrollax.min.js"></script>
  
  <script src="js/main.js"></script>
    
  </body>
</html>
