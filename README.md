# Code Refactor Starter Code

## Table of Contents

* [Project Description](#project-description)
    * [Why is Web Accessibility Important](#why-is-web-accessibilty-important)
    * [Semantic HTML](#semantic-html)
* [Outcomes](#outcomes)
* [Screenshots](#screenshots)
* [Website](#website)


## Project Description

For this project, I worked with a sample company, Horiseon and took their exisiting code and refactored it to ensure the site is accessible and optimized for SEO. I achieved this goal by improving the code in the following ways:

1. implemented semantic HTML, 
2. consolidated CSS selectors and properties, and
3. added comments to the HTML document and CSS stylesheet.

### Why is Web Accessibilty Important

*Web Accessibility helps everyone!* Implementing web accessibility standards not only helps individuals using assistive technologies, such as screen readers, but all users visiting your site. For example, adding alt attributes to images is necessary in order for screen readers to be able to describe the image, but is it also helpful if the image does not load correctly. Another example is by implementing a color scheme with contrasting colors helps users with visual impairments, but is also helpful for other users without such impairment. 

### Semantic HTML

The use of semantic HTML is important for SEO and web accessibility. This is because it provides context to the screen reader about the specific html element type. While you could create most elements as div tags, it is best to use semantic HTML, so that screen readers are able to correctly interpret elements of the page. For example, use the header tag instead of the div tag. Not only is this helpful for individuals using assistive technologies but also conveys meaning to search engines, so they know which sections are more important than others. 

## Outcomes

Here are some highlights of the adjustments I made to the code to create an accessible, opitmized SEO site with semantic HTML and CSS that follows industry best preactices:
 - Added a concise page title.
 - Added alt attributes to all images.
 - Added comments in both the HTML doc and CSS stylesheet.
 - Removed and defined various div tags throughout, including:
    - header, nav, sections and footer.
- Corrected the Search Engine Optimization anchor link.
- Consolidated CSS selectors and properties - greatly reducing the number of declarations on the CSS stylesheet - from 200 lines to 142. (See screenshoots below)
    - Created new .service class to replace seperate classes for search-engine-optimization, online-reputation-management, and social-media-marketing.
    - created new .benefit class to replace seperate classes for benefit-lead, benfit-brand, and benefit-cost.

By refactoring the code for Horiseon's website, I have ensured that the user experience for all users will be a positive interaction.

 ## Screenshots

![HTML code side by side #1](/assets/images/code-screenshot-1.png)

![HTML code side by side #2](/assets/images/code-screenshot-2.png)

![CSS code side by side #1](/assets/images/CSS-screenshot-1.png)

![CSS code side by side #2](/assets/images/CSS-screenshot-2.png)

![CSS code side by side #3](/assets/images/CSS-screenshot-3.png)

## Website

To view final site, open: 
[https://vpratnicki.github.io/module-1-challenge/](https://vpratnicki.github.io/module-1-challenge/)
