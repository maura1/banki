# BANKI: All the questions to prep for interviews

- Any questions on this list are fair game for technical interviews.
- Resources where you can find most answers are at the end.
- Original list courtesy of https://leonnoel.com/100devs/

---

## Table of Contents

1. [Behaviorial](#behavioral)
2. [Technical](#technical-questions)
    - [HTML](#html)
    - [CSS](#css)
    - [Javascript](#javascript)
    - [Javascript General](#javascript-general)
    - [Node](#node)
    - [CS Theory](#cs-theory)
3. [Questions to ask your interviewer](#questions-to-ask-your-interviewer)
4. [Whiteboard](#whiteboard)
5. [Resources](#resources)

---

## Behavioral

Most of the behavioral questions should be answered in the CAR format. At least three sentences for each question (one for cause, one for action and one for result). When answering begin with "At my last opportunity..." or "At my last company". Don't sell yourself out and say "bootcamp" or "school".

### CAR

- **Cause**
  - Why did you need to take action?
- **Action**
  - Steps you took so solve problem
  - Be positive
  - Don't be humble
- **Result**
  - How are you better?

### Questions

- [ ] Give me an example of a project or initiative that you started on your own. What prompted you to get started?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a time you had to work on several projects at once. How did you handle this?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you felt you had not communicated well enough. What did you do? How did you handle it?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about when you had to deal with conflict within your team. How was the conflict solved? How did you handle that? How would you deal with it now?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give me an example of a time you had to take a creative and unusual approach to solve coding problem. How did this idea come to your mind? Why do you think it was unusual?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you worked diligently on a project and it did not produce the desired results. Why didn't you get the desired results? What did you learn from the experience?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Give an example of an important project goal you reached and how you achieved it.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation in which you experienced difficulty in getting others to accept your ideas? What was your approach? How did this work? Were you able to successfully persuade someone to see things your way
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you were responsible for project planning. Did everything go according to your plan? If not, then why and what kind of counteractions did you have to take?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a situation when you made a mistake at work. What happened exactly and how did you deal with it? What steps did you take to improve the situation?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about a time when you worked with someone who was not completing his or her share of the work. How did you handle the situation? Did you discuss your concern with your coworker? With your manager? If yes, how did your coworker respond to your concern? What was your manager's response?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Describe a situation when you worked effectively under pressure. How did you feel when working under pressure? What was going on, and how did you get through it?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about yourself.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about your experience at 100Devs.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you know about our company?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why do you want to work for us?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Why are you interested in this opportunity?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me about your dream job??? What do you really want to do with your career?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Tell me a time when you failed.
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What do you read on a regular basis?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] What's some critical feedback you've gotten recently?
  - **Cause:**
  - **Action:**
  - **Result:**
- [ ] Do you have any questions?
  - **Cause:**
  - **Action:**
  - **Result:**

## Technical Questions

Most of the technical questions should have a three sentence response in the EUE format:

- **Explanation**
- **Use**
- **Example**

### HTML

- [ ] What does a doctype do?
  - **Explanation:**The DOCTYPE declaration is an instruction to the web browser about what version of HTML the page is   written in. 
  - **Use:** This ensures that the web page is parsed the same way by different web browsers. It must be the very first line of code in an HTML document(aside from comments, which can go before if needed).
  - **Example:** ##This is the doctype syntax for HTML5 and beyond: `<DOCTYPE html>`
  - **Source:** https//www.freecodecamp.org

- [ ] How do you serve a page with content in multiple languages?
  - **Explanation:** By setting the lang attributes on various elements within the page.
  - **Use:** The lang attribute can be defined anywhere in the document  eg: html, p, li..
  - **Example:** The whole site for example can be set in english by setting the `<html lang="en">`
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/lang

- [ ] What kinds of things must you be wary of when designing or developing for multilingual sites?
  - **Explanation:**Some nuances to pay attention to including:
    - Including the `lang` attribute
    - Allowing users to change the language
    - Minimize text in raster based images
    - Text overflow when translated
    - How colors are perceived
    - Date and currency formats
    - Language reading direction
    - Don't concatenate translated strings
  - **Use:**Respecting all users that user your site
  - **Example:**Colors are percieved differently accross languages and cultures.
  - **Source:**https://www.frontendinterviewhandbook.com/html-questions

- [ ] What are `data-` attributes good for?
  - **Explanation:** To store custom private data to the page or application.
  - **Use:** They used to be used to store data in the DOM, but that is generally discouraged now, as the user could
      modify the data attributes easily by using the inspect element in the browser.
  - **Example:** A valid reason for using data attributes, is to add a hook for end to end testing fromeworks such 
    as Selenium and Capybara without having to create meaningless classes or ID attributes.
  - **Source:**https://www.frontendinterviewhandbook.com/html-questions

- [ ] Consider HTML5 as an open web platform. What are the building blocks of HTML5?
  - **Explanation:**
      - Semantics - Allowing you to describe more precisely what your content is.
      - Connectivity - Allowing you to communicate with the server in new and innovative ways.
      - Offline and storage - Allowing webpages to store data on the client-side locally and operate offline more          efficiently.
      - Multimedia - Making video and audio first-class citizens in the Open Web.
      - 2D/3D graphics and effects - Allowing a much more diverse range of presentation options.
      - Performance and integration - Providing greater speed optimization and better usage of computer hardware.
      - Device access - Allowing for the usage of various input and output devices.
      - Styling - Letting authors write more sophisticated themes  
  - **Source:**https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5

- [ ] Describe the difference between a cookie, sessionStorage and localStorage.
  - **Explanation:**Cookies can be initiated by the server, have a manually set expiration date, a small file size and   are sent to the server with a HTTP request.
  Local and session are both initiated by the client, are a relatively large file and are not sent to the server. 
  Local storage persists forever until cleared manualy. 
  Session storage is cleared when the tab is closed
  - **Use:** They are all used for client side storage of strings in key-value pairs.
  - **Source:**https://www.frontendinterviewhandbook.com/html-questions

- [ ] Describe the difference between `<script>, <script async> and <script defer>`.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Why is it generally a good idea to position CSS `<link>`s within `<head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
  - **Explanation:**
  `<script>`HTML parsing is blocked, script is fetched and executed immediately
  `<script async>`script is fetched in paralled to HTML parsing and executed as soon as it is available.
  `<script defer>`script fetched in paralled ot HTML parsing and executed when the page has finished parsing.
  - **Use:**
  - Use `async`when the script is independent of any other scripts on the page
  - Use `defer`when you need to ensure that the HTML is fully parsed before executing.
  - **Example:**
  - `async`could be used for analytical scripts.
  - A defered script should not contain `document.write`
    ##The async and defer attributes are ignored for scripts that have no `src`attributes.
  - **Source:**https://www.frontendinterviewhandbook.com/html-questions

- [ ] What is progressive rendering?
  - **Explanation:** Techniques used to imporve performance of a web page to render content for display as quickly as possible.
  - **Use:** Imporving perceived loadtime.
  - **Example:** Lazy loading of images, prioritizing visible content ( or above-the-fold rendering) and async HTML fragments.
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions

- [ ] Why you would use a `srcset` attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
  - **Explanation:** It is used when you want to serve different images to users depending on their device display width - 
  - **Use:** Serve higher quality images to devices with retina display enhances the  user experience while serving lower resolution images to low-end devices increse performance and decrease data wastage(because serving a larger image will not have any visible difference)
  - **Example:** `<img srcset="small.jpg 500w, medium.jpg 1000w, large.jpg 2000w" src="..." alt="">`
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions

- [ ] Have you used different HTML templating languages before?
  - **Explanation:** EJS ans Handlebars They provide similar functionality of escaping content and helpful filters for manipulating the data to be displayed. Most templating engines will also allow you to inject your own filters in the event you need custom processing before display.
  - **Use:** When using dynamic data.
  - **Example:**
  - **Source:** https://www.frontendinterviewhandbook.com/html-questions

### CSS

- [ ] What is CSS selector specificity and how does it work?
  - **Explanation:** The means by which browsers decide which CSS property values are the most relevant to an element and, therefore, will be applied.
  - **Use:** Specificity is a weight that is applied to a given CSS declaration, determined by the number of each selector type in the matching selector.
  - **Example:** Id's count for 100, classes for 10 and tags 1, therefore a selector of `#id .class tag` would have 111 points as
  - **Source:** https://www.sitepoint.com/css-selectors-specificity/

- [ ] What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
  - **Explanation:**  "Normalize" alters the default styles of various browsers to match each other. "Reset" will remove the browsers default styles so you are starting from scratch.
  - **Use:** Normalizing preserves useful default styles rather than "unstyling" everything. It also corrects bugs for common browser dependencies.
   The main purpose of applying either "normalize" or "reset" is to try and make websites visually consistent across different browsers. A mix of both can be used, normalize to keep it conscise and then add some elements like anchors and headers with a reset.
  - **Example:**
  Normalize:
  

h1{
  font-size:2em
  margin : 1em;
}
 

Reset:

``` 
html, body, div, span, ..., audio, video {  
   margin: 0;  
   padding: 0;  
   border: 0;  
   font-size: 100%;  
   font: inherit;  
   vertical-align: baseline; 
}
```
   **Source:**https://elad.medium.com/normalize-css-or-css-reset-9d75175c5d1e

- [ ] Describe floats and how they work.
  - **Explanation:** Float is a CSS positioning property where the element that is floated will be removed from the flow of the page and affect the elements around it. A parent element will collapse to zero height if it contains only floated elements, to fix this it was common to use a `.clearfix` hack.
  The .clearfix hack uses a clever CSS pseudo selector (:after) to clear floats. Rather than setting the overflow on the parent, you apply an additional class clearfix to it. Then apply this CSS:
```
.clearfix:after {
  content: ' ';
  visibility: hidden;
  display: block;
  height: 0;
  clear: both;
}
```
Alternatively, give overflow: auto or overflow: hidden property to the parent element which will establish a new block formatting context inside the children and it will expand to contain its children.

  - **Use:** It was used prior to flex and grid to layout pages in a more flexible manner.
  - **Example:** To position three elemetns of equal width equally accross the page you could use float left  and give them widths of 33.3% .
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Describe z-index and how stacking context is formed.
  - **Explanation:**The z-index property in CSS controls the vertical stacking order of overlapping HTML elements. z-index only affects elements that have a position value which is not static.
  Elements with a higher index will be placed on top of elements with a lower index.

  Without any z-index value, elements stack in the order that they appear in the DOM (the lowest one down at the same hierarchy level appears on top). Elements with non-static positioning (and their children) will always appear on top of elements with default static positioning, regardless of HTML hierarchy.
  - **Use:**To determind in which order elements will be displayed on top of each order.
  - **Example:**
  /* Default value if not specified */
z-index: auto;

/* Integer values */
z-index: 1;
z-index: 100;
z-index: 9999;
z-index: -1;

/* Global values */
z-index: inherit;
z-index: initial;
z-index: unset;
  - **Source:** https://www.freecodecamp.org/

- [ ] Describe BFC (Block Formatting Context) and how it works.
  - **Explanation:**
  It is part of the visual CSS rendering of a web page in which block boxes are laid out.
  Floats, absolutely positioned elements, inline-blocks, table-cells, table-captions, and elements with overflow other than visible (except when that value has been propagated to the viewport) establish new block formatting contexts.

  A BFC is an HTML box that satisfies at least one of the following conditions:
    - The value of float is not none.
    - The value of position is neither static nor relative.
    - The value of display is table-cell, table-caption, inline-block, flex, or inline-flex, grid, or inline-grid.
    - The value of overflow is not visible.
  - **Use:**Knowing how to establish a block formatting context is important, because without doing so, the containing box will not contain floated children
  - **Example:** Without forming a BFC you could have content of a float that is taller than the content alongside it. The border of the parent element could then "cut-through" the floated box.
  - **Source:**https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Block_formatting_context

- [ ] What are the various clearing techniques and which is appropriate for what context?
  - **Explanation:**  
  - Empty div method - <div style="clear:both;"></div>.
  - Clearfix method - Refer to the .clearfix class above.
  - Overflow: auto or overflow: hidden method - Parent will establish a new block formatting context and expand to      contains its floated children.    
  - **Use:** `.clearfix` utility class is probably the best method to use in general as it doesn't take long to construct and doesn't suffer from clipping issues like the overflow methods.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Explain CSS sprites, and how you would implement them on a page or site.
  - **Explanation:** CSS Sprites are a means of combining multiple images into a single image file for use on a website, to help with performance.
  - **Use:** Browsers limit the number of concurrent requests a site can make so leading several images with a single HTTP request helps increase page load speed.
  - **Example:**An example would be combining press logo's for Wired, NY Times and The Washington Post into a single image file. Then on the site, with CSS, placing the file three times and moving/cropping it to display the applicable logo.
  - **Source:**https://css-tricks.com/css-sprites/

- [ ] How would you approach fixing browser-specific styling issues?
  - **Explanation:**
  - After identifying the issue and the offending browser, use a separate style sheet that only loads when that specific  browser is being used. This technique requires server-side rendering though.
  - Use libraries like Bootstrap that already handles these styling issues for you.
  - Use autoprefixer to automatically add vendor prefixes to your code.
  - Use Reset CSS or Normalize.css.( a combination of both can be used)
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

- [ ] How do you serve your pages for feature-constrained browsers? What techniques/processes do you use?
  - **Explanation:**
  - Graceful degradation - The practice of building an application for modern browsers while ensuring it remains functional in older browsers.
  - Progressive enhancement - The practice of building an application for a base level of user experience, but adding functional enhancements when a browser supports it.
  - **Use:**checking [caniuse.com](https://caniuse.com/)  to know what if functional in each browser and using vendor prefixs and polyfills if required.
  - **Example:**Replacing `<div>` with  more semantically appropriate tags like `<section> <aside> <article> <header> <footer>
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

- [ ] What are the different ways to visually hide content (and make it available only for screen readers)?
  - **Explanation:**
     - Make the element have a size of zero `width: 0; height: 0`
    - Absolute position off screen `position: absolute; left: -99999px`
    - Text indent off screen if within block element `text-indent: -9999px`
    - aria-label which will read the string given to the attribute.
  - **Use:** Using absolute positioning of an element off screen covers most scenarios.
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Have you ever used a grid system, and if so, what do you prefer?
  - **Explanation:**Yes, it can be imlemented easily and helps to align, structure, and shape design
  - **Use:** To eatablish a set of guidelines for how should be positioned within a layout.
  - **Source:**https://css-tricks.com/snippets/css/complete-guide-grid/

- [ ] Have you used or implemented media queries or mobile specific layouts/CSS?
  - **Explanation:**Yes, frequently.
  - **Use:** On every website and I mostly build mobile first. The breakpoints and media queries are then used to   convert the layout from mobile to desktop.
  - **Example:** Sometimes elements that are positioned horizontally when shown on a desktop may need to be stacked when  displayed on a mobile device to make them more readable.
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Are you familiar with styling SVG?
  - **Explanation:** Yes, svg images can be printed with high quality at any resolution, they are zoomable.
     Most importantly, they don't lose any quality if they are zoomed or reqized.
  - **Use:**The infinite scalability of SVG is its greatest asset, so they can be easily used as a background image.
  - **Example:**Often used as icons.
  - **Source:**https://css-tricks.com

- [ ] Can you give an example of an `@media` property other than screen?
  - **Explanation:**
  Yes, there are four types of @media properties (including screen):
  - all - for all media type devices
  - print - for printers
  - speech - for screenreaders that "reads" the page out loud
  - screen - for computer screens, tablets, smart-phones etc.
  - **Use:**
  - **Example:**
  Here is an example of print media type's usage:

@media print {
  body {
    color: black;
  }
}
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions

- [ ] What are some of the "gotchas" for writing efficient CSS?
  - **Explanation:**
  - Browsers match selectors from rightmost (key selector) to left. The shorter the length of the chain the faster the browser can find a match. Avoid using tag and universal selectors for your key selector.
  
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/

- [ ] What are the advantages/disadvantages of using CSS preprocessors?
  - **Explanation:**
   Advantages:
   - CSS easier to maintain.
   - Easy to write nested selectors.
   - Variables can be used for consistent theming. Can share theme files across different projects.
   - Mixins can be used for repeated styles.
   - Code can be split into different files.

 Disadvantages:

  - Additional tooling is required.
  - No possible to use the most current features of standard CSS. 
  - **Source:** https://www.frontendinterviewhandbook.com/

- [ ] Describe what you like and dislike about the CSS preprocessors you have used.
  - **Explanation:**Being able to split files and nest selectors is the most useful, it keeps the code more organized. A couple of downsides are that debugging is a little more difficult and having to wait for compilation.
  
  - **Source:**https://www.freecodecamp.org/news/css-preprocessors/

- [ ] How would you implement a web design comp that uses non-standard fonts?
  - **Explanation:** Use @font-face and define font-family for different font-weights. 
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Explain how a browser determines what elements match a CSS selector.
  - **Explanation:** Browsers match selectors from rightmost (key selector) to left.
  - **Example:**For example with this selector `p span`, browsers firstly find all the `<span>` elements and traverse up its parent all the way up to the root to find the `<p>` element. For a particular `<span>`, as soon as it finds a `<p>`, it knows that the `<span>` matches and can stop its matchin
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Describe pseudo-elements and discuss what they are used for.
  - **Explanation:** A CSS pseudo-element is a keyword added to a selector that lets you style a specific part of the selected element(s)
  - **Use:**
  - **Example:****::first-line can be used to change the font of the first line of a paragraph
  - **Source:****https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements

- [ ] Explain your understanding of the box model and how you would tell the browser, through CSS, to render your layout in different box models.
  - **Explanation:**The CSS box model describes the rectangular boxes that are generated for elements in the document tree and laid out according to the visual formatting model. Each box has a content area and optional surrounding padding, border, and margin areas.
  - **Use:**The standard box model calculates box size by taking a specified `height` and `width`, then adding the padding and border. However to change to the alternative box model you would set `box-sizing: border-box` which allows you to set the box size with `height` and `width`.
  - **Example:**
  - **Source:** https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#what_is_the_css_box_model

- [ ] What does `* { box-sizing: border-box; }` do? What are its advantages?
  - **Explanation:** It allows you to specify the actual width and height of a box using the `width` and `height` properties. This allows you to input true sizes and not have to do any math to take padding and borders into account
  - **Use:**
  - **Example:**
  - **Source:** https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model#the_alternative_css_box_model

- [ ] What is the CSS `display` property and can you give a few examples of its use?
  - **Explanation:**  The display CSS property sets whether an element is treated as a block or inline element and the layout used for its children, such as flow layout, grid or flex.
  - **Use:**
  - **Example:** `display: block` would make the element consume the whole line width. `display: grid` would allow you to layout children in a grid system. If you wanted three columns you could pair it with something like `grid-template-columns: 1fr 1fr 1fr`
  - **Source:** https://developer.mozilla.org/en-US/docs/Web/CSS/display

- [ ] What's the difference between `inline` and `inline-block`?
  - **Explanation:**- `inline`
      - CANNOT specify width and height
      - Can only set margin and padding for the sides, not top and bottom.
    - `inline-block`
      - CAN specify width and height
      - Can set margin and padding on all sides
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/
 

- [ ] What's the difference between a `relative`, `fixed`, `absolute` and `static` positioned element?
  - **Explanation:**
    - Relative - Position is relative to it's original static position. Original space on the page is preserved.
    - Fixed - Element removed from page flow and placed in spot relative to viewport. It won't move when scrolled.
    - Absolute - Element removed from page flow and positioned relative to it closest "positioned" ancestor. Original space on the page is not preserved
    - Static - The default position. `top`, `right`, `bottom`, `left` and `z-index` properties do not apply.
  - **Use:**
  - **Example:**
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/

- [ ] What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
  - **Explanation:**Bootstrap - Slow release cycle. Bootstrap 4 has been in alpha for almost 2 years. Add a spinner button component, as it is widely used.
  - **Use:**
  - **Example:**
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Have you played around with the new CSS Flexbox or Grid specs?
  - **Explanation:**Yes. Flexbox is mainly meant for 1-dimensional layouts while Grid is meant for 2-dimensional layouts.

Flexbox solves many common problems in CSS, such as vertical centering of elements within a container, sticky footer, etc. Bootstrap and Bulma are based on Flexbox, and it is probably the recommended way to create layouts these days. Have tried Flexbox before but ran into some browser incompatibility issues (Safari) in using flex-grow, and I had to rewrite my code using inline-blocks and math to calculate the widths in percentages, it wasn't a nice experience.

Grid is by far the most intuitive approach for creating grid-based layouts (it better be!) but browser support is not wide at the moment.
  - **Use:**
  - **Example:**
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
  - **Explanation:**
      Note that these two 2 approaches are not exclusive.

Making a website responsive means that some elements will respond by adapting its size or other functionality according to the device's screen size, typically the viewport width, through CSS media queries, for example, making the font size smaller on smaller devices.

@media (min-width: 601px) {
  .my-class {
    font-size: 24px;
  }
}

@media (max-width: 600px) {
  .my-class {
    font-size: 12px;
  }
}
A mobile-first strategy is also responsive, however it agrees we should default and define all the styles for mobile devices, and only add specific responsive rules to other devices later. Following the previous example:

.my-class {
  font-size: 12px;
}

@media (min-width: 600px) {
  .my-class {
    font-size: 24px;
  }
}

A mobile-first strategy has 2 main advantages:

It's more performant on mobile devices, since all the rules applied for them don't have to be validated against any media queries.
It forces to write cleaner code in respect to responsive CSS rules.
  - **Use:**
  - **Example:**
  - **Source:** https://www.frontendinterviewhandbook.com/css-questions/

- [ ] How is responsive design different from adaptive design?
  - **Explanation:**
  Both responsive and adaptive design attempt to optimize the user experience across different devices, adjusting for different viewport sizes, resolutions, usage contexts, control mechanisms, and so on.

Responsive design works on the principle of flexibility - a single fluid website that can look good on any device. Responsive websites use media queries, flexible grids, and responsive images to create a user experience that flexes and changes based on a multitude of factors. Like a single ball growing or shrinking to fit through several different hoops.

Adaptive design is more like the modern definition of progressive enhancement. Instead of one flexible design, adaptive design detects the device and other features and then provides the appropriate feature and layout based on a predefined set of viewport sizes and other characteristics. The site detects the type of device used and delivers the pre-set layout for that device. Instead of a single ball going through several different-sized hoops, you'd have several different balls to use depending on the hoop size.
  - **Use:**Both have these methods have some issues that need to be weighed:

- Responsive design can be quite challenging, as you're essentially using a single albeit responsive layout to fit all situations. How to set the media query breakpoints is one such challenge. Do you use standardized breakpoint values? Or, do you use breakpoints that make sense to your particular layout? What if that layout changes?
- Adaptive design generally requires user agent sniffing, or DPI detection, etc., all of which can prove unreliable.
  - **Example:**
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Have you ever worked with retina graphics? If so, when and what techniques did you use?
  - **Explanation:**Retina is just a marketing term to refer to high resolution screens with a pixel ratio bigger than 1. The key thing to know is that using a pixel ratio means these displays are emulating a lower resolution screen in order to show elements with the same size. Nowadays we consider all mobile devices retina defacto displays.

Browsers by default render DOM elements according to the device resolution, except for images.

In order to have crisp, good-looking graphics that make the best of retina displays we need to use high resolution images whenever possible. However using always the highest resolution images will have an impact on performance as more bytes will need to be sent over the wire.

To overcome this problem, we can use responsive images, as specified in HTML5. It requires making available different resolution files of the same image to the browser and let it decide which image is best, using the html attribute srcset and optionally sizes, for instance:
```<div responsive-background-image>
  <img
    src="/images/test-1600.jpg"
    sizes="
      (min-width: 768px) 50vw,
      (min-width: 1024px) 66vw,
      100vw"
    srcset="
      /images/test-400.jpg   400w,
      /images/test-800.jpg   800w,
      /images/test-1200.jpg 1200w
    "
  />
</div>

```
It is important to note that browsers which don't support HTML5's srcset (i.e. IE11) will ignore it and use src instead. If we really need to support IE11 and we want to provide this feature for performance reasons, we can use a JavaScript polyfill, e.g. Picturefill (link in the references).

For icons, I would also opt to use SVGs and icon fonts where possible, as they render very crisply regardless of resolution.
  - **Use:**
  - **Example:**
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/

- [ ] Is there any reason you'd want to use `translate()` instead of `absolute` positioning, or vice-versa? And why?
  - **Explanation:**translate() is a value of CSS transform. Changing transform or opacity does not trigger browser reflow or repaint but does trigger compositions; whereas changing the absolute positioning triggers reflow. transform causes the browser to create a GPU layer for the element but changing absolute positioning properties uses the CPU. Hence translate() is more efficient and will result in shorter paint times for smoother animations.

When using translate(), the element still occupies its original space (sort of like position: relative), unlike in changing the absolute positioning.
  - **Use:**
  - **Example:**
  - **Source:**https://www.frontendinterviewhandbook.com/css-questions/

### Javascript

- [ ] Explain event delegation
  - **Explanation:** It is used to handle events efficiently as it allowy you to avoid adding event listners to specific nodes, instead the event listener is added to one parent.The event listner analyzes bubbled events to find a match on child elements.
  - **Use:**To reduce memory footprint as only one single handler is needed on the parent element, rather than having to attach event handlers on each descendant.
  There is also no need to unbind the handler from elements that are removed and to bind the evnet for new elements.
  - **Example:**We have a parent UL element with several child elements and something needs to happen when when each child element is clicked.
  Instead of adding a seperate event listner to each individula LI element a better solution would be to add an event listner to the parent UL element. This would be very userful if adding and removing event listners was necessary and adding or removing code in different places was required.
  To identify which child(LI)was clicked the target property would give the reference to the node clicked.

  ```const customUI = document.createElement('ul');

function responding(evt) {
    if (evt.target.nodeName === 'li')
        console.log('Responding')
}

for (var i = 1; i <= 10; i++) {
    const newElement = document.createElement('li');
    newElement.textContent = "This is line " + i;
    customUI.appendChild(newElement);
}

customUI.addEventListener('click', responding);```

  
  - **Source:**https://www.geeksforgeeks.org/event-delegation-in-javascript/
              https://davidwalsh.name/event-delegate

- [ ] Explain how `this` works in JavaScript
  - **Explanation:**`this` references an object. When inside of a constructor function or class it will reference the object on instantiation.
  - **Use:**It is used to assign properties and values to an object on instantiation
  - **Example:**
  - **Source:**https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this

- [ ] Explain how prototypal inheritance works
  - **Explanation:** In JavaScript, an object can inherit properties of another object. The object from where the properties are inherited is named protptype.All JS objects have a __proto__property with the exception of objects created with Object.create(null).
  When a property is accessed on an objet and if the property is not found on the that abject, the JS engine looks at the object's __proto__, and the __proto__'s __proto__ and so on, until it finds teh property defined on one of the __proto__'s or until it reached the end of the property chain.
  - **Use:**It solves the problem on data and logic duplication.By inheriting objects can share properties and method.
  - **Example:**
    function Parent() {
  this.name = 'Parent';
}

Parent.prototype.greet = function () {
  console.log('Hello from ' + this.name);
};

const child = Object.create(Parent.prototype);

child.cry = function () {
  console.log('waaaaaahhhh!');
};

child.cry();
// waaaaaahhhh!

child.greet();
// hello from Parent

child.constructor;
// ?? Parent() {
//   this.name = 'Parent';
// }

child.constructor.name;
// 'Parent'

- .greet is not defined on the child, so the engine goes up the prototype chain and finds .greet
off the inherited from the Parent.

-.greet is not defined on the child, so the engine goes up the prototype chain and finds .greet off the inherited from Parent.
We need to call Object.create in one of following ways for the prototype methods to be inherited:
Object.create(Parent.prototype);
Object.create(new Parent(null));
Object.create(objLiteral);
Currently, child.constructor is pointing to the Parent:

If we'd like to correct this, one option would be to do:
function Parent() {
  this.name = 'Parent';
}

Parent.prototype.greet = function () {
  console.log('Hello from ' + this.name);
};

function Child() {
  Parent.call(this);
  this.name = 'Child';
}

Child.prototype = Object.create(Parent.prototype);
Child.prototype.constructor = Child;

const child = new Child();

child.greet();
// hello from Child

child.constructor.name;
// 'Child'



  - **Source:**https://davidwalsh.name/javascript-objects
             https://www.frontendinterviewhandbook.com/javascript-questions

- [ ] What do you think of AMD vs CommonJS?
  - **Explanation:**Both implement a module system.CommonJS is synchronous while AMD(Asynchronous Module Definition)is asynchronous. 
  CommonJS is designed with server-side development in mind, while AMD with its support for asynchronous loading of modules, is more intended for browsers.AMD syntax is verbose. CommonJS is closer styles to Node style of writhing modules and there is less context switching between client side JS development
  EMS(ECMAScipt Modules) has a simpler syntas ans async nature.
  - **Use:**CommonJS has been used in node.js for a while, but the current version of node now allows the use of EMS:
  - **Source:**https://www.frontendinterviewhandbook.com/javascript-questions

- [ ] Explain why the following doesn't work as an IIFE: `function foo(){ }();`. What needs to be changed to properly make it an IIFE?
  - **Explanation:**IIFE = Immediately Invoked Function Expressions
  - The JS parser reads it as two seperate statements. First the function declaration `function foo(){}` and then a blank function call attempt `()`. The best way to fix this would be to add another set of parentheses wrapping the function declaration `(function foo(){})()`This changes it from a function declaration to a function expression.
  - **Use:**
  - **Example:**
  - **Source:**https://www.frontendinterviewhandbook.com/javascript-questions

- [ ] What's the difference between a variable that is: `null`, `undefined` or undeclared? How would you go about checking for any of these states?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a closure, and how/why would you use one?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Can you describe the main difference between a `.forEach()` loop and a `.map()` loop and why you would pick one versus the other?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What's a typical use case for anonymous functions?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] How do you organize your code? (module pattern, classical inheritance?)
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What's the difference between host objects and native objects?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is the difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What's the difference between `.call()` and `.apply()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain `Function.prototype.bind`.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] When would you use `document.write()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What's the difference between feature detection, feature inference, and using the UA string?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain Ajax in as much detail as possible.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are the advantages and disadvantages of using Ajax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain how JSONP works (and how it's not really Ajax).
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Have you ever used JavaScript templating? If so, what libraries have you used?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain "hoisting".
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Describe event bubbling.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What's the difference between an "attribute" and a "property"?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Why is extending built-in JavaScript objects not a good idea?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Difference between document `load` event and document `DOMContentLoaded` event?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is the difference between `==` and `===`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  
- [ ] Explain the same-origin policy with regards to JavaScript.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Make this work: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5] `
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Why is it called a ternary expression, what does the word "ternary" indicate?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is "use strict";? what are the advantages and disadvantages to using it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Create a for loop that iterates up to 100 while outputting "fizz" at multiples of 3, "buzz" at multiples of 5 and "fizzbuzz" at multiples of 3 and 5
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] Explain what a single page app is and how to make one SEO-friendly.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**
- [ ] What is the extent of your experience with Promises and/or their polyfills?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are the pros and cons of using Promises instead of callbacks?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What tools and techniques do you use debugging JavaScript code?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What language constructions do you use for iterating over object properties and array items?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain the difference between mutable and immutable objects.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain the difference between synchronous and asynchronous functions.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is event loop? What is the difference between call stack and task queue?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain the differences on the usage of foo between `function foo() {}` and `var foo = function() {}`
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are the differences between variables created using `let`, `var` or `const`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are the differences between ES6 class and ES5 function constructors?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What advantage is there for using the arrow syntax for a method in a constructor?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is the definition of a higher-order function?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Can you give an example for destructuring an object or an array?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Can you give an example of a curry function and why this syntax offers an advantage?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are the benefits of using spread syntax and how is it different from rest syntax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] How can you share code between files?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Why you might want to create static class members?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Javascript General

- [ ] Can you name two programming paradigms important for JavaScript app developers?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is functional programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is the difference between classical inheritance and prototypal inheritance?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are the pros and cons of functional programming vs object-oriented programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are two-way data binding and one-way data flow, and how are they different?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is asynchronous programming, and why is it important in JavaScript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### Node

- [ ] What is Node.js? Where can you use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Why use Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are the features of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] How do you update NPM to a new version in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Why is Node.js Single-threaded?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain callback in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is callback hell in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] How do you prevent/fix callback hell?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain the role of REPL in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Name the types of API functions in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are the functionalities of NPM in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is the difference between Node.js and Ajax?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are ???streams??? in Node.js? Explain the different types of streams present in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Explain chaining in Node.js.
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are Globals in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is Event-driven programming?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is Event loop in Node.js work? And How does it work?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is the purpose of `module.exports` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is the difference between Asynchronous and Non-blocking?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is Tracing in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] How will you debug an application in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Difference between `setImmediate()` and `setTimeout()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is `process.nextTick()`?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is package.json? What is it used for?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is libuv?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are some of the most popular modules of Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is `EventEmitter` in Node.js?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

### CS Theory??

- [ ] What is recursion and give an example using javascript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are types?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What are data structures?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is an algorithm?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is scope / lexical scope in javascript?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is polymorphism?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is encapsulation?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Doubly Linked List?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Queue?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Stack?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Hash Table?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Heap?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Trie?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Binary Search Tree?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Disjoint Set?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] What is a Bloom Filter?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Demonstrate Bubble Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Demonstrate Insertion Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Demonstrate Merge Sort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

- [ ] Demonstrate Quicksort and explain when you might use it?
  - **Explanation:**
  - **Use:**
  - **Example:**
  - **Source:**

## Questions to ask your interviewer

1. How does Bob???s Burgers measure the success of their engineers?
2. What challenges can an engineer come across while working at Bob???s Burgers?
3. Can you explain "thing you read on their engineering blog" and how it affects Bob???s Burgers Engineers?
4. What traits are hard to find in an engineer that Bob???s Burgers would like to have?
5. How is critique given to engineers at Bob???s Burgers?
6. Do you have any questions or concerns about my qualifications?

Here is a helpful list of other reverse interview questions: [https://github.com/viraptor/reverse-interview](https://github.com/viraptor/reverse-interview)

## Whiteboard

When talking through a whiteboard problem or a coding challenge with an interviewer you should use the PREP method. (Don't write PREP in the actual interview, but use it now while doing codewars/leetcode). Going through this will help you engage with the interviewer (and possibly burn up some time ????)

- **Parameters**
  - Inputs
  - Ask questions
    - Will it always be a number?
    - Will it ever be negative?
    - Any gotchas?
- **Returns**
  - Ask questions
    - Do you want it returned or is a console.log better?
    - Should I pass a whole array of solutions back or just a single solution?
- **Examples**
  - Show a couple black box examples, aka test cases
    - I pass in these arguments and get these results, is that correct?
  - Examples are a good idea because "you have the receipts" if the interviewer decides to change things.
- **Pseudocode**
  - Write pseudocode of each of the steps

## Resources:

- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
- [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [https://github.com/yangshun/front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook)
- [https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)
- [https://www.simplilearn.com/node-js-interview-questions-and-answers-article](https://www.simplilearn.com/node-js-interview-questions-and-answers-article)
- [https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678](https://medium.com/@vigowebs/frequently-asked-node-js-interview-questions-and-answers-b74fa1f20678)
