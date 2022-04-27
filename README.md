## Title of the project
Code Refactor
## Purpose of this project
Our goal is to make this web page more comprehensible by better defining the sections and sequential lay out of the pages.Refactoring the code for an existing webpage by adding semantic HTML elements and eliminating non-semantic elements which defines no meaningful content.This will have a better User experience and ADA-compliant.
Created common class in HTML and Consolidated CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements.Included comments before each element or sections of the page.

## Semantic HTML Elements used and meaning
- nav  
  The element defines a set of navigation links.
- section
  The element defines a section in a document.
- article  
  An Element specifies independent, self-contained content.
- alt  
  Specifies an alternate text for an area, if the image cannot be displayed .
- aside  
  Element defines some content aside (Sidebar).
- footer  
  The element defines a footer for a document or section.

## See the below example
html
```
<nav>
    <ul>
        <li>
            <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
            <a href="#social-media-marketing">Social Media Marketing</a>
        </li>
    </ul>
</nav>
```
```
<article id="search-engine-optimization"class="SEO-ORM-SMM"><img src="./assets/images/search-engine-optimization.jpg"class="float-left"alt="Search Engine optimization"/>
     <h2>Search Engine Optimization</h2>
    <p>
     The dominance of mobile internet use means that users are searching
     for the right business as they travel, shop, or sit on their couch at
     home. Search Engine Optimization (SEO) allows you to increase your
     visibility and find the right customers for your business.
    </p>
</article> 
```
## Links  
My favorite search engine is [ Google ] <a href="https://www.google.com/">link to the Google webpage</a>
Link to the deployed Webpage - <a href="https://ashachakre0906.github.io/Code-Refactoring/">Link to Refactor-Code</a>

## License
MIT License

Copyright (c) [ 2022] [Asha Chakre]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
