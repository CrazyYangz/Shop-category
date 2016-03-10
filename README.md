# Shop-category
商城二级分类显示插件

###html结构

```html
<div class="category-box">
	<div class="nav-box">
		<ul>
			<li>nav 1</li>
			<li>nav 2</li>
			<li>nav 3</li>
			<li>nav 4</li>
		</ul>
	</div>
	<div class="nav-main">
		<div class="c1">
			<div class="colume">
				<h5>nav 1-1</h5>
				<nav>
					<a href="">nav 1-1-1</a>
					<a href="">nav 1-1-2</a>
					<a href="">nav 1-1-3</a>
				</nav>
			</div>
		</div>
		<div class="c2">
			<div class="colume">
				<h5>nav 1-2</h5>
				<nav>
					<a href="">nav 1-2-1</a>
					<a href="">nav 1-2-2</a>
					<a href="">nav 1-2-3</a>
					<a href="">nav 1-2-4</a>
				</nav>
			</div>
		</div>
		<div class="c3">
			<div class="colume">
				<h5>nav 1-3</h5>
				<nav>
					<a href="">nav 1-3-1</a>
					<a href="">nav 1-3-2</a>
					<a href="">nav 1-3-3</a>
					<a href="">nav 1-3-4</a>
					<a href="">nav 1-3-5</a>
					<a href="">nav 1-3-6</a>
					<a href="">nav 1-3-7</a>
				</nav>
			</div>
		</div>
		<div class="c4">
			<div class="colume">
				<h5>nav 1-4</h5>
				<nav>
					<a href="">nav 1-4-1</a>
					<a href="">nav 1-4-2</a>
				</nav>
			</div>
		</div>
	</div>
</div>
```

###使用方法
```javascript
jQuery(".category-box").tab({titCell:'.nav-index li',mainCell:'.nav-main'}); //javascript
```
