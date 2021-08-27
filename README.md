# Search_Engine_Accessibility_Standards

**User Story**

As a Marketing Agency 
------
I Want  : my website codebase to follow accessibility standards
------
So that : my own site is optimized for search engines
------

**Goal**

To refacor the existing source code to make it : More Accessible
                                               : More Cleaner


**Acceptance Criteria**

The Given existing code base meet the required goal when : 

*(1) There are semantic HTML elements present in html page.*

It's considered done 
WHEN : <div class="header"> is put inside a <header> element.
WHEN : <div class="header"> is replaced with a <nav> bar.
WHEN : <div class="benefits"> is put inside <aside> element.
WHEN : <div class="hero">, <div class="content">, and 
       <aside> are put inside <main> element.
WHEN : <div class="footer"> is put inside <footer> tag and class 
       name is removed.

*(2) HTML elements follow a logical structure independent of styling and positioning.*

It's considered done
WHEN : There is no style attribute applied in html page

*(3) All the icons and image have accessible alt attribute.*

It's considered done
WHEN : all the <img> tags in index.html have a 'alt' value in it.

*(4) Heading attributes fall in sequential order.*

*(5) Title element consist of concise and descriptive title.*

*(6) All the anchor <a> tags in navbar <nav> are working properly.*

It's considered done
WHEN : <div class="search-engine-optimization"> has also an id 
       of "search-engine-optimization".

*(7) Application's CSS selectors and properties are consolidated and organized to follow semantic structure.*

It's considered done
WHEN : selector - .header h1 .seo {} 
       is replaced with - span {} 

WHEN : class selector  .header {}
       is replaced with - element selector header {}

WHEN : .header div ul {} is removed.

WHEN : class selector .benefits {} is replaced with element 
      selector aside{}

WHEN : .benefit-lead {}, .benefit-brand {}, .benefit-cost {} are 
       removed and clubbed together in .benefits div {}

WHEN : .benefit-lead h3 {}, .benefit-brand h3 {}, .benefit-cost h3
       {} are removed and clubbed together in .benefits h3 {}.

WHEN :  .benefit-lead img {}, .benefit-brand img {}, .benefit-cost 
         img {} are removed and clubbed together in .benefits img {}

WHEN : .search-engine-optimization {}, online-reputation-management 
        {}, .social-media-marketing {} are removed and clubbed together in .content div {}.

WHEN : .search-engine-optimization img {}, .online-reputation-
        management img {}, .social-media-marketing img {} are 
        removed and clubbed together in .content img {}.

WHEN : .search-engine-optimization h2 {}, .online-reputation-
        management h2 {}, .social-media-marketing h2 {} are 
        removed and clubbed together in .content h2 {}.

WHEN : class selector .footer {} is replaced with element selector 
       footer {}.

WHEN : class selector .footer h2 {} is replaced with element 
       selector footer h2 {}.

*(8) Application's CSS file is properly commented.*
It's considered done
WHEN : there is a short descriptive comment in style.css for 
       each selector.


**Screen-shot for deployed application**

1. ./Application-Screenshots/Screenshot-1.png
2. ./Application-Screenshots/Screenshot-2.png
3. ./Application-Screenshots/Screenshot-3.png
