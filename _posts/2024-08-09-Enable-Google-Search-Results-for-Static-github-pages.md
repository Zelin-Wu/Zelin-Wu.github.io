---
title: 'Enable Google Search Results for Static github pages'
date: 2024-08-09
permalink: /posts/2024-08-09-Enable-Google-Search-Results-for-Static-github-pages
tags:
  - random
---

This is a sample blog post. Lorem ipsum I can't remember the rest of lorem ipsum and don't have an internet connection right now. Testing testing testing this blog post. Blog posts are cool.



After configuring the personal github.io page, it must be expected your customized  pages could be found using the Google search engines. However, it is not for granted and in this Blog, we'll show how to achieve this.

Begin by testing
======

Generally speaking, the github.io page may not be found during search. But we may first give it a try!



Open your google explorer and input the following 

```html
site:https://your_github_id.github.io/
```



* In the best case, you can find your page, then we are done! (Cheers~)



* But for those failed, don't worry, the following is a step-by-step tutorial to configure the Google Search Console.





Step 0:  Initialize
======



* Click the link [Google Search Console](https://search.google.com/search-console/about) and click the "Start now" button.



* Then you go into this page asking you to select the verification type. Usually, using the "URL prefix" approach.

![img](https://charlesqueen.github.io/resources/p14.png)

* Entering your website "https://your_github_id.github.io/" here. 



Step 1: Verify the ownership
======

Use HTML file to verify

![image-20240809104710627](C:\Users\IDEA\AppData\Roaming\Typora\typora-user-images\image-20240809104710627.png)

* Follow the instructions, download the file and then upload to your root of the Github repository.
* Wait for a minute and have a cup of tea.
* Click the "VERIFY" button and then you are done.



Step 2: Add a sitemap
======



![image-20240809105127382](C:\Users\IDEA\AppData\Roaming\Typora\typora-user-images\image-20240809105127382.png)



If you are using the template [academicpages](https://github.com/academicpages/academicpages.github.io) as I do, then the sitemap is automatically generated, and you may just enter "sitemap.xml" and submit.



For other users, you may need to generate the sitemap.xml file beforehand, as the instructions may be found online. 



Step -1: Just wait
======

You are good to go and need to wait for a couple of days to get your request processed by Google.

