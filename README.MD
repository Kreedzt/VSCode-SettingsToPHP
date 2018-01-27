# VSCode 配置 PHP 开发

> 随笔类型

> Debugger(断点调试)还在摸索中...

## 插件获取

> Tips: 大小写不一定准确, 搜索时可不输出完整单词, 进行模糊搜索

* PHP Debug
  断点准备
* PHP Extensition Pack
  后续扩展依赖(语法提示依赖)
* PHP IntelliSense
  语法提示, 安装后记得**关闭**系统提示, 否则引起冲突
* PHP Intelephense 高性能查错工具

## 修改设置

如果 phpStudy 安装在 D 盘, 可直接复制我的设置

```json
    "php.suggest.basic": false, // 关闭自带的基础建议

    "php.validate.enable": false, // 关闭自带的PHP验证(若安装了第三方验证则关闭)

    "php.validate.executablePath": "D:/phpStudy/php/php-5.4.45/php.exe", // 指向 PHP 可执行文件。


    // 此处仅支持 PHP 7 版本(扩展基于PHP远程调试), 若用 5 版本可以先不设置
    "php.executablePath": "D:/phpStudy/php/php-5.4.45/php.exe", // 指向 PHP 可执行文件。
```
