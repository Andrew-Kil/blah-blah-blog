---
title: Improve Your Web Pages With Lighthouse Audits
date: '2020-07-07T15:00:38.189Z'
template: 'post'
draft: false
slug: 'improve-your-web-pages-with-lighthouse-audits'
category: 'Web Development'
tags:
  - 'Web Development'
  - 'Google Chrome'
  - 'Chrome DevTools'
  - 'SEO'
  - 'Accessibility'
description: 'How to improve the performance, accessibility, best practices, and SEO of your website by running a Lighthouse audit.'
socialImage: '/media/lighthouse/lighthouse-scores.png'
---

- [What is Lighthouse](#what-is-lighthouse)
- [How to get started](#how-to-get-started)
- [Generating Lighthouse audit reports using Chrome DevTools](#generating-lighthouse-audit-reports-using-chrome-devtools)
- [Your turn](#your-turn)

![lighthouse-scores.png](/media/lighthouse/lighthouse-scores.png)
_Lighthouse results on my portfolio website_

## What is Lighthouse

Lighthouse is an open-source tool provided by Google that is used to perform audits and analyze different aspects of a web page including search engine optimization, load times, and accessibility. The audit simulates a user visiting your website with a slow 3G connection and older devices to see how it handles packet loss and other conditions. After the audit is run, the user is presented with scores for different categories as well as more detailed information about different metrics and suggestions on how to improve your web page.

## How to get started

There are different ways to get started with Lighthouse including using a [Chrome extension] and [PageSpeed Insights]. This blog post will walk you through how I use Google Chrome DevTools to perform Google Lighthouse audits.

## Generating Lighthouse audit reports using Chrome DevTools

The only thing that you will need to get started is [Google Chrome]. Go to the URL of the web page that you would like to audit and open up Chrome Developer Tools by pressing Option + ⌘ + J (on macOS), or Shift + CTRL + J (on Windows/Linux). Alternatively, you can also right click anywhere on the page and press **Inspect**. Navigate to the **Lighthouse** tab in DevTools.

![lighthouse-tab.png](/media/lighthouse/lighthouse-tab.png)

<p style="text-align: center; font-style: italic">Lighthouse tab in DevTools</p>

As you can see, there are different categories to choose from and an option to set the device as Mobile or Desktop. If you are using a lot of Chrome extensions, you may see this image:

![lighthouse-chrome-extension-issues.jpg](/media/lighthouse/lighthouse-chrome-extension-issues.jpg)

When you're ready to start the audit, hit the Generate report button. In order to get accurate results, I would suggest using incognito mode and generating reports for both Mobile and Desktop.

The Lighthouse report will show you how the web page is performing in the different categories that you selected. If you scroll down, you will see suggestions about how to improve in specific categories.

![lighthouse-performance.png](/media/lighthouse/lighthouse-performance.png)

<p style="text-align: center; font-style: italic">Opportunities to improve performance and diagnostics</p>

## Your turn

Google Lighthouse is a valuable tool to add to your toolkit in order to make sure your website is optimized for performance, SEO, and accessibility. Try it out today on your own websites!

[chrome extension]: https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en
[pagespeed insights]: https://developers.google.com/speed/pagespeed/insights/
[google chrome]: https://www.google.com/chrome/
