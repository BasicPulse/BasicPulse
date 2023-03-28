<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='true' b:js='true' expr:dir='data:blog.languageDirection' lang='en' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
	<title><data:blog.pageTitle/></title> 
	<b:else/>
	<title><data:blog.pageName/> | <data:blog.title/></title>
 	</b:if>
 	<b:if cond='data:blog.url == data:blog.homepageUrl'>
 	<title><data:blog.pageName/> | <data:blog.title/></title>
 	</b:if>
 	<b:if cond='data:blog.pageType == &quot;item&quot;'>
 	<meta expr:content='data:blog.pageName' property='og:title'/>
   	</b:if>
    <meta content='text/html; charset=utf-8' http-equiv='Content-Type'/>
    <meta content='Applying patterns essential for living a remarkable life.' name='description'/>
    <meta content='Remarkable, Uduk, Satisfaction, Fulfilment, Essentialism, Essential' name='keywords'/>
    <meta content='Paul Uduk' name='Author'/>
    <meta content='width=device-width, initial-scale=1, maximum-scale=1' name='viewport'/>
    <link href='http://fonts.googleapis.com/css?family=Yanone+Kaffeesatz:300' media='print' onload='this.media=&apos;all&apos;' rel='stylesheet'/>
	<link href='https://www.gstatic.com/_/freebird/_/js/k=freebird.v.en.BEl5XYbGPl0.O/d=1/rs=AMjVe6iRo0XtZ4hTGOga0bO8l4o9pmoM0w/m=viewer_base' rel='dns-preconnect'/> 
    <b:skin><![CDATA[
/* Variable definitions
   ====================
   <Variable name="bgcolor" description="Page Background Color"
             type="color" default="#fff" value="#ffffff">
   <Variable name="textcolor" description="Text Color"
             type="color" default="#666" value="#000000">
   <Variable name="linkcolor" description="Link Color"
             type="color" default="#999" value="#999999">
   <Variable name="linkhovercolor" description="Link Hover Color"
             type="color" default="#333" value="#ffbd1b">
   <Variable name="pagetitlecolor" description="Blog Title Color"
             type="color" default="#000" value="#000000">
   <Variable name="descriptioncolor" description="Blog Description Color"
             type="color" default="#777" value="#777777">
   <Variable name="titlecolor" description="Post Title Color"
             type="color" default="#333" value="#000000">
   <Variable name="bordercolor" description="Border Color"
             type="color" default="#ccc" value="#cccccc">
   <Variable name="sidebarcolor" description="Sidebar Title Color"
             type="color" default="#777" value="#777777">
   <Variable name="sidebartextcolor" description="Sidebar Text Color"
             type="color" default="#666" value="#666666">
   <Variable name="visitedlinkcolor" description="Visited Link Color"
             type="color" default="#888" value="#888888">
   <Variable name="pagelinkcolor" description="Page Link Color"
             type="color" default="#333" value="#ffbd1b">
   <Variable name="widgettitlefont" description="Widget Title Font"
             type="font" default="normal normal 11px Arial, Georgia, Serif" value="normal normal 16px Verdana, Geneva, sans-serif">
   <Variable name="bodyfont" description="Text Font"
             type="font" default="normal normal 11px Arial, Georgia, Serif" value="normal normal 18px Arial, Tahoma, Helvetica, FreeSans, sans-serif">
   <Variable name="headerfont" description="Sidebar Title Font"
             type="font"
             default="normal normal 11px 'Verdana',Trebuchet,Trebuchet MS,Arial,Sans-serif" value="normal normal 16px &#39;Verdana&#39;,Trebuchet,Trebuchet MS,Arial,Sans-serif">
   <Variable name="pagetitlefont" description="Blog Title Font"
             type="font"
             default="normal normal 60px Oswald, Georgia, Serif" value="normal bold 55px Georgia, Utopia, &#39;Palatino Linotype&#39;, Palatino, serif">
   <Variable name="descriptionfont" description="Blog Description Font"
             type="font"
             default="normal normal 10px 'Arial', Verdana, Trebuchet, Trebuchet MS, Verdana, Sans-serif" value="normal normal 16px Josefin Slab">
   <Variable name="postfooterfont" description="Post Footer Font"
             type="font"
             default="normal normal 78% 'Trebuchet MS', Trebuchet, Arial, Verdana, Sans-serif" value="normal normal 16px Arial, Tahoma, Helvetica, FreeSans, sans-serif">
   <Variable name="pagenavifont" description="Page Navigation Font"
             type="font"
             default="normal normal 10px Verdana, Arial, Serif" value="normal normal 14px Verdana, Arial">
   <Variable name="startSide" description="Side where text starts in blog language"
             type="automatic" default="left">
   <Variable name="endSide" description="Side where text ends in blog language"
             type="automatic" default="right">

*/
     
/* =============================
Misc and Reset
============================= */
#navbar-iframe, .feed-links, .status-msg-wrap {
  display:none;
}
#ArchiveList {
  font: 300 15px Yanone Kaffeesatz;
}
.widget .Label {
  font: 300 17px Yanone Kaffeesatz;
}
::selection {
  background:#000000;
  color:#fff
}
::-moz-selection {
  background:#000000;
  color:#fff
}
.follow-by-email-address {
  margin-top:2px;
  border-radius:3px;
  box-shadow:none;
}
.flickr_badge_image {
  float:left;
  margin:0 5px 0 0;
}
.flickr_badge_image img {
  height:70px;
  width:70px;
}
.flickr_info {
  margin:0 5px;
  font:10px arial;
  color:333;
}
body {
  margin:0;
  color:#333;
  background:$bgcolor;
  text-align:center;
}
a:link {
  color:$linkcolor;
  text-decoration:none;
}
a:visited {
  color:$visitedlinkcolor;
  text-decoration:none;
}
a:hover {
  color:$linkhovercolor;
  text-decoration:underline;
}
a img {
  border-width:0;
}


/* =============================
Popular Posts Style
============================= */
.PopularPosts {
  font-family: arial;
}
.PopularPosts .item-content {
  border-bottom: 1px dotted #eee;
  padding-bottom :10px;
}
.PopularPosts .item-snippet {
  font: 15px Arial;
  text-align: justify;
}
.PopularPosts .item-title {
  font: 16px Yanone Kaffeesatz !important;
} 
.PopularPosts .item-thumbnail img {
  border: 1px solid #fbfbfb;
  padding: 0;
}


/* =============================
LightBox
============================= */
#jquery-overlay {
  position:absolute;
  top:0;
  left:0;
  z-index:90;
  width:100%;
  height:500px;
}
#jquery-lightbox {
  position:absolute;
  top:0;
  left:0;
  width:100%;
  z-index:100;
  text-align:center;
  line-height:0;
}
#jquery-lightbox a, #jquery-lightbox a:hover {
  border:none;
}
#jquery-lightbox a img {
  border:none;
}
#lightbox-container-image-box {
  position:relative;
  background-color:#fff;
  width:250px;
  height:250px;
  margin:0 auto;
}
#lightbox-container-image {
  padding:10px;
}
#lightbox-loading {
  position:absolute;
  top:40%;
  left:0%;
  height:25%;
  width:100%;
  text-align:center;
  line-height:0;
}
#lightbox-nav{
  position:absolute;
  top:0;
  left:0;
  height:100%;
  width:100%;
  z-index:10;
}
#lightbox-container-image-box > #lightbox-nav {
  left:0;
}
#lightbox-nav a {
  outline:none;
}
#lightbox-nav-btnPrev, #lightbox-nav-btnNext {
  width:49%;
  height:100%;
  zoom:1;
  display:block;
}
#lightbox-nav-btnPrev {
  left:0;
  float:left;
}
#lightbox-nav-btnNext {
  right:0;
  float:right;
}
#lightbox-container-image-data-box {
  font:10px Verdana,Helvetica,sans-serif;
  background-color:#fff;
  margin:0 auto;
  line-height:1.4em;
  overflow:auto;
  width:100%;
  padding:0 10px 0;
}
#lightbox-container-image-data {
  padding:0 10px;
  color:#666;
}
#lightbox-container-image-data #lightbox-image-details {
  width:70%;
  float:left;
  text-align:left;
}
#lightbox-image-details-caption {
  font-weight:bold;
}
#lightbox-image-details-currentNumber {
  display:block;
  clear:left;
  padding-bottom:1.0em;
}
#lightbox-secNav-btnClose {
  width:66px;
  float:right;
  padding-bottom:0.7em;
}


/* =============================
Social Links
============================= */
#interwebz-wrapper {
  display:inline-block;
  width:950px;
  border-bottom:1px solid #f2f2f2;
  border-top:none;
  padding:5px 0;
}
.interwebz {
  list-style:none;
  margin:0;
  padding:10px 0;
  width:auto;
  overflow:hidden;
  float:left;
}
.interwebz li {
  float:left;
  margin-right:10px;
  border:none;
}

.interwebz li:last-child{margin:0}

