WebUploader
========================

`WebUploader` 是由 `Baidu WebFE(FEX)` 团队开发的一个简单的以`HTML5` 为主，`FLASH` 为辅的现代文件上传组件。在现代的浏览器里面能充分发挥 `HTML5` 的优势，同时又不摒弃主流IE浏览器，沿用原来的 `FLASH` 运行时，兼容 `IE6+，iOS 6+, android 4+`。两套运行时，同样的调用方式，可供用户任意选用。

采用**大文件分片并发上传**，极大的提高了文件上传效率。

> 官网:   http://fex.baidu.com/webuploader/

```bash
├── Uploader.swf                      # SWF文件，当使用Flash运行时需要引入。
├
├── webuploader.js                    # 完全版本。
├── webuploader.min.js                # min版本
├
├── webuploader.flashonly.js          # 只有Flash实现的版本。
├── webuploader.flashonly.min.js      # min版本
├
├── webuploader.html5only.js          # 只有Html5实现的版本。
├── webuploader.html5only.min.js      # min版本
├
├── webuploader.noimage.js            # 去除图片处理的版本，包括HTML5和FLASH.
├── webuploader.noimage.min.js        # min版本
├
├── webuploader.custom.js             # 自定义打包方案，请查看 Gruntfile.js，满足移动端使用。
└── webuploader.custom.min.js         # min版本
```

