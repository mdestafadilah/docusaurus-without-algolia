# Website

This website is built using [Docusaurus 2](https://v2.docusaurus.io/), a modern static website generator.

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Local Search

```
https://github.com/lelouch77/docusurus-lunr-search
```

### Netlify Host

```
https://docusaurus-without-algolia.netlify.com 
```

### Problem
1. Add 
	```
	"devDependencies":{
		"@babel/preset-typescript": "^7.7.4"
	},
	```
2. Comment  `//require(`prismjs/components/prism-${lang}`); // eslint-disable-line` when you run `yarn run build`
