EasyTabs
========

A simple jQuery plugin for tabs.

Usage
-----
The tabs are controlled by a <ul> element of class 'easytabs-nav' and a number of <li> elements, depending on how many tabs you want.

Following the <ul> should be a number of block elements of class 'easytabs-pane'. These will contain the content to be displayed when its corresponding tab is clicked. 

There should be the same number of 'easytabs-pane' block elements as there are <li> elements in the 'easytabs-nav' <ul>.

Enable the tab functionality by wrapping everything in a container element and calling 'easyTabs()' on it.

Example
-------
```
<div class="easytabs-container">
	<ul class="easytabs-nav">
		<li>Tab 1</li>
		<li>Tab 2</li>
		<li>Tab 3</li>
	</ul>
	<div class="easytabs-pane">
		Content of tab 1
	</div>
	<div class="easytabs-pane">
		Content of tab 2
	</div>
	<div class="easytabs-pane">
		Content of tab 3
	</div>
</div>

<script>
	$(function (){
		$('.easytabs-container').easyTabs();
	});
</script>

```