/* Flickr */
.icon-flickr a, .icon-instagram a, .icon-facebook a, .icon-gplus a, .icon-lastfm a, .icon-feed a, .icon-skype a, .icon-twitter a, .icon-youtube a {
  float:left;
  background:url(http://lh3.googleusercontent.com/-ZNmJ3GyC0w8/UCauR4zdumI/AAAAAAAADsw/an6k7AUCQ3Y/s0/social-media.png) no-repeat left bottom;
  text-indent:-9999px;
  width:32px;
  height:32px;
  -o-transition: all 0.3s; 
  -moz-transition: all 0.3s; 
  -webkit-transition: all 0.3s;
}
.icon-flickr a:hover, .icon-instagram a:hover, .icon-facebook a:hover, .icon-gplus a:hover, .icon-lastfm a:hover, .icon-feed a:hover, .icon-skype a:hover, .icon-twitter a:hover, .icon-youtube a:hover {
  background:url(http://lh3.googleusercontent.com/-ZNmJ3GyC0w8/UCauR4zdumI/AAAAAAAADsw/an6k7AUCQ3Y/s0/social-media.png) no-repeat left top;
  -o-transition: all 0.3s; 
  -moz-transition: all 0.3s; 
  -webkit-transition: all 0.3s;
}

/* Facebook */
.icon-facebook, .icon-facebook a {
  background-position:-64px bottom;
}
.icon-facebook:hover, .icon-facebook a:hover {
  background-position:-64px top;
}


/* RSS Feed */
.icon-feed, .icon-feed a {
  background-position:-160px bottom;
}
.icon-feed:hover, .icon-feed a:hover {
  background-position:-160px top;
}

/* Twitter */
.icon-twitter, .icon-twitter a {
  background-position:-224px bottom;
}
.icon-twitter:hover, .icon-twitter a:hover {
  background-position:-224px top;
}

/* =============================
Search Box
============================= */
#srcnt {
  float:right;
  margin:0;
  padding:13px 0;
  width:auto;
  overflow:hidden;
}
#search input[type="text"] {
  border: 1px solid #eee;
  border-radius:3px;
  color: #777;
  width: 180px;
  padding: 7px;
  font:normal 10px Verdana, Arial;
  text-transform:uppercase;
  -webkit-transition: all 0.5s ease 0s;
  -moz-transition: all 0.5s ease 0s;
  -o-transition: all 0.5s ease 0s;
  transition: all 0.5s ease 0s;
}
#search input[type="text"]:focus {
  width: 220px;
}


/* =============================
Header
============================= */
#header-wrapper{
  width:950px;
  margin:20px auto 0;
}
#header-inner {
  background-position: center;
  margin:0 auto;
  width:950px;
}
#header { 
  margin:0;
  text-align: center;
  color:$pagetitlecolor;
  width:950px;
}
#header h1 {
  margin:5px 5px 0;
  padding:15px 20px 0;
  line-height:1.2em;
  text-transform:uppercase;
  letter-spacing:.2em;
  font: $pagetitlefont;
}

#header a {
  color:$pagetitlecolor;
  text-decoration:none;
}
#header a:hover {
  color:$pagetitlecolor;
}
#header .description {
  margin:0 5px 0;
  padding:0 20px 15px;
  max-width:950px;
  letter-spacing:.2em;
  line-height: 1.4em;
  font: $descriptionfont;
  color: $descriptioncolor;
  text-transform: uppercase;
}
#header-inner img {
  margin:0 auto;
  max-width:950px;
  height:auto;
}
#header img {
  margin:0 auto;
  max-width:950px;
  height:auto;
}

/* =============================
Navigation
============================= */
*{
  margin:0;
  padding:0;
  outline:0;
}
.nav {
  width:100%;
  height:auto;
  border-bottom:1px solid #eee;
  margin:10px auto 5px;
  display:inline-block;
  
}
.menu {
  width:auto;
  list-style:none;
  font: 20px Yanone Kaffeesatz;
  text-align:center;
  margin:0 auto;
}
.menu a {
  float:center;
  color:#999;
  text-decoration:none;
  text-transform:uppercase;
  width:auto;
  line-height:36px;
  padding:0 20px;
}
.menu a:hover,li.menuhover a{
  color:#ffbd1b;
}

.menu li {
  position:relative;
  float:none;
  width:auto;
  display:inline;
}
.menu li:last-child {
  background:none;
}
.menu ul{
  display:inline-block;
  position:absolute;
  top:36px;
  left:0;
  background:#fbfbfb;
  display:none;
  list-style:none;
}
.menu ul li{
  float:none;
  border-top:1px solid #e3e3e3;
  border-right:1px solid #e3e3e3;
  border-left:1px solid #e3e3e3;
  width:auto;
  background:none;
}
.menu ul li:last-child {
  border-bottom:1px solid #e3e3e3
}
.menu ul li a{
  float:none;
  display:block;
  background:none;
  line-height:36px;
  min-width:137px;
  width:auto;
  text-align:left;
  padding-left:10px;
  color:#444;
}
.menu ul li a:hover{
  background:#fdfdfd;
  color:#777;
}


/* =============================
Wrapper
============================= */
#total-wrapper {
  margin: 0 auto;
  padding 0 10px;
  background:#fff;
  width:1000px;
}
#outer-wrapper{
  width:960px;
  margin:10px auto 0;
  padding:5px 20px 0;
  text-align:$startSide;
  font:$bodyfont;
}
#main-wrapper {
  width:720px;
  float:$startSide;
  word-wrap:break-word;
  overflow:hidden;
}

#sidebar-wrapper{
  width:240px;
  float:$startSide;
  word-wrap:break-word;
  overflow:hidden;
}


/* =============================
Heading
============================= */
h2{
  margin:1.5em 0 10px;
  font:23px Yanone Kaffeesatz;
  text-transform:uppercase;
  line-height: 1.2em;
  padding-bottom: 2px;
  letter-spacing:.2em;
  color:#000;
}
.sidebar h2 {
  padding:9px 3px 10px;
  margin:0 0 15px;
  letter-spacing:1px;
  border-bottom:1px solid #eee;
  font:300 18px Yanone Kaffeesatz;
  background:url(http://lh4.googleusercontent.com/-1uhYrRStLp8/UCXF4vd4bnI/AAAAAAAADrM/86ME3YtzuH8/s0/h2-date-header.png)right bottom no-repeat #fff;
}
#blog-date-header {
  font:normal 8px Verdana, Arial;
  color:#555;
  letter-spacing:0;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  -o-text-overflow: ellipsis;
  -moz-binding: url(&#39;assets/xml/ellipsis.xml#ellipsis&#39;);
}
#blog-date-header i {
  text-transform:none;
}
h2.date-header {
  border-bottom:1px solid #eee;
  color:#777;
}


/* =============================
Posts
============================= */
.post {
  margin:.5em 0 2em;
  border-bottom:1px solid #eee;
  padding-bottom:1.5em;
  font-family:Arial,Sans-serif,Verdana;
  color:#000;
}
.post h3 {
  margin:.25em 0 0;
  padding:0 0 4px;
  font-size:16px;
  line-height:1.4em;
  color:#333;
  font-family:oswald;
}
.post h3 a, .post h3 a:visited, .post h3 strong {
  display:block;
  text-decoration:none;
  color:#333;
  font-weight:400;
}
.post h3 strong, .post h3 a:hover {
  color:#000;
}
.post-body {
  margin:0 0 1.75em;
  line-height:1.6em;
  font: 22px Georgia;
  text-align: left;
  margin-right: 20px;
  
} 
.post-body blockquote {
  line-height:1.6em;
}
.post-footer {
  margin:.75em 0;
  color:#777;
  text-transform:uppercase;
  letter-spacing:.1em;
  font:$postfooterfont;
  line-height:1.4em;
}
.comment-link {
  margin-startside:.6em;
}
.post img {
 width:auto;
  height:auto;
  padding-right:1px;
  float:left;
  margin-right:20px;
  
}
.post table. tr-caption-container {
  padding-bottom:4px;
}
.tr-caption-container img {
  border:none;
  padding:0;
}
.post blockquote {
  margin:1em 20px;
  padding:2px 5px 2px 35px;
  font-style:italic;
  color:#777;
}
.post blockquote p {
  margin:.75em 0;
}


.post ol > li {
    list-style-type: decimal;
	display: list-item;
	margin-left: 40px;
	font-size: 22px; 
	line-height:1.6em;
	margin-bottom: 10px;
	margin-top: 10px;
	margin-right: 50px;
    	

}

.post ul > li {
    list-style-type: circle;
	display: list-item;
	margin-left: 40px;
	font-size: 22px; 
	line-height:1.6em;
	margin-bottom: 10px;
	margin-top: 10px;
	margin-right: 50px;
}

.post ul > li:before {
    width: 1.5em;
	   
    
}

/* =============================
Post Navigation
============================= */
#blog-pager-newer-link, #blog-pager-newer-link a {
  background:url(http://lh4.googleusercontent.com/-4Rz-XruFG94/UCJjn7nKmRI/AAAAAAAADnI/c-wLS0RhBxE/s0/post-navi.png) no-repeat left top;
  float:left;
  width:26px;
  height:26px;
  text-indent:-9999px;
}
#blog-pager-older-link, #blog-pager-older-link a {
  background:url(http://lh4.googleusercontent.com/-4Rz-XruFG94/UCJjn7nKmRI/AAAAAAAADnI/c-wLS0RhBxE/s0/post-navi.png) no-repeat right top;
  float:right;
  width:26px;
  height:26px;
  text-indent:-9999px;
}
#blog-pager { 
  text-align: center;
  border-top:1px solid #eee;
  margin: 10px 5px 0;
}
.home-link{}

