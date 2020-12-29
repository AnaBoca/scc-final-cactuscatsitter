<!DOCTYPE html>
<html lang="en">

<head>
  <title>Home | Cactus Cat Sitter</title>
  
	<link rel="icon" href="favicon.ico" />
	
	<meta charset="utf-8">
  
	<!-- Required meta tag for resposive pages -->
	<meta name="viewport" content="width=device-width, initial-scale=1">
	
	<!-- Latest compiled and minified bootstrap CSS -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css">
		<!-- LINK TO LOCAL STYLESHEET -->
		<link href="cactus.css" rel="stylesheet">
		<!-- LINK TO GOOGLE FONTS - SATISFY -->
		<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Satisfy"/>

	<!-- Font Awesome -->
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css">
	
	<!-- jQuery library -->
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

	<!-- Popper JS -->
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.6/umd/popper.min.js"></script>

	<!-- Latest compiled JavaScript -->
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.2.1/js/bootstrap.min.js"></script>
	
</head>

<body>

	<header class="banner w-100 pt-md-3">
	
		<div id="overlay" onclick="off()"> 
			<div class="d-flex flex-column justify-content-around align-items-center py-5 px-4" id="overlayNav">
				<a href="index.html">Home</a>
				<a href="services.html">Services</a>
				<a href="index.html">
					<img class="img-fluid logo-overlay" src="images/logo_overlay.png" alt="Cactus Cat Sitter"/>
				</a>
				<a href="sitters.html">Sitters</a>
				<a href="contact.html">Contact</a>
			</div><!-- End overlay nav flex column -->
		</div><!-- End overlay nav -->
		
		<div class="container container-fluid">
		
			<button onclick="on()" id ="overlay_btn" class="btn float-right my-4" type="button" data-target="#overlayNav">
				<span>
				 <i class="fas fa-bars"></i>
				</span>
			</button>
			
			<div class="row py-5">
				<div class="col-12 text-center">
					
					<h1 class="text-center">Cactus Cat Sitter</h1>
					<h2 id="header_h2">The Valley of the Sun's Premier Cat Sitter Service</h2>
					
					<nav id="second-nav" class="navbar navbar-expand-md my-3">
						<div class="container-fluid pt-3 mt-5">
							<div class="collapse navbar-collapse justify-content-center p-0 m-0" id="MainNav">

								<ul class="navbar-nav">
									<li class="nav-item">
										<a class="nav-link" href="index.html">Home</a>
									</li>
									<li class="nav-item">
										<a class="nav-link" href="services.html">Services</a>
									</li>
									<li class="nav-item img-item">
										<a class="nav-link" href="index.html">
											<img class="img-fluid logo-main mx-4" src="images/logo_main.png" alt="Cactus Cat Sitter"/>
										</a>
									</li>
									<li class="nav-item">
										<a class="nav-link" href="sitters.html">Sitters</a>
									</li>
									<li class="nav-item">
										<a class="nav-link" href="contact.html">Contact</a>
									</li>
								</ul>

							</div><!-- End main nav collapse -->
						</div><!-- End container -->
					</nav>
					
				</div><!-- End column -->
			</div><!-- End row -->
			
		</div><!-- End main nav container -->
		
	</header>
	
	<main>
		
		<div class="row row-1 p-0">
			<div>
				
				<div class="image-wrapper">
					<img id="slide" class="img-fluid" src="images/banner.jpg" alt=""/>
				</div><!-- End image wrapper -->
				<div id="slides">
					<img src="images/banner.jpg" alt="FIRST CAT BANNER"/>
					<img src="images/banner2.jpg" alt="SECOND CAT BANNER"/>
					<img src="images/banner3.jpg" alt="THIRD CAT BANNER"/>
				</div><!-- End pre-loaded slides -->
			
			</div><!-- End carousel div -->
		</div><!-- End carousel row -->
		
		<div class="section section-mission">
			<div class="container container-fluid">
				
				<h2 class="text-center text-white mb-4">Our Mission</h2>
				
				<img id="figure-1" class="img-fluid ml-md-5 mb-5" src="images/mission.jpg" alt="WOMAN HOLDING TABBY CAT"/>
				
				<p class="lead">At Cactus Cat Sitter, our mission, plain and simple, is cats.</p>
				
				<ul class="lead">
					<p>We know cats.</p>
					<p>We love cats.</p>
					<p>We want to "catify" the world.</p>
				</ul>
				
				<p class="lead">Our sitters are trained in Cat Behaviorist Jackson Galaxy's effective "catify-ing" methodologies. 
				You can rest assured knowing that the unique needs of your beloved feline are in knowledgeable and capable hands.</p>
				
				<div class="clearfix">
				</div><!-- End clearfix for img float -->
				
			</div><!-- End container -->
		</div><!-- End mission section -->
		
		<div class="section section-about">
			
			<div class="container container-fluid mb-5">
				<h2 class="text-center text-white mb-4">About Us</h2>
				
				<img id="figure-2" class="img-fluid mr-sm-5 mb-5" src="images/about_new.jpg" alt="CATS ON SHELVES"/>
				
				<p class="lead">CEO and Founder Ana Boca started Cactus Cat Sitter in 2017. 
				Ana became frustrated as a cat lover and owner by the lack of individualized pet care for cats. 
				Most pet sitting services are offered in the form of pet hotels. 
				This means taking cats away from their home environment causing undue stress to the cats. 
				So, Ana set out to create a niche in individualized cat care with Cactus Cat Sitter. 
				</p>
				
				<p class="lead">At Cactus Cat Sitter, cats stay in their stress-free home environments, 
				while cat sitters across the valley travel to take care of the cats.
				</p>
				
				<p class="lead">The company has expanded to serve the entire Phoenix Metro area, including: 
				Phoenix, Scottsdale, Tempe, Mesa, Chandler, Peoria, and Gilbert.
				</p>
				
				<div class="clearfix">
				</div><!-- End clearfix for img float -->
			</div>
				
				<h3 class="text-center text-white">Testimonials</h3>
				<div class="container container-fluid">
				
					<div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
						
						<div class="carousel-inner">
							<div class="carousel-item active">
								<p class="lead text-center font-italic">"Awesome company!"<p>
								<blockquote class="blockquote-footer text-center text-white">Evelina K. | Cat Owner | Phoenix, AZ</blockquote>
							</div>
							<div class="carousel-item">
								<p class="lead text-center font-italic">"Wow!!!"<p>
								<blockquote class="blockquote-footer text-center text-white">Dmitry E. | Cat Owner | Scottsdale, AZ</blockquote>
							</div>
							<div class="carousel-item">
								<p class="lead text-center font-italic">"What a great service!"<p>
								<blockquote class="blockquote-footer text-center text-white">Larisa R. | Cat Owner | Gilbert, AZ</blockquote>
							</div>
							<div class="carousel-item">
								<p class="lead text-center font-italic">"Meowwww!"<p>
								<blockquote class="blockquote-footer text-center text-white">Gage | Cat | Tempe, AZ</blockquote>
							</div>
							<div class="carousel-item">
								<p class="lead text-center font-italic">"Squeak!"<p>
								<blockquote class="blockquote-footer text-center text-white">Barsik | Cat | Chandler, AZ</blockquote>
							</div>
						</div>
						
						
						<a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
							<span class="carousel-control-prev-icon" aria-hidden="true"></span>
							<span class="sr-only">Previous</span>
						</a>
						<a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
							<span class="carousel-control-next-icon" aria-hidden="true"></span>
							<span class="sr-only">Next</span>
						</a>
						
					</div><!-- CarouselExampleControls -->
				</div><!-- container -->
			
		</div><!-- End about section -->
		
	</main>
	
	<div id="section-footer" class="section container-fluid">
	
		<nav class="navbar navbar-expand social-nav mb-3" id="SocialNav">
			<div class="container-fluid justify-content-center">
				
				<ul class="navbar-nav">
					<li class="nav-item">
						<a class ="nav-link" href="#">
							<i class="fab fa-facebook-square"></i>
						</a>
					</li>
					<li class="nav-item">
						<a class ="nav-link" href="#">
							<i class="fab fa-twitter-square"></i>
						</a>
					</li>
					<li class="nav-item">
						<a class ="nav-link" href="#">
							<i class="fab fa-instagram"></i>
						</a>
					</li>
					<li class="nav-item">
						<a class ="nav-link" href="#">
							<i class="fab fa-youtube-square"></i>
						</a>
					</li>
					<li class="nav-item">
						<a class ="nav-link" href="#">
							<i class="fab fa-pinterest-square"></i>
						</a>
					</li>
				</ul>
					
			</div><!-- End container -->
		</nav><!-- End social nav -->
			
			
		<footer class="text-center">
			<i class="far fa-copyright"></i> 2019 Ana Boca
		</footer>
				
		
	</div><!-- End responsive footer -->
	
<script src="scripts/carousel.js"></script>
<script src="scripts/overlay.js"></script>

</body>
</html>