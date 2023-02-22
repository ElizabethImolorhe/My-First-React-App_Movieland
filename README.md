# My First React App_Movieland
This App was created while watching a YouTube video by JavaScript Mastery


## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### Screenshot

![image](https://user-images.githubusercontent.com/100562475/220578925-bec7e7c8-e460-46db-b6ad-98b500f2ef8a.png)
![image](https://user-images.githubusercontent.com/100562475/220579268-8362eefc-6dd8-41b6-b0b2-fb4a61e4aad2.png)

### Links

- https://www.youtube.com/watch?v=b9eMGE7QtTk
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- React.JS
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

This is my very first attempt on React.JS. It was quite a huge chanllenge and also a big step for me into the world of web development. I enjoyed every bit of the journey using YouTube video by JavaScript Mastery . I still have a whole lot to learn but I believe this starting point is a milestone for me. I learnt a lot, some of my take aways are:
-Installation of node.js 
-React.JS environment setup 
-using the npx command to install React packages
-using the npm command to start the App on a ocal host.
-React.Js hooks, useState and useEffect

To see how you can add code snippets, see below:

```JS
import React, { useState, useEffect } from "react";

import MovieCard from "./MovieCard";
import SearchIcon from "./search.svg";
import "./App.css";
const API_URL = "http://www.omdbapi.com?apikey=b6003d8a";

```css
h1 {
  font-size: 3rem;
  letter-spacing: 0.9px;
  background: linear-gradient(
    90deg,
    rgba(249, 211, 180, 1) 0%,
    rgba(249, 211, 180, 0) 100%
  );
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  width: fit-content;
}
```
```jsx
<div className="movie" key={imdbID}>
      <div>
        <p>{Year}</p>
      </div>
```


### Continued development

As this is my very first interaction with React.JS, I still have a lot to learn. Many of the components, Hooks and Functions used in this project are still daunting for me. But I strongly believe that with moe practice I will get a good grasp of React.JS.

### Useful resources

- https://reactjs.org/docs/getting-started.html - This gave me an intro into ReactJS. I really liked this pattern and will use it going forward.
- https://reactjs.org/tutorial/tutorial.html - This gave me a hands-on practicum on React.JS 
- https://www.youtube.com/watch?v=b9eMGE7QtTk  - This JavaScript Mastery Youtube video is the backbone for this project. The method and style of teaching is top-notch. I will recommend it for any newbie like me.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments
Many thanks to my teacher and mentor, Simon Joseph. Your help is invaluable.
