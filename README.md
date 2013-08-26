jqverify
========

An age verification (or age gate) using HTML, CSS, and jQuery/JavaScript. [Live Demo](http://komejo.com/jqverify/example.html)

This age verification system is set up for Legal Drinking Age, has a JS cookie option, and works in a modal window. It could easily be adapted for other uses.

I wrote / pieced this together because I could not find a solution that was frontend-only, had all of the HTML, countries / drinking ages, set cookies, and had a 'remember me' checkbox.

## Basic Use

Add the content in modal.html and modal.css to all entry points of your site. Upload jqverify.js, and include it in your header or footer, depending on your preference (I call it in the footer): `<script src="./jqverify.js"></script>`

Then wrap your sensitive content in a div like so: `<div id="content" class="content"></div>`

If you already have a content wrapper, just update `content  = "#content";` as needed in jqverify.js.

If you want to test it repeatedly, there's a commented out function call at the top of jqverify.js `\\ eraseCookie('jqverify');`


## License and Credits

© 2013 <a href="https://github.com/komejo">Komejo</a>. Created by <a href="http://twitter.com/KomejoDev">Joe Komenda</a>.

Credit to [Cats Who Code](http://www.catswhocode.com/blog/10-jquery-snippets-for-efficient-developers) for the 'Validate a date of birth using jQuery' section.

jqverify.js is released under the <a href="http://opensource.org/licenses/MIT">MIT license</a>.