/* =============================
Comment
============================= */
.comments .comments-content {
  font:normal 16px Arial;
  text-align: center;
  line-height:1.4em;
  margin-bottom:16px;
}
.comments .comments-content .user {
  font-style:normal;
  font-weight:normal;
  text-transform:uppercase;
  color:#000;
}
.comments .comments-content .datetime {
  margin-left:10px;
}
.comment-replies{
  background:#fbfbfd;
  box-shadow:inset 0 0 0 1px #f2f2f2;
  border-radius:3px;
}
.comments .comment .comment-actions a {
  background:#999;
  color:#fff;
  padding:2px 5px;
  margin-right:10px;
  font:10px sans-serif;
  border-radius:3px;
  -moz-border-radius:3px;
  -webkit-border-radius:3px;
  transition:.2s linear;
  -moz-transition:.2s linear;
  -webkit-transition:.2s linear;
}
.comments .comment .comment-actions a:hover {
  background:#000;
  text-decoration:none;
  transition:.2s linear;
  -moz-transition:.2s linear;
  -webkit-transition:.2s linear;
}
.comments .avatar-image-container {
  border-radius:3px;
}  
.comments .thread-toggle a {
  color:#a58;
}
.comments .thread-toggle a:hover {
  padding-left:10px;
  color:#a47;
  text-decoration:none;
}
.comments .thread-toggle a:hover, .comments .thread-toggle a {
  transition:.2s linear;
  -moz-transition:.2s linear;
  -webkit-transition:.2s linear;
}
#comments h4 {
  margin:1em 0;
  line-height:1.4em;
  letter-spacing:.2em;
  color:$sidebarcolor;
  text-transform:uppercase;
  font:normal 11px Arial;
}
#comments-block {
  margin:1em 0 1.5em;
  line-height:1.6em;
}
#comments-block .comment-author {
  margin:.5em 0;
}
#comments-block .comment-body {
  margin:.25em 0 0;
}
#comments-block .comment-footer {
  margin:-.25em 0 2em;
  line-height: 1.4em;
  text-transform:uppercase;
  letter-spacing:.1em;
}
#comments-block .comment-body p {
  margin:0 0 .75em;
}
.deleted-comment {
  font-style:italic;
  color:gray;
}



/* =============================
Sidebar
============================= */
.sidebar { 
  color: $sidebartextcolor;
  line-height: 1.5em;
  margin:0 5px 0 10px;
}
.sidebar ul {
  list-style:none;
  padding:0;
  margin:0;
}
.sidebar li {
  line-height:1.5em;
}
.sidebar .widget { 
  margin:0 0 1.5em;
  padding:0 0 1.5em;
}
.main .widget{
  border-bottom:1px solid #ccc;
  margin:0 0 1px;
  padding:0 0 1.5em;
}

.main .Blog{
  border-bottom-width:0;
}


/* =============================
Profile
============================= */
.profile-img { 
  float: $startSide;
  margin-top: 0;
  margin-$endSide: 5px;
  margin-bottom: 5px;
  margin-$startSide: 0;
  padding: 4px;
  border: 1px solid $bordercolor;
}
.profile-data {
  margin:0;
  text-transform:uppercase;
  letter-spacing:.1em;
  font: $postfooterfont;
  color: $sidebarcolor;
  font-weight: bold;
  line-height: 1.6em;
}
.profile-datablock { 
  margin:.5em 0 .5em;
}
.profile-textblock { 
  margin: 0.5em 0;
  line-height: 1.6em;
}
.profile-link { 
  font: $postfooterfont;
  text-transform: uppercase;
  letter-spacing: .1em;
}

/* =============================
Twitter Widget
============================= */
#twitter_div ul {
  list-style-type:none;
  margin:0 10px 0 0;
  padding:0;
}
#twitter_div ul li {
  border:none;
background:url(http://lh6.googleusercontent.com/-c-LErZwdbAk/T_c7mi-YXhI/AAAAAAAADV4/-pliiRp1o_k/s15/tweet-li.png) no-repeat left 5px;
  padding:0 0 10px 25px;
  font-family:arial;
  font-size:11px;
  color:#555;
}
#twitter_div ul li a {
  color:#111;
  font-style:italic;
}


/* =============================
Error Page
============================= */

#errorpage {
  width:400px;
  text-align:center;
  margin:20px auto;
  text-transform:uppercase;
}
#errorpage h1 {
  font:300 60px Yanone Kaffeesatz;
}
#errorpage h3 {
  font:300 20px Oswald;
  color:#555;
}
#errorpage p {
  font:9px Arial;
  margin-top:5px;
  border-top:1px dashed #ddd;
  padding-top:10px;
  color:#888;
}
#srcnt-errorpage {
  margin:0;
  padding:13px 0;
  width:auto;
  overflow:hidden;
}
#search-errorpage input[type="text"] {
  border: 1px solid #ccc;
  border-radius:3px;
  color: #777;
  width: 180px;
  padding: 7px;
  font:normal 10px Verdana, Arial;
  text-transform:uppercase;
}
#search-errorpage input[type="text"]:focus {
  border: 1px solid #777;
}

/* =============================
Posts Thumbnail and Description
============================= */
.snips-image{
  width:310px;
  height:185px;
  position:relative;
  line-height:1.6em;
  margin:0;
  overflow:hidden;
}
.snips-image img{
  top:0;
  left:0;
  border:0;
  position:absolute;
  min-height:185px;
  max-width:310px;
}
.snips-image a{
  display:block;
  position:relative;
  overflow:hidden;
  height:185px;
  width:310px;
  color:#555;
}
.snips-image a:hover{
  text-decoration:none;
}
.summary{
  padding:10px 0;
  margin:0 50px;
  font:16px Arial, sans-serif;
  border-bottom:1px solid #eee;
  border-top:1px solid #eee;
  color:#666;
}
.snips-header{
  margin:25px 50px 10px;
  font:300 17px Oswald;
  text-decoration:underlined;
}


/* =============================
Middle and Footer
============================= */
#middle-wrapper {
  width:950px;
  margin:0 auto;
  padding-top:20px;
  border-top:1px solid #eee
}
#middle-columns {
  font:normal 13px Arial;
  width:950px;
  margin:0 auto 20px;
  text-align:$startSide;
  padding:0 0 20px;
}
#middle-columns h2 {
  margin:1.5em 0 15px;
  font:$widgettitlefont;
  border-bottom:1px solid #eee;
  line-height: 1.4em;
  padding: 0 0 10px;
  text-transform:uppercase;
  letter-spacing:.2em;
  color:#555;
}
.column1 {
  width:300px;
  float:left;
  margin:3px 25px 3px 0;
  text-align:left;
}
.column2 {
  width:300px;
  float:Left;
  margin:3px 0;
  text-align:left;
}
.column3 {
  width:300px;
  float:left;
  margin:3px 0 3px 25px;
  text-align:Left;
}
#col1, #col2, #col3 {
  text-align:justify;
  color:#555;
  line-height:17.5px;
}
#col1 a, #col2 a, #col3 a {
  color:#$linkcolor;
}

/* =============================
Footer Links and Credits
============================= */
#footer-links-wrap {
  padding:20px 0 20px;
  width:950px;
  margin:5px auto 0;
  border-top:1px solid #eee;
  background:url(http://lh5.googleusercontent.com/-ZFiM8ihZXig/UC_bbJy1PPI/AAAAAAAAD2E/RgkwRJmXVy4/s0/bottom-left.png) no-repeat left center ,url(http://lh6.googleusercontent.com/-_j5Iw4rQkbg/UC_bbDYu6vI/AAAAAAAAD2I/K4p4oxKcR9c/s0/bottom-right.png) no-repeat right center;
}
#footer-links a {
  color:#333;
  font-style:normal;
}
#credits {
  line-height:20px;
}
.widget .post-body ul{
	padding: 0;
	margin: 0;
	line-height: 1;
}
.section,.widget,.widget li,.widget ul{
	margin: 0;
	padding: 0;
}

  
/* =============================
800px
============================= */
@media screen and (max-width : 800px) {

#total-wrapper {
            width: 95%;
}
#header-wrapper {
                        width:100%;
                        margin:auto;         
}
#header-inner {
                        background-position:center;
                        margin:auto;
                        width:100%;
}
#header {
            
                       width:100%;
}
     #header img {
                      margin:auto;
max-width: 100%;
}  		  
           #interwebz-wrapper {
                        display:inline-block;
                        width:65%;
                        border-bottom:1px solid #f2f2f2;
                        border-top:none;
                        padding:5px 0;
						zoom:1;
}  
.interwebz {
  float:center;
	margin-left:1px;
}
           #outer-wrapper {
                        max-width:100%;!Important
                        float:center:!Important
						
 margin:1px auto 0;
  padding:1px 40px 0;
}   
     #main-wrapper {
                        max-width:100%;!Important 
}
    .main .Blog{
                       border-bottom-width:100%;
}
         .post {
                       padding-bottom:22px;
      				   max-width:100%;!Important
					   
      	           
      }
.post-body {
  padding-right: 20px;
  
} 
     #middle-wrapper {
                        width:100%;
                        margin:auto;
                        padding-top:20px;
                        border-top:1px solid #000
                        border-bottom:1px solid #000;
   					    text-align:center;
}     

                #middle-columns {
                        font:normal 11px arial;
                        width:100%;
                        margin:auto;
                        padding-top:20px;
                        border-top:1px solid #000
                        border-bottom:1px solid #000;
}
#middle-columns h2 {
                        margin:1.5em 0 5px;
                        font:$widgettitlefont;
                        border-bottom:1px solid #555;
                        line-height: 1.4em;
                        padding: 0 0 0px;
                        text-transform:uppercase;
                        letter-spacing:.2em;
                        color:#555;
                        text-align:center;
}
                .column1 {
                        width:95%;
                        float:none;
                        padding:7px 7px 7px;
                        text-align:center;
}                .column2 {
                        width:95%;
                        float:center;
                        padding:7px 7px 7px;
                        text-align:Center;
}
                .column3 {
                        width:95%;
                        float:None;
                        margin:7px 7px 7px;
                        text-align:Center;
}
      #sidebar-wrapper{
  width:95%;
}
 #footer-links-wrap {
                        padding:20px 0 20px;
                        width:100%;
                        margin:5px auto 0;
                        border-top:1px solid #eee;
                        background:url(http://lh5.googleusercontent.com/-ZFiM8ihZXig/UC_bbJy1PPI/AAAAAAAAD2E/RgkwRJmXVy4/s0/bottom-left.png) no-repeat left center ,url(http://lh6.googleusercontent.com/-_j5Iw4rQkbg/UC_bbDYu6vI/AAAAAAAAD2I/K4p4oxKcR9c/s0/bottom-right.png) no-repeat right center;
}
                #footer-links {
                        color:#000;
                        width:100%;
                        margin:0 auto;
                        clear:both;
                        font:italic 11px arial;
                        text-align:center;
}

