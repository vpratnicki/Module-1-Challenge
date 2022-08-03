# Code Refactor Starter Code

## Table of Contents

* [Project Description](#project-description)
    * [Why is Web Accessibility Important](#why-is-web-accessibilty-important)
    * [Semantic HTML](#semantic-html)
* [Outcomes](#outcomes)
* [Screenshots](#screenshots)
* [Website](#website)


## Project Description

For this project, I worked with a sample comapny, Horiseon and took their exisiting code and refactored it to ensure the site is accessible and optimized for SEO. In addition to making the code accessible, I also improved  the code by:

1. implementing semantic HTML, 
2. consolidating CSS selectors and properties, and
3. adding comments to the HTML document and CSS stylesheet.

### Why is Web Accessibilty Important

**Web Accessibility helps everyone!** Implementing web accessibility standards not only helps individuals using assistive technologies, such as screen readers, but all users visiting your site. For example, adding alt attributes to images is necessary in order for screen readers to be able to describe the image, but is it also helpful if the image does not load correctly. Another example is by implementing a color scheme with contrasting colors helps users with visual impairments, but is also helpful for other users without such impairment. 

### Semantic HTML

The use of semantic HTML is important for SEO and web accessibility. This is because is a way to provide context to the screen reader about the specific html element type. While you could create most element as div tags, it is best to use semantic HTML, so that screen readers are able to correctly interpret elements of the page. For example, use header tag (<header>) instead of div (<div>). No only is this helpful for individuals using assistive technologies but also conveys means to search engines, so they know which sections are more important than other. 

## Outcomes

In order to create an accessible, opitmized SEO site with semantic HTML and CSS that follows industry best preactices. Here are some highloghts of the adjustments I made to the code:
 - Added a concise page title
 - Added alt attributes to all images
 - Added comments in both the HTML doc and CSS stylesheet
 - Removed and defined various <div> tags throughout, including:
    - header, nav, sections and footer
- Corrected the Search Engine Optimization anchor link
- Consolidating CSS selectors and properties - greatly reducing the number of decloarations on the CSS stylesheet. (See screenshoots below)
    - Original CSS 200 lines of code, I conslidated this to 142.
    - Created new class call service so that there are no longer 3 seperate classes for search-engine-optimization, online-reputation-management, and social-media-marketing.
    - created new class called benefit to replace benefit-lead, benfit-brand, and benefit-cost.

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
