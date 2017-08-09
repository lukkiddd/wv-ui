# <wv-select>
Select input for webview of messenger's ui

### Todos
- [ ] Icon
- [ ] Event firing

## How to use
```html
<wv-select id="select" placeholder="Default placeholder" options=[[options]]>
</wv-select>

<script>
	window.addEventListener('WebComponentsReady', function () {
		var select = document.getElementById('select');
		
		var options = [{
			value: 'apple',
			name: 'Apple'
		},{
			value: 'mongo',
			name: 'Mango'
		}];

		select.options = options;
	})
</script>
```

