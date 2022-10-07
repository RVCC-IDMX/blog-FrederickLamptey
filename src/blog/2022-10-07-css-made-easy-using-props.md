---
title: CSS Made Easy Using Props
author: Frederick Lamptey
description: This article talks about a way to make writing css easier for web
  developers. Now developers can use predefined variables from prop's page to
  write their css.
date: 2022-10-07T02:30:21.840Z
tags:
  - Article
image: /assets/blog/sincerely-media-l6ysdz2m6nm-unsplash.jpg
imageAlt: A man on his laptop that I want to use to depict a picture of someone
  coding in css.
---
Have you noticed that without the artificial intelligence of most integrated development environments (IDE's) such as visual studio code, coding and writing Html and stylesheets become tiring and even stressful due to the fact that one would have to type in everything by him or herself since there isn't nothing like auto-aiding? If you haven't noticed, you can try it now. However, there's no need to because open props are here to help you.

According to <!--StartFragment-->[Open Props: sub-atomic styles (open-props.style)](https://open-props.style/) <!--EndFragment-->, open props are supercharged CSS variables. Personally, I term them as pre-defined variables that can be transported once a required link(s) is activated in their new location. What this means is that although open props can work in every stylesheet, there are certain links that a user must plant in either their html file or stylesheet according to the instructions given in the links' section on the page of the link provided above.

Now, I know you may be wondering who the creator of the open props page is if only you have not already searched it on google. Well, I am here to introduce to you Adam Argyle, the creator of the popular open props that most developers such as Kevin Powell uses in some of his projects. You can check out Kevin's YouTube open props usage tutorial via this link <!--StartFragment-->[(6107) Supercharge your CSS with Open Props - YouTube](https://www.youtube.com/watch?v=szPNMKZazzQ&t=72s) <!--EndFragment-->. 

Still confused after watching Kevin's video? Don't worry let me break it down with one or two code examples here. But before I begin with the examples, I would like you to think of open props as values that can be used to complete the normal in-built CSS variables to achieve the expected styles of a user. Lets take a look at an example of a normal css code below:

\`﻿\`` css

body {

   background-color: blue;   

}﻿

\`﻿\``

Now, lets take a look at an example of this same code written using open props below and then we talk about the difference right after:

\`﻿\``

body {

   background-color: var(--blue-6);

}﻿

\`﻿\``

At this point, I believe things should be a little clear to you after viewing the above code examples carefully. Now, to make things to you, when you look at the above codes, you would realize that the only differences between them are the representations of the values assigned to the various variables. In the second code example, the style of representation of the value "blue" is "var(--blue-6)" which is simply blue as the above but then again, it is using an open props syntax for indicating the color blue. The "var" in the beginning is just something that follows a value in open props, and the number "6" is a specified range of blue I want in my code. In the open props page, the range of blue you can choose from is 0-9. I guess this defines the intensity of the blue, but i am not sure about that as at this point of me writing this article.

Although, I only chose to explain the concept of open props to you with an example of representing colors in open props, I want to let you know that open props are wide and hence, you can find "values" that you can use to represent other things in your stylesheet (CSS). You can find open props to define your fonts, your line spacing, etc. 

To conclude, the days of web development being strenuous is fast fading and open props is one initiative that is contributing to that. Hence, as a web developer I urge you to take a good look at after reading this article.