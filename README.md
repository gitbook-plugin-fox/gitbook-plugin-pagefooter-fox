# gitbook-plugin-pagefooter-fox

* 插件配置

```javascript
"pagefooter-fox": {
  "copyright":"&copy Taobao FED Team",
  "modify_label": "该文件修订时间：",
  "modify_format": "YYYY-MM-DD HH:mm:ss",
  "override_copyright":true
}
```

* copyright 和 modify_label 支持 html 代码
* override_copyright为true时将完全采用自定义的版权信息

来源于[https://github.com/zhj3618/gitbook-plugin-tbfed-pagefooter](https://github.com/zhj3618/gitbook-plugin-tbfed-pagefooter)，但对其作了一些改进，完全支持自定义的copyright信息