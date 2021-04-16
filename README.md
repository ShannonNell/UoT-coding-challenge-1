# Challenge 1: Code Refactor

This is code refactored for UoT's Coding Bootcamp challenge assignment 1. Code was given to be cleaned up, condensed, and organized.

```bash
words
oh look, more words.
Words (in) ('color')
```

```sh
git add -A
git commit -m "my message"
terminal commands
```
> these words are
> in a different box
> but not on different lines? 

- creates a list [link-name](http://google.ca)

| Plugin | README |
| ------ | ------|
| Dropbox | [link](http://google.ca) |



## Things to do:
- √ add/fix semantic HTML elements
- √ logical flow to HTML elements; structure correct
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
- condensed css styles that were duplicates

### CSS style sheet
- font-famiy for ".benefits", .search-engine-optimization, .online-reputation-management, and .social-media-marketing were all the same so updated .body to hold the font-family element to condense code
- font color throughout was mostly all white; added color: "ffffff" to body, took it off of others (Just not header and had to adjust footer color)
- started utility class section 
- seo, orm, and smm styles are all the same; consolidated them into one style to clean repeat code 
    - deleted style for: .search-engine-optimization + .img + h2
        - .online-reputation-management + .img + h2
        - .social-media-marketing + .img +h2
    - consolidated them into new class .content-info (margin, padding, height, bg color, and overflow)
        - .content-info img (took out float from img html, put in css as its own style)
            - deleted .online-reputation-management img and .social-media-marketing img --> merged into .content-info img style with the proper float
    - new utility class style for text alignment to float in .content section
<!--still working on -->


#### come back to look at:
- when browser changes sizes, text doesn't always fit in its boxes (nav doesn't, SEO, etc content falls out of box)
    - noted in Instructions as future learning how to fix
- alt text for hero bg?
- header nav CSS still contains font-family that is same as body; when tried to change it and include with body it changed font size
    
