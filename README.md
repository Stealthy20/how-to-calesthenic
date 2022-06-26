# How To Calisthenic
How To Calisthenic is a website dedicated to folks who are interested in learning more about calisthenics and getting started with it. There are countless videos available, the majority of which highlight the sport's difficult and glamorous aspects. I wanted to acquire the basics for a beginning, as well as some solid people to follow in the community. So that they will have the best chance of being successful with calisthenics.

![mockup image of my website](docs/mockup.JPG)

# Live Site
[How To Calisthenic](https://stealthy20.github.io/how-to-calisthenic/)
# Repository
[GitHub](https://github.com/Stealthy20/how-to-calisthenic)
# Features
**This site contains the following content**
- Landing page with introduction to the site and calisthenic
- Get started page
- Inspiration page
- Form to sign up for a newsletter
- Custom 404 page to take the user back the page

## Existing Features
- **Navigation Bar**
  - A fully responsive navigation bar and logo to make sure that the user can navigate the page. That is identical across all pages for easy navigation and familiarity
  - Larger font on the active page to make sure the user knows where he/she is and a hover effect on the navigation elements. 

![Image of the header](docs/header.JPG)

- **Footer**
  - A fully responsive footer with links to social media and a link to sign up for the newsletter. That is identical across all pages for easy navigation and familiarity
  - Hover effect on the elements to make sure the user knows that they are clickable. 

![Image of the footer](docs/footer.JPG)

- **Landing/introduction**
  - The landing page is made up of two sections.
    - A colorful, energetic picture to make sure the user gets a good first impression of the page.
    - And an introduction to calisthenics where we cover what calisthenics is, the basics of it, how to get started and where to train. 

![Image of the landing page image](docs/landing-page-image.JPG)
![Image of the content in the introduction](docs/introduction.JPG)

- **Get Started**
  - The get started page is where the user should go after they got the introduction to calisthenic. Here will the user find the 4 basic exercises to calisthenics, a short explanation of the exercise, and a link to a good video to watch on Youtube.

![Image of the content in the get started page](docs/get-started.JPG)

- **Inspiration**
  - This page is a very important page for me. There are thousands of different  people that claims that they know what they are talking about. I have listed three really good and inspirational people for beginners to follow.
  - The page has a short introduction of the person, so the user knows who it is and what they do. So they can decide if the person is worth following. There is an image of the person aswell links to their Youtube and Instagram.
![Image of the content in the inspiration page](docs/inspiration.JPG)

- **Sign up for newsletter**
  - Here can the user sign up for a newsletter if they want to get news regarding calisthenics and updates to good exercises. 
  - The page includes a form to sign up and a "thank you for signing up" page, and a link to get back to the front page again.

![Image of the content in the sign up for newsletter](docs/newsletter.JPG)
![Image of the content in the signed-up page](docs/signed-up.JPG)

- **Custom 404 page**
  - A landing page when something goes wrong to make sure that the user still can navigate the page and get to the intended content.
  - The 404 page has the same header and footer as all the other pages for easy navigation and familiarity 

![Image of the content in the 404 page](docs/404.JPG)

## Upcoming features 
  - I want to add a Google map for the user to see the closest calisthenic parks or outdoor gyms in their area.
  - I want to implement a place where user can share experiences and look for advice.

# Testing
I have tested the page continuously as I built it. This will be noticeable as we go through some bugs since the colors will be different from the finished product. I will show screenshots and an explanation of some of the bugs i encountered during this progress. 

## Bugs

- **Bug 1**
  - I didn't get the logo in the header and the navigation bar to get on the same row in the header. 

![Image of the first bug where the navigation bar and logo in the header appeared on two rows](docs/bug1.JPG) 

- **Fix for bug 1**
  - Added float left property to the logo in the header. Which made the navigation bar to pop up on the same row with its float right element. 

![Image of the fix for the first bug](docs/bug1-fix.JPG) 

- **Bug 2**
  - Had a problem where all the left elements didn't appear on the left and some were stacked on the right side. As you can see from the colors. The blue should all be on the left and the red should all be on the right. 

![Image of the second bug where the elements didn't align](docs/bug2.JPG) 

- **Fix for bug 2**
  - The height difference were the problem which made the blue go over on the right side. 
  - Fixed it by setting the same height to both the elements.

![Image of the fix for the second bug](docs/bug2-fix.JPG) 

- **Bug 3**
  - The navigation bar wasn't responsive on smaller screens. It made a new row and stayed on the right. Which wasn't looking good.

![Image of the third bug where navigation bar wasn't responsive on smaller screens](docs/bug3.JPG) 

- **Fix for bug 3**
  - Added float left property to the navigation bar for screen sizes of 850px and down.
  - Reduced the font size to make it fit under the logo in the header.

![Image of the fix for the third bug](docs/bug3-fix.JPG) 

- **Bug 4**
  - The footer didn't stick to the bottom of the screen when it was too little content to push it down.

![Image of the fourth bug where the footer didn't stick to the bottom of the screen](docs/bug4.JPG) 

- **Fix for bug 4**
  - Fixed with flexbox, i got the code from [Kiran Workspace](https://kiranworkspace.com/how-to-stick-footer-to-bottom-of-page/)
  - Added a class to the content div and added code in style.css from Kiran.

![Image of the fix for the fourth bug](docs/bug4-fix.JPG) 

## Responsiveness
- **This was tested manually with Dev tools to look at the content from different sizes. From which i choose some breaking points to add media queries to make sure the content looks good on all devices.**
  - 1300px wide and down: From where the introduction first encountered problems. Solved it by moving the image down under the text content. 
  - 850px wide and down: From this size and down, all the pages started to get problems with overflow. So from here and down all content is stacked vertically instead of horizontally. 
  - 550px wide and down: The footer collapsed and didn't work at all. So i increased the height of the footer and stacked the link to the newsletter form and social links on top of each other. 
  - 425px wide and down: Reduced some font sizes to make it look better on smaller screens. 

 ## Validator Testing
  - **HTML through W3C Validator**
    - No errors
  - **CSS through Jigsaw Validator**
    - No errors
  - **Contrast validator through WebAim**
    - No errors
  - **Accessibility check through Wave**
    - No errors

## Technology Used
- HTML
- CSS
- Font Awesome

# Deployment
I deployed this website by using GitPages and following the steps below:

- GitHub pages deployment
  - Log in to GitHub
  - In your Repository section, select the project repository that you want to deploy.
  - In the menu located at the top of this section, click "Settings".
  - Select "Pages" on the left-hand menu.
  - In the source section, select branch "Main" and save
  - The page is then given a site URL which you will see above the source section. Wait a minute and refresh the page.
  - The background around your URL should have turned green with a check mark before it. 
  - It's now live and ready to share.

 **Forking the Guthub Repository.**
- You can fork the original GitHub Respository to be able to view or make changes without it affecting the original repository.
  - Go to the GitHub repository.
  - in the top right, press the button named "Fork".
  - You will now have a copy of the repository in your own GitHub. 

**Make a Local Clone**
- Go to the GitHub Repository.
  - Click the "Clone" button in the top of the repository.
  - Copy the link.
  - Open Git Bash.
  - Change the current working directory to the location where you want the cloned directory.
  - Type git clone, and then paste the URL you copied earlier.
  - Press Enter to create your local clone.

  # Credits

  - All the images (except images of real-life inspirations) are taken from [Shutterstock](https://www.shutterstock.com/)
  - Linked to real life inspirational people on Youtube and Instagram [Chris Heria](https://www.youtube.com/c/CHRISHERIA/) [Browney](https://www.youtube.com/c/Browney) [HannibalforKing](https://www.youtube.com/c/HannibalForKing1) 
  - Flexbox code for the footer to stick on the bottom taken from [Kirian Workspace](https://kiranworkspace.com/how-to-stick-footer-to-bottom-of-page/)
  - Icons in the footer are from [Font Awesome](https://fontawesome.com/)
  - Basics of the form taken from the Love Running Challenge