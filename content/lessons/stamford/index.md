---
title: Welcome to Stamford
date: "2017-02-19T22:40:32.169Z"
---

## Welcome! All our resources are listed here

### Getting started checklist

- attendance! You've let us know you are here yay!
- connect to wi-fi/check that you are logged in to teh library computer
- make sure you have enough power for your lapto p or plug yourself in
- make sure you are using a modern browser like chrome, safari, firefox. Do NOT use ie (internet explorer - we'll be using a web app called `codepen` and it doesn't work in ie)
- relax and make a new friend, say hello to someone you are sitting next to!


### Step 1 A Place to Code
You can choose to write your code online in the browser and keep everything in the cloud:
- [Sign up for CodePen](https://codepen.io)
- You can skip filling out your profile information. You can always do it later

### Step 2 A Sample Code Pen

- [Click here to see a codepen](https://codepen.io/krafalski/pen/GzMoae)

## HTML

### Step 3 Get Coding! (After Introduction)
 - Codepen lets you copy someone else's `pen` and make it your own so you can play with it and edit it
 - For reasons we won't talk about today, the way you copy code is often referred to as 'forking'
 - [Fork this codepen and make it your own](https://codepen.io/krafalski/pen/omGbmd?editors=1100)
 - Fork it by pressing the `fork` button along the top
 - If you have successfully forked it, then you'll see a new button called `save`, now you can save it and any time you are logged in on any computer you can go back to your copy of your pen

<details><summary> Mockup

</summary>

![bill murray](https://i.imgur.com/wO90R7T.png)

</details>

## CSS

### Code along

- Go back to your original pen we did together, you should be able to access it through your [codepen dashboard](https://codepen.io/dashboard/)

### On Your Own
- [Lab time let's go back to this pen our Bill Murray Pen - find it on your dashboard](https://codepen.io/dashboard/)


<details>
  <summary> Mockup Basic CSS</summary>

![bill murray](https://i.imgur.com/CJeQFfR.png)

</details>


<details><summary> Mockup CSS Challenge

</summary>

![bill murray](https://i.imgur.com/26Bnrgb.png)

</details>



## HTML Reference Sheet

|tag name| purpose| example |
|:-:|:-:|:-:|
|[h1](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)|Main Page Header|`<h1>Site Title</h1>`|
|[h2-h4](https://www.w3schools.com/tags/tag_hn.asp)|Subheadings|`<h3>My Blog Title</h3>`|
|[p](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)|Paragraph|`<p>Lorem Ipsum</p>`|
|[a](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)|Anchor(link)|`<a href="urlhere"/> Link Text </a>`|
|[li](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_lists)| List item|<`li>One</li>`|
|[ul](https://www.tutorialspoint.com/html/html_lists.htm)| Unordered List|`<ul><li></li></ul>`|
|[ol](https://www.w3schools.com/tags/tag_ol.asp)| Ordered List|`<ol><li></li></ol>`|
|[img](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)|Image| `<img src="image.png" alt="image description" />`|

Example unordered list
```html
<ul>
  <li>Take out the trash</li>
  <li>Vacuum</li>
  <li>Dust</li>
</ul>
```


## CSS Reference Sheet

|property| possible options | example |
|:-:|:-:|:-:|
|[color](https://css-tricks.com/almanac/properties/c/color/)|hex, rgba, hsl, etc| `color:#054391;`|
|[background-color](https://www.w3schools.com/css/css_background.asp)|hex, rgba, hsl, etc|`color:#fedcba;`|
|[text-align](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)|left,right,center, justify|`text-align:center;`|
|[text-decoration]()|none,underline, line-through|`text-decoration: underline;`|
|[text-transform]()|none, capitalize, uppercase, lowercase|`text-transform:uppercase;`|
|[font-weight]()|normal, bold, 600|`font-weight:400;`|
|[font-style]()|normal, italic, oblique|`font-style: italic;`|
|[font-family]()|family name, serif, sans-serif|`font-family: "Raleway", sans-serif;`|
|[font-size]()|length(12px, 1em, 2rem, 8vw)|`font-size: 32px`|
|[line-height]()|normal, numner(1.5), length(20px)|`line-height:20px`|

#### Sample styling for paragraphs
```css

p {
  color: #fedcba;
  background: #054391;
  font-family: sans-serif;
  text-align: justify;
}
```

### Extra: Box Model

[Every element in web design is a rectangular box.](https://www.w3schools.com/css/css_boxmodel.asp)

- Boxes can be next to each other (horizontally, vertically)
- Boxes can be nested inside of each other
- Boxes can overlap by using CSS properties
- Boxes can appear as other shapes (circles) by using CSS properties

[Interactive Box Model On Code Pen](https://codepen.io/guyroutledge/pen/hgpez)
