# UofM-STP-FSF-PT-03-2020-U-C

HOMEWORK 1
Due date 4/4/2020

USER STORY:
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

Review
You are required to submit the following for review:
The URL of the deployed application.
The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

//Change Note:
//In ./assets/css/style.css
Changed .header to header
Changed .header h1 to header h1
Changed .header h1 .seo to #seo
Changed .header div to header div
Removed .header div ul{}
changed .header div ul li{} to just li

removed .benefit-cost img{} and .benefit-lead img{}
removed .benefit-cost {} and benefit-brand {}
removed .benefit-cost h3{} and benefit-brand h3{}

removed .online-reputation-management and .social-media-marketing
removed .online-reputation-management img{} and .social-media-marketing img{}
added .content img{}
removed .online-reputation-management h2 {] and .social-media-marketing h2 {}
Changed .footer into footer
changed .footer h2 {} into footer h2{}

//In index.html
Changed Title from website to Horiseon because "website" is a stupid website name
Changed <div class="header"> to just <header>
Changed Class="seo" int ID="seo"
Added id="search-engine-optimization" into line 29 so the link would work
Changed src="./assets/images/search-engine-optimization.jpg" to "assets/images/search-engine-optimization.jpg"
as well as image sources for the rest of the website
Added alt="" for all the images
All <div> tags within <content> now use the same class="search-engine-optimization"
All <div> tags within <div class="benefits"> now use the same class="benefit-lead"
Change <div=class="footer"> into just footer{}


# Homework1