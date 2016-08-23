React-Tags inline styles (fork for inline styles)
===
This is a fork of https://github.com/prakhar1989/react-tags v4.3.0

It adds the ability to change the tag colours at run-time, using a calculated colour:

### Inline styles for background and text color
Sometimes classes are not enough. For example, if you want your tag to be a color that is only known at run-time, or from user input, you need to modify the style and apply a specific color property that can't be defined ahead of time in a class. To avoid direct DOM manipulation using something like JQuery, use these properties that set the inline style of the tag:
```js
	<ReactTags
		backgroundColor={ someCalculatedColor }
		textColor={ someCalculatedColor }
	...>
```	
##See original repo for full documentation: https://github.com/prakhar1989/react-tags

