<html>
<head>
<title> HTML: A Basic Guide </title>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center-right;
  padding: 14px 16px;
  text-decoration: none;
  font-family: Comic Sans MS;
  font-size: 20px;
}

li a:hover {
  background-color: #111;
}
#h1 {
font-family: Comic Sans MS;
}
body {margin:0;}

.vert {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
  position: fixed;
  bottom: 0;
  width: 100%;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover:not(.passive) {
  background-color: #111;
}

.passive {
  background-color: #04AA6D;
}
body{
font-family: Comic Sans MS;
background-color: #50C878;
}
</style>
</head>
<body>
<marquee direction="right" bgcolor= "lavender">
<h1 id= "home"> HTML: A Basic Guide</h1>
</marquee>
<ul>
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="#news">HTML Tags</a></li>
  <li><a href="#contact">History</a></li>
   <li><a href="#contact">Other Sources</a></li>
    <li><a href="#contact">Videos</a></li>
  <li><a href="">About</a></li>
</ul>
<ul class="vert">
  <li><a class="passive" href="#home">Home</a></li>
  <li><a href="#html">HTML</a></li>
  <li><a href="#content">Content</a></li>
  <li><a href="#elements">Elements</a></li>
   <li><a href="#browsers">Browsers</a></li>
    <li><a href="#structure">Structure</a></li>
	
</ul>
<div style="padding:20px;background-color:#50C878;height:1500px;"> 
<br>
<big><strong>
<h1 id="h1" align="center"> Home</h1></strong></big>
<u><h1 id="html">What is HTML? <h1></u>
<h2 align="left">HTML stands for Hyper Text Markup Language<br>
HTML is the standard markup language for creating Web pages<br>
HTML describes the structure of a Web page<br>
HTML consists of a series of elements<br>
HTML elements tell the browser how to display the content<br>
HTML elements label pieces of content</h2><br>
<u><h1 id="content">Content Explained</h1>
</u>
<h2>The < html > declaration defines that this document is an HTML document
<br>The < html > element is the root element of an HTML page
<br>The < head > element contains meta information about the HTML page
<br>The < title > element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
<br>The < body > element defines the document's body, and is a container for all the visible contents, such as headings and paragraphs
<br>The < h1 > element defines a large heading<br>
The < p > element defines a paragraph</h2><br>
<h1 id="elements"><u>HTML Elements</u></h1>
<h2>An HTML element is defined by a start tag, some content, and an end tag:
<br><br>
< tagname > Content goes here... < /tagname ><br>
The HTML element is everything from the start tag to the end tag:
<br>
<h1 >My First Heading (h1) </h1 >
<p >My first paragraph. (p) </p >
</h2><br>
<h1 id="browsers"><u>Web Browsers</u></h1>
<h2>The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.
<br><br>
A browser does not display the HTML tags, but uses them to determine how to display the document</h2><br>
<h1 id="structure"><u>HTML Page Structure</u></h1>
<h2> The HTML code structure is given below<br><br>
< html ><br>
< head ><br>
< title >Page title< /title ><br>
< /head ><br>
< body ><br>
< h1 >This is a heading< /h1 ><br>
< p >This is a paragraph.< /p ><br>
< p >This is another paragraph.< /p ><br>
< /body ><br>
< /html ></h2><br><br>	

</div></body>
</html>
