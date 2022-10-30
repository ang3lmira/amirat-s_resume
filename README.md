# amirat-s_resume
Hello, My name is Olumudi Amirat. I am a 20-year-old second year psychology student and also a cybersecurity intern. This is a website that showcases my resume.  🙂 You can use this as a resume template, just fork it and edit to personalize it.


This is a basic HTML skeleton.
```
<html>
    <!-- container for all HTML code -->

	<head>
        <!-- contains all the information about the page -->

		<link href="style.css" rel="stylesheet">
        <!-- signifies the stylesheet being used -->

		<title>amirat's resume</title>
        <!-- title of the page to display on the toolbar -->

	</head>

	<body>
        <!-- indicates all the page content to be shown to the user-->

		<header id="header">
			<!-- semantic tags (header, main, article & section)-->

			<h1>**insert your name**</h1>
            <!-- level one header -->

			<hr>
            <!-- rule a horizontal line -->
			your role title
			<hr>

		</header>

		<main>
			<article id="mainLeft">
                <!-- assign unique id -->

				<section>
					<h2>CONTACT</h2>
					<!-- contact info including social media -->
				</section>

				<section>
					<h2>SKILLS</h2>
					<!-- your skills -->
				</section>

				<section>
					<h2>EDUCATION</h2>
					<!-- your education -->
				</section>            
			</article>

			<article id="mainRight">
				<section>
					<h2>ABOUT</h2>
					<!-- about you -->
				</section>
                
				<section>
					<h2>WORK EXPERIENCE</h2>
					<!-- your work experience -->
				</section>
			</article>
		</main>
	</body>
</html>
```

This is the basic CSS styling
```
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 12px;
    max-width: 960px;
    margin: auto;
}
```

This is the sizing css code
```
h1 {
    font-size: 3em;
    letter-spacing: .6em;
    padding-top: 1em;
    padding-bottom: 1em;
}

h2 {
    font-size: 1.5em;
    padding-bottom: 1em;
}

h3 {
    font-size: 1em;
    padding-bottom: 1em;
}
```
This is the padding css code
```
header {
    text-align: center;
    margin: auto 2em;
}

section {
    margin: auto 1em 4em 2em;
}

i {
    margin-right: .5em;
}

p {
    margin: .2em auto
}

hr {
    border: none;
    background-color: lightgray;
    height: 1px;
}

h1, h2, h3 {
    font-weight: 100;
    margin-bottom: 0;
}
```

This is the selecting ID code
```
#mainLeft {
    border-right: 1px solid lightgray;
}
```