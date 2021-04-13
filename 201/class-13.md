# Local storage

The operating system provides an abstraction layer for storing and retrieving application-specific data like the preferences or runtime state of the local machine.

**Cookies**: Were invented early in the web's history, and they used for persistent local storage of small amounts of data.

Cookies have disadvantages:

1) Cookies are included with every ***HTTP*** request, which that making the web application slowing down.

2) Sending data unencrypted over the internet.

3) They are limited to **4KB** of data.

# Before HTML5

Internet Explorer (which is a Microsoft browser) has DHTML behaviors, and one of these behaviors was called **userData**.

userData allows web pages to store up to **64KB** of data per domain.

In 2002, Adobe invented **Flash cookies** within the Flash environment, and it is allowed to store up **100KB** of data per domain.

In 2007, Google launched **Gears**, which can store unlimited amounts of data per domain.

# HTML5 storage

HTML5 storage is a way for web pages to store named key/value pairs locally within the client web browser.

From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser supports it.