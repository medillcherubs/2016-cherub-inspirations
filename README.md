# 2016-cherub-inspirations
Cherubs inspiration chain

https://medillcherubs.github.io/2016-cherub-inspirations/

Paste this into your Wordpress post, under the "Text" tab instead of the "Visual" tab:

```
[raw]
<div id="cherub-inspirations"></div>
<script type="text/javascript" src="//www.cherubs2015.org/wp-content/themes/cherubs-2015/js/vendor/pym.min.js"></script> <script> var pymParent = new pym.Parent("cherub-inspirations", "//medillcherubs.github.io/2016-cherub-inspirations/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2016-cherub-inspirations/edit/gh-pages/index.html -->
[/raw]
```

Make sure the following code is at the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script>
<script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
