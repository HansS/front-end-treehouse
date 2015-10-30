##Css for Navigation


###About Page
most what we need is in the index.html. You can copy it from index.html
Modify about.html
+ header
+ section
+ footer

###html
+ Add class select to about.html in about.html
+ Add image to section
+ Add h3 tag
+ Add p "This is my profile portfolio....."
+ Add p "If you want to follow me this is my twitter profile"

###css
.profile-photo {
	display:block;
	max-width:150px;
	margin; 0 auto 30px;
	border-radius:100%; // picture will be a circle
}
h3 {
	margin: 0 0 1em 0;
}
##Contact Page
+ create contact.html
+ copy from about.html
+ set selected class to contact.html
+ delete section content
+ add second section with h3 and p sibling tags

###html
+ add list item for phone details with href="tel:666-664"
+ add list item for email with href="mail-to:nick@nick.com"
+ add list item for twitter with class twitter
+ add ul to second section with class contact-info
+ add list item for facebook with class facebook

###css
.contact-info {
	list-style;none;
	margin:0;
	font-size:0.9em;
	
}
.contact-info a {
	display:block;
	min-height:20px;
	background-repeat:no-repeat;
	background-size:20px 20px;
	padding; 0 0 0 30px;
	margin:0 0 10px;
}
.contact-info li.phone a {
	backgroun-image: url('../img/phone.png);
}

##Responsive Webdesign

###Fluid Desing
do not use fixed width or height, instead use relative sizes
from px to em
from px to percent
img {max-width:100%}
body {margin:0 auto}
##Mobile First
Reduce the complexity of a website to its simplest form

##Media Queries

1 Media query stands for a grid point
// Because we started with mobile first our main.css
// holds the rules for mobile-first

// if screen is larger than 480px the following rule will apply
@media screen and (min-width: 480px) {
	#primary {
		width:50%;
		float:left;
	}
	
	#secondary {
		float: right;
		width:40%;
	}
	
	// 3 cols for desktop
	// for portfolio page, clear every 4th list item -> 
	// 4.item will cleared to the left
	#gallery li {
		width: 28.33333333%;
		
	}
	
	#gallery li:nth-child(4n) {
		clear:left;
		
	}
	
} 

@media screen and (min-width: 660px){
	nav {
		background:none;
		float:right;
		margin-right:5%;
		text-aligh:right;
		width:45%;
	}
	
	#logo {
		float:left;
		margin-left:5%;
		text-align:left;
		width:45%;
		
	}
	
	h1{}
	
	h2{}
	
	header {
		border-bottom:5px solid #599a68;
		margin-bottom: 60px1;
	}
	
	##Add meta viewport tag in each html page
	<meta name="viewport" content="device-width, initial-scale:1.0">
	
	
}

###Profile Page - About.html

.profile-photo {
	float:left;
	margin:0 5% 80px 0;
}

###Testing the Website

##Make Screensots for every Breakpoint and paste it
into a Text processing Editor or into an Image Editor

In the Image Editor you can blur th colors to see the design
Also rotate the design to see it the design is balanced.

##Valid your pages on W3C Validor
validator.w3.org/check

###Website testing on different browsers

Browserstack will make screenshots of your website
for all main devices.


