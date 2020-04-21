[Home](README.md) || [My GitHub](https://github.com/leahgrace555) || [The Growth Mindset](thegrowthmindset.md) || [Learning Markdown](blogpost1.md) || [Text Editors](blogpost2.md)|| [Terminal Cheatsheet](terminalcheatsheet.md) || [Guide to Git](blogpost3.md) || [Structure & HTML](blogpost4.md) || [Styling Webpages](blogpost5.md) || [Javascript](blogpost6.md) || [How Computers Work](blogpost6b.md)

# What I've Learned


Markdown is a relatively simple way to change the styling of text on a webpage.
For example, you can make text look like:
- **This** by typing 
```` 
**this**
````
- Or *this* by typing 
```` 
*this* 
````

It also took me a little while to figure out that surrounding code with backticks is how you add the raw code to a webpage. 
Seeing "Type *this* to make it look like *this* on the rendered webpage wasn't very helpful. 

Some other helpful styling methods using GitHub Markdown are listed below. 

## Headers

You may have noticed that this header is smaller than the one at the top of the page. How did I do that? 

# This the Biggest Header 
and 
###### This is the smallest header

Headers are added using:

````
# For the Biggest 
## For the next biggest
etc... until we get to 
###### For the smallest 
````


## Lists

There are two types of lists that can be added. Lists are either ordered or unordered. 

Create an ordered list like this:
1. Item 1
2. Item 2 
3. Item #
4. Etc..

by typing:

````
1. Item 1
2. Item 2 
3. Item #
4. Etc..
````

And create an unordered list like this:

* Thing 1 
* Thing 2
* Thing 3
* And that other thing

By typing:
````
* Thing 1 
* Thing 2
* Thing 3
* And that other thing
````

## Linking to Websites

It's very common to see websites include clickable links to other websites. For example, I included a link to my GitHub profile on another page of this site. Markdown in GitHub can automatically recognize URLs and create links to their pages like this:

https://github.com/leahgrace555

By simply copying and pasting the URL. But if I wanted so say "Click [this](https://github.com/leahgrace555) to go to my GitHub profile", I could use the following code to make any word a clickable link:

````
[The text you want to be clickable](www.instertURLhere.com)
````

## Block Quotes

To insert a quote like this:

>"this is how you do a block quote" - Leah Russo

use this code:

````
>"this is how you do a block quote" - Leah Russo
````

## Final Thoughts

This exercise really helped me to understand the workflow of GitHub much better. At first, the concepts of creating branches, commits and pull requests really confused me but now I understand the value of editing non-destructively in a branch separate from the master. Branches allow you to test new code free of consequences before merging it into a full project. With a simple project like this, making a few changes that cause something to not work correctly isn't very serious, but with more complicated projects, I can see that using this kind of workflow will have a lot of benefits and make collaborative work much easier. 







