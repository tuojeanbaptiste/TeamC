<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">

<head>

<meta charset="utf-8" />
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="generator" content="pandoc" />




<title>Wilmington University</title>

<script src="site_libs/jquery-1.11.3/jquery.min.js"></script>
<meta name="viewport" content="width=device-width, initial-scale=1" />
<link href="site_libs/bootstrap-3.3.5/css/cosmo.min.css" rel="stylesheet" />
<script src="site_libs/bootstrap-3.3.5/js/bootstrap.min.js"></script>
<script src="site_libs/bootstrap-3.3.5/shim/html5shiv.min.js"></script>
<script src="site_libs/bootstrap-3.3.5/shim/respond.min.js"></script>
<script src="site_libs/navigation-1.1/tabsets.js"></script>
<link href="site_libs/highlightjs-9.12.0/default.css" rel="stylesheet" />
<script src="site_libs/highlightjs-9.12.0/highlight.js"></script>

<meta name="description" content="Turn your analyses into high quality documents, reports, presentations and dashboards with R Markdown. Use a productive notebook interface to weave together narrative text and code to produce elegantly formatted output. Use multiple languages including R, Python, and SQL. R Markdown supports a reproducible workflow for dozens of static and dynamic output formats including HTML, PDF, MS Word, Beamer, HTML5 slides, Tufte-style handouts, books, dashboards, shiny applications, scientific articles, websites, and more." />

<link rel="icon" type="image/png" href="images/wilmu-logo.png" />

<style type="text/css">code{white-space: pre;}</style>
<style type="text/css">
  pre:not([class]) {
    background-color: white;
  }
</style>
<script type="text/javascript">
if (window.hljs) {
  hljs.configure({languages: []});
  hljs.initHighlightingOnLoad();
  if (document.readyState && document.readyState === "complete") {
    window.setTimeout(function() { hljs.initHighlighting(); }, 0);
  }
}
</script>



<style type="text/css">
h1 {
  font-size: 34px;
}
h1.title {
  font-size: 38px;
}
h2 {
  font-size: 30px;
}
h3 {
  font-size: 24px;
}
h4 {
  font-size: 18px;
}
h5 {
  font-size: 16px;
}
h6 {
  font-size: 12px;
}
.table th:not([align]) {
  text-align: left;
}
</style>


</head>

<body>

<style type = "text/css">
.main-container {
  max-width: 940px;
  margin-left: auto;
  margin-right: auto;
}
code {
  color: inherit;
  background-color: rgba(0, 0, 0, 0.04);
}
img {
  max-width:100%;
  height: auto;
}
.tabbed-pane {
  padding-top: 12px;
}
.html-widget {
  margin-bottom: 20px;
}
button.code-folding-btn:focus {
  outline: none;
}
</style>


<style type="text/css">
/* padding for bootstrap navbar */
body {
  padding-top: 51px;
  padding-bottom: 40px;
}
/* offset scroll position for anchor links (for fixed navbar)  */
.section h1 {
  padding-top: 56px;
  margin-top: -56px;
}

.section h2 {
  padding-top: 56px;
  margin-top: -56px;
}
.section h3 {
  padding-top: 56px;
  margin-top: -56px;
}
.section h4 {
  padding-top: 56px;
  margin-top: -56px;
}
.section h5 {
  padding-top: 56px;
  margin-top: -56px;
}
.section h6 {
  padding-top: 56px;
  margin-top: -56px;
}
</style>

<script>
// manage active state of menu based on current page
$(document).ready(function () {
  // active menu anchor
  href = window.location.pathname
  href = href.substr(href.lastIndexOf('/') + 1)
  if (href === "")
    href = "index.html";
  var menuAnchor = $('a[href="' + href + '"]');

  // mark it active
  menuAnchor.parent().addClass('active');

  // if it's got a parent navbar menu mark it active as well
  menuAnchor.closest('li.dropdown').addClass('active');
});
</script>


<div class="container-fluid main-container">

<!-- tabsets -->
<script>
$(document).ready(function () {
  window.buildTabsets("TOC");
});
</script>

<!-- code folding -->





 <div class="navbar navbar-default navbar-fixed-top" role="navigation" style="border:1px">
   <div id="navbar" class="navbar-collapse collapse">
      <ul class="nav navbar-nav">
        <li><a href="login.html">myWilmU</a></li>
        <li><a href="lesson-1.html">Library</a></li>
        <li><a href="Staff.html">Faculty & Staff</a></li>
        <li><a href="Safety.html">Safety</a></li>
        <li><a href="Contact.html">Contact Us</a></li>
        <li><a href="Apply.html">Apply Now</a></li>
      </ul>
       <div class="container">
       <ul class="nav navbar-right">
        <div class="wrapper">
             <input type="text" placeholder="Search.." required>
             <input type="button" value="Search">
        </div>
      </ul>
      </div>
    </div><!--/.nav-collapse -->
 </div>
 <div class="navbar navbar-default" style="border: 1px">
   <div class="navbar-header">
    <center>
         <img src="images/wilmu-logo.png" height="100" width="100">
    </center>
    </div>
   <div id="navbar" class="navbar-collapse collapse" background-color: #030033;>
    <ul class="nav navbar-nav">
     <li><a href="index.html">Academics</a></li>
     <li><a href="Admission.html">Admission</a></li>
     <li><a href="StudentServices.html">Student Services</a></li>
     <li><a href="StudentLife.html">Student Life</a></li>
     <li><a href="Alumni.html">Alumni</a></li>
     <li><a href="AthleticsUs.html">Athletics Us</a></li>
     <li><a href="AboutWilmu.html">About Wilmu</a></li>
    </ul>
   </div><!--/.nav-collapse -->
