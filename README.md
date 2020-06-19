### Simditor

---

Simditor is a browser-based WYSIWYG text editor.

It is used by [Tower](http://tower.im) -- a popular project management web application.

Supported Browsers: IE10+、Chrome、Firefox、Safari.
* [Download Zip](https://github.com/mycolorway/simditor/releases)
* Install with npm: $ npm install simditor</li>

Demo and docs can be found [here](http://simditor.tower.im/).

### 更改
由于官方上传组件不支持设置http header，因此fork了官方项目进行修改。修改内容如下：

* 引用`simple-uploader`改为引用`simple-uploader-support-headers`

* 在原项目`simple-uploader`基础上加入http header的支持

> 注意：以下两个包仅支持npm安装

### NPM包

[simditor-support-headers](https://www.npmjs.com/package/simditor-support-headers)

[simple-uploader-support-headers](https://www.npmjs.com/package/simple-uploader-support-headers)

### 安装

```shell
npm install simditor-support-headers
```

### 其他

* 为什么没有yarn、brower等安装方式？

    由于此需求是项目内部的需要，加之，**本人太懒了**。如果有需要的朋友，可以参见相关文档自行发布。
* 为什么不给官方提PR而是自己fork来搞？

    我看到官方项目有类似的PR请求但似乎并没有被合并，加之，**本人太懒了**
  
### 大感谢

最后感谢 @彩程设计([@mycolorway](https://github.com/mycolorway)) 为开源世界贡献出如此优秀的作品！感谢！~ 
