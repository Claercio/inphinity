# Inphinity

> Infinity Scroll without [jQuery](https://jquery.com/) or other dependency.

## About

Inphinity was made to Jekyll static blogs, Drupal and Wordpress sites/blogs.

### Who is using this?

- [My personal blog](http://raphamorim.com/blog)

### How to use?

Relax bro! A better documentation coming soon. For while, see a simple example:

```javascript
inphinity.on('#posts').set({
  navSelector : "p.pagination",
  nextSelector  : "p.pagination a.older",
  itemSelector  : ".container ul#posts li.post",
  finishedMsg: "<em>That's all folks!</em>",
  loadingMsg: 'Loading more...',
  animationSpeed: "slow"
});
```

### Options 

####• navSelector
Description: Pagination nav 

Default: `div.navigation`

####• nextSelector
Description: href attribute, who specifies the URL of the next page.

Default: `div.navigation a:first`

####• itemSelector
Description: List items in structure 

Default: `div.post`

####• finishedMsg
Description: Message to show when finish pages when ends 

Format: raw HTML

Default: `<em>That's all folks!</em>`

####• loadingMsg
Description: Message to show when load more items

Format: raw HTML

Default: `Loading more...`

####• animationSpeed 
Description: Set speed of the animations

Suggestions: `normal`, `slow`, `fast` 

Default: `500`


## Credits

Infinitely inspired by [Infinity Scroll](https://github.com/infinite-scroll/infinite-scroll)

## License

The MIT License (MIT)

Copyright (c) 2015 [Raphael Amorim](http://github.com/raphamorim)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
