
# Launch

Launch is a collection of super useful CSS resources + a custom grid packed into a convinient little stylesheet that may serve useful in your next big project. It is _not a frontend framework_ but a starter point for large projects and also a personal reference for [me](http://scottcss.github.io/).

__What does it include?__

* [Normalize.css](http://necolas.github.io/normalize.css/)
* Typography
* Custom twelve column grid
* Helper/Utility classes

### Grid

The grid is a flexible twelve column grid with super simple syntax, it is also heavily influenced by [Grid](http://adamkaplan.me/grid/) and [Kindling](http://timothylong.com/kindling/).

__Usage__

Simple three column layout

```
<div class="container">
	<div class="row">
		<div class="column four"></div>
		<div class="column four"></div>
		<div class="column four"></div>
	</div>
</div>
```

### Utility Classes

Grid includes a small set of helper/utility classes that make writing markup easy and fun, here's a quick example, and a list of all helper classes:

```
<h1 class="uppercase weight 600 italic">Launch</h1>
```

outputs:

_*LAUNCH*_

* `.capitalize`
* `.uppercase`
* `.lowercase`