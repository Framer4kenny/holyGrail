# holyGrail layout

holygrail
```
<body>
<div class="container">
<header>
	<h1>헤더제목</h1>
</header>

<section class="content"> 
	<nav>
		<ul>
			<li>menu1</li>
			<li>menu2</li>
			<li>menu3</li>
			<li>menu4</li>
		</ul>
	</nav>
	<main>
		<p>본문 내용</p>
	</main>
	<aside> AD </aside>
</section>
<footer>
	copyright
</footer>
</div>

</body>
```

media query
```
		@media (max-width: 750px){
			.content {
				flex-direction: column;
			}
			.content nav{
				border-right: none;
				border-bottom: 1px solid gray;
			}
			.content aside{
				/*border-left: none;*/
				/*border-top: 1px solid gray;*/
				display: none;
			}
		}
```
