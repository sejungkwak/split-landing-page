# split-landing-page

<img width="1437" alt="Screenshot 2021-03-09 at 23 46 16" src="https://user-images.githubusercontent.com/71224770/110553895-acf43c00-8131-11eb-8514-b6591a2cb9e9.png">


#### project notes<br />

1. HTML<br />
2 section<br />
title<br />
buttons<br />

2. CSS<br />
background-image<br />
section:hover expand from 50% to 75%<br />
button:hover<br />

3. JavaScript<br />
mouseover<br />
I didn't use it. I used hover in CSS instead since I don't see the difference.

Challenge from Brad Traversy & Florin Pop on Udemy '50 Projects in 50 Days'

#### Takeaways from the instructor

1. HTML
- wrap sections in a container
- using <a> for buttons

2. CSS
- no flex in body
- container position: relative
- for overlay used ::before and position: absolute
- title also position: absolute, white-space: nowrap(make the text nowrap)
+ when position is absolute,  left: 50% makes the content beginning of the middle. transform: translateX(-50%) makes it middle of the middle.

3. JavaScript
- mouseenter, mouseleave eventListener - changes the width(set in CSS)
