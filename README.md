<!doctype html>
<html>
<head>

<meta charset="utf-8"/>
<title> Thank you for reading </title>
<script src  ="jsm/jquery/3.3.1/jquery.min.js"></script>
<script src  ="js/marked.js"></script>
<link   href ="css/my.css" rel="stylesheet">

</head>
<body>
<pre class="md_source">

# Markdown web page demo
这个例子展示了mardown格式的网页, 你写一次markdown代码, 就能同时支持github和本地浏览器的页面浏览!

- [Let's go!](main/Main.md)

</pre>
<div class="md_render"></div>
<script>$('.md_render').html(marked($('.md_source').html()));
</script>
</body>
</html>