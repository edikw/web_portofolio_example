<template>
	<div class="index">
		<div class="navbar">
			<div class="nav">
	          <nav role="navigation">
	            <div id="menuToggle">
	              <input type="checkbox" ref="checkbox">
	              <div class="burger" id="close">
	                <span></span>
	                <span></span>
	                <span></span>
	              </div>
	              <ul id="menu" v-on:click="hide" >
	                <a href="#home"><li>Home</li></a>
	                <a href="#meet-us"><li>Overview</li></a>
	                <a href="#services"><li>Service</li></a>
	                <a href="#works"><li>Portfolio</li></a>
	                <a href="#about-us"><li>About Us</li></a>
	                <a href="#contact"><li>Contact Us</li></a>
	              </ul>
	            </div>
	          </nav>
	        </div>
		</div>
		<div id="home">
			<div class=" container text-center">	
				<div class="content">
					<h4>We've got the special power</h4>
					<hr>
					<div class="header-text btn">
						<h1><span id="head-title">We Are Web Developer</span></h1>
					</div>
				</div>
				<!-- <a href="#"></a> -->
				 <a href="#meet-us" class="down-btn page-scroll">
	                <span class="fa fa-angle-down"></span>
	            </a>
	        </div>
		</div>

		<div id="meet-us">
			<div class="container">
				<div class="row justify-content-center text-center">
		    		<div class="col-md-8 col-md-offset-2">
		        		<div class="section-title">
		            		<h2>Meet Us</h2>
		            		<hr>
		        		</div>
				        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
			        	<a href="#services" class="down-btn page-scroll">
		            		<span class="fa fa-angle-down"></span>
		        		</a>
		    		</div>
				</div>
			</div>
		</div>

		<div id="overview-video">
	        <div class="overlay">
	            <div class="container text-center">
	                <a href="#">
	                    <span class="fa fa-play" id="play"></span>
	                </a>
	            </div>
	        </div>
	    </div>

		<div id="services">
	        <div class="container text-center">
	            <div class="row justify-content-center">
	                <div class="col-md-8 col-md-offset-2">
	                    <div class="section-title">
	                        <h2>Services</h2>
	                        <hr>
	                    </div>
	                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
	                </div>
	            </div>

	            <div class="space"></div>

	            <div class="row">
	                <div class="col-md-4 col-sm-4">
	                    <div class="service">
	                        <span class="fas fa-pen-fancy fa-3x"></span>
	                        <h4>Web Design</h4>
	                        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a</p>
	                    </div>
	                </div>

	                <div class="col-md-4 col-sm-4">
	                    <div class="service">
	                        <span class="fas fa-code fa-3x"></span>
	                        <h4>Web Development</h4>
	                         <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a</p>
	                    </div>
	                </div>

	                <div class="col-md-4 col-sm-4">
	                    <div class="service">
	                        <span class="fas fa-gamepad fa-3x"></span>
	                        <h4>Game Development</h4>
	                         <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a</p>
	                    </div>
	                </div>
	            </div>
	            <a href="#works" class="down-btn page-scroll">
	                <span class="fa fa-angle-down"></span>
	            </a>
	        </div>
	    </div>

	     <div id="cta">
	        <div class="container text-center">
	            <a href="#" class="btn go-to-btn" id="butonCta">Check our shop</a>
	        </div>
	    </div>

	    <div id="works">
	        <div class="container">
	            <div class="row justify-content-center text-center">
	                <div class="col-md-8 col-md-offset-2">
	                    <div class="section-title">
	                        <h2>Our Latest Projects</h2>
	                        <hr>
	                    </div>
	                   	<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
	                </div>
	            </div>
	            <div class="space"></div>
	        </div>
	        <div class="container-fluid">
	            <div class="row">
	                <div class="col-md-3 col-sm-6 nopadding">
	                    <div class="portfolio-item">
	                        <div class="hover-bg">
	                            <a href="#">
	                                <div class="hover-text">
	                                    <h5>Web Design</h5>
	                                    <p class="lead">Client Seal</p>
	                                    <div class="hline"></div>
	                                </div>
	                                <img src="../assets/bg/layout.png" class="img-responsive" alt="...">
	                            </a>
	                        </div>
	                    </div>
	                </div>
	                <div class="col-md-3 col-sm-6 nopadding">
	                    <div class="portfolio-item">
	                        <div class="hover-bg">
	                            <a href="#">
	                                <div class="hover-text">
	                                    <h5>Web Development</h5>
	                                    <p class="lead">Does University</p>
	                                    <div class="hline"></div>
	                                </div>
	                                <img src="../assets/bg/layout.png" class="img-responsive" alt="...">
	                            </a>
	                        </div>
	                    </div>
	                </div>
	                <div class="col-md-3 col-sm-6 nopadding">
	                    <div class="portfolio-item">
	                        <div class="hover-bg">
	                            <a href="#">
	                                <div class="hover-text">
	                                    <h5>Web Development</h5>
	                                    <p class="lead">Does University</p>
	                                    <div class="hline"></div>
	                                </div>
	                            </a>
	                            <img src="../assets/bg/layout.png" class="img-responsive" alt="...">
	                        </div>
	                    </div>
	                </div>
	                <div class="col-md-3 col-sm-6 nopadding">
	                    <div class="portfolio-item">
	                        <div class="hover-bg">
	                            <a href="#">
	                                <div class="hover-text">
	                                    <h5>Game Development</h5>
	                                    <p class="lead">Atas Game</p>
	                                    <div class="hline"></div>
	                                </div>
	                            </a>
	                            <img src="../assets/bg/layout.png" class="img-responsive" alt="...">
	                        </div>
	                    </div>
	                </div>
	            </div>
	        </div>
	        <div class="space"></div>
	        <div class="text-center">
	            <a href="#" class="btn read-more-btn">Check on Dribbble</a>
	            <br>
	            <a href="#about-us" class="down-btn page-scroll"><span class="fa fa-angle-down"></span></a>
	        </div>
	    </div>

	    <div id="clients">
	        <div class="overlay">
	            <div class="container text-center">
	                <div class="section-title">
	                    <h2>Our Partners</h2>
	                    <hr>
	                </div>

	                <ul class="clients">
	                    <li><a href="#"><h2 class="text-white font-weight-bold">Logo</h2></a></li>
	                    <li><a href="#"><h2 class="text-white font-weight-bold">Logo</h2></a></li>
	                    <li><a href="#"><h2 class="text-white font-weight-bold">Logo</h2></a></li>
	                    <li><a href="#"><h2 class="text-white font-weight-bold">Logo</h2></a></li>
	                </ul>
	            </div>
	        </div>
	    </div>

	     <div id="about-us">
	        <div class="container">
	            <div class="row justify-content-center text-center">
	                <div class="col-md-8 col-md-offset-2">
	                    <div class="section-title">
	                        <h2>About Us</h2>
	                        <hr>
	                    </div>
	                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
	                </div>
	            </div>
	            <div class="space"></div>
	            <div class="row">
	                <div class="col-md-10 col-sm-10">
	                    <div class="row">
	                        <div class="col-md-4 col-sm-4">
	                            <div class="team">
	                                <img src="../assets/team/edi.jpg" class="img-responsive img-circle" alt="...">
	                                <br>
	                                <h4>Edi Kurniawan W</h4>
	                                <p class="small">Programmer</p>
	                                <hr>
	                            </div>
	                        </div>

	                        <div class="col-md-4 col-sm-4">
	                            <div class="team">
	                                <img src="../assets/team/edi.jpg" class="img-responsive img-circle" alt="...">
	                                <br>
	                                <h4>Athix Mubaroz 123</h4>
	                                <p class="small">Programmer</p>
	                                <hr>
	                            </div>
	                        </div>

	                        <div class="col-md-4 col-sm-4">
	                            <div class="team">
	                                <img src="../assets/team/edi.jpg" class="img-responsive img-circle" alt="...">
	                                <br>
	                                <h4>Topan Pandz3rd</h4>
	                                <p class="small">Programmer</p>
	                                <hr>
	                            </div>
	                        </div>

	                    </div>
	                </div>

	                <div class="col-md-2 col-sm-2">
	                    <div class="team hire">
	                        <h4>and anymore</h4>
	                        <hr>
	                        <div class="space"></div>
	                        <a href="#">
	                            <span class="fa fa-paper-plane-o fa-2x"></span>
	                        </a>
	                    </div>
	                </div>
	            </div>

	            <div class="text-center">
	                <a href="#contact" class="page-scroll down-btn">
	                    <span class="fa fa-angle-down"></span>
	                </a>
	            </div>

	        </div>
	    </div>

	    <div id="testimonials">
	        <div class="overlay">
	            <div class="container">
	                <div class="section-title">
	                    <h2>What my Clients Say...</h2>
	                    <hr>
	                </div>

	                <div id="testimonial" class="owl-carousel owl-theme">
	                  <div class="item">
	                    <h3>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <br> when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged </h3>
	                    <br>
	                    <h6>LJ, Abc Company</h6>
	                  </div>

	                  <div class="item">
	                    <h3>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <br> when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged </h3>
	                    <br>
	                    <h6>Kai, Web Geekster</h6>
	                  </div>

	                  <div class="item">
	                    <h3>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, <br> when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged </h3>
	                    <br>
	                    <h6>Jenn, Coders' Playground</h6>
	                  </div>
	                </div>
	            </div>
	        </div>
	    </div>

	    <div id="contact">
	        <div class="container">
	            <div class="section-title text-center">
	                <h2>Contact Us</h2>
	                <hr>
	            </div>
	            <div class="space"></div>
	            <div class="row">
	                <div class="col-md-3">
	                    <address>
	                        <strong>Address</strong><br>
	                        <br>
	                        Soekamtiland<br>
	                        Sidoarum, Godean<br>
	                        5704, Yogyakarta<br>
	                        Phone: 08521145xxxx
	                        <ul class="social">
	                            <li><a href="#"><span class="fab fa-facebook"></span></a></li>
	                            <li><a href="#"><span class="fab fa-google-plus"></span></a></li>
	                            <li><a href="#"><span class="fab fa-instagram"></span></a></li>
	                            <li><a href="#"><span class="fab fa-github"></span></a></li>
	                          </ul>
	                    </address>
	                </div>

	                <div class="col-md-9">
	                    <form autocomplete="off">
	                        <div class="row">
	                            <div class="col-md-6">
	                                <input type="text" class="form-control" placeholder="Your Name">
	                                <input type="text" class="form-control" placeholder="Phone No.">
	                            </div>
	                            <div class="col-md-6">
	                                <input type="text" class="form-control" placeholder="Email">
	                                <input type="text" class="form-control" placeholder="Subject">
	                            </div>
	                        </div>
	                        <textarea class="form-control" rows="4" placeholder="Message"></textarea>
	                        <div class="text-right">
	                            <a href="#" class="btn send-btn">Send</a>
	                        </div>
	                    </form>
	                </div>
	            </div>
	        </div>
	    </div>

	     <nav id="footer">
	        <div class="container">
	             <div class="pull-left">
	                <p>2018 © Edi Kurniawan Wibowo | Does University</p>
	            </div>
	            <div class="pull-right"> 
	                <a href="#home" class="page-scroll">Back to Top <span class="fa fa-angle-up"></span></a>
	            </div>
	        </div>
	    </nav>
	</div>
