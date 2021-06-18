# Making Horiseon More Accessible 

More people than ever rely on the internet to gain knowledge, find inspiration and connect with others. As it becomes a more basic necessity in 2021, it is essential that the Web is accessible to everyone. This project had two main focuses: refactor the HTML to create a more accessible experience for the user, and consolidate the code to leave it better than it was found. 


## It's Just Semantics - Why Change?

One of our main jobs as developers is ensure that our users can actually *use* our work. Why put in the effort of debugging, getting stuck, trying again etc, if the individuals who want to use it ... can't? The basis of this project was to expand the accessibility of the webpage using Semantic HTML tags to break the code into smaller sections. This makes it easier and more accessible for individuals who use screen-readers or other applications to use the Web. 

Additionaly, Semantic HTML improves the webpages SEO (Search Engine Optimization) by breaking the webpage down into more definable sections. This allows the browser to better interpret the content inside and display more accurate information to a search, therefore boosting our user interaction. A win win. 

## Examples of Changes Made

In using Semantic HTML, my goal was to preserve the appearance and format of the webpage but optimize the accessibility and SEO. The first step was separating the page into more specific sections instead of only `div` elements. I added `header` , `nav` , `main` , `section` and `aside` tags to help specify each part of the webpage. 

The `header` element started like this: 

```
<div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>...</li>
            </ul>
        </div>
    </div>

```

And changed to this via Semantic HTML elements:

```
<header class="header"> 
        <h1>Hori<span class="seo">seo</span>n</h1>
            <nav> 
                <ul>
                    <li>...</li>
                </ul>
            </nav>
    </header> 

```

## Fully Optimized Webpage! ![screen capture of website] (images/screen_capture.png)
