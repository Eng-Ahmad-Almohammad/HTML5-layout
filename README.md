# HTML5-layout
## Headers & Footers
## < header > < footer >
### The < header > and < footer > elements can be used for:
● The main header or footer that appears at the top or bottom of every page on the site.

● A header or footer for an individual < article > or < section > within the page.
### In this example, the < header > element used to contain the site name and the main navigation. The < footer > element contains copyright information, along with links to the privacy policy and terms and conditions. Each individual < article > and < section > element can also have its own < header > and < footer > elements to hold the header or footer information for that section within the page.
![header and footer](https://user-images.githubusercontent.com/70091044/92302622-415cc680-ef76-11ea-8c93-ad170f4f84c9.PNG)
## Navigation
## < nav >
### The < nav > element is used to contain the major navigational blocks on the site such as the primary site navigation.
![Nav](https://user-images.githubusercontent.com/70091044/92302702-d3fd6580-ef76-11ea-95f0-4d929b283175.PNG)
## Articles
## < article >
### The < article > element acts as a container for any section of a page that could stand alone and potentially be syndicated.
### This could be an individual article or blog entry, a comment or forum post, or any other independent piece of content.
![artical](https://user-images.githubusercontent.com/70091044/92302891-a4e7f380-ef78-11ea-89ea-eda56f770a63.PNG)
## Asides
## < aside >
### The < aside > element has two purposes, depending on whether it is inside an < article > element or not.
### 1-When the < aside > element is used inside an < article > element, it should contain information that is related to the article but not essential to its overall meaning. For example, a pullquote or glossary might be considered as an aside to the article it relates to.
### 2-When the < aside > element is used outside of an < article > element, it acts as a container for content that is related to the entire page. For example, it might contain links to other sections of the site, a list of recent posts, a search box, or recent tweets by the author.
![aside](https://user-images.githubusercontent.com/70091044/92302993-abc33600-ef79-11ea-8c5d-d06848525655.PNG)
## Sections
## < section >
### The < section > element groups related content together, and typically each section would have its own heading.
### For example, on a homepage there may be several < section > elements to contain different sections of the page, such as latest news, top products, and newsletter signup.
### Alternatively, if you have a page with a long article, the < section > element can be used to split the article up into separate sections.
![section](https://user-images.githubusercontent.com/70091044/92303103-82ef7080-ef7a-11ea-85fc-9df87207337e.PNG)
## Heading Groups
## < hgroup >
### The purpose of the < hgroup > element is to group together a set of one or more < h1 > through < h6 > elements so that they are treated as one single heading.
### For example, the < hgroup > element could be used to contain both a title inside an < h2 > element and a subtitle within an < h3 > element.
![hgroup](https://user-images.githubusercontent.com/70091044/92303201-52f49d00-ef7b-11ea-947a-d2b147ed3422.PNG)
## Figures
## < figure > < figcaption >
###  It can be used to contain any content that is referenced from the main flow of an article (not just images).
### It is important to note that the article should still make sense if the content of the < figure > element were moved (to another part of the page, or even to a different page altogether). For this reason, it should only be used when the content simply references the element (and not for something that is absolutely integral to the flow of a page).
### Examples of usage include:
● Images

● Videos

● Graphs

● Diagrams

● Code samples
 
● Text that supports the main
body of an article
### The < figure > element should also contain a < figcaption > element which provides a text decription for the content of the < figure > element. 
![figure](https://user-images.githubusercontent.com/70091044/92303318-52a8d180-ef7c-11ea-936b-1ee5c0b6137e.PNG)