</template>

<script>

	export default {
	 methods: {
	 	hide() {
        this.$refs.checkbox.checked = false;
      }
	}
}
</script>

<style scoped>
 
    .navbar {
      padding: 0;
      margin: 0;
    }
	h1{
		font-weight: 700;
		font-size: 46px;
	}

	h2{
		text-transform: uppercase;
		font-size: 20px;
	}
	h3{
		font-size: 14px;
		font-style: italic;
		font-weight: 100;
		line-height: 26px;
	}

	h4{
		text-transform: uppercase;
		font-size: 16px;
		word-spacing: 2px;
	}
	h5{
		text-transform: uppercase;
		font-size: 12px;
		word-spacing: 2px;
	}
	h6{
		text-transform: uppercase;
		font-size: 10px;
		word-spacing: 2px;
		letter-spacing: 2px;
	}

	p{
		font-weight: 400;
	}
	hr{
		width: 50px;
		border-color: #c59a6d;
	}
	a {color: #222222}
	a:hover,
	a:focus{
		color: #c59a6d;
		text-decoration: none;
	}

	#home{
		background: url(../assets/bg/banner.png);
		background-size: cover;
		background-repeat: no-repeat;
		background-position:center;
		height: auto;
		min-height: 710px;
		/*padding-top: 60px;*/
		color: #fff; 
	}
	#home a.down-btn span.fa.fa-angle-down {
		font-size: 26px;
		border: 1px solid #c59a6d;
		border-radius: 2px;
		padding: 7px 5px;
		position: relative;
		margin-top: 100px;
		transition: all 0.5s;
		color: #ffffff;
		cursor: pointer;
	}
	.content {
		padding-top: 16%;
	}
	#meet-us {
		padding: 60px 0; 
	}
	#meet-us a.down-btn span.fa.fa-angle-down {
		font-size: 26px;
		border: 1px solid #c59a6d;
		border-radius: 2px;
		padding: 7px 5px;
		position: relative;
		margin-top: 20px;
		color: #c59a6d;
		transition: all 0.5s;
		cursor: pointer;
	}
	.row {
		margin-left: -15px;
		margin-right: -15px;
	}
	#overview-video {
		background: url(../assets/bg/banner2.jpg);
		background-size: cover;
		background-repeat: no-repeat;
		background-attachment: scroll;
		text-align: center;
		background-position: center;
	}
	#overview-video .overlay {
		background: rgba(34, 34, 34, 0.85);
		height: auto;
		min-height: 200px;
		padding:12% 0;
	}
	#overview-video .overlay #play {
		font-size: 40px;
		color: #fff;
		/*text-align: center;*/
		margin: auto 0;
	}
	#services {
		padding: 60px 0;
	}
	#services a.down-btn span.fa.fa-angle-down {
		font-size: 26px;
		border: 1px solid #c59a6d;
		border-radius: 2px;
		padding: 7px 5px;
		position: relative;
		margin-top: 20px;
		color: #c59a6d;
		cursor: pointer;
		transition: all 0.5s;
	}
	.space {
		padding: 20px;
	}
	.service {
		border: 1px solid #000;
		margin-top: 20px;
		margin-bottom: 0px;
		transition: all 0.3s;
		position: relative;
		padding: 60px 25px;
	}
	.service span {
		font-size: 3em;
		margin-bottom: 10px;
	}
	.service p {
		font-size: 14px;
		padding: 20px;
		font-size: 'lato', sans-serif;
	}
	.service:hover {
		border-color: #c59a6d;
		margin-top: 0px;
		margin-bottom: 0px;
		padding-top: 80px;
		padding-bottom: 80px;

	}
	#cta {
		background: #000;
		padding: 4% 0;
	}
	#cta #butonCta {
		text-transform: uppercase;
		border: 1px solid #c59a6d;
		font-size: 12px;
		color: #fff;
		transition: all 0.5s;
	}
	#cta #butonCta:hover {
		color: #000;
		background-color: #c59a6d;
	}
	#works {
		padding: 60px 0;
	}
	.portfolio-item .hover-bg {
		height: 280px;
		overflow: hidden;
		position: relative;
	}
	.portfolio-item .hover-bg .hover-text {
		position: absolute;
		text-align: center;
		margin: 0 auto;
		color: #000;
		background: rgba(0, 0, 0, 0.66);
		padding: 30% 0;
		height: 100%;
		width: 100%;
		opacity: 0;
		transition: all 0.5s;
	}
	.hover-bg img .img-responsive {
		display: block;
		max-width: 50%;
		height: auto;
		vertical-align: middle;
		border: 0;
	}
	.nopadding {
		padding: 0;
		margin: 0;
	}

	.hover-bg .hover-text>h5{
		opacity: 0;
		-webkit-transform: translateY(100%);
            transform: translateY(100%);
            transition: all 0.3s;
            color: #fff;
	}
	.hover-bg:hover .hover-text>h5{
		opacity: 1;
	    -webkit-backface-visibility:hidden;
	    -webkit-transform: translateY(0);
	            transform: translateY(0);
	}
	.hover-bg .hover-text>.hline{
		opacity: 0;
		-webkit-transform: translateY(0);
	            transform: translateY(0);
	            transition: all 0.3s;
	}
	.hover-bg:hover .hover-text>.hline{
		opacity: 1;
	    -webkit-backface-visibility:hidden;
	   -webkit-transform: translateY(100%);
	            transform: translateY(100%);
	}
	.hover-bg:hover .hover-text{
		opacity: 1;
	}
	.hline{
		height: 5px;
		width: 30px;
		border-top: 2px solid #f1f1f1;
		margin: 0 auto
	}

	.hover-text p.lead{
		color: #c59a6d;
	}


	a.btn.read-more-btn{
		text-transform: uppercase;
		background: #c59a6d;
		color: #282f35;
		word-spacing: 2px;
		padding: 7px 30px;
		border-radius: 2px;
		font-size: 12px;
		color: #ffffff;
		transition: all 0.5s;
	}
	a.btn.read-more-btn:hover{
		background: #222222;
		color: #ffffff;
	}

	a.btn.send-btn{
		text-transform: uppercase;
		background: #c59a6d;
		color: #282f35;
		padding: 15px 35px;
		border-radius: 0;
		font-size: 12px;
		color: #ffffff;
		transition: all 0.5s;
	}
	a.btn.send-btn:hover{
		background: transparent;
		border: 1px solid #c59a6d;
		color: #ffffff;
	}
	#works a.down-btn span.fa.fa-angle-down {
		font-size: 26px;
		border: 1px solid #c59a6d;
		border-radius: 2px;
		padding: 7px 5px;
		position: relative;
		margin-top: 20px;
		color: #c59a6d;
		cursor: pointer;
		transition: all 0.5s;
	}
	#clients {
		background: url(../assets/bg/bg3.jpg);
		background-size: cover;
		background-repeat: no-repeat;
		background-attachment: fixed;
		text-align: center;
		background-position: center;
	}
	#clients .overlay {
		background: rgba(34, 34, 34, 0.85);
		height: auto;
		min-height: 200px;
		padding: 8% 0;
		color: #fff;
	}

	#clients .overlay ul {
		list-style: none;
		padding: 0;
	}
	#clients .overlay ul li {
		padding:20px 40px;
		display: inline-block;
		vertical-align: middle;
	}
	#about-us {
		padding: 60px 0;
	}
	.team {
		border: 1px solid #c3c3c3;
		padding: 100px 20px;
		text-align: center;
		opacity: 0.7;
		transition: all 0.8s;
		max-height: 340px;
		margin-bottom: 30px;
	}
	.team img {
		width: 100px;
		margin: 0 auto;
	}
	.team .img-circle {
		border-radius: 10%;
		margin-bottom: 30px;
	}
	#about-us a.down-btn span.fa.fa-angle-down {
		font-size: 26px;
		border: 1px solid #c59a6d;
		border-radius: 2px;
		padding: 7px 5px;
		position: relative;
		margin-top: 20px;
		color: #c59a6d;
		cursor: pointer;
		transition: all 0.5s;
	}
	.team:hover {
		border: 1px solid #000;
		opacity: 1;
	}
	#testimonials {
		background: url(../assets/bg/bg4.jpg);
		background-attachment: scroll;
		background-repeat: no-repeat;
		background-position: center;
		background-size: cover;
		text-align: center;
	}
	#testimonials .overlay {
		background: rgba(34, 34, 34, 0.85);
		height: auto;
		min-height: 200px;
		padding: 5% 0;
		color: #fff;
	}

	#contact {
		padding: 100px;
		background: #282f35;
		color: #fff;
	}
	address {
		/*font-style: italic;*/
		font-size: 14px;
		font-family: 'lato', sans-serif;
		letter-spacing: 1px;
		color: #ccc;
	}
	address strong {
		color: #fff;
		text-transform: uppercase;
		font-style: normal;
		font-family: 'Montserrat', sans-serif;
	} 
	address ul {
		list-style: none;
		padding: 0;
	} 
	address ul li {
		display: inline-block;
		margin-right: 20px;
		margin-top: 30px;
	}
	address ul li a{
		color: #fff;
		font-size: 17px;
	}
	ul.social li{
		display: inline-block;
		margin-right: 20px;
		margin-top: 30px;
	}

	ul.social li a{
		color: #ffffff;
		font-size: 16px;
	}
	ul.social li a:hover {
		color: #c59a6d;
	}
	#contact .form-control {
		display: block;
		width: 100%;
		height: 40px;
		padding: 7px 12px;
		font-size: 14px;
		line-height: 1;
		color: #555;
		background-color: #1e2429;
		background-image: none;
		border: none;
		border-top: 2px solid transparent;
		border-radius: 0;
		transition: all 0.5s;
	}
	#contact .form-control:focus {
		border-color: #c59a6d;
		outline: 0;
		-webkit-box-shadow: none;
		box-shadow: none;
	}
	input , textarea{
		font-family: inherit;
		margin-bottom: 30px;
	}

	#footer {
		background: #282f35;
		padding: 40px 0;
		color: #fff;
		border-bottom: 5px solid #c59a6d;
		font-size: 13px;
	}
	#footer span.fa{
	color: #c59a6d;
	font-size: 26px;
	margin-left: 10px;
	}
	#footer a{
		color: #ffffff;
	}
	#footer a:hover{
		color: #c59a6d;
	}
	.pull-left{
		display: inline-block;
	}
	.pull-right {
		display: inline-block;
		float: right;
	}
	#works  a.down-btn span.fa.fa-angle-down:hover, 
	#services  a.down-btn span.fa.fa-angle-down:hover,
	#meet-us  a.down-btn span.fa.fa-angle-down:hover, 
	#home  a.down-btn span.fa.fa-angle-down:hover,
	 #about-us a.down-btn span.fa.fa-angle-down:hover {
		padding: 10px 5px;
	}
</style>
