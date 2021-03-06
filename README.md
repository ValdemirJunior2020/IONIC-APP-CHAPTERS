# IONIC-APP-CHAPTERS
Requirements
Build an Apache Cordova app using Ionic that implements a page-turner book app that can be used to display a sequence of content pages in a book. Each content page contains an optional chapter title text, followed by a combination of text and image content, as well as a content page number that starts at 1. Each content page should also provide navigation to the next and previous content pages in the book.

The first page to be displayed is the book cover page, and the second page is the TOC page (table of contents). After that, there is an arbitrary sequence of content pages that may or may not contain a chapter title text. The TOC page should provide navigation links to each of the content pages that contain a chapter title text, using links that display the chapter title text of those content pages.

The initial screen displayed when you start the app for the first time will be the cover page, which contains the book title text and optionally any additional content, such as an image. Tapping on the cover page should navigate to the TOC page. From there, you can either navigate to the next content page in the usual way, or you can navigate to a particular content page by tapping on the chapter title text listed in the table of contents.

In this assignment, you do not have to implement any data persistence. That means that when you start the app again in the future, it does not have to remember what page you were on last. It is OK always to go back to the cover page every time. Storing and retrieving the last known current page as a bookmark would be a nice feature to include, but would add too much development time to this project. However, if you do find that you have time to add that feature, feel free to try it out!

Of course, you can use google search and stackoverflow.com, as well as the many available tutorials and videos on the web. You can also use any GitHub repos that you can find that might help you develop your solution. If you find a GitHub example that is very close to these requirements, do try to customize in some interesting ways, because you will want a distinctive code example on your own GitHub account to show potential employers what you can do. However, you are permitted to copy and use any public domain code in your solution that you find in any resources that you may find helpful.

Provide the link to your project solution on GitHub to your instructor for verification.

Structure
The following might help to understand the structure of the book content.

Cover page:

Book title text
Optionally any additional cover page information, such as an image.
Next page navigation to the TOC page
TOC page (table of contents):

Direct navigation links to each of the content pages that contain chapter title text
Next page navigation to the first content page
Previous page navigation to the cover page
Content page:

Optional chapter title text (only for the first page in a chapter)
Text and image content
Content page number
Direct navigation link to the TOC page
Next page navigation to the next content page, if there is one
Previous page navigation to the previous page, if there is one
