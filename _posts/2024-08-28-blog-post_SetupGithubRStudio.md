---
title: 'Setting up Github pages and edit with RStudio'
date: 2024-08-28
permalink: /posts/blog-github-rstudio-website/
tags:
  - Github
  - RStudio
  - Website
---

I had the opportunity to design many tutorials as a Ph.D student and after graduating. Generally, the slides and other stuff are just somewhere on my hard drive, taking the digital dust. Therefore, I've had the idea to create another Github pages where I could post my tutorials! #OpenScience <br>
The thing is that I don't really like editing the pages on the Github page. I've tried other programs, such as Github Desktop, but I've never quite enjoyed this. I've been looking for other options, and as a (now long-time) user of R and RStudio, I thought it was time to give it a try such that I can modify all as I want with this program. <br>
<br>
I'd like to post my notes here about the process I've been through when setting everything up -- I'm pretty sure I'll forget how I did it in the future, and it can also be useful for other people!<br>
<br>
[Warning!](){: .btn .btn--danger}
<br> When I say I'd like to document the process, it means that I'll write down the failed steps as well! Try-and-error is, I think, the best way to learn things for me (I can read as many tutorials as possible, I'll always need hands-on practices to really catch the concepts).
So, beware!
And if you have solutions for my errors, please don't hesitate to share!


---

First, set up the Github page
======

Ok, I can't avoid the Github page. This still need to be created somewhere! I've tried setting up as a subpage of this webpage... but for reasons that I'm still not completely sure of, it never really worked. I believe the problem was that I was trying to create a subpage of this website, but with different themes, so in the end the codes in the files were not consistent (but is it the real reason? I don't know!).<br>
My solution has been to create another Github account, setting up the page as usual (there are plenty of very informative tutorials on the web for that, I won't give the details) witht the theme I wanted, and then to create other pages. There may have other solutions to do everything under the same account, and I may even decide to use the same theme in the end, but I actually prefer keeping things seperated.<br>
<br>
So far so good, I can edit the website directly from the Github webpage, so it seems to work. Let's move on the next step.<br>
<br>

Second, make it communicate with R/RStudio.
======

Oh this step has been a headache for me. I don't recommend multitasking while going through this step, or you'll run into many failures impossible to understand as I did.


> <b> Get the Github repository into the computer with RStudio </b>

Now my computer needs to have the same folders/files as in the Github repository... or more simply, let's download the repository!<br>
apparently this can be done with RStudio. We just need to open a new project, specify that it is a Git one, provide the web address of the project, and... Tadaaam!<br>
```
<b> How to do?</b> File > New Project... > Version Control > Git > Paste the address of the repository, configure the options > Create Project
```

<img src="https://aymeric-collart.github.io/images/RStudioGithubCreation.gif" alt="Alt text" style="box-shadow: 3px 3px 3px gray;">

I know I should have clicked on "open in a new session", but this was already a new session.<br>
And if it works, you now have a new option near the "environment" window: the "Git" option.

<img src="https://aymeric-collart.github.io/images/GitOption.png" alt="Alt text" style="box-shadow: 3px 3px 3px gray;">

Yes, done!

[Post to finish at a later time -- I need to go through the steps one more time to document with details and images!]