# vendor

首页地球用到的第三方文件，原先从 cdn.jsdelivr.net 加载。
jsdelivr 在中国大陆常被污染或限速，首页因此要等很久才出地球，
所以改为随仓库自托管，与页面同源，不再多一次 DNS 与 TLS 握手。

| 文件 | 版本 | 来源 | 许可 |
|---|---|---|---|
| `globe.gl.min.js` | 2.41.4 | https://github.com/vasturiano/globe.gl | MIT |
| `topojson-client.min.js` | 3.1.0 | https://github.com/topojson/topojson-client | ISC |
| `countries-110m.json` | world-atlas@2 | https://github.com/topojson/world-atlas | ISC |

升级时直接从 npm 取同名文件覆盖，并核对上面的版本号。
