
Bootstrap IE6
===

Twitter Bootstrap shim for IE6.

## Usage

Insert the following code fragment into your page.

```html
<!--[if IE 6]>
<link href="bootstrap-ie6.css" rel="stylesheet">
<script src="DD_belatedPNG_0.0.8a-min.js"></script>
<script>
	$(function() {
		$('[class^="icon-"]').each(function() {
			DD_belatedPNG.fixPng(this);
		});
	});
</script>
<![endif]-->
```

## License

Copyright (c) 2012 Twitter, Inc

Licensed under the Apache License v2.0, http://www.apache.org/licenses/LICENSE-2.0
