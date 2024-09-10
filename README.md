# slf_api.js
Web-API for [slftool.github.io](https://slftool.github.io) an compact solution for Stadt Land Fluss in German

## Example
```JavaScript
async function main() {
	const { SlfApi } = require("./slf_api.js");
	const slfApi = new SlfApi()
	const data = await slfApi.getData()
	console.log(data)
}

main()
```
