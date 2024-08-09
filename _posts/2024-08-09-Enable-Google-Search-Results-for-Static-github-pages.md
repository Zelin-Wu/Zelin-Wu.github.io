---
title: 'Enable Google Search Results for Static GitHub pages'
date: 2024-08-09
permalink: /posts/2024/08/Enable-Google-Search-Results-for-Static-github-pages/
excerpt_separator: <!--more-->
tags:
  - Technical Tutorial
  - 2024
---

After configuring the personal github.io page, it is expected that your customized pages will be found using Google search engines. However, it is not for granted and in this Blog, we'll show how to achieve this. <!--more-->


Begin by testing
======

Generally speaking, the github.io page may not be found during the search. But we may first give it a try!



Open your Google Explorer and input the following 

```html
site:https://your_github_id.github.io/
```



* In the best case, you can find your page.



* But for those who failed, don't worry, the following is a step-by-step tutorial to configure the Google Search Console.

Step 0:  Initialize
======



* Click the link [Google Search Console](https://search.google.com/search-console/about) and click the "Start now" button.



* Then you go into this page asking you to select the verification type. Usually, using the "URL prefix" approach.

![img](https://charlesqueen.github.io/resources/p14.png)

* Entering your website "https://your_github_id.github.io/" here. 

Step 1: Verify the ownership
======

Use an HTML file to verify

![img](https://zelin-wu.github.io/images/posts/google-search-enable/google-search-verify-ownship.png)

* Follow the instructions, download the file, and then upload it to your root of the GitHub repository.
* Wait for a minute and have a cup of tea.
* Click the "VERIFY" button and then you are done.



Step 2: Add a sitemap
======



![img](https://zelin-wu.github.io/images/posts/google-search-enable/google-search-add-sitemap.png)



If you are using the template [academicpages](https://github.com/academicpages/academicpages.github.io) as I do, then the sitemap is automatically generated, and you may just enter "sitemap.xml" and submit.



For other users, you may need to generate the sitemap.xml file beforehand, as the instructions may be found online. 



Step -1: Just wait
======

You are good to go, but you need to wait a couple of days for Google to process your request.

