# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview
This is my first "formal" project with a workflow that has guidelines. Perhaps to no ones surprise but mine, I found that it is much better practice to have a design reference rather than build out from scratch and using ones imagination. As well this would be the first time using github, so im happy the project has forced me to start unveiling how that works.

### Screenshot

![](./images/FEM.io%20-%20QR%20code%20challenge%20-%20Desktop%20-March%2020th%20-%202022.png)
![](./images/FEM.io%20-%20QR%20code%20challenge%20-Mobile%20-%20March%2020th%20-%202022.png)


### Links

- Solution URL: [https://github.com/Jorgus1710/FEMchallenge-QRcode]
- Live Site URL: [https://jorgus1710.github.io/FEMchallenge-QRcode/]


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow


### What I learned

Overall I didnt find the QR code card to be particularily challenging, I did run into a few situations where I saw things can be done in an alternative way, in particular centering the actual card in the middle of the page. In this situation I found I didnt need to use flexbox or grid at all, and got away with using margins and padding to do the job.

I used a mobile first workflow, as well I added a seperate CSS file to reset the default browser stlyes.

When it came to media queries for desktop view, I added a min-width pixel range of 376, so 1 pixel more than the standard mobile pixel width outline here of 375px, and that did the job nicely for me. I would like to know if that is a logical approach, as well if there are better practices for achieving this in the future.


``` CSS
@media all and (min-width: 376px) {
    .card {
        width: 325px;
        margin: 110px auto;
        
        
    }
}
```

### Continued development

Im looking forward to learn best practices or common methods of centering a card or any div for that matter. Im curious what will be suited for me as time goes on.

### Useful resources

- Youtube and Google were excellent resources, as well I highly reccomend the following youtube video from ZerotoMastery.io [https://www.youtube.com/watch?v=PY_iIeAKFw0&ab_channel=ZeroToMastery] - the first part of the video is free and is what really helped me understand how important training from a design file is, as well there were numerous tips in the video. The rest of the workshop video can be seen through a subscription to (Zerotomatery.io). I Highly reccomend it.

## Author

- George Stawowczyk
- Frontend Mentor - [@Jorgus1710](https://www.frontendmentor.io/profile/Jorgus1710)

