# Code Refactor Starter Code

## Things to do:
- add/fix semantic HTML elements
- logical flow to HTML elements; structure correct
- √ image elements have alt attributes 
- √ heading attributes fall in sequential order 
- √ title elements concise and descriptive



## What I've changed so far

### Overall Appearance
1. Proper indentation 
2. Added title elements (to HTML and CSS)
3. Changed head title to one more reflective of website
4. Grouped sections together

### Navigation
- header tag instead of div in HTML; "header" instead of ".header" in CSS
- linked nav header title to homepage (or should I do the "/" and be linked to the index?)
- nav tag instead of div
- linked seo to its proper id

### Content
- sections instead of div
- added id to link SEO with navigation
- alt text to images; images are decorative but also worth explaining

### Benefits
- alt text to images; since images are purely decorative just used alt=""

### CSS style sheet
- font-famiy for ".benefits", .search-engine-optimization, .online-reputation-management, and .social-media-marketing were all the same so updated .body to hold the font-family element to condense code
- font color throughout was mostly all white; added color: "ffffff" to body, took it off of others (Just not header and had to adjust footer color)
- started utility class section 
<!--still working on -->
- seo, orm, and smm styles are all the same; consolidated them into one style to clean repeat code (NOT DONE YET!)


#### come back to look at:
- when browser changes sizes, text doesn't always fit in its boxes (nav doesn't, SEO, etc content falls out of box)
    - noted in Instructions as future learning how to fix
- alt text for hero bg?
- header nav CSS still contains font-family that is same as body; when tried to change it and include with body it changed font size
    
