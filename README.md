# 01-02 Challenge | Module 01 - HTML, Git, CSS
### On-the-job ticket &mdash; *Code Refactor*

## Description

This is my very first code refactoring challenge. I reviewed both the html and css files along side and restructured the code with the semantic flow in mind. Althogh tempted to add flex-box styling to the CSS, I decided against it, becuse it goes against _"improving it **without** changing what it does"_!

The first Module is challenging me with the following User Story and Acceptance Criteria. I believe that I have fulfilled all the criteria noted below.  

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements - [done]
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning - [done]
WHEN I view the icon and image elements
THEN I find accessible alt attributes - [done]
WHEN I view the heading attributes
THEN they fall in sequential order - [done]
WHEN I view the title element
THEN I find a concise, descriptive title - [done]
```

## Mock-Up

The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./assets/images/01-html-css-git-homework-demo.png)

> Note: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. In the next Module we'll learn how to make elements responsive so that the web application is optimized for any screen size. It is NOT the scope of this exercise.


## My Work
### 1. Changes to HTML
I made the following changes to restructure the HTML:
> - added more meta elements
> - updated the title to a more descriptive phrase
> - tagged the semantic elements in the comments preceeding them
> - in the header> changed the original div> to a more practical nav> - also a semantic HTML element
> - changed the arbitrary 'hero' class to a more meaningfull figure> - also a semantic HTML element, and used it as a placeholder for the background image
> - properly implemented main> in the flow
> - replaced div> to section> under main>
> - added alternative description to all image elements
> - removed non-essential white space from paragraphs
> - regrouped the original benefit segment under aside> which is also a semantic HTML element
> - repurposed the class benefit and its subs - subsequently this helped with cleaning up the CSS 
> - decided to use dev> instead of section> as children to aside>. I believe it makes the flow cleaner this way 
> - properly implemented footer>
> - removed all un-necessary and redundant id's

### 2. Changes to CSS
I made the following changes to restructure the CSS:
> - tagged the top-down flow segments in the comments preceeding them
> - corrected syntax error under font-family - missing '' - fixed all 'Calibri'
> - consolidated the relevant styles under their semantic elemnts
> - removed un-necessary and redundant id calls


## References
I used files and resources provided by BCS : GitLab repo UTOR-VIRT-FSF-PT-04-2023-U-LOLC

#### Authors Notes:
_This README and accompanying repo have been brought to you by:_ <br>
© Sam Azimi - 2023 CodeCamp Studen.
