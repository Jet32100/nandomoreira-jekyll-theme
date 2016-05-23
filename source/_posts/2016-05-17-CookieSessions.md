---
layout: post
title: "Blog Post #8"
date: 2016-05-17 09:41:18
comments: true
description: "Cookies and Sessions"
keywords: ""
categories:
- welcome
tags:
- welcome
---

What is a "Cookie"?
A cookie is a small piece of text stored on a user's computer by their browser. Common uses for cookies are authentication, storing of site preferences, shopping cart items, and server session identification. Cookies are responsible for managing things such as your most visited websites, as well as keeping you logged in when returning to a website after closing it.

Each time the users' web browser interacts with a web server it will pass the cookie information to the web server. Only the cookies stored by the browser that relate to the domain in the requested URL will be sent to the server. This means that cookies that relate to www.example.com will not be sent to www.exampledomain.com. When you choose to “clear cookies” in your browser, you are removing your history with each website from your computer, which is why if you return to that website you may notice you have been logged out, and you will need to log back in to continue.

In essence, a cookie is a great way of linking one page to the next for a user's interaction with a web site or web application.

What is a "Session"?
A session can be defined as a server-side storage of information that is desired to persist throughout the user's interaction with the web site or web application. 

Instead of storing large and constantly changing information via cookies in the user's browser, only a unique identifier is stored on the client side (called a "session id"). This session id is passed to the web server every time the browser makes an HTTP request (ie a page link). The web application pairs this session id with it's internal database and retrieves the stored variables for use by the requested page.

