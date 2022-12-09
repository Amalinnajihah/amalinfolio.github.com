<!DOCTYPE html>
<html>
<head>
	<title>Portfolio website</title>
	<link rel="stylesheet" type="text/css" href="css/test.css">

	<link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <div class="hero">

        <video autoplay loop muted plays-inline class="back-video">
<source src="img/video.mp4" type="video/mp4">

        </video>

        <nav>
            <img  class="logo">
            <ul>
                <li><a href="#content">HOME</a></li>
                <li><a href="#about">ABOUT ME</a></li>
                <li><a href="#tentangsaya">COURSE ACHIEVEMENT</a></li>
                <li><a href="#wrapper">SKILLS</a></li>
                <li><a href="#activities">ACTIVITIES</a></li>
                <li><a href="#program">BLOGS</a></li>
            </ul>
            <a section id="btn" class="btn">CLICK ME</a>
			<script>
				document.getElementById("btn").addEventListener("click", function(){
					alert("HELLO GUYS!");});
			</script>
        </nav>
        <div section id="content" class=" content">
        <h1>AMALINFOLIO</h1>
        <a onmouseover="mOver(this)" onmouseout="mOut(this)">Let's Go</a>

		<script>
			function mOver(obj){
				obj.innerHTML= "Let's Go"
			}
			function mOut(obj){
				obj.innerHTML= "Visit My Website"
			}
		</script>
        <h3><marquee behavior="scroll" direction="left">HELLO! Welcome to my website <3</marquee></h3>
        </div>
    </div>

    <section id="about" class="about">
		<div class="main">
			<img src="img/my.jpg">
			<div class="about-text">
				<h2>ABOUT <span>ME</span></h2>
				
				<p style = "color:rgb(23, 26, 23);"><i>My name is Nur Amalin Najihah.My matric numbers is 067981. I'm 21 years old, stayed at Tanah Merah,Kelantan. I am second year student, studies in Universiti Sultan Zainal Abidin at Besut,Terengganu. Proceeding with my studies in a bachelor's degree in informatics media.</i></p>
				<button href="#" type="button">Let's Talk</button>
			</div>
		</div>
	</section>

    <div id="tentangsaya" class="tentangsaya">
		<div class="title">
			<h2><marquee direction = "left">COURSE <span>ACHIEVE</span>MENT</marquee></h2>
		</div>

		<div class="box">
			<div class="card">
				<i class="fa fa-building"></i>
				<h5>SPM</h5>
				<div class="pra">
					<p style = "color:rgb(23, 26, 23);">  I'm a pure Science student during high school </p>
					<p style="text-align: center;">
						
					</p>
				</div>
			</div>

			<div class="card">
				<i class="fa fa-building"></i>
				<h5>STPM</h5>
				<div class="pra">
					<p style = "color:rgb(23, 26, 23);"> Course that I took for STPM is Social Science and I got 3.13 for CGPA in STPM.</p>

					<p style="text-align: center;">
						
					</p>
				</div>
			</div>

			<div class="card">
				<i class="fa fa-university"></i>
				<h5>Bachelor</h5>
				<div class="pra">
					<p style = "color:rgb(23, 26, 23);"> studying in informatic media for 3years and a half at UniSZA Campus Besut. Currently, as a second years student</p>

					<p style="text-align: center;">
						
					</p>
				</div>
			</div>
		</div>
	</div>

    <div section id="wrapper" class="wrapper">
		<div class="title2">
		  <h2> <marquee direction = "right">S<span>KILL</span>S</h2></marquee>
		</div>
			<div class="shape-1"></div>
			<div class="shape-2"></div>
			<div class="container">
				<div class="skills">
					<div class="details">
						<span1>COMMUNICATION</span1>
						<span1>80%</span1>
					</div>
					<div class="bar1">
						<div id="html-bar"></div>
					</div>
				</div>
				<div class="skills">
					<div class="details">
						<span2>TIME MANAGEMENT</span2>
						<span2>75%</span2>
					</div>
					<div class="bar2 ">
						<div id="css-bar"></div>
					</div>
				</div>
				<div class="skills">
					<div class="details">
						<span3>CREATIVITY</span3>
						<span3>70%</span3>
					</div>
					<div class="bar3">
						<div id="js-bar"></div>
					</div>
				</div>
				<div class="skills">
					<div class="details">
						<span4>MULTITASKING</span4>
						<span4>65%</span4>
					</div>
					<div class="bar4">
						<div id="jQuery-bar"></div>
					</div>
				</div>
			</div>
		</div>

