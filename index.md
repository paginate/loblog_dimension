---
---

<!DOCTYPE HTML>
<!--
	Dimension by HTML5 UP
	html5up.net | @ajlkn
	Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
-->
<html>
	<head>
		<title>LoBlog</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="assets/css/main.css" />
		<!--[if lte IE 9]><link rel="stylesheet" href="assets/css/ie9.css" /><![endif]-->
		<noscript><link rel="stylesheet" href="assets/css/noscript.css" /></noscript>
	</head>
	<body>

		<!-- Wrapper -->
			<div id="wrapper">

				<!-- Header -->
					<header id="header">
						<div class="logo">
							<span class="icon" style="font-size:50px">&#x271D;</span>
						</div>
						<div class="content">
							<div class="inner">
								<h1>LoBlog</h1>
								<p>\$0.02 \times \infty</p>
							</div>
						</div>
						<nav>
							<ul>
								<li><a href="#about">About Me</a></li>
								<li><a href="#news">News</a></li>
								<!--<li><a href="#elements">Elements</a></li>-->
							</ul>
						</nav>
					</header>

				<!-- Main -->
					<div id="main">

						<!-- About -->
							<article id="about">
								<h2 class="major">About</h2>
								<span class="image main"><img src="images/pic01.jpg" alt="" /></span>
								<h3>Caleb Lo</h3>
								<p>UT Austin EE PhD</p>
								<p>Specializes in networking optimization</p>
							</article>


						<!-- News -->
							<article id="news">
								<h2 class="major">News</h2>
								<span class="image main"><img src="images/pic03.jpg" alt="" /></span>
								<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <div class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</div>
        <div>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title | escape }}</a>
        </div>
      </li>
    {% endfor %}
  </ul>
							</article>

						<!-- Elements -->
							<article id="elements">
								<h2 class="major">Elements</h2>

							</article>

					</div>

				<!-- Footer -->
					<footer id="footer">
						<p class="copyright">&copy; Designed by <a href="https://html5up.net">HTML5 UP</a>.
						Maintained by Paginate.</p>
					</footer>

			</div>

		<!-- BG -->
			<div id="bg"></div>

		<!-- Scripts -->
			<script src="assets/js/jquery.min.js"></script>
			<script src="assets/js/skel.min.js"></script>
			<script src="assets/js/util.js"></script>
			<script src="assets/js/main.js"></script>

	</body>
</html>
