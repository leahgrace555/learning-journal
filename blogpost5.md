[Home](README.md) || [My GitHub](https://github.com/leahgrace555) 

# Introducing CSS

CSS stands for "Cascading Style Sheets". It works by applying styles, such as colors, fonts, sizes and other attributes, to selected HTML elements

## Syntax

The syntax of CSS is as follows:
````
p {
    font-family: Arial;
}
````
In this case, p is the **selector**, and the type inside the curly brackets is the **delcraration**. The selector tells CSS which HTML tag to apply the style to, and the declaration states what that style rule is. 

Declarations are also made up of a **property** and a **value**. Properties indicate the aspect fo the element you want to change, and values specify what to chnage it to. In the above example, "font-family" is the property and "Arial" is the value.  

## Internal VS External CSS

CSS can be applied both internally (between a style tag in the HTML document) or externally, by linking an external style sheet in the head section of your HTML document. It is best practice to use external style sheets because it creates consistency across all pages of a site if formatted correctly.

Link an external style sheet by doing the following:
````
<head>
    <title> This is the title of you webpage </title>
    <link href="name-of-css-document.CSS" type="text/css" rel="stylesheet" />
<head>
````
***NOTE*** that the link tag is a self-closing tag and is always inside the head element (not the header).

## How Rules Cascade

CSS files are read from top to bottom, so it is important to understand which rules will take precedence over others.
If two rules have identical selectors, the *last* rule will take precedence (meaning the one lowest on the style sheet). 
Specificity will also take precedence over other selectors. For example, if a rule is applied to a body tag, and a different rule is applied to the h1 inside the body, the rule applied to the h1 tag will take precende because it is more specific. 

# Colors and CSS

Colors is CSS can be specified in 4 ways:

1. RGB Values: These express colors in terms of how much green, red and blue are used to make it. They are written like rgb(100,100,90), for example. 

2. Hex Codes: These are siz digit codes that represent the amount of red, green and blue in a color, for example, #ee3e80

3. Color Names: These are a list of predefined colors that browsers recognize.

4. HSLA: Short for Hue, Saturation, Lightness and Alpha. 

## Contrast

When desinging pages, it is extremely important to consider contrast.

Low Contrast: text is hard to read in this condition, and it also affects that abilities of people with visual impairments or colorblindness to read the pages.

High contrast: These conditions make text easier to read and attracts attention, but may cause strain when reading long spans of small text.

Medium contrast: These conditions improve readability for long spans of text. This is created using dark grey text on a white background, or off-white text on a dark background. 