# Webb snippets

```text
{
	"CSS reset": {
		"scope": "css",
		"prefix": "reset",
		"body": [
			"/* Enkel CSS-reset */"
			"html {"
			"	box-sizing: border-box;"
			"}"
			"*, *:before, *:after {"
			"	box-sizing: inherit;"
			"}"
			"body, h1, h2, h3, h4, h5, h6, p, ul {"
			"	margin: 0;"
			"	padding: 0;"
			"}"
		],
		"description": "Enkel CSS reset"
	},
	"HTML5_grundkod": {
		"prefix": "html5",
		"description": "HTML5 grundkod",
		"body": [
			"<!DOCTYPE html>"
			"<html lang=\"sv\">"
			"<head>"
			"	<meta charset=\"utf-8\">"
			"	<meta name=\"viewport\" content=\"width=device-width, initial-scale=1\">"
			"	<title></title>"
			"	<link rel=\"stylesheet\" href=\"style.css\">"
			"</head>"
			"<body>"
			"	${1}"
			"</body>"
			"</html>"
		]
	}
}
```

