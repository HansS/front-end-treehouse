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

