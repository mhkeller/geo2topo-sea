Geo2Topo Single-Executable App
===

> An experiment to package up topojson-server's [geo2topo](https://github.com/topojson/topojson-server) as a [single-executable app](https://nodejs.org/api/single-executable-applications.html)

I put a few different options into the `package.json` including pkg, nexe, esbuild+node-sea, deno and bun. The best one is `npm run bun` since actually works and it has the smallest file size, although it is still 56.9mb. 

```sh
npm i
npm run bun
```
