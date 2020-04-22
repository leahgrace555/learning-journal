[Home](README.md) || [My GitHub](https://github.com/leahgrace555) 
# Structuring Web Pages with HTML

## Process and Design

When you begin to design a web page, the following are important things to consider

### 1. Who is the target audience?

All sites should be desinged with a target audience in mind. Think about things such as age range, country of residence, occupation, status, gender, what device they will use to access the page, etc...

### 2. Why are people visiting the page?

- Is it for entertainment purposes?
- Do they have a specific goal associated with visiting your site?
- Is it essential or a luxury?
- Do they want general information/research or more specific?
- Are they familiar with your product/service or are they being introduced to it for the first time?
- Will they need to contact you?

### 3. Site Maps

Site maps can be extremely helpful when designing a page. These create a diagram of the pages and layout of information you want to include on the site. 

Sites typically begin on a homepage. If the site is large and needing to contain lots of information, it may require compartmentilization and links to individual sections. Creating a site map can help visualize and better organize these diffrent sections

### 4. Wireframes

Wireframes are a simple sketch of key information that needs to appear on a page. These do **NOT** include color, font, or images. The purpose of wireframes is to indicate the hierarhcy of the most important parts of the page, as well as design for functionality, not look. 

## HTML Layout

HTML5 includes some new elements that allow syou to divide up a page.

**Header** and **footer tags** are used to display information at the top and bottom of a page, respectively. 

The **navigation** element ` <nav> ` is now used to contain the main site navigation links. It resides inside the header element

An example of a header with navitagion is as follows:
````
<header>
    <h1> Bunnies Are Cute</h1>
     <nav>
         <ul class = "menu">
             <li> 
                 <a href="index.html" ><em>Home</em></a>
             </li> 
             <li> 
                 <a href="Galley.html"><em>Gallery</em></a> 
             </li> 
         </ul>
     </nav>
</header>
````

The **article** element acts as a container for sections of a page that could stand alone or be syndicated. For example, an article may contain a figure, along with the figures heading and caption as seen below:
````
<article>
    <figure>
        <img src="img.jpg />
        <figcaption> image </figcaption>
    </figure>
    <hgroup>
        <h2> This is a heading </h2>
        <h3>  This is also a heading </h3>
    </hgroup>
</article>
````

The **aside** element has two purposes:

1. When inside an article, the aside should contain information related to the article, but not essential to its overall meaning

2. When outside an article, the aside should contain information relevant ot the page as a whole, such as links to other sections

The **section** element groups together related content and each section will typically have its own heading. 

The **hgroup** element is used to group together different h1-h6 elements as if they were one heading

The **div** element is not new, but still an important way to group related elements that do not fall into any of the previously mentioned categories, as those elements should be used for anything but their intended purposes. 

## Extra Markup

Starting each project with ` <!DOCTYPE html> ` will allow the browser to correctly interpret which verison of html you are using. 

**Comments** are added using 
` <!-- "content of the comment goes here--> `

The **ID attribute** can be added to any element in HTML and is used to identify the element uniquely from others in the page. This is useful when using CSS to style specific parts of a page. 
````
<p> id="quote" Thing a person said -That person </p>
````

The **class attribute** is similar to the Id attribute, but can be used on more than one element on a page, and is used more to group elements together rather than uniquely identify them. 

**Block elements** will always start on a new line

**Inline elements** will continute on the same line as their neighboring elements. 

The **meta** element lives inside the head element and contains information about that webpage It is not visible to users but has purposes such as aiding sreach engines in finding the page. Attributes that can be added are name, content, description, and keywords. 

**Escape characters** are used to nullify the meaning of other characters and symbols that are reserved for code.