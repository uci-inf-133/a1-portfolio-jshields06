--Readme document for Jasmine Shields, shieldj1@uci.edu--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

*/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features

Images (3 downloaded and stored in images folder, 4 from url links)
Headings and paragraph text
Links to external pages
Multiple pages
Semantic HTML tags


(b) CSS features
Paddings and Margins
Text color modifications


(c) Advanced features
Navagation bar at the top, including a nav-brand.

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

A lot of the warnings from the AChecks considered alt text. Not neccessarily explaining blantant mistakes, but rather if the alt text could possibly be incorrect.
Also, in terms of structure checks, even though I tried to include semantic tags, it found that there were ways to make it simplier IF things like text direction, unicode marks, or visual lists were present.
Additionally, I wanted the headings to look a certain way, but in order to keep structure, I overridded with class specifications, eg. h3 since I was using it different ways on different pages.
For direct image warnings, it doesn't actually process the image itself (?) so it can't tell if it's one color, if the alt text matches, or if its decorative. 
For page text and titles, it has a lot of maybes as well that aren't actually happening. eg. text in the body of index.html.


4. How long, in hours, did it take you to complete this assignment?
1 + 2 + 2 + 4 + 1= 10 hours


5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
https://www.w3schools.com/htmlcss/default.asp
https://www.w3schools.com/bootstrap5/index.php
https://www.w3schools.com/html/default.asp
https://wiki.whatwg.org/wiki/Presentational_elements_and_attributes
https://www.w3schools.com/html/html5_semantic_elements.asp
https://cloudinary.com/guides/automatic-image-cropping/5-ways-to-crop-images-in-html-css
https://www.w3schools.com/howto/howto_css_images_side_by_side.asp
https://www.w3schools.com/css/css3_gradients.asp

I used AI to:
- give me ideas on what might qualify as an advanced feature for this project
- how to use bootstrap 5
- how to make the section go to the bottom of the page
- formatting images to be square
- adding a decorative line in between about me and images of me
- different nav bar - endings and what they mean 
- using !important
- using clamp()
- coming up with fake projects


6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
Emily Melgarejo: Approaches for structure. Having multiple pages instead of just one page. Ideas for advanced features. Validity checking comparison ie. what kind of errors if any.

7. Is there anything special we need to know in order to run your code?
// index.html is the home page including the about me and images
// projects.html is the projects page including project details
// resume.html is the resume page including my resume and links to my linkedin and github

Bootstrap5 should be installed.
Optimally, you can use a terminal to run the code using "open index.html" for macOS or "start index.html" for Windows.
