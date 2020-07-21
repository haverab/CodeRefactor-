# CodeRefactor-
This is homework 1
# Description
The main objective for this first homework assignment was to refactor an existing webpage to make it more accessible. This is an important lesson for a future web developer as one of the most common tasks requested by clients of front-end and junior developers is to refactor existing code to meet certain standards and/or implement new technology. Web accessibility is a very important aspect to business as it ensures that they can reach all potential clients/customers, including those with disabilities and socio-economic restrictions. To achieve accessibility, one needed to follow five different acceptance criteria: incorporating semantic code, making sure elements follow a logical structure independent of styling and positioning, using accessible alt attributes for image elements, making sure heading attributes are in sequential order, and giving the title element a concise and descriptive title. 
# How I met each acceptance criteria
1.) Use of semantic elements:  The source I used to look up the difference between semantic elements and div tags and why it’s important for accessibility is www.w3schools.com.
Semantic elements are elements with meaning. They clearly describe not only the elements meaning and content to the browser but to the developer as well, while div tags, or other non-semantic elements, tell the browser and developer nothing. Semantic elements are imperative to accessibility because they enable data to be understood more clearly. 
The original code I was given used a lot of div tags instead of semantic elements. To make sure this criteria was achieved I replaced the div tags with the appropriate semantic elements. 
  
2.) Making sure elements follow a logical structure independent of styling and positioning: To do this I made sure the order of the html code from top to bottom was logical and followed the layout of the website from top to bottom.

3.) Using accessible alt attributes for image elements: The original code did not contain any alt attributes for image elements. After consulting, www.w3school.com, I learned that alt attributes for image elements specifies an alternate text for an image, if the image cannot be displayed. The alt attribute needs to describe what the image is if the image has information and explain where the link goes is the image is inside an <a> tag, which is a hyperlink. To meet these criteria, I added alt attributes to each image by putting: alt= "description of image" after the src= "url" in the image tags.
  
4.) Making sure heading attributes are in sequential order: I achieved this by making sure the heading attributes fell in sequential order by changing the footer heading at the bottom to an h4 tag. 
  
5.) Giving the title element a concise and descriptive title: The original title element did not contain a concise and descriptive title, so I added one to better describe the website. I used the official name of the company, Horiseon Social Solution Services, Inc. 

# Additional changes 
I noticed in the original code that the Search Image Optimization link in the header did not take you to its description in the main content like the other two, Online Reputation Management and Social Media Marketing. The latter two, had included an id that in CSS sheet enabled the link from the header to the main content. So I added an id to the Search Engine Optimization.
I also changed the url to the digital marketing meeting image in the css page to make it easier to load.
