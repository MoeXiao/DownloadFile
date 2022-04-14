# [DownloadFile](https://moexc.com/code/DownloadFile.html)
**Typecho 文件下载插件，使下载的文件保持上传时的文件名。**

* 不修改数据库，不修改上传的文件，仅修改文章内附件连接。
* 仅对新上传的文件起作用。
* 旧文件需在修改文章页面点击附件中的文件重新插入新下载链接。
* 插件禁用后会导致启用插件期间已发布文章中的文件无法下载，进入修改文章页面点击附件中的文件重新插入下载链接即可恢复。
* 对腾讯云COS\阿里云OSS对象存储支持

## Typecho 插件安装及使用
0. **插件更新升级时，请先禁用插件后再上传**
1. [点此](https://github.com/DT27/DownloadFile/archive/master.zip)下载插件
2. 将下载的文件解压，文件夹重命名为`DownloadFile`，上传到Typecho`usr/plugins/`目录下
3. 登陆后台，在`控制台`下拉菜单中点击`插件`进入`插件管理`
4. 找到`DownloadFile`，点击`启用`
5. 如果开启对象存储，则输入对象存储地址，没有放空
6. 根据需要更新设置

## License
> Copyright © 2016 [DT27](https://dt27.org)  
> License: [GNU General Public License v3.0](https://github.com/DT27/DownloadFile/blob/master/LICENSE.txt)