/* =============================
700px
============================= */
@media screen and (max-width : 700px) {

#total-wrapper {
            width: 100%;
}
#header-wrapper {
                        width:100%;
                        margin:auto;         
}
#header-inner {
                        background-position:center;
                        margin:auto;
                        width:100%;
}
#header {
            
                       width:100%;
}
     #header img {
                      margin:auto;
max-width: 100%;
}  		  
           #interwebz-wrapper {
                        display:inline-block;
                        width:65%;
                        border-bottom:1px solid #f2f2f2;
                        border-top:none;
                        padding:5px 0;
						zoom:1;
}  
.interwebz {
  float:center;
	margin-left:1px;
}
           #outer-wrapper {
                        max-width:100%;!Important
                        float:center:!Important
 margin:1px auto 0;
  padding:1px 1px 0;
}   
     #main-wrapper {
                        max-width:100%;!Important 
}
 
         .post {
                       padding-bottom:22px;
      				   max-width:100%;!Important
					   
      	           
      }
     #middle-wrapper {
                        width:100%;
                        margin:auto;
                        padding-top:20px;
                        border-top:1px solid #000
                        border-bottom:1px solid #000;
   					    text-align:center;
}     

                #middle-columns {
                        font:normal 11px arial;
                        width:100%;
                        margin:auto;
                        padding-top:20px;
                        border-top:1px solid #000
                        border-bottom:1px solid #000;
}
                .column1 {
                        width:95%;
                        float:none;
                        padding:7px 7px 7px;
                        text-align:center;
}                .column2 {
                        width:95%;
                        float:center;
                        padding:7px 7px 7px;
                        text-align:Center;
}
                .column3 {
                        width:95%;
                        float:None;
                        margin:7px 7px 7px;
                        text-align:Center;
}
      #sidebar-wrapper{
  width:95%;
}
 #footer-links-wrap {
                        padding:20px 0 20px;
                        width:100%;
                        margin:5px auto 0;
                        border-top:1px solid #eee;
                        background:url(http://lh5.googleusercontent.com/-ZFiM8ihZXig/UC_bbJy1PPI/AAAAAAAAD2E/RgkwRJmXVy4/s0/bottom-left.png) no-repeat left center ,url(http://lh6.googleusercontent.com/-_j5Iw4rQkbg/UC_bbDYu6vI/AAAAAAAAD2I/K4p4oxKcR9c/s0/bottom-right.png) no-repeat right center;
}
                #footer-links {
                        color:#000;
                        width:100%;
                        margin:0 auto;
                        clear:both;
                        font:italic 11px arial;
                        text-align:center;
}
   
    /* =============================
670px
============================= */
@media screen and (max-width : 670px) {

#total-wrapper {
            width: 100%;
}
#header-wrapper {
                        width:100%;
                        margin:auto;         
}
#header-inner {
                        background-position:center;
                        margin:auto;
                        width:100%;
}
#header {
            
                       width:100%;
}
     #header img {
                      margin:auto;
max-width: 100%;
}  		  
           #interwebz-wrapper {
                        display:inline-block;
                        width:65%;
                        border-bottom:1px solid #f2f2f2;
                        border-top:none;
                        padding:5px 0;
						zoom:1;
}  
.interwebz {
  float:center;
	margin-left:1px;
}
           #outer-wrapper {
                        max-width:100%;!Important
                        float:center:!Important
 margin:1px auto 0;
  padding:1px 1px 0;
}   
     #main-wrapper {
                        max-width:102%;!Important 
}
 
         .post {
                       padding-bottom:22px;
      				   max-width:100%;!Important
					   
      	           
      }
     #middle-wrapper {
                        width:100%;
                        margin:auto;
                        padding-top:20px;
                        border-top:1px solid #000
                        border-bottom:1px solid #000;
   					    text-align:center;
}     

                #middle-columns {
                        font:normal 11px arial;
                        width:100%;
                        margin:auto;
                        padding-top:20px;
                        border-top:1px solid #000
                        border-bottom:1px solid #000;
}
                .column1 {
                        width:95%;
                        float:none;
                        padding:7px 7px 7px;
                        text-align:center;
}                .column2 {
                        width:95%;
                        float:center;
                        padding:7px 7px 7px;
                        text-align:Center;
}
                .column3 {
                        width:95%;
                        float:None;
                        margin:7px 7px 7px;
                        text-align:Center;
}
      #sidebar-wrapper{
  width:95%;
}
 #footer-links-wrap {
                        padding:20px 0 20px;
                        width:100%;
                        margin:5px auto 0;
                        border-top:1px solid #eee;
                        background:url(http://lh5.googleusercontent.com/-ZFiM8ihZXig/UC_bbJy1PPI/AAAAAAAAD2E/RgkwRJmXVy4/s0/bottom-left.png) no-repeat left center ,url(http://lh6.googleusercontent.com/-_j5Iw4rQkbg/UC_bbDYu6vI/AAAAAAAAD2I/K4p4oxKcR9c/s0/bottom-right.png) no-repeat right center;
}
                #footer-links {
                        color:#000;
                        width:100%;
                        margin:0 auto;
                        clear:both;
                        font:italic 11px arial;
                        text-align:center;
}

      /* =============================
420px
============================= */
@media screen and (max-width : 420px) {

#total-wrapper {
            width: 80%;
}
#header-wrapper {
                        width:100%;
                        margin:auto;         
}
#header-inner {
                        background-position:center;
                        margin:auto;
                        width:100%;
}
#header {
            
                       width:100%;
}
     #header img {
                      margin:auto;
max-width: 100%;
}  		  
           #interwebz-wrapper {
                        display:inline-block;
                        width:65%;
                        border-bottom:1px solid #f2f2f2;
                        border-top:none;
                        padding:5px 0;
						zoom:1;
}  
.interwebz {
  float:center;
	margin-left:30px;
}
           #outer-wrapper {
                        max-width:100%;!Important
                        float:center:!Important
 margin:1px auto 0;
  padding:1px 1px 0;
}   
     #main-wrapper {
                        max-width:100%;!Important 
}
 
         .post {
                       padding-bottom:22px;
      				   max-width:100%;!Important
					  
      	           
      }
     #middle-wrapper {
                        width:100%;
                        margin:auto;
                        padding-top:20px;
                        border-top:1px solid #000
                        border-bottom:1px solid #000;
   					    text-align:center;
}     

                #middle-columns {
                        font:normal 11px arial;
                        width:100%;
                        margin:auto;
                        padding-top:20px;
                        border-top:1px solid #000
                        border-bottom:1px solid #000;
}
                .column1 {
                        width:95%;
                        float:none;
                        padding:7px 7px 7px;
                        text-align:center;
}                .column2 {
                        width:95%;
                        float:center;
                        padding:7px 7px 7px;
                        text-align:Center;
}
                .column3 {
                        width:95%;
                        float:None;
                        margin:7px 7px 7px;
                        text-align:Center;
}
      #sidebar-wrapper{
  width:95%;
}
 #footer-links-wrap {
                        padding:20px 0 20px;
                        width:100%;
                        margin:5px auto 0;
                        border-top:1px solid #eee;
                        background:url(http://lh5.googleusercontent.com/-ZFiM8ihZXig/UC_bbJy1PPI/AAAAAAAAD2E/RgkwRJmXVy4/s0/bottom-left.png) no-repeat left center ,url(http://lh6.googleusercontent.com/-_j5Iw4rQkbg/UC_bbDYu6vI/AAAAAAAAD2I/K4p4oxKcR9c/s0/bottom-right.png) no-repeat right center;
}
                #footer-links {
                        color:#000;
                        width:100%;
                        margin:0 auto;
                        clear:both;
                        font:italic 11px arial;
                        text-align:center;
}  
    ]]></b:skin>
    <style/>
    
 
  

<script src='http://ajax.googleapis.com/ajax/libs/jquery/1.6.3/jquery.min.js' type='text/javascript'/>
    
