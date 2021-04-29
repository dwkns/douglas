# Douglas
For the dog, not for you

In your settings file:
```json
"vsicons.associations.files": [
  { "icon": "nunjucks", "extensions": ["njk"], "format": "svg" }
],
```

This might be a better (simpler) starting place:
https://github.com/eseom/nunjucks-template


https://vscode.readthedocs.io/en/latest/getstarted/theme-color-reference/


## Configuration

##### Keep YAML front-matter data.

default: `true`

```json
"nunjucksFormat.frontMatterData": true
```

##### Force an Empty Line Above Comments.

default: `false`

```json
"nunjucksFormat.commline": false
```

##### End Self-Closing Tags with a Space.

default: `false`

```json
"nunjucksFormat.spaceclose": false
```

##### Indent Style/Script independently.

default: `false`

```json
"nunjucksFormat.style": false
```

##### Merge Empty Tag Sets Into A Single Self-Closing Tag.

default: `false`

```json
"nunjucksFormat.tagmerge": false
```

##### Sort Child Items of Each Parent Element tagsort.

default: `false`

```json
"nunjucksFormat.tagsort": false
```

##### Preserve white space in text Content

default: `true`

```json
"nunjucksFormat.textpreserve": true
```

##### Preserve HTML tag and attributes

default: `true`

```json
"nunjucksFormat.unformatted": true
```
