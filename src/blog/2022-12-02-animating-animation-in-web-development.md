---
title: Animating Animation in Web Development
author: Frederick Lamptey
description: Accessible Web Animation
date: 2022-12-01T23:17:32.269Z
tags:
  - post
image: /assets/blog/dynamic-wang-tqftvttlmag-unsplash.jpg
imageAlt: "A still animation (Image credit: Dynamic Wang) "
---
Animation in web design is adding motion or interaction to an object such as an image on a web page or website to serve different purposes. These purposes can be dire or beneficial to audiences of a website. And on this article, I am going to talk about both the dire and beneficial purposes of it, and when and how they should be used or implemented on a webpage. 

Firstly, I would like to talk about the negative effects of using animation. An animation can be measured or considered negative when looked at from the perspective of accessibility. A standard webpage is a page that is accessible to all. Thus, it serves its content to all types of audiences without having them struggle or triggering something in them. Hence, as a good web developer or UX designer, you need to take note of the following things that a bad animation can do to an audience:

An audience with a vestibular system disorder will find a webpage containing bad animation an unwelcoming place to be. A vestibular system according to Val Head in his article “Designing Safer Web Animation for Motion Sensitivity” is the system around our inner ear and brain that processes sensory information involved in controlling balance and eye movements. Based on this definition, an audience with a vestibular system disorder may have imbalance and/or eye movements problems if they chance on bad animation on a web page.  Hence, as a web designer or developer, you should ensure that this is avoided.

Nevertheless, designers and developers should also note that animated interfaces can cause headache, dizziness, and nausea for some people. People with migraine sensitivities, epilepsy, and even vestibular disorders go through this if they encounter bad animation. A bad animation such as one that is bigger than the viewport can cause dizziness and even headache. Parallax scrolling (both background and foreground are moving at the same speed) can cause all the problems to an audience. 

However, inasmuch as bad animation can cause these problems, good animation can be of great benefits too and hence, can’t be ruled out from the world of web development or design. Below are some of these benefits:

A good animation aids in an audience understanding of the content of a webpage. Sometimes people struggle to comprehend the message or information that a webpage content is trying to send across. Hence, incorporating things like a good animation that throws more light on the message or information that is intended to go out by the writer of the webpage helps a lot. This is because humans tend to understand stuff better with illustrations, and animation is an example of an illustration.

Nonetheless, a good animation makes a webpage lively, and gives it some sort of warmth or makes it friendly to an audience. Sometimes a webpage or website that is devoid of an image, an animation or a video becomes boring or unattractive to be on. Therefore, as a good developer, involving a good animation in your page can give your page the expected traffic.
Now, talking about a good animation, what is good animation?

A good animation is one that is smaller than its viewport. As a web designer, when designing an animation, consider the relative size of movement to the screen. The higher the ratio is, the more people will be triggered by it negatively.

A good animation is one devoid of parallax scrolling. Parallax scrolling as already defined earlier is when both background and foreground are moving at the same speed. You can use subtle parallax effects if you desire, but there are a couple of behaviors you should avoid by any means.

First and foremost, avoid “Scrolljacking”. This is when the scrollbar is controlled to behave independently of the user’s efforts and intents. It’s not a nice experience to begin with. But, when combined with parallax scrolling, the animated background begins to move at its own speed and your website becomes basically unusable for people with vestibular system disorders.
Also avoid horizontal scrolling when using parallax effects. Horizontal scrolling on a website is a surprise to most users and not always a pleasant one. Generally, always think carefully about surprising movements on the screen: they tend to make people with balance problems lose direction and the symptoms ensue. 

Moreover, a good animation is one that allows users to control carousels. Carousels are strategic image, graphic, text and video display formula, that manifest in one interactive sliding block. When users are given the opportunity to control animation or carousels, they tend to be able to interact with the webpage how they want it. This doesn’t just make the animation good, but very friendly and welcoming to users or audience.

Nonetheless, for an animation to be good or accessible, you need to specify the duration of it. Many at times, an animation without a duration becomes confusing to look at or even hard to understand. You tend not to know what or where the starting point of it is, and hence, this could be very disturbing and irritating to people with the aforementioned health issues or sensitivities. Hence, as a good web designer, it is expected of you to add an animation duration to your animation in order for your page to be accessible to all. 

``` css
d﻿iv {
 ﻿ transition: wide 4s;
}```﻿css

However, a good animation can have a reduce motion feature to make it accessible to its audience. Mostly, fast moving animations are the ones that cause a lot of problems for some audiences. Such animations tend to make audiences feel dizzy, trigger headaches, and even can cause some of them to puke.  Therefore, in order to avoid this, designers or web developers can make use of the reduce motion feature. This feature will help them put the motion of an animation at an accessible and friendly manner. Example:

<figure>
<iframe height="300" style="width: 100%;" scrolling="no" title="Untitled" src="https://codepen.io/fredericklamptey/embed/preview/BaVOEzv?default-tab=html%2Cresult&editable=true" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/fredericklamptey/pen/BaVOEzv">
  Untitled</a> by FrederickLamptey (<a href="https://codepen.io/fredericklamptey">@fredericklamptey</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>
<figcaption>Animated Tab (Inspired by https://css-tricks.com/accessible-web-animation-the-wcag-on-animation-explained/)</figcaption>
</figure>

To conclude, animations are inevitable in web development or design, however, how you present it in your webpage or website is what determines how accessible it is to the targeted audience(s).