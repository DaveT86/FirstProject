#Milestone Project 1 Code Institute

##Page title-Plant Based Can Be Easy!

*Click this link to go to my live website [Plant Based Can Be Easy](https://davet86.github.io/FirstProject/index.html)

###External User's Goal: 
*People interested in incorparating items into their diet which are vegan.
#People looking for vegan recipes

###Site owner's goal : 
*To educate and inform people of sustainable alternatives that they can add to their normal routine.
*To create a robust page that can be used to show an example of work in a portfolio.
*To create a website with accesibility in mind implementing any best practices to reach that goal.
*To create a website compatiable with different screensizes and browsers.

###Potential Features to Include :
*Stong brand.
*Informative Landing Page.
*Easy to navigate between recipes.
*Area for users to submit recipes.
*Link to other sites which share similar interests.

###Design

####Landing Page

*My initial design choice was to have a large hero image on the sites landing page 
![Home Version1](readme/assets/homever1.png)
*However I did not like the way this intereacted with smaller viewing devices and I made the decision to make my informative website more informative from the get go whilst still maintaining a good first impression.
*My revised landing page took into account the responsiveness required for veiwing on PC, Phone and Tablet and I was confident that I would be able to implement it using flex properties in css.
![Home Version2](readme/assets/homever2.png)

####Recipe Page

*My initial intention for the recipe page went far beyond and above the requirment for the project, a sleek looking website utilising I-frames with follow along instructions and recipe information containing a lot of data.
*My eventual implementation I feel still meets the external users goal and delivers on my goals at the site owner even though it is is overly simplistic.
*My eventual design choice was to go for a single web page with anchors for each recipe and then external links to the actual recipe featured on other websites.
![Recipe Page](readme/assets/recipe.png)

####Contact Page

*The last page of my website is very simple utilising an embedded google form to allow viewers to give feedback and offer suggestions for future content for the website, I went for this option not only because of it's ease in implentation but because it's far easier to collate and process the data given through it.

###Testing

####Validators

*My initial testing highlighted a few problems which were not too hard to address, mainly issues with margin and spacing, I did spend significant time thinking about and tasting the best implementation for my nav bar on mobile, a lot of complicated very clever solutions were tried however I felt the best was was just to diable the on hover sub menu in the nav bar on smaller devices, it's a clean and effective solution.

*My CSS code succesfully passed the W3C Validator first time
*HTML validator highlighted a few issues which I needed to address, I had a few line breaks in the code and a couple superflourous closing tags that had been left behind whilst modifying my code, upon implementing these changes my HTML succeeded in passing the validator.
*Google Lighthouse in Chrome Devtools highlighted a few improvemnts that could be made to my SEO I had overlooked adding a meta despcription in my page head, it also highlighted some improvements that could be be made to my imagaes to improve loading times, I had made my images with web in mind at an opimal resolution for the web however I could of considered using .png > .jpg to make them slightly smaller, I made the decision to keep them as they are this time but will hold it in consideration for future projects, in spite of this my website still achieved a perfect socre of 100 on browser and a score of 99 on mobile.
![Lighthouse Browser](readme/assets/LHBrowserTest.png)
![Lighthouse Mobile](readme/assets/LHMobileTest.png)
My recipe page recieved a similar score, my suggestion page scored lower due to cookies in the form implemented via embedded IFrame Google Form, I desided the benefits outweighed the negatives and stuck with the current implementation.

####Manual Testing

The manual testing of my website in chrome, IE and Opera browser on both Windows PC and Android OS did not highlight any issues with the design of my website, I was warned I may have an issue with my styling choices for my navbar and that prooved to be true in the Firefox Browser



###Sources and Recources

In order to make my nav bar appear how I wanted I had to use some cutom css styling derived from code mentioned here, https://stackoverflow.com/questions/51295524/how-to-create-a-box-with-slanted-edges

Researching best colour palettes to use on website food related https://jenndavid.com/colors-that-influence-food-sales-infographic/

Google forms, the website uses an embedded google form to allow people to submit suggestions for future content to the website, google forms was chosen over creating a form mainly because I do not have an email address I'm willing to commit to the site and not currently in the posession of the tools to implement .php and additional it seemed like a better way to process the data recieved than implementing a custom form.

Chat-Gpt proved to be an invaluable tool for offering suggestions to fix problems I encountered and also for proof reading text content and code within the site https://chatgpt.com/

Chrome-Dev Tools- Proved invauable for modifying my css and undertstanding the margin and spacing required to make my site as visuabbly apealing as possible on different screen sizes.

VSCode was the IDE I chose for this project, seems to have a good amount of QOL and despite being intitally daunting as someone with no proper prior experience in coding surprisingly intuitive and for the task at hand.




