Simple-Jekyll-Search
====================

No additional gems required. 

Works out of the box. 

Fast, lightweight, super easy to set up and fully customizable with CSS!

#####v2

Version 2 comes with improved *search* and *templating* engine!

#####v3

But what if I don't want jQuery? No problem, I got you covered. `jekyll-search.js` is what you've been looking for on the second page of Google search results.


##How to 

First of all include the script
```html
<script src="js/jekyll-search.js"></script>
```

This will create a global object called `JekyllSearch`, on which you can invoke the `init()` function.

If you want, you can customize several options of this plugin:

- `searchInput`				(Element) the input field to listen on
- `searchResults`			(Element) the container to which JekyllSearch will write the matched search results 
- `jsonFile`				(String) location of the JSON file, our little "database"
- `template`				(String) <a href="#template">template</a> (Mustache-like)
- `searchResultsHeader`		(String) Heading of the search results
- `limit`					(Integer) Limit the search results to a sane amount (10-15)
- `fuzzy`					(Boolean) Turn on/off <a href="#fuzzysearch">fuzzy search</a>
- `noResults`				(String) Text to display if nothing matched the search criteria

<h2 id="template">Template</h2>
<h2 id="fuzzysearch">Fuzzy search</h2>






####Special thanks

These people helped with suggestions, improvements and bug reports to make this plugin better :

- [dashaman](http://dashaman.com/)
- [Todd Motto](http://toddmotto.com/)
- [Dillon de Voor](http://www.crocodillon.com/)


#License
##MIT licensed
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.