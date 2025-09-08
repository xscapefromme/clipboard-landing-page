# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)



### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here]([https://your-solution-url.com](https://github.com/xscapefromme/clipboard-landing-page.git))
- Live Site URL: [Add live site URL here]([https://your-live-site-url.com](https://clipboard-landing-page-gules-eight.vercel.app/))

## My process
Started with mobile layout as I found that to be the easiest while still referncing how the desktop would look like and after I finsihed mobile layout added media querys to be in a proper responsivness form and thats how I did my project.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- So learned about the image reizing. Didn't really know how before doing it in this project but know I know by placing height:auto; then placing a max-width so it can be responsive with a 100% width so it can be able to take the full width of the container.
- setting a background image through the url value forgot about that but remember through this project
- organizing my HTML through sections with the header and footer outside of the main content. That really matter and made everything very easy to styling the text in each individual section container.
- Starting out with mobile then as it expands higher I used a media query and eventually get the proper desktop layout.
- Responsiveness with the features description that was what I was having a hard time with the Ul so they can be lined up straighted. Learned that the height of the icons matter, as well as the amount of width they take.
- To definitely be more organized less about the user but for myself as it was getting a little messy and was getting confused in my own code. Was getting tricky and did make a mistake that did costed me some time to fix but eventually did fix it but was very frustrating.
- The icons to have a set height so they can be flushed and aligend. Utilizing gap, as well as using display: grid for the contact pages.

-being able to be consistent with the image widths and height so I can avoid cumlative layout shifts(CLS)
-Icons and backgrounds no alt text as they are more for decorative purposes.
- Using the BEM stying and that is what im going to be doing moving forward to having everything with the BEM naming approach as it is more organized and effective.
- the type attribute for the button.
- Doing self hoested fonts as they provide better user security and utilzing the font-face rule. There is also a way where without the delay can use the pre-load value with the rel property. <link rel="preload"> Its the to not have that delay and will definitely utilize as is annoying to have that quick flash of the default browser font then eventually the set font family that im using.

@font-face {
  font-display: swap;
  font-family: "Bai Jamjuree";
  font-style: normal;
  font-weight: 400;
  src: url("../fonts/bai-jamjuree-v12-latin-regular.woff2") format("woff2");
}

@font-face {
  font-display: swap;
  font-family: "Bai Jamjuree";
  font-style: normal;
  font-weight: 600;
  src: url("../fonts/bai-jamjuree-v12-latin-600.woff2") format("woff2");
}
<link
  rel="preload"
  href="../fonts/bai-jamjuree-v12-latin-regular.woff2"
  as="font"
  type="font/woff2"
  crossorigin
/>

<link
  rel="preload"
  href="../fonts/bai-jamjuree-v12-latin-600.woff2"
  as="font"
  type="font/woff2"
  crossorigin
/>



- Use rem or em for max-width and gap instead of using px just for better consistently.
- Using the clamp property to reduce the use of media querys and will definitely do more research on that as does get a little complicated using media-querys.
- Using pixel-perfect to get the right sizing and features of the webpage.[Wasn't really a big deal but now I can do it exactly how it looks like]




### Continued development

-Iam going to continue to get better with mobile first layout, and overall responsivness. Little details still missing and something that I can put more effort but the overall layout and overall project is already completeed and just wanted to move without being a perfionalist. 
- Going to also start to implement some Java Script while still practicing HTML and CSS and looking at doing that for the remainder to be able to combine all 3 into a well made project and eventually one of my own.
- To also grasp the deeper modern concepts of CSS being the min max, clamp etc in upcoming projects but main part is having it responsivness.




