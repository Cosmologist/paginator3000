Paginator 3000 is a slider-based pagination menu
=========================
![](https://github.com/Cosmologist/paginator3000/blob/master/docs/paginator-3000.png)

The paginator was featured in Smashing Magazine as [Creative Solutions Can Be User-Friendly](https://www.smashingmagazine.com/2007/11/pagination-gallery-examples-and-good-practices/) in the article [Pagination Gallery: Examples And Good Practices](https://www.smashingmagazine.com/2007/11/pagination-gallery-examples-and-good-practices/).  
Was previously posted [here](http://karaboz.ru/2007/11/19/paginator-3000-postranichnaya-navigaciya-budushhego/)

# Usage

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="paginator3000.css" />
  <script type="text/javascript" src="paginator3000.js"></script>
</head>

<body>
  ...
  <div class="paginator" id="paginator_example"></div>
  <script type="text/javascript">
  	paginator_example = new Paginator(
  		"paginator_example", // id контейнера, куда ляжет пагинатор
  		2048, // общее число страниц
  		10, // число страниц, видимых одновременно
  		300, // номер текущей страницы
  		"http://www.yourwebsite.com/pages/" // url страниц
  	);
  </script>
</body>
```