<script type='text/javascript'>
$(function() {$(&#39;.snips-image&#39;).hover(function(){$(this).find(&#39;img&#39;).animate({top:&#39;220px&#39;},{queue:false,duration:200});}, function(){$(this).find(&#39;img&#39;).animate({top:&#39;0px&#39;},{queue:false,duration:200});});})
</script>
    <script> 
$(document).ready(function(){$(&#39;#back-top a&#39;).click(function () {
$(&#39;body,html&#39;).animate({scrollTop: 0}, 800);return false;});});
</script>

    
<link href='' rel='stylesheet' type='text/css'/>
    <link href='http://fonts.googleapis.com/css?family=Oswald:300,400' media='print' onload='this.media=&apos;all&apos;' rel='stylesheet'/>
    
   

<b:if cond='data:blog.pageType != &quot;item&quot;'>
 <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
    <style>
      
  
#main-wrapper {
  width:1000px;
      float:center;
}
.post {
  width:320px;
  height:217px;
  float:left;
  margin:5px;
  border-bottom:none;
  border-top:1px solid #fff;
  background:#fff;
}
.post-body {
  margin:0 0 0;
  line-height:1.6em;
  font:16px Arial;
  text-align:justify;
  background:url(http://lh3.googleusercontent.com/-Ws6YyaMmcJc/UCWy8PMdF9I/AAAAAAAADq4/xqY6GKyxB8Y/s0/post-bg.png) bottom center no-repeat #ffffff;
}
.post h2:hover {
  margin-left:10px;
  transition:.3s linear;
  -o-transition:.3s linear;
  -moz-transition:.3s linear;
  -webkit-transition:.3s linear;
}
.post h2 {
  font:Oswald;
  font-size:19px;
  margin:0;
  height:40px;
  text-align:center;
  padding:10px;
  background:url(http://lh4.googleusercontent.com/-1uhYrRStLp8/UCXF4vd4bnI/AAAAAAAADrM/86ME3YtzuH8/s0/h2-date-header.png)right center no-repeat #fff;
  text-transform:uppercase;
  letter-spacing:1px;
  transition:.3s linear;
  -o-transition:.3s linear;
  -moz-transition:.3s linear;
  -webkit-transition:.3s linear;
  overflow:hidden;
  text-overflow: ellipsis;
  -o-text-overflow: ellipsis;
  -moz-binding: url(&#39;assets/xml/ellipsis.xml#ellipsis&#39;);
}
.post h3 a, .post h3 a:visited, .post h3 strong {
  font-weight:300;
}
.post img {
  padding:0;
}
.post-footer-line-1, .post-footer-line-2, .post-footer-line-3, .post-footer, #sidebar-wrapper, h2.date-header, .sidebar, .date-post-top-wrapper {
  display:none;
}
</style>
 </b:if>
</b:if>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
  
<style>
#outer-wrapper {
  width:100%;
}
#main-wrapper {
  width:680px;
  border-right:2px solid #eee;
  padding-left:0px;
  padding-right:10px;
  margin:0 2px 0;
  
}
#post-header-top {
  border-bottom:1px solid #ddd;
  margin-bottom:20px;
  padding-left:10px;
}
.date-post-top-wrapper {
  float:left;
  margin-right:10px;
}
  
.post-date-day-name {
  font:300 25px Yanone Kaffeesatz;
}
.post-date-day-month-year {
  font:italic 10px arial;
}
.page-date-day-name {
  font:300 25px Yanone Kaffeesatz;
}
.page-date-day-month-year {
  font:italic 10px arial;
}
.post h2 {
  margin:0 0 1px;
 Font: 300 44px Yanone Kaffeesatz !important;
  text-transform:uppercase;
  text-align:left;
  letter-spacing:0.05em;
}
.post-footer {
  padding:5px 10px;
  margin:0 0 5px;
  background:#fbfbfb;
  border:1px solid #f2f2f2;
  margin-left:2px;
}
.post {
  margin:0 0 1.5em;
  line-height:1.6em;
}
.post-body {
  margin:0 0 1.75em;
  font:22px Georgia;
  line-height:1.6em !important;
  margin-left:0.5px;
  margin-right:7px;
  width:auto;
}
.post img {
  width:95%;
  margin-right:50px;
}
.comments {
  margin-left:2px;
  width:95%;
}
  #blog-pager {
  margin-left:40px;
}

#related-posts {
  float:center;
  text-transform:none;
  height:100%;
  min-height:100%;
  padding-top:5px;
  margin-left:2px;
}
#related-posts h2 {
  color:#555;
  padding:5px;
  margin:0 0 10px;
  text-align:center;
  background:#fbfbfb;
  border-top:1px solid #eee;
  font:300 17px Yanone Kaffeesatz;
}
#related-posts a {
  color:#000;
  overflow:hidden;
  display:block;
  width:80px;
  height:155px;
  
}
#related-posts a:hover {
  background:#fbfbfb;
  color:#000;
  overflow:hidden;
}
#related-posts a img {
  transition:.3s linear;
  -moz-transition:all .3s;
  -webkit-transition:.3s linear;
  box-shadow:none;
  padding:4px;
  padding-top:7px;
}
#related-posts a img:hover {
  transition:.3s linear;
  -moz-transition:all .3s;
  -webkit-transition:.3s linear;
  margin-bottom:5px;
}
#rptxt{
  padding-top:5px;
  width:68px;
  height:78px;
  margin:5px;
  border-top:1px solid #ccc;
  font:300 14px Yanone Kaffeesatz;
  font-style:Bold;
}
</style>
 
    
    
    
    
    </b:if>
    <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
      <style>
        #outer-wrapper {
  width:1000px
}
        #main-wrapper {
  width:600;
  border-right:2px solid #eee;
  padding-left:5px;
  padding-right:10px;
        margin:0 5px 0;
}

        #post-header-top {
  border-bottom:1px solid #ddd;
        margin-bottom:20px;
  padding-left:10px;
         }
        
        .post {
  margin:0 0 1.5em;
  
}
        
       .post h2 {
  margin:0 0 1px;
 Font: 300 44px Yanone Kaffeesatz !important;
  text-transform:uppercase;
  text-align:left;
  letter-spacing:0.05em;

}
       
 .date-post-top-wrapper {
  float:left;
  margin-right:10px;
}
        
        .post-body {
  margin:0 0 1.75em;
  font:22px Georgia;
  line-height:1.6em !important;
  margin-left:0.5px;
  margin-right:7px;
  width:auto;
}
.post img {
  width:95%;
  margin-right:50px;
}
.comments {
  margin-left:2px;
        width:95%;
}
.post-footer {
  padding:5px 10px;
  margin:0 0 5px;
  background:#fbfbfb;
  border:1px solid #f2f2f2;
  margin-left:2px;
}  
.post-date-day-name {
  font:300 25px Yanone Kaffeesatz;
}
.post-date-day-month-year {
  font:italic 10px arial;
}
.page-date-day-name {
  font:300 25px Yanone Kaffeesatz;
}
.page-date-day-month-year {
  font:italic 10px arial;
}  
        
#blog-pager {
  margin-left:40px;
}

#related-posts {
  float:center;
  text-transform:none;
  height:100%;
  min-height:100%;
  padding-top:5px;
  margin-left:2px;
}
#related-posts h2 {
  color:#555;
  padding:5px;
  margin:0 0 10px;
  text-align:center;
  background:#fbfbfb;
  border-top:1px solid #eee;
  font:300 17px Yanone Kaffeesatz;
}
#related-posts a {
  color:#000;
  overflow:hidden;
  display:block;
  width:80px;
  height:155px;
  
}
#related-posts a:hover {
  background:#fbfbfb;
  color:#000;
  overflow:hidden;
}
#related-posts a img {
  transition:.3s linear;
  -moz-transition:all .3s;
  -webkit-transition:.3s linear;
  box-shadow:none;
  padding:4px;
  padding-top:7px;
}
#related-posts a img:hover {
  transition:.3s linear;
  -moz-transition:all .3s;
  -webkit-transition:.3s linear;
  margin-bottom:5px;
}
#rptxt{
  padding-top:5px;
  width:68px;
  height:78px;
  margin:5px;
  border-top:1px solid #ccc;
  font:300 14px Yanone Kaffeesatz;
  font-style:Bold;
}

</style>
    </b:if>


<script async='async' type='text/javascript'>
//<![CDATA[
$(document).ready(function(){
    $("#nav-mobile").html($("#nav-main").html());
    $("#nav-trigger span").click(function(){
        if ($("nav#nav-mobile ul").hasClass("expanded")) {
            $("nav#nav-mobile ul.expanded").removeClass("expanded").slideUp(250);
            $(this).removeClass("open");
        } else {
            $("nav#nav-mobile ul").addClass("expanded").slideDown(250);
            $(this).addClass("open");
        }
    });
});
//]]>
</script>
    <script async='async' type='application/ld+json'>
{
  &quot;@context&quot; : &quot;http://schema.org&quot;,
  &quot;@type&quot; : &quot;Article&quot;,
  &quot;name&quot; : &quot;BasicPulse&quot;,
  &quot;image&quot; : &quot;https://1.bp.blogspot.com/-EDH-kVg-I0s/WNvV4HRbUNI/AAAAAAAAApc/N4yLxwlUaLwI61fa5gBuVW3VBDzJ9R5wwCK4B/s1600/BP.jpg&quot;,
  &quot;url&quot; : &quot;https://basicpulse.blogspot.com/&quot;
}
</script>
     
    
<link href='https://www.blogger.com/static/v1/widgets/204402360-widget_css_bundle.css' media='none' onload='if(media!=&apos;all&apos;)media=&apos;all&apos;' rel='stylesheet'/>

    
</head>
<body>
<div id='total-wrapper'>
 <div id='interwebz-wrapper'>

<!-- Start - Social Links  -->
  <ul class='interwebz'>
   <li class='icon-feed'>
     <a expr:href='data:blog.homepageUrl + &quot;feeds/posts/default&quot;'>Feed</a>
   </li>
   <li class='icon-facebook'>
     <a href='https://www.facebook.com/bazicpulze'>Facebook</a>
   </li>
   <li class='icon-twitter'>
     <a href='https://twitter.com/Basic_Pulse'>Twitter</a>
   </li>
  </ul>
<!-- End - Social Links  -->

  <div id='srcnt'>
<form action='/search' id='search' method='get'>
  <input name='q' placeholder='looking for something?' size='40' type='text'/>
</form>
  </div>
</div>

    <div id='header-wrapper'>
      <b:section class='header' id='header' maxwidgets='1' showaddelement='no'>
        <b:widget id='Header1' locked='false' title='BasicPulse... (Header)' type='Header' version='1'>
          <b:widget-settings>
            <b:widget-setting name='displayUrl'>http://1.bp.blogspot.com/-EDH-kVg-I0s/WNvV4HRbUNI/AAAAAAAAApc/N4yLxwlUaLwI61fa5gBuVW3VBDzJ9R5wwCK4B/s1600/BP.jpg</b:widget-setting>
            <b:widget-setting name='displayHeight'>236</b:widget-setting>
            <b:widget-setting name='sectionWidth'>802</b:widget-setting>
            <b:widget-setting name='useImage'>true</b:widget-setting>
            <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
            <b:widget-setting name='imagePlacement'>REPLACE</b:widget-setting>
            <b:widget-setting name='displayWidth'>804</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <b:if cond='data:mobile'>
          <div id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
              <h1 class='title' style='background: transparent; border-width: 0px'>
                <b:include name='title'/>
              </h1>
            </div>
            <b:include name='description'/>
          </div>
        <b:else/>
          <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                        + &quot;background-position: &quot;                        + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
              <h1 class='title' style='background: transparent; border-width: 0px'>
                <b:include name='title'/>
              </h1>
            </div>
            <b:include name='description'/>
          </div>
        </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
          <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
          <b:includable id='title'>
  <b:tag cond='data:blog.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
    <data:title/>
  </b:tag>
