## 使用效果

![](https://raw.githubusercontent.com/fei0810/image-host/master/img/20190914114547.gif)

## 源文件

markdown here github https://github.com/adam-p/markdown-here

## zotero 插件制作

zotero 的插件格式和Firefox一致，后缀为xpi，但是本质其实是一个zip压缩文件

新建一个目录`markdownhere4zoter`包含如下内容

```
chrome.manifest
install.rdf
common/
firefox/
```

在该目录下进行zip即可

```sh
zip -r ./markdownhere4zoter.zip ./
```

## 下载地址

http://url.kaopubear.top/PT9lBK
