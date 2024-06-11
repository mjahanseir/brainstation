# brainstation
Challenge Overview
Welcome to the Software Engineering Admissions Challenge. There are three mandatory deliverables in the Software Engineering Admissions Challenge focused on: (1) HTML & CSS, (2) Pseudocode and (3) JavaScript.

Introductory Lessons
We highly encourage you to take a look at our free introductory lessons to assist you in preparation of this challenge.

Software Engineering Introductory Lessons
Learn the foundation components of a basic web page, how to problem solve while programming and the basics of JavaScript.

We recommend opening the introductory lessons in Google Chrome.
You may experience issues using other browsers.

Challenge Requirements
Challenge 1: HTML & CSS
Congratulations! You have been hired as a Software Engineer intern. You'll be taking over the build of a site from another developer, so please take your time reviewing the files you've been given as you won't be starting from scratch, but using these files to finish off the project.

All your additions to this document will be done within the index.html file provided. You'll see there's opening and closing <style> tag within the <head> </head> tags for you to place your styling. All HTML tags will be placed between the opening and closing <body> tags.

Please download the starter code for this challenge here.

#Part1
To start, you'll finish off the site using the notes provided from the last developer. You can find the notes below:

Since starting the site, the client has 2 more features they'd like to add to the features section. They should be added to the end of the existing list as new list items.
Notifications from Popular Apps
10 Days of Battery Life
An image has been provided for the right side of the features section. You'll see there's an image tag there already in the HTML (has a class of features__image), but the source attribute is empty. Please link the correct image here.
There are two paragraph elements in the footer, one for the email and one for the phone number. Change these elements to use anchor tags instead of paragraph tags. Keep the same class name, as this will keep the proper styling applied.
For the email:
Use info@ff.com as the content
Use mailto:info@ff.com as the hyperlink reference
For the phone number:
Use 867 - 102 - 4337 as the content
Use tel:8671024337 as the hyperlink reference
The client would like to have the 'features' link in the top navigation bar to be highlighted always. Add the class nav__sections-link--highlight in order to have this applied.
Add two taglines to follow the header copy:
Minimal, yet sharp
Modern, yet timeless
The last word of each tagline should be lowercase in your HTML file, but you should use CSS to modify the text to use uppercase casing. (ie. SHARP, TIMELESS) The last word should also be bolded, while the rest of the tagline can use a normal weight.
You should identify and create the right tags yourself and not use ones that exist in the HTML already. These taglines should each be within their own HTML tag.
The client would like to include a breakdown of what is included in each pricing package. They're provided the following information:
The copy should be added to the pricing__card-bottom section, and the information should be in the order provided. Use your knowledge of semantic HTML to build out this section.
Use the copy provided:
Package 1 includes: Watch face, Interchangeable band (white), Charging cable
Package 2 includes: Everything in Package 1, Interchangeable band (black)
Package 3 includes: Everything in Package 2, Extra charging cable, Warranty for 5 years
Add a 2px solid black dividing line between the pricing__card-top & pricing__card-bottom sections by using the appropriate box model property.
#Part2
The client has requested that a new section of the website be built between the "Features" and the "Pricing" sections. This new section will be a more comprehensive breakdown of the features mentioned. You can find the content below. There is no mockup provided for this section. With your knowledge of HTML (don't forget about semantics!), build this to the best of your ability. Then use your knowledge of CSS to style the section.

A Massive 1.5 Inch Touch Screen
Size is what matters when it comes to a smart watch screen. Read all your notifications with plenty of space.

Mix and Match Designs
Personalize your watch face to match your own unique style with many combinations of background images, clock styles and colors.

Water Resistant up to 7 Feet
IP68 Weatherproof rating. Fit to withstand dust, dirt and sand and resistant to submersion up to a maximum depth of 7 feet underwater for up to 30 minutes.

Tracking your Steps, Heart Rate & Sleep.
Check out your step progress during the day with the in app-tracker. Keep an eye on your heart rate easily and conveniently. And when you’re ready for your head to hit the pillow, track that too. 

Notifications from Popular Apps
Get all your notifications from all your accounts conveniently on your wrist

Up to 10 Days of Battery Life
With a battery capacity up to 300mAh, you’ll have no problem getting through the week with plenty of charge to spare. 
Furthermore, you may go beyond the basic requirements above to showcase your current HTML and CSS skills, including any skills not covered in the Admissions Challenge such as Flexbox or CSS animations.how
Challenge 2: Pseudocode
The intended functionality of the program below is to take a list of more than 1000 numbers (not in sequence) and determine the biggest number in the list. Identify any error(s) within this pseudocode solution and provide an explanation on why you identified this as a potential problem.

Let maxNumber represent the biggest number, set it to zero to start
While there are still numbers left in the list
	Look at the next number in the list
	Compare it to the maxNumber
		If next number is smaller than maxNumber
			Set maxNumber to that number
Report maxNumber as the biggest in the list
Challenge 3: JavaScript
This challenge is divided into two sections:

Operations & Comparisons
Arrays & Loops
In order to complete this challenge, follow the instructions outlined in the JavaScript file provided here.
