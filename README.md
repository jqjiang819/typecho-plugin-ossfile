# OssForTypecho

**Important: This repo is no longer maintained since I am not using typecho for years, and you may suffer from bugs and security issues. If you want any features or bug fixing, please fork, thanks!**

**重要提示: 抱歉，此插件已停止维护！由于我已长期未使用Typecho，此插件可能存在无法预知的问题以及安全隐患。由于无法测试，因此也不再接收PR。如有需要，可自行fork和修改。感谢！**

OssForTypecho是基于Typecho的一个支持文件附件上传、修改和删除功能的插件。（支持Typecho 1.x版本）

## 插件功能

1. 支持基本的上传、修改、删除操作；
2. 支持阿里云OSS自定义域名。（支持HTTPS）

## 注意事项

1. 在在阿里云 [AccessKey管理控制台](https://ak-console.aliyun.com/#/accesskey) 页面里获取AccessKeyID与AccessKeySecret；
2. 插件会替换所有之前上传的文件的链接，若启用插件前存在已上传的数据，请自行将其上传至OSS相同目录中以保证正常显示；同时，禁用插件也会导致链接恢复，也请自行将数据下载至相同目录中；
3. 插件不会验证配置的正确性，请自行确认配置信息正确，否则不能正常使用。

## 更新日志
- **2020-07-25：** 升级OSS-PHP-SDK，支持流上传 ，[dragonflylee](https://github.com/dragonflylee) and [权那他](https://github.com/kraity)
- **2018-08-08：** 升级OSS-PHP-SDK，使用phar包
- **2018-04-05：** 首次发布，支持Typecho 1.x版本

原作者: [Charmeryl](https://github.com/jqjiang819)

## 开源许可
	The MIT License (MIT)

    Copyright (c) 2014 Hugh Jiang

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