<div class="headline"><h2><marquee direction = "left"><span>AC</span>TIVITI<span>ES</span></marquee></h2></div>
        <div section id="activities" class="activities">
			<div class="title3">
						<img src="img/colorun.jpg">
						<div class="layer"> </div>
						<h5 style = "color:rgb(23, 26, 23);">COLOR RUN</h5>
						<br><p style = "color:rgb(225, 250, 86);">"Have fun. Regret nothing and don't let people bring you down"</p></br>
						<div class="pra">
							<p style="text-align: center;">
							</p>

						</div>
					</div>
					<div class="title3">
						<img src="img/volleyball.jpg">
						<div class="layer"> </div>
						<h5 style = "color:rgb(23, 26, 23);">VOLLEYBALL</h5>
						<br><p style = "color:rgb(225, 250, 86);">"Champions believe in themselves, even when no one else does"</p></br>
						<div class="pra"></div>
							<p style="text-align: center;">
							</p>
					</div>
					<div class="title3">
						<img src="img/ceramah.jpg">
						<div class="layer"> </div>
						<h5 style = "color:rgb(23, 26, 23);">TALK</h5>
						<br><p style = "color:rgb(225, 250, 86);">"Remember the reason you are doing this is to make your life better"</p></br>
						<div class="pra"></div>
							<p style="text-align: center;">
							</p>
					</div>
				</div>


	<div class="headline1"> <h2><marquee direction = "right"><span>BLO</span>GS</marquee></h2></div>
        <div section id="program" class=" program">
            <div class="blog">
                <h2 style = "color:rgb(23, 26, 23);">PROBABILITY & STATISTICAL DATA ANALYSIS</h2>
                <div class="caption">
                    <p>After learning Probability & Statistical Data Analysis for almost 8weeks, I learned several types of statistical analysis tools that can help organization or anyone to analysis the data. Then it can help to come up a solution or answer from the data that is collected. I also can help myself to be more confident to answer this type of mathematical questions. Other than that, I love how the lecturer explain to me about several topic. Their explanations really make all the topics easy to understand for me.</p>
                    <button type="button">Know More</button>
                </div>
                <img src="img/math.jpg">
            </div>
            <div class="blog">
                <h2 style = "color:rgb(23, 26, 23);">WEB APPLICATION DEVELOPMENT</h2>
                <div class="caption">
                    <p>The process of learning coding in web application was enjoyable. Although sometimes it was difficult to understand the attributes such as in HTML, CSS, JAVASCRIPT and many others. However, I eventually accepted that coding may be fun when we understand how to use it.</p>
                    <button type="button">Know More</button>
                </div>
                <img src="img/cc.jpg">
            </div>
            <div class="blog">
                <h2 style = "color:rgb(23, 26, 23);">DATABASE</h2>
                <div class="caption">
                    <p>I was introduced to data modelling techniques and database analysis, recording, and understanding. Various of the valuable commercial database administration tools were also discussed, as well as some tools for easy and quick data visualisation and retrieval. Moreover, we learned how to analyze, access and employ data in an effective manner during the course.</p>
                    <button type="button">Know More</button>
                </div>
                <img src="img/donno.jpg">
            </div>
</div>
        </div>

       



    
    
    </body>
    </html>
