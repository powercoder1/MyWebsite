# MyWebsite<html>
<head>
	<title>Sir Tim Berners-Lee</title>
	<link rel="stylesheet" href="style.css">
</head>

<body>

	<section id="welcome" class="parallax-container">
		<div class="parallax-inner">
			<img src="stbl.jpg" class="profile" />
			<h1>I Am <br><span id="name">Tim Berners-Lee</span></h1>
			<h2> I am the founder of www: World Wide Web</h2>
		</div>
	</section>
	
	
	
	<section id="bio">
		<h1>Hi!</h1>
		<div class="line"></div>
		<p>Tim Berners-Lee is a software engineer who invented the Internet (or the World Wide Web) in 1989 while at CERN, the European Particle Physics Laboratory.

			He is director of the World Wide Web Consortium that he founded and a Professor in the Computer Science Department at the University of Oxford.

			In 2001 he became a Fellow of the Royal Society and in 2004 he was knighted.<br/><br/>In 1994 Berners-Lee founded the World Wide Web Consortium (W3C) at the Laboratory of Computer Science (LCS) at the Massachusetts Institute of Technology in Boston. It was made up of companies that wanted to work together to create Web standards and also improve the Web. It was quickly agreed that the technology should be free of royalties and patents. Berners-Lee has served as director of this W3C since it was founded.

			In 1995 Microsoft produced the first version of Internet Explorer and this commercial browser created enormous growth in websites and web users.

			The Web was first used for e-commerce in 1997.</p>
	</section>

</body></html>

body {
    margin: 0;
    padding-top: 800px;
}

.profile {
    width: 175px;
    margin-bottom: 50px;
    border-radius: 50%;
}

#welcome {
    position: absolute;
    overflow: hidden;
    height: 800px;
    color: #FFFFFF;
    left: 0;
    top: 0;
    bottom: 0;
    right: 0;
    opacity: 0.83;
    background: linear-gradient(#60ebeb 0%, #27ae60 100%);
    display: table;
    width: 100%;
    height: 100%;
}



h1 {

    font-size: 40px;
    line-height: 1.2;
    font-family: 'Lato', sans-serif;
    font-weight: 300;
}

#name {
    font-size: 30px;
    line-height: 1.2;
    font-family: cursive
}

h2 {
    font-size: 30px;
    font-weight: 300;
    line-height: 1.2;
    font-family: monospace
}

#bio {

    padding: 50px;
    text-align: center;
    font-size: 42px;
}

.line {
    height: 6px;
    background-color: #000;
    width: 70px;
    margin: 8px auto;
}


p {
    max-width: 450px;
    margin: 25px auto;
    font-size: 17px;
    line-height: 1.3;
}

.parallax-inner {

    display: table-cell;
    position: relative;
    text-align: center;
    vertical-align: middle;

}

