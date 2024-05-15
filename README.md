# Milestone Project 1 Code Institute

## Page title-Plant Based Can Be Easy!

*Click this link to go to my live website [Plant Based Can Be Easy](https://davet86.github.io/FirstProject/index.html)

### External User's Goal: 
*People new to Veganism or have recently become concerned with sustainability and areinterested in incorporating items into their diet which are vegan.
*People who are already vegan looking for vegan recipes.

### Site Owner's Goal
* To educate and inform people about sustainable alternatives they can incorporate into their normal routine.
* To create a robust page that can serve as an example of work in a portfolio.
* To design a website with accessibility in mind, implementing best practices to achieve that goal.
* To create a website compatible with different screen sizes and browsers.

### Potential Features to Include:
*Strong brand.
*Informative Landing Page.
*Easy to navigate between recipes.
*Area for users to submit recipes.
*Link to other sites which share similar interests.

### Design

#### Landing Page

*My initial design choice was to have a large hero image on the sites landing page 
![Home Version1](Readme/assets/homever1.png)
*However I did not like the way this interacted with smaller viewing devices and I made the decision to make my informative website more informative from the get go whilst still maintaining a good first impression.
*My revised landing page took into account the responsiveness required for viewing on PC, Phone and Tablet and I was confident that I would be able to implement it using flex properties in CSS.
![Home Version2](Readme/assets/homever2.png)


#### Recipe Page

* My initial intention for the recipe page exceeded the project's requirements, aiming for a sleek website utilizing I-frames with follow-along instructions and comprehensive recipe information.
* Despite simplifying my eventual design, I believe it still meets the external users' goal and fulfills my objectives as a site owner.
* I opted for a single web page with anchors for each recipe and external links to the featured recipes on other websites.
![Recipe Page](Readme/assets/recipe.png)


#### Contact Page

*The last page of my website is very simple utilising an embedded google form to allow viewers to give feedback and offer suggestions for future content for the website, I went for this option not only because of it's ease in implementation but because it's far easier to collate and process the data given through it.

### Testing

#### Validators

*My CSS code successfully passed the W3C Validator first time
*HTML validator highlighted a few issues which I needed to address, I had a few line breaks in the code and a couple superfluous closing tags that had been left behind whilst modifying my code, upon implementing these changes my HTML succeeded in passing the validator.
*Google Lighthouse in Chrome DevTools highlighted a few improvements that could be made to my SEO I had overlooked adding a meta description in my page head, it also highlighted some improvements that could be be made to my images to improve loading times, I had made my images with web in mind at an optimal resolution for the web however I could of considered using .png > .jpg to make them slightly smaller, I made the decision to keep them as they are this time but will hold it in consideration for future projects, in spite of this my website still achieved a perfect score of 100 on browser and a score of 99 on mobile.
![Lighthouse Browser](Readme/assets/LHBrowserTest.png)
![Lighthouse Mobile](Readme/assets/LHMobileTest.png)
*My recipe page received a similar score, my suggestion page scored lower due to cookies in the form implemented via embedded IFrame Google Form, I decided the benefits outweighed the negatives and stuck with the current implementation.

#### Manual Testing

*My initial testing phase highlighted a few problems which were not too hard to address, mainly issues with margins and spacing.
*I did spend significant time thinking about and testing the best implementation for my nav bar on mobile, a lot of complicated very clever solutions were tried however I felt the best one was just to disable the on hover sub menu in the nav bar on smaller devices, it's a clean and effective solution.
*The manual testing of my website in chrome, IE and Opera browser on both Windows PC and Android OS did not highlight any issues with the design of my website, I was warned I may have an issue with my styling choices for my navbar on some browsers and that proved to be true in the Mozilla Firefox Browser, I implemnted a media query targetting Mozilla browsers which isn't prefect but does make the nav bar display better then it was.

### What's Next For This Project?

*If I was to continue working on this project in the future there would be a number of additional things I would like to implement, a stronger focus on the brand with social media precense to help drive traffic and additionally merchandise featuring my custom graphics to monetise the site.


### Sources and Resources

* In order to achieve the desired appearance of my navigation bar, I utilized custom CSS derived from code found [here](https://stackoverflow.com/questions/51295524/how-to-create-a-box-with-slanted-edges).
* I researched optimal color palettes for food-related websites, referencing [this resource](https://jenndavid.com/colors-that-influence-food-sales-infographic/).
* Google Forms was used to facilitate user submissions due to its simplicity and efficient data processing capabilities, as I lacked the necessary tools for implementing a custom form.
* Chat-GPT and other modern ai's proved invaluable for providing suggestions and proofreading text content and code within the site. [ChatGpt] https://chatgpt.com/
* Chrome DevTools were essential for CSS modification and understanding margin and spacing adjustments for different screen sizes.
* VS Code was the IDE of choice for its user-friendly interface and helpful features, despite initial challenges as a newcomer to coding.