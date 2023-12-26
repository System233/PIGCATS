<!--
 Copyright (c) 2022 System233
 
 This software is released under the MIT License.
 https://opensource.org/licenses/MIT
-->

# PIGCAT's百度云批量保存

解除百度云批量保存文件数量限制

## 使用方法

* 前置浏览器插件：浏览器上需要先安装一个油猴脚本插件，如[Tampermonkey](https://microsoftedge.microsoft.com/addons/detail/%E7%AF%A1%E6%94%B9%E7%8C%B4/iikmkjmpaadaobahmlepeloendndfphd)，同类浏览器插件有很多，装有一个就行。若没有安装油猴插件的话，点击安装链接不会弹出安装页面。

1. 点击 [安装(Github源)](https://github.com/System233/PIGCATS/raw/main/transfer.user.js) 或 [安装(GreasyFork源)](https://greasyfork.org/zh-CN/scripts/453280-%E7%99%BE%E5%BA%A6%E4%BA%91%E6%89%B9%E9%87%8F%E4%BF%9D%E5%AD%98) 安装油猴脚本
2. 打开分享链接
3. 勾选要保存的文件，点击`批量保存到网盘`按钮，选择保存的路径
4. 点击`确定`，开始转存

过程中不要点击影响脚本动作

脚本会自动尝试保存所有文件，过程中尽量不要点击影响脚本动作。
* 若文件未保存完成，且页面超过10秒没有动作，说明保存失败，脚本与当前文件分享页面存在兼容性问题，可以在评论区提供截图等信息反馈问题。
* 若要中断自动保存，可以直接刷新页面，不影响已保存的文件。