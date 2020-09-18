Horiseon Code Refactoring

Cory J. Quirk
17 September 2020

For the code refactor project, I was given the task of reducing the Horiseon web page's redundant code down to less lines while maintaining the exact same visual look. To do this, I consolidated multiple CSS classes that provided the same visual attributes but could be combined to be used multiple times. I brought the CSS code down from 200 lines to 130 lines. 

I created a new class in CSS called search-online-social that combined these three classes into one class: search-engine-optimization, online-reputation-management, and social-media-marketing. The same applied for the h2 and img classes for these three sections.

My HTML code went from 82 to 122 lines. This is because I took to reorganizing the HTML to make it easier for me to read and work with. This involved hitting the return key and the tab key to get my code organized in a way that seemed more logical to me, and in a way that visually represented how the HTML elements were nested within each other. I introduced semantic tags for the header and footer to separate them from the body in my HTML file.

The code had a few mistakes to be remedied as well, such as missing alt tags for images, the header missing a website title, and the old code using <img></img> instead of having a self closing tag. The link at the top for the "Search Engine Optimization" was broken, but this was a simple fix as the other two similarily styled links were working.

Next time I could have done a better job organizing the code in my CSS file. I spent about a half hour toying with a header labelled h2, befuddled as to why it the margins wouldn't adjust as I expected, only to find that I had a duplicate of another h2 tag hiding at the bottom of my code that was conflicting with the first one I was editing. I discovered this when using the ctrl-f to take inventory of all of my margin proerties being used.

I found the benefits section to be the most difficult section to work with. However, after some trial and error, I was able to consolidate all the benefit-xxx/img/h3 classes into just three (benefits, benefits-img, and h4).

Next time I would reduce my use of the ctrl-/ "note out" function, because it caused a lot of extra clutter that made my CSS code harder to read. Next time I think it will be more helpful to keep an eye on my active code instead of the leftover junk getting in the way. I had a much easier time organizing my HTML file into an easy to read and follow structure compared to my CSS file.

I want to thank my classmates, my TAs, and my instructor to help me develop my understanding in refactoring HTML and CSS code to help meet accessibility standards.

--- --- --- --- ---
cq change log
-fixed link for Search Engine Optimization at the top so that it moves you down to that section
-changed website title from "website" to "Horiseon"
-hit the return key many times to make code easier to read
-added semantic tags for header and footer, and moved hero out of body into header
-consolidated CSS for .benefit-lead, .benefit-brand, .benefit-cost, .benefit-lead h3, .benefit-brand h3, and .benefit-cost h3 into h3
-consolidated CSS for 3 benefits img classes into one class .benefits img
-created .benefits p to add a bottom-margin
-consolidated CSS classes for .search-engine-optimization, .online-reputation-management, and .social-media-marketing plus their respective img and h2 classes into three classes (normal, img, and h2)
-deleted an </img> tag because <img/> is a self closing tag
-in CSS moved font size under p to body, deleted p
-changed .footer h2 to h4
-created h3 for benefits headers