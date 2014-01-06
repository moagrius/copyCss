<h1>jQuery.copyCSS</h1>

<p>Quick, simple jQuery extension to retrieve or copy all styles (with optional whitelist and blacklist) from an HTML element.</p>

<p>Tested in Chrome, FireFox, Safari, IE6-9.  Thanks to Vincent (link unknown) who tested and provided a fix for Opera.</p>

<p>Usage:</p>

```
$('#some-element').copyCSS('#another-element');  // copy all styles
$('#some-element').copyCSS('#another-element', ['top', 'left']);  // copy just top and left
$('#some-element').copyCSS('#another-element', null, ['top', 'left']);  // copy everything except top and left
```

<p>This method can be a resource hog.  Try to use the whitelist parameter if possible.</p>
