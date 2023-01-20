# Figma Logo using CSS Grid and Logical Properties

## Motivations:

I saw a tweet by Carmen Ansio that showed how to create the logo of Figma in CSS with the help of flexbox.

Her solution is clever: she sets the width of the elements, and then gives the container the same width as a pair of elements. Then, with the help of the `flex-wrap` CSS property, she stacks the elements in pairs in the way she wants.

She threw down the challenge to make the logo using grid, so now it is my turn.

## Grid Solution

First, using this tool, [imagecolorpicker](https://imagecolorpicker.com/)  and got the exact Figma logo colors. And I declared those and the background color as variables in the root of the document.

Then, using the same trick, I have declared my foundation size as
`--item-size`.

I have declared other variable for the rounded corners, `--radius: 50%;`.

After that, I have declared a explicit grid using the basis size. And rounded the items using the declared variable `--radius` and the CSS 
shorthand property `border-radius`.

Finally, 

## You can see Carmen Ansio solving this challenge with flexbox in TikTok in the following link:

[Carmen solving this challenge with Flexbox in TikTok](https://www.tiktok.com/@carmenansio_/video/7186747216965520645)

- Carmen Ansio 

[GitHub](https://github.com/carmenansio/carmenansio) | 
[Twitter](https://twitter.com/carmenansio)

