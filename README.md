# Figma Logo using CSS Grid and Logical Properties

## Motivations:

I saw a tweet by Carmen Ansio that showed how to create the logo of Figma in CSS with the help of flexbox.

Her solution is clever: she sets the width of the elements, and then gives the container the same width as a pair of elements. Then, with the help of the `flex-wrap` CSS property, she stacks the elements in pairs in the way she wants.

She threw down the challenge to make the logo using grid, so now it is my turn.

## Grid Solution

First, I used this tool, [imagecolorpicker](https://imagecolorpicker.com/) to get the exact colours of the _Figma_ logo. And I declared those and the background colour as variables in the root of the document.

Then, using the same trick as Carmen, I declared my base size as
`item-size`.

I declared another variable to create the rounded corners, `--radius: 50%;`.

Then I declared an explicit grid using the base size. And rounded the elements using the declared variable `--radius` and the CSS 
shorthand property `border-radius`.

I used the `inline-size` logical property to set the size of each box.

Finally, I set the inline and block size of each element, wich in a language with writing mode horizontal oriented is equivalent to width and height of the element, respectivily. 

## Learn more about logical properties

- [web.dev](https://web.dev/learn/css/logical-properties/)
- [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Logical_Properties)

## You can see Carmen Ansio solving this challenge with flexbox in TikTok in the following link:

- [Carmen solving this challenge with Flexbox in TikTok](https://www.tiktok.com/@carmenansio_/video/7186747216965520645)

- Follow Carmen Ansio: 

[GitHub](https://github.com/carmenansio/carmenansio) | 
[Twitter](https://twitter.com/carmenansio)