</b:includable>
        </b:widget>
      </b:section>
    </div>
<!-- Start - Navigation Menu  -->
<div class='nav'>
<ul class='menu' id='menu'>
<li><a expr:href='data:blog.homepageUrl'>home</a></li>
<li><a href='https://basicpulse.blogspot.com/p/about-basicpulse.html'>About</a></li>
<li><a href='https://basicpulse.blogspot.com/p/contact.html'>Contact</a></li>
</ul>
</div>
<nav id='nav-mobile'/>
<!-- End - Navigation Menu  -->


  <div id='outer-wrapper'><div id='wrap2'>

    <!-- skip links for text browsers -->
    <span id='skiplinks' style='display:none;'>
      <a href='#main'>skip to main </a> |
      <a href='#sidebar'>skip to sidebar</a>
    </span>

<!-- Start - Error 404 Page  -->
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<div id='errorpage'>
<h1>404</h1>
<h3>We couldn&#39;t find the page</h3>
<p>The page you&#39;ve requested can not be displayed. It appears you&#39;ve missed your intended destination, either through a bad or outdated link, or a typo in the page you were hoping to reach</p>
  <div id='srcnt-errorpage'>
<form action='/search' id='search-errorpage' method='get'>
  <input name='q' placeholder='' size='40' type='text'/>
</form>
  </div>
</div>
</b:if>
<!-- End - Error 404 Page  -->

    <div id='content-wrapper'>

      <div id='main-wrapper'>
        <b:section class='main' id='main' showaddelement='no'>
          <b:widget id='Blog1' locked='false' title='Blog Posts' type='Blog' version='1'>
            <b:widget-settings>
              <b:widget-setting name='showDateHeader'>true</b:widget-setting>
              <b:widget-setting name='style.textcolor'>#000000</b:widget-setting>
              <b:widget-setting name='showShareButtons'>false</b:widget-setting>
              <b:widget-setting name='showCommentLink'>true</b:widget-setting>
              <b:widget-setting name='style.urlcolor'>#000000</b:widget-setting>
              <b:widget-setting name='showAuthor'>true</b:widget-setting>
              <b:widget-setting name='style.linkcolor'>#000000</b:widget-setting>
              <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
              <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='timestampLabel'>on</b:widget-setting>
              <b:widget-setting name='reactionsLabel'/>
              <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
              <b:widget-setting name='style.layout'>1x1</b:widget-setting>
              <b:widget-setting name='showLabels'>false</b:widget-setting>
              <b:widget-setting name='showLocation'>false</b:widget-setting>
              <b:widget-setting name='showTimestamp'>true</b:widget-setting>
              <b:widget-setting name='postsPerAd'>1</b:widget-setting>
              <b:widget-setting name='showBacklinks'>false</b:widget-setting>
              <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='showInlineAds'>false</b:widget-setting>
              <b:widget-setting name='showReactions'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='top'>
   <b:if cond='data:mobile == &quot;false&quot;'>

    <!-- posts -->
<div class='blog-posts hfeed'>
  
 <b:include data='top' name='status-message'/>
  
 <data:defaultAdStart/>
 <b:loop values='data:posts' var='post'>
  <div class='date-outer'>
   <div class='date-posts'>
    <div class='post-outer'>
     <b:include data='post' name='post'/>
     <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
     <b:include data='post' name='comments'/>
     </b:if>
      

       <b:if cond='data:blog.pageType == &quot;item&quot;'>
         <b:if cond='data:post.showThreadedComments'>
           <b:include data='post' name='threaded_comments'/>
         <b:else/>
           <b:include data='post' name='comments'/>
         </b:if>
       </b:if> 


    </div>
    <b:if cond='data:post.includeAd'>
     <b:if cond='data:post.isFirstPost'>
     <data:defaultAdEnd/>
     <b:else/>
     <data:adEnd/>
     </b:if>
      <div class='inline-ad'>
       <data:adCode/>
      </div>
      <data:adStart/>
    </b:if>
    <b:if cond='data:post.trackLatency'>
     <data:post.latencyJs/>
    </b:if>
   </div>
  </div>
 </b:loop>
 <data:adEnd/>
</div>



    <!-- feed links -->
    <b:include name='feedLinks'/>
    <div class='clear'/>

    <!-- navigation -->
    <b:include name='nextprev'/>
    <b:if cond='data:top.showStars'>
      <script defer='defer' src='//www.google.com/jsapi' type='text/javascript'/>
      <script defer='defer' type='text/javascript'>
        google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
        function initialize() {
          google.annotations.setApplicationId(<data:top.blogspotReviews/>);
          google.annotations.createAll();
          google.annotations.fetch();
        }
        google.setOnLoadCallback(initialize);
      </script>
    </b:if>

  <b:else/>
    <b:include name='mobile-main'/>
    </b:if>

  <b:if cond='data:top.showDummy'>
    <data:top.dummyBootstrap/>
  </b:if>
