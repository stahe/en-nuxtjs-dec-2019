# Introduction to the NUXT.JS Framework with Examples

📘 **Access the course documentation:** [https://stahe.github.io/en-nuxtjs-dec-2019/](https://stahe.github.io/en-nuxtjs-dec-2019/)

---

This document presents examples of how to use the NUXT.JS framework.

The [Nuxt.js](https://fr.nuxtjs.org/) framework will allow us to implement the following functionality:

- The first page of the web application is served, for example, by a [Node.js](https://fr.nuxtjs.org/) server. Furthermore, the other pages of the application are also hosted on this same server. They are served when the user manually types their URL into the browser. These pages embed a [Vue.js] application (approximately).
- Once the first page is loaded in the browser, the application behaves like a standard [Vue.js] application.

Ultimately, the application behaves like a [Vue.js] application except for the first page and when the user manually types in URLs. In these cases, the page is retrieved from the server. 

When a search engine requests the various pages of the application, it receives the pages from the server. These pages may have been optimized for SEO (Search Engine Optimization). In a classic [Vue.js] application, the search engine receives a page with little SEO value.

## Methodology

The scripts in the document are commented on and their execution is reproduced. Additional explanations are sometimes provided. The document requires active reading: to understand a script, you must read its code, its comments, and its execution results.