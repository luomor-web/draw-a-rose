1. 下载代码 `git clone git@github.com:jrg-team/draw-a-rose.git`
2. 文件夹内运行 `parcel src/index.html`
3. 浏览器中查看 `http://localhost:1234`
4. 预览链接：[点击预览](https://jrg-team.github.io/draw-a-rose/)
5. 效果图：
![](https://static.xiedaimala.com/xdml/image/2f52ffb4-4a2a-40c0-bd0d-d63d700669f8/2021-5-14-12-53-5.png)

```
https://www.parceljs.cn/

cnpm install -g parcel-bundler
parcel src/index.html

parcel build src/index.html
parcel build src/index.html --public-url /2022

parcel help build
```

```
parcel --help
Usage: parcel <command> [options]

Options:
  -V, --version               output the version number
  -h, --help                  output usage information

Commands:
  serve [options] [input...]  starts a development server
  watch [options] [input...]  starts the bundler in watch mode
  build [options] [input...]  bundles for production
  info                        Prints debugging information about the local environment
  help [command]              display help information for a command

  Run `parcel help <command>` for more information on specific commands

  
parcel help build
Usage: build [options] [input...]

bundles for production

Options:
  -d, --out-dir <path>           set the output directory. defaults to "dist"
  -o, --out-file <filename>      set the output filename for the application entry point.
  --public-url <url>             set the public URL to serve on. defaults to "/"
  --global <variable>            expose your module through a global variable
  --no-minify                    disable minification
  --no-cache                     disable the filesystem cache
  --no-source-maps               disable sourcemaps
  --no-autoinstall               disable autoinstall
  --no-content-hash              disable content hashing
  --experimental-scope-hoisting  enable experimental scope hoisting/tree shaking support
  -t, --target <target>          set the runtime environment, either "node", "browser" or "electron". defaults to "browser"
  --bundle-node-modules          force bundling node modules, even on node/electron target
  --detailed-report [depth]      print a detailed build report after a completed build. If enabled, defaults to depth "10"
  --log-level <level>            set the log level, either "0" (no output), "1" (errors), "2" (warnings), "3" (info), "4" (verbose) or "5" (debug, creates a log file).
  --cache-dir <path>             set the cache directory. defaults to ".cache"
  -h, --help                     output usage information
```