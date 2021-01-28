## JExcel Plugin : Contextmenu rows advanced actions

ContextMenu rows advanced actions is a plugin for add new items in contextMenu of JExcel Pro for manage rows. 

![preview](https://user-images.githubusercontent.com/52194475/102090914-5b802d80-3e1e-11eb-9fe6-572cea5eecae.png)

This plugin is **Free**

## What is JExcel ?

jExcel, a lightweight Vanilla JavaScript plugin, can help you create exceptional web-based interactive tables and spreadsheets. Compatible with most widely-used spreadsheet software, such as Excel or Google Spreadsheet, it offers users an unrivalled Excel-like user experience. It also works well with prominent modern frameworks and flexibly utilizes a large collection of events, extensions and configurations to meet different application requirements. Impress your clients with a better user experience and a great dynamic interactive data management tool.

- [Download JExcel Pro](https://www.jexcel.net) 
- [Download JExcel CE](https://bossanova.uk/jexcel/)

## Documentation

### Dependencies

- [JExcel Pro v7](https://www.jexcel.net/v7)

- With default options of plugin, you should use [Material Design icons](https://material.io/resources/icons/). 

```HTML
<link href="https://fonts.googleapis.com/css?family=Material+Icons|Material+Icons+Outlined|Material+Icons+Two+Tone|Material+Icons+Round|Material+Icons+Sharp" rel="stylesheet">
 ```   

### Options of plugin

<table>
	<thead>
		<tr>
			<th>Option name</th>
			<th>Description</th>
			<th>Type</th>
			<th>Default Value</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td><code>icon_moveup</code></td>
			<td>Icon for "move up rows"</td>
			<td><code>String</code></td>
			<td><code>arrow_upward</code></td>
		</tr>
		<tr>
			<td><code>icon_movedown</code></td>
			<td>Icon for "Move down rows"</td>
			<td><code>String</code></td>
			<td><code>arrow_downward</code></td>
		</tr>
		<tr>
			<td><code>icon_duplicate</code></td>
			<td>Icon for "Duplicate rows"</td>
			<td><code>String</code></td>
			<td><code>content_copy</code></td>
		</tr>
		<tr>
			<td><code>icon_deleteSelectedColumns</code></td>
			<td>Icon for "Delete selected columns"</td>
			<td><code>String</code></td>
			<td><code>delete</code></td>
		</tr>
		<tr>
			<td><code>text_moveup</code></td>
			<td>Text for "move up rows"</td>
			<td><code>String</code></td>
			<td><code>Move up row(s) selected</code></td>
		</tr>
		<tr>
			<td><code>text_movedown</code></td>
			<td>Text for "move down rows"</td>
			<td><code>String</code></td>
			<td><code>Move down row(s) selected</code></td>
		</tr>
		<tr>
			<td><code>text_duplicate</code></td>
			<td>Text for "duplicate rows"</td>
			<td><code>String</code></td>
			<td><code>Duplicate row(s) selected</code></td>
		</tr>
	</tbody>
</table>

### Get started

Header on page
```HTML
<script src="https://jexcel.net/v7/jexcel.js"></script>
<script src="https://jexcel.net/v7/jsuites.js"></script>
<link rel="stylesheet" href="https://jexcel.net/v7/jsuites.css" type="text/css" />
<link rel="stylesheet" href="https://jexcel.net/v7/jexcel.css" type="text/css" />
<link href="https://fonts.googleapis.com/css?family=Material+Icons|Material+Icons+Outlined|Material+Icons+Two+Tone|Material+Icons+Round|Material+Icons+Sharp" rel="stylesheet">

<script src="/path/to/jexcel.contextmenu_rowAdvancedActions.js"></script>
```

Initialize plugin on JExcel
```JavaScript
jexcel(document.getElementById('spreadsheet'), {
	...
	plugins: [
      ...
      { name:'rowsAdvancedAction', plugin:jexcel_contextmenu_rowAdvancedActions},
      ...  
    ],
    ...
});
```


## CDN

You can use this CDN link

```HTML
<script src="https://cdn.jsdelivr.net/gh/Guillaume-Bo/jexcel-plugins-and-editors@latest/plugins/contextmenu_rowAdvancedActions/jexcel.contextmenu_rowAdvancedActions.js"></script>
```

## Copyright and license

Copyright [GBonnaire.fr](https://www.gbonnaire.fr) and Code released under the MIT License