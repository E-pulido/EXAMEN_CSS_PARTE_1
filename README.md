# EXAMEN_CSS_PARTE_2
<head>
	<meta charset="UTF-8">
	<title>Eric Pulido Carnicé</title>
	<link href='https://fonts.googleapis.com/css?family=Fauna+One'rel='stylesheet' type='text/css'>
	<link rel="stylesheet" href="style.css">
	<meta name="viewport" content="width=device-width, initial-scale=1.0"
	<!--[if IE]><script src="https://html5shiv.googlecode.com/svn/trunk/html5.js"></script><![endif]-->

</head>
<body>
	
		<!-- LANDING PAGE -->
		<section id="home">
			<!-- OVERLAY -->
			<div class="overlay">
				<!-- PRIMARY NAVIGATION -->
				<nav role="navigation">
					<ul class="vertical-list">
						<li><a href="#home">Home</a></li>
						<li><a href="#about">About me</a></li>

					</ul>
				</nav>
				<!-- END OF PRIMARY NAVIGATION -->

				<!-- CONTAINER -->
				<div class="container">
					<h1><span class="logo">lab</span><small>web / automation development</small></h1>
						<ul class="social-links vertical-list">
					</ul>
				</div>
				<!-- END OF CONTAINER -->
			</div>
			<!-- END OF OVERLAY -->
		</section>
		<!-- END OF LANDING PAGE -->


		<!-- ABOUT -->
		<section id="about">
			<!-- CONTAINER -->
			<div class="container">
				<h2>Sobre mi</h2>
				<div class="row info">
					<div class="col-sm-8">
						<p>
							Aquest sira el meu espai de porfoli on podre adjuntar qualsevol tipus d’arxius i presentacions que utilitzare en aquest curs: Sistemes microinformatics i xarxes que estic cursant al centre ILERNA.
                        </p>
                    </div>
					

					<div class="col-md-4">
						
					</div>
				</div>
				
		
			<!-- END OF CONTAINER -->
		</section>
		<!-- END OF ABOUT -->

				
		<!-- CONTACT PAGE -->
		<section id="contact">
			<div class="overlay">
				<div class="container">
					<h2>Contactar conmigo</h2>
					
					<div class="row">
						<div class="col-lg-9">
						<form role="form" method="POST">
							<div class="form-group">
								<label for="nameTXT">Your Name</label>
								<input type="text" id="nameTXT" name="nameTXT">
							</div>

							<div class="form-group">
								<label for="emailTXT">Email Address</label>
								<input type="email" id="emailTXT" name="emailTXT">
							</div>

							<div class="form-group">
								<label for="subjectTXT">Subject</label>
								<input type="text" id="subjectTXT" name="subjectTXT">
							</div>

							<div class="form-group">
								<label for="messageTXT">Message</label>
								<textarea cols="36" rows="8" id="messageTXT" name="messageTXT"></textarea>
							</div>

							<button type="submit" class="noir" id="submitBTN" name="submitBTN"><span class="glyphicon glyphicon-send"></span>Send</button>
						</form>	
					</div>
					
					<div class="col-lg-3 overflow">
						<ul class="social-links vertical-list">
						</ul>
					</div>
					</div>
				</div>
			</div>
		</section>
		<!-- END OF CONTACT PAGE -->