</div>
<!--
<div id="rStudioHeader" class="alwaysShrunk">
  <div class="innards bandContent">
   <div id="menu">
     <div id="menuToggler"></div>
      <div id="menuItems">
        <a class="menuItem" href="lesson-1.html">Get Started</a>
        <a class="menuItem" href="gallery.html">Gallery</a>
        <a class="menuItem" href="formats.html">Formats</a>
        <a class="menuItem" href="articles.html">Articles</a>
      </div>
    </div>
 </div>
</div>
-->
<style type="text/css">
#TOC {
  margin-left: 35px;
  margin-top: 90px;
}
</style>
<!-- If you remove this comments, then the page content shifts complete left 
<script type="text/javascript">
$(".main-container").removeClass("main-container").removeClass("container-fluid").addClass("footerPushDown");
</script>
-->

<div id="pageContent" class="standardPadding">
<div class="articleBandContent">

<style type="text/css">
.title {
  display: none;
}
#disqus_thread {
  display: none;
}
</style>

<div class="fluid-row" id="header">



<h1 class="title toc-ignore">Wilmington University</h1>

</div>


<script type="text/javascript">
$("#rStudioHeader").removeClass("alwaysShrunk");
$("#pageContent").removeClass("standardPadding");
</script>
<p>At Wilmington University, students have the opportunity to pursue a career and become a leader. It’s not just about meeting your potential, it’s about exceeding it.</p>
<p>Wilmington University is a private, non-sectarian university which offers both undergraduate and graduate degree programs in a wide range of career areas. The University began with a charter class of 194 students in 1968 and now enrolls a diverse student body numbering more than 18,000 annually.</p>
<p>The program of day, evening, and weekend classes serves traditional high school graduates as well as non-traditional adult students in need of flexible scheduling. Classes are primarily offered in 15-week, 7-week, and weekend modular formats. Introduced in 2005, Fusion programs combine online and face-to-face learning. These programs are designed for students who wish to complete their degree in less time than is possible with traditional courses.</p>
<p>Wilmington University’s main campus is located near the cities of Wilmington and historic New Castle, Delaware. The campus is easily accessible by air, rail, and bus. Our central location in the northeast/mid-Atlantic corridor of the United States provides students convenient access to the major cities of Philadelphia, New York, Baltimore, and Washington D.C. Recreational areas such as beaches and ski resorts are within easy driving distance.</p>
<p>Additional sites include the Wilson Graduate Center, Dover, Dover Air Force Base, the William A. Carter Partnership Center in Georgetown, and Brandywine. In New Jersey, Wilmington University offers programs on the Burlington County College and Cumberland County College campuses, and the Joint Base Education Center for McGuire AFB/Fort Dix/Lakehurst Naval Air Station.</p>
<p>Wilmington University generally serves commuter students and does not provide student housing facilities. However, the University welcomes all qualified students and assists those needing living accommodations by providing a listing of nearby rental opportunities. Click here for more consumer information.</p>
<p>Data compiled by the Office of Institutional Research</p>
<p>Wilmington University is a 501(c)(3) organization.</p>

</div> <!-- lessonContent -->
</div> <!-- lessonPage -->

<script type="text/javascript">
  var lesson = window.location.href.match(/lesson-[0-9]+/g);
  if (lesson !== null) {
    lesson = 'nav-' + lesson[0];
    $('#'+lesson).addClass('current');
  }

  $('#show-answer').on("click", function() {
    $('#show-answer').addClass('showing');
    $('#model-answer').addClass('showing');
  })
</script>
</div> <!-- articleBandContent -->
</div> <!-- pageContent -->

<div id="rStudioFooter" class="band full">
<div class="bandContent">
			<div id="footer-contact" class="col-xs-12 col-sm-12 col-md-4 col-lg-4">
				<h3>Contact &amp; Visit</h3>
					<div class="row">
							<div id="address">
								<address>
								<strong> Wilmington University</strong><br>
								320 N. DuPont Hwy<br>
								New Castle, DE 19720
								</address>
							</div>	
					 <div id="logos">
  					 <a href="https://www.facebook.com/WilmingtonUniversity" class="footerLogo facebook"></a>
  					  <a href="https://twitter.com/theWilmU" class="footerLogo twitter"></a>
  				   <a href="https://www.instagram.com/wilmingtonuniversity" class="footerLogo instagram"></a>
  				   <a href="https://www.linkedin.com/edu/wilmington-university-18075" class="footerLogo linkedin"></a>
  				   <a href="https://www.youtube.com/user/wilmu68" class="footerLogo youtube"></a>
           </div>
					</div>
		 	 </div>
</div>
</div>
<!-- END .row -->
<p class="copyright">&copy; 2018 Wilmington University</p>



</div>

<script>

// add bootstrap table styles to pandoc tables
function bootstrapStylePandocTables() {
  $('tr.header').parent('thead').parent('table').addClass('table table-condensed');
}
$(document).ready(function () {
  bootstrapStylePandocTables();
});


</script>


</body>
</html>