<script> 
  (function(i,s,o,g,r,a,m){i[&#39;GoogleAnalyticsObject&#39;]=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,&#39;script&#39;,&#39;https://www.google-analytics.com/analytics.js&#39;,&#39;ga&#39;);

  ga(&#39;create&#39;, &#39;UA-89683601-1&#39;, &#39;auto&#39;);
  ga(&#39;send&#39;, &#39;pageview&#39;);

</script>
</b:includable>
            <b:includable id='backlinkDeleteIcon' var='backlink'/>
            <b:includable id='backlinks' var='post'/>
            <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
      <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
            <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
            <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.canonicalUrl'>
    </span>
  <b:else/>
    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
      <data:post.commentLabelFull/>:
    </a>
  </b:if>
</b:includable>
            <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threaded_comments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
            <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4>
        <b:if cond='data:post.numComments == 1'>
          1 <data:commentLabel/>:
        <b:else/>
          <data:post.numComments/> <data:commentLabelPlural/>:
        </b:if>
      </h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
          &#160;
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/><a href='http://www.spiceupyourblog.com'><img alt='Best Blogger Tips' src='http://3.bp.blogspot.com/_rKG-ziTSNUQ/TQ5eV0U0EiI/AAAAAAAACik/xo2eFaDbfrE/s1600/best+blogger+tips.png'/></a><span class='comment-reply'><a expr:href='&quot;https://www.blogger.com/comment.g?blogID=3772610404125516813&amp;postID=&quot; + data:post.id + &quot;&amp;isPopup=true&amp;postBody=%40%3C%61%20%68%72%65%66%3D%22%23&quot; + data:comment.anchorName + &quot;%22%3E&quot; + data:comment.author + &quot;%3C%2F%61%3E#form&quot;' onclick='javascript:window.open(this.href, &quot;bloggerPopup&quot;, &quot;toolbar=0,location=0,statusbar=1,menubar=0,scrollbars=yes,width=400,height=450&quot;); return false;'>[Reply to comment]</a></span><a href='http://www.bestbloggertemplates.net'><img alt='Best Blogger Templates' src='http://3.bp.blogspot.com/_rKG-ziTSNUQ/TQ5eV0U0EiI/AAAAAAAACik/xo2eFaDbfrE/s1600/best+blogger+tips.png'/></a>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
          </b:if>
        </b:if>

      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
            <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

  <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:include cond='data:post.allowComments and data:post.feedLinks' data='post.feedLinks' name='feedLinksBody'/>
      </b:loop>
    </div>
  </b:if>
</b:includable>
            <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
            <b:includable id='iframe_comments' var='post'>

  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.canonicalUrl' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
            <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title' itemprop='name'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.allowComments'>
            <b:if cond='data:post.numComments != 0'>
              <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
            </b:if>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
            <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
            <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
            <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:Header'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h2 class='post-title entry-title' itemprop='name'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:else/>
                <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                    <a expr:href='data:post.url'><data:post.title/></a>
                  <b:else/>
                    <data:post.title/>
                  </b:if>
                <b:else/>
                  <data:post.title/>
                </b:if>
              </b:if>
            </h2>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn'>
                      <a expr:href='data:post.authorProfileUrl' itemprop='author' rel='author' title='author profile'>
                        <data:post.author/>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn'><data:post.author/></span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <a class='timestamp-link' expr:href='data:post.url' itemprop='url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:if cond='data:blog.pageType != &quot;item&quot;'>
                  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                    <b:if cond='data:post.allowComments'>
                      <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
                    </b:if>
                  </b:if>
                </b:if>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
            <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

<span id='back-top'><a class='home-link' href='#top'><img src='http://lh3.googleusercontent.com/-CsAdYBr1498/UC_WgBQDmhI/AAAAAAAAD1M/22AIGQQAib8/s0/top-button.png'/></a></span>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
            <b:includable id='post' var='post'>

  <div class='post hentry'>

<div id='post-header-top'>
  
<div class='date-post-top-wrapper'>
<div class='date-container'>
<span class='post-date-day-name'>
<script type='text/javascript'>document.write(date_dayname);</script>
</span>
<br/>
<span class='post-date-day-month-year'>
<script type='text/javascript'>document.write(date_daymonyear);</script>
</span>
</div>
</div>

    <a expr:name='data:post.id'/>
    <b:if cond='data:post.title'>
      <h2 class='post-title entry-title'>
      <b:if cond='data:post.link'>
        <a expr:href='data:post.link'><data:post.title/></a>
      <b:else/>
        <b:if cond='data:post.url'>
          <b:if cond='data:blog.url != data:post.url'>
            <a expr:href='data:post.url'><data:post.title/></a>
<script type='text/javascript'>var ssyby=&#39;<data:post.dateHeader/>&#39;;
</script>

          <b:else/>
            <data:post.title/>
          </b:if>
        <b:else/>
          <data:post.title/>
        </b:if>
      </b:if>
      </h2>
     <div class='clear'/>
    </b:if>
    </div>
    <div class='post-header'>
    <div class='post-header-line-1'/>
    </div>
    <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>

      <b:if cond='data:blog.pageType != &quot;item&quot;'><b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:post.isFirstPost'>
<script type='text/javascript'>
//<![CDATA[
function snips_image_creator(image_url,post_title)
{
var image_size=400;
var show_default_thumbnail=true;
var default_thumbnail="http://2.bp.blogspot.com/-erTXCq61ULM/TmHYAQBZ0GI/AAAAAAAACCs/6cBX54Dn6Gs/s72-c/default.png";
if(show_default_thumbnail == true && image_url == "") image_url= default_thumbnail;
image_tag='<img src="'+image_url.replace('/s72-c/','/w'+image_size+'/')+'" alt="'+post_title+'"/>';
if(image_url!="") return image_tag; else return "";
}
//]]>
</script>
</b:if>

<b:if cond='data:post.snippet'>
<div class='snips-image'>
<a expr:href='data:post.url'>
<script type='text/javascript'>
document.write(snips_image_creator(&quot;<data:post.thumbnailUrl/>&quot;,&quot;<data:post.title/>&quot;));
</script>
<div class='snips-header'>
<b:if cond='data:post.numComments == 1'>1 comment<b:else/><b:if cond='data:post.numComments == 0'>0 comment<b:else/><data:post.numComments/> comments</b:if></b:if>
</div>
<div class='summary'>
<data:post.snippet/>
</div>
</a>
</div>
          <b:else/>
            <data:post.body/>
          </b:if>
      <b:else/>
      <data:post.body/>
      </b:if>
<b:else/>
<data:post.body/>
</b:if>

      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div>

    <div class='post-footer'>
    <div class='post-footer-line post-footer-line-1'><span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <data:top.authorLabel/>
            <b:if cond='data:post.authorProfileUrl'>
              <span class='fn'>
                <a expr:href='data:post.authorProfileUrl' itemprop='author' rel='author' title='author profile'>
                  <data:post.author/>
                </a>
              </span>
            <b:else/>
              <span class='fn'><data:post.author/></span>
            </b:if>
        </b:if>
      </span> <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <data:top.timestampLabel/>
        <b:if cond='data:post.url'>
          <a class='timestamp-link' expr:href='data:post.url' itemprop='url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
        </b:if>
        </b:if>
      </span> <span class='post-comment-link'>
        <b:if cond='data:blog.pageType != &quot;item&quot;'>
          <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
            <b:if cond='data:post.allowComments'>
              <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
            </b:if>
          </b:if>
        </b:if>
      </span> <span class='post-icons'>
        <!-- email post links -->
        <b:if cond='data:post.emailPostUrl'>
          <span class='item-action'>
          <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
              <img alt='' class='icon-action' height='13' src='http://img1.blogblog.com/img/icon18_email.gif' width='18'/>
          </a>
          </span>
        </b:if>

        <!-- quickedit pencil -->
        <b:include data='post' name='postQuickEdit'/>
      </span> </div>

<div class='post-footer-line post-footer-line-2'><span class='post-labels'>
        <b:if cond='data:post.labels'>
          <data:postLabelsLabel/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url + &quot;?max-results=6&quot;' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
          </b:loop>
        </b:if>
      </span></div>

      <div class='post-footer-line post-footer-line-3'><span class='post-location'>
        <b:if cond='data:top.showLocation'>
          <b:if cond='data:post.location'>
            <data:postLocationLabel/>
            <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
          </b:if>
        </b:if>
      </span> </div>
       <div class='post-share-buttons goog-inline-block'>
        <b:if cond='data:post.sharePostUrl'>
          <b:include data='post' name='shareButtons'/>
        </b:if>
      </div> 
    </div>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div id='related-posts'>
<b:loop values='data:post.labels' var='label'>
<b:if cond='data:label.isLast != &quot;true&quot;'>
</b:if>
<script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels_thumbs&amp;max-results=7&quot;' type='text/javascript'/></b:loop>

</div><div style='clear:both'/>
<br/>
</b:if>
  </div>
</b:includable>
            <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='https://resources.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
            <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToOrkutMsg/></span></a></b:if><b:if cond='data:top.showDummy'><div class='goog-inline-block dummy-container'><data:post.dummyTag/></div></b:if>
</b:includable>
            <b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
  </b:if>
</b:includable>
            <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
            <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();


// ]]>
  </script>
</b:includable>
            <b:includable id='threaded_comments' var='post-body'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4>
      <b:if cond='data:post.numComments == 1'>
        1 <data:commentLabel/>:
      <b:else/>
        <data:post.numComments/> <data:commentLabelPlural/>:
      </b:if>
    </h4>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threaded_comment_js'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
          </b:widget>
        </b:section>
      </div>

      <div id='sidebar-wrapper'>
        <b:section class='sidebar' id='sidebar' preferred='yes'>
          <b:widget id='PopularPosts1' locked='false' title='Trending' type='PopularPosts' version='1'>
            <b:widget-settings>
              <b:widget-setting name='numItemsToShow'>5</b:widget-setting>
              <b:widget-setting name='showThumbnails'>true</b:widget-setting>
              <b:widget-setting name='showSnippets'>true</b:widget-setting>
              <b:widget-setting name='timeRange'>LAST_WEEK</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.thumbnail'>
              <div class='item-thumbnail'>
                <a expr:href='data:post.href' target='_blank'>
                  <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                </a>
              </div>
            </b:if>
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <b:if cond='data:showSnippets'>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          </div>
          <div style='clear: both;'/>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
          </b:widget>
          <b:widget id='BlogArchive1' locked='false' title='Blog Archive' type='BlogArchive' version='1'>
            <b:widget-settings>
              <b:widget-setting name='showStyle'>HIERARCHY</b:widget-setting>
              <b:widget-setting name='yearPattern'>yyyy</b:widget-setting>
              <b:widget-setting name='showWeekEnd'>true</b:widget-setting>
              <b:widget-setting name='monthPattern'>MMMM</b:widget-setting>
              <b:widget-setting name='dayPattern'>MMM dd</b:widget-setting>
              <b:widget-setting name='weekPattern'>MM/dd</b:widget-setting>
              <b:widget-setting name='chronological'>false</b:widget-setting>
              <b:widget-setting name='showPosts'>true</b:widget-setting>
              <b:widget-setting name='frequency'>MONTHLY</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div class='widget-content'>
  <div id='ArchiveList'>
  <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
    <b:include cond='data:style == &quot;HIERARCHY&quot;' data='data' name='interval'/>
    <b:include cond='data:style == &quot;FLAT&quot;' data='data' name='flat'/>
    <b:include cond='data:style == &quot;MENU&quot;' data='data' name='menu'/>
  </div>
  </div>
  <b:include name='quickedit'/>
  </div>
</b:includable>
            <b:includable id='flat' var='data'>
  <ul class='flat'>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
      </li>
    </b:loop>
  </ul>
</b:includable>
            <b:includable id='interval' var='intervalData'>
  <b:loop values='data:intervalData' var='i'>
      <ul class='hierarchy'>
        <li expr:class='&quot;archivedate &quot; + data:i.expclass'>
          <b:include data='i' name='toggle'/>
          <a class='post-count-link' expr:href='data:i.url'><data:i.name/></a>
            <span class='post-count' dir='ltr'>(<data:i.post-count/>)</span>
          <b:include cond='data:i.data' data='i.data' name='interval'/>
          <b:include cond='data:i.posts' data='i.posts' name='posts'/>
        </li>
      </ul>
  </b:loop>
</b:includable>
            <b:includable id='menu' var='data'>
  <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
    <option value=''><data:title/></option>
    <b:loop values='data:data' var='i'>
      <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
    </b:loop>
  </select>
</b:includable>
            <b:includable id='posts' var='posts'>
  <ul class='posts'>
    <b:loop values='data:posts' var='post'>
      <li><a expr:href='data:post.url'><data:post.title/></a></li>
    </b:loop>
  </ul>
</b:includable>
            <b:includable id='toggle' var='interval'>
  <b:if cond='data:interval.toggleId'>
  <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
    <a class='toggle' href='javascript:void(0)'>
      <span class='zippy toggle-open'>&#9660;&#160;</span>
    </a>
  <b:else/>
    <a class='toggle' href='javascript:void(0)'>
      <span class='zippy'>
        <b:if cond='data:blog.languageDirection == &quot;rtl&quot;'>
          &#9668;&#160;
        <b:else/>
          &#9658;&#160;
        </b:if>
      </span>
    </a>

  </b:if>
 </b:if>
            
</b:includable>
          </b:widget>
          <b:widget id='LinkList1' locked='false' title='Blogs We Love' type='LinkList'>
            <b:widget-settings>
              <b:widget-setting name='link-5'>http://glowrite.wordpress.com</b:widget-setting>
              <b:widget-setting name='link-3'>http://www.paulgraham.com</b:widget-setting>
              <b:widget-setting name='link-4'>http://samharris.org</b:widget-setting>
              <b:widget-setting name='text-1'>Cal Newport </b:widget-setting>
              <b:widget-setting name='text-0'>The Book Of Life</b:widget-setting>
              <b:widget-setting name='text-3'>Paul Graham </b:widget-setting>
              <b:widget-setting name='text-2'>Four Hour Work Week</b:widget-setting>
              <b:widget-setting name='text-5'>Glowrite</b:widget-setting>
              <b:widget-setting name='text-4'>Sam Harris</b:widget-setting>
              <b:widget-setting name='shownum'>10</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='link-1'>http://www.calnewport.com</b:widget-setting>
              <b:widget-setting name='link-2'>http://www.fourhourworkweek.com</b:widget-setting>
              <b:widget-setting name='link-0'>http://www.thebookoflife.org</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>

<b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
 <div class='widget-content'>
   <ul>
     <b:loop values='data:links' var='link'>
       <li><a expr:href='data:link.target'><data:link.name/></a></li>
     </b:loop>
   </ul>
   <b:include name='quickedit'/>
 </div>
</b:includable>
          </b:widget>
          <b:widget id='HTML5' locked='false' title='Hello!' type='HTML'>
            <b:widget-settings>
              <b:widget-setting name='content'>&lt;div dir=&quot;ltr&quot; style=&quot;text-align: center;&quot; trbidi=&quot;off&quot;&gt;
&lt;iframe frameborder=&quot;0&quot; height=&quot;450&quot; marginheight=&quot;0&quot; marginwidth=&quot;0&quot; src=&quot;https://docs.google.com/forms/d/e/1FAIpQLSe6cZFm0R0516DjPG1qvqjwgQIVUmB9W4pr1oGbPl-HxvA5Dw/viewform?embedded=true&quot; width=&quot;100%&quot;&gt;Loading...&lt;/iframe&gt;&lt;/div&gt;</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
          </b:widget>
          <b:widget id='Navbar1' locked='true' title='Navbar' type='Navbar' version='1'>
            <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/platform.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar.g?targetBlogID\x3d3772610404125516813\x26blogName\x3dBasicPulse...\x26publishMode\x3dPUBLISH_MODE_BLOGSPOT\x26navbarType\x3dDISABLED\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttps://basicpulse.blogspot.com/search\x26blogLocale\x3den_GB\x26v\x3d2\x26homepageUrl\x3dhttp://basicpulse.blogspot.com/\x26vt\x3d5942051455564089368&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
          </b:widget>
          <b:widget id='Attribution1' locked='true' mobile='no' title='' type='Attribution'>
            <b:widget-settings>
              <b:widget-setting name='copyright'>BasicPulse..</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
          </b:widget>
          <b:widget id='Label1' locked='false' title='Category' type='Label' version='1'>
            <b:widget-settings>
              <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
              <b:widget-setting name='display'>LIST</b:widget-setting>
              <b:widget-setting name='selectedLabelsList'/>
              <b:widget-setting name='showType'>ALL</b:widget-setting>
              <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
      <b:loop values='data:labels' var='label'>
        <li>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?max-results=6&quot;'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </li>
      </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url + &quot;?max-results=6&quot;'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
          </b:widget>
        </b:section>
      </div>

      <!-- spacer for skins that want sidebar and main to be the same height-->
      <div class='clear'>&#160;</div>

    </div> <!-- end content-wrapper -->


  </div></div> <!-- end outer-wrapper -->

    <div id='middle-wrapper'>
<div id='middle-columns'>
<div class='column1'>
<b:section class='addwidget' id='col1' preferred='yes' style='float:left;'>
  <b:widget id='Text1' locked='false' title='Behind The Scene' type='Text'>
    <b:widget-settings>
      <b:widget-setting name='content'><![CDATA[<span><p align="left"><span =""  style="font-size:130%;">BasicPulse is written by <a href="https://basicpulse.blogspot.com/p/uduk.html">Paul Uduk.</a></span></p><br/><p align="left"><span =""  style="font-size:130%;">If you are new to my blog, a good place to start is the <a href="http://basicpulse.blogspot.com.ng/2012/12/basicpulse.html">description page</a> and a list of <a href="http://basicpulse.blogspot.com.ng/search/label/Top%20Six?max-results=6">the six essential ideas held on the blog.</a></span></p></span>]]></b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
  <b:widget id='HTML2' locked='false' title='Flickr Photostream' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'/>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
</div>
<div class='column2'>
<b:section class='addwidget' id='col2' preferred='yes' style='float:center'>
  <b:widget id='HTML1' locked='false' title='Join Our Readers' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;style&gt;
.rb-email{
background:url(http://4.bp.blogspot.com/_MbejYjGokMM/TSeZHmWJ6oI/AAAAAAAAALE/93ELYyzmi64/s1600/email.png) no-repeat 0px 12px ;
width:300px;
padding:10px 0 0 55px;
float:left;
font-size:1.4em;
font-weight:bold;
margin:0 0 10px 0;
color:#686B6C;
}

.rb-emailsubmit{
background:#9B9895;
cursor:pointer;
color:#fff;
border:none;
padding:3px;
text-shadow:0 -1px 1px rgba(0,0,0,0.25);
-moz-border-radius:6px;
-webkit-border-radius:6px;
border-radius:6px;
font:12px sans-serif;
}
.rb-emailsubmit:hover{
background:#E98313;
}
.textarea{
padding:2px;
margin:6px 2px 6px 2px;
background:#f9f9f9;
border:1px solid #ccc;
resize:none;
box-shadow:inset 1px 1px 1px rgba(0,0,0,0.1);
-moz-box-shadow:inset 1px 1px 1px rgba(0,0,0,0.1);
-webkit-box-shadow:inset 1px 1px 1px rgba(0,0,0,0.1); font-size:13px;&#160; 
width:170px;
color:#666;}

&lt;/style&gt;

&lt;div class=&quot;rb-email&quot;&gt;
Get Posts in Your Inbox 
&lt;form action=&quot;https://feedburner.google.com/fb/a/mailverify&quot; id=&quot;feedform&quot; method=&quot;post&quot; target=&quot;popupwindow&quot; onsubmit=&quot;window.open(&#39;http://feedburner.google.com/fb/a/mailverify?uri=BasicPulse...&#39;, &#39;popupwindow&#39;, &#39;scrollbars=yes,width=550,height=520&#39;);return true&quot;&gt;
&lt;input gtbfieldid=&quot;3&quot; class=&quot;textarea&quot; name=&quot;email&quot; onblur=&quot;if (this.value == &amp;quot;&amp;quot;) {this.value = &amp;quot;Enter email address here...&amp;quot;;}&quot; onfocus=&quot;if (this.value == &amp;quot;Enter email address here...&amp;quot;) {this.value = &amp;quot;&amp;quot;;}&quot; value=&quot;Enter email address here...&quot; type=&quot;text&quot; /&gt;
&lt;input type=&quot;hidden&quot; value=&quot;BasicPulse&quot; name=&quot;uri&quot;/&gt;&lt;input type=&quot;hidden&quot; name=&quot;loc&quot; value=&quot;en_US&quot;/&gt;
&lt;input class=&quot;rb-emailsubmit&quot; value=&quot;Submit&quot; type=&quot;submit&quot; /&gt;
&lt;/form&gt;
&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
  <b:widget id='HTML4' locked='false' title='Twitter Updates' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'/>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
</div>
<div class='column3'>
<b:section class='addwidget' id='col3' preferred='yes' style='float:right;'>
  <b:widget id='FeaturedPost1' locked='false' title='Featured post' type='FeaturedPost'>
    <b:widget-settings>
      <b:widget-setting name='showSnippet'>false</b:widget-setting>
      <b:widget-setting name='showPostTitle'>true</b:widget-setting>
      <b:widget-setting name='postId'>231920687922304842</b:widget-setting>
      <b:widget-setting name='showFirstImage'>true</b:widget-setting>
      <b:widget-setting name='useMostRecentPost'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- Only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <b:include name='content'/>

  <b:include name='quickedit'/>
</b:includable>
    <b:includable id='content'>
  <div class='post-summary'>
    <b:if cond='data:showPostTitle and data:postTitle != &quot;&quot;'>
      <h3><a expr:href='data:postUrl'><data:postTitle/></a></h3>
    </b:if>
    <b:if cond='data:showSnippet and data:postSummary != &quot;&quot;'>
      <p>
        <data:postSummary/>
      </p>
    </b:if>
    <b:if cond='data:showFirstImage and data:postFirstImage != &quot;&quot;'>
      <img class='image' expr:src='data:postFirstImage'/>
    </b:if>
  </div>

  <style type='text/css'>
    .image {
      width: 100%;
    }
  </style>
</b:includable>
  </b:widget>
  <b:widget id='HTML3' locked='false' title='Meet The Author' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'/>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
</div>
<div style='clear:both;'/>
</div>
    </div>

<div id='footer-links-wrap'>
 <div id='footer-links'>

<!-- credits start (please don't remove this) -->
  <div id='credits'>
Copyright &#169; &#8226; <a expr:href='data:blog.homepageUrl'><data:blog.title/></a> &#8226; All Rights Reserved<br/>
<a href='http://www.blogger.com'>Blog at Blogger.com</a> &#8226; Template by <a href='http://iksandi.com' title='Design and Development by Iksandi Lojaya'>Lojaya</a>
  </div>
<!-- credits end (please don't remove this) -->

 </div>
<div style='clear:both;'/>
</div>
  <b:include data='blog' name='google-analytics'/>
</div>

<!-- 
Galauness - XML Blogger Template Style
Designed by Iksandi Lojaya - http://iksandi.com
http://iksandilojaya.com
--> 
  
&lt;!--</body>
--&gt; &lt;/body&gt;
</html>
