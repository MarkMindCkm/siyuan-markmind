# 思源笔记-markmind 插件

#### 本插件是基于 Markmind 开发，为国产思源笔记开发的一款思维导图插件，本插件源码并非公开
网站：https://www.markmind.net/siyuan

本插件暂时定价为 45元/年，现处于优惠价格： 30元/年，免费可以体验至少2周，过期之后如果不买激活码将只能阅读，无法编辑


#### 插件使用
1. 使用插件市场安装或者手动下载安装后，在设置页面打开插件，之后会在顶部有个菜单按钮，插件路径和文件如下  
![3](https://github.com/MarkMindCkm/siyuan-markmind/assets/18719494/3b718f38-981c-4109-ac31-aef196f6bcc6)

2. 在菜单按钮里点击 `初始化插件` ，会在你的思源笔记 `data` 文件夹下生成一个 `markmind` 文件夹，之后插件生成的思维导图文件将保存在此，该文件本质上是一个`json`文件，后缀名为 `mmxd`  
![1](https://github.com/MarkMindCkm/siyuan-markmind/assets/18719494/9d1db3d2-cec0-446e-93ee-06ab3751067f)

3.新建思维导图，在左下角打开思维导图 dock ,然后如下操作  
![2](https://github.com/MarkMindCkm/siyuan-markmind/assets/18719494/6c96c813-79d5-4c80-a7e8-e2ace02dd617)

4.之后就可以正常操作思维导图了，如下图，注意：**每次操作后，在右上角会有保存提示，请保存成功后在关闭软件或者切换到其他tab页，防止数据保存失败，丢失数据**  
![4](https://github.com/MarkMindCkm/siyuan-markmind/assets/18719494/531cecaa-d294-4452-9c25-8320d5476681)

#### 和思源笔记结合
1. PDF 标注结合，如下图，注意：**由于目前思源笔记 API 还在开发中，如果想要向下图那样点击节点标注跳转到 PDF，首先需要打开一篇思源自身的笔记才行，等后面API 完善后可以不需要这个操作**
![5](https://github.com/MarkMindCkm/siyuan-markmind/assets/18719494/338694bb-dee0-44d9-aa0c-7845803bc587)
2. 节点支持解析 markdown 语法，支持思源链接
![6](https://github.com/MarkMindCkm/siyuan-markmind/assets/18719494/1d6d9729-4fcf-46d1-ab27-675373da7b71)

#### 使用建议 （重要提醒）

1. 由于思源笔记 API 目前还在完善中，本插件也是处于 Beta 版本，后面会跟随思源笔记一起成长。
2. 由于本插件的复杂性，**建议只同时最多打开2个tab页，否则可能会影响思源笔记性能，后面也会跟随 API 进行改善**
3. 同样由于本插件的复杂性，目前不可避免的会有一些BUG,请多多包含，**使用中请备份好数据，以防丢失**
4. 有问题请提 issue ,我会尽量尽快解决

#### 思维导图快捷键

|功能                           | 快捷键                   |
| --------------------------------------- | ---------------------------- |
| 新建节点                          | Tab                          |
| 新建同级节点                      | enter                        |
| 删除节点                             | Delete/Backspace             |
| 编辑节点                              | Space/双击节点          |
| 撤销                                   | Ctrl/Cmd+Z                   |
| 恢复                                    | Ctrl/Cmd+Y                   |
| 退出编辑节点                          | Tab                          |
| 展开节点                             | Ctrl/Cmd + /                 |
| 收缩节点                           | Ctrl/Cmd + /                 |
| 节点改变位置               | 拖动节点到其他节点上          |
| 切换焦点节点                               | Up/down/left/right           |
| 放大、缩小画布                             | Ctrl/Cmd + 鼠标滚轮       |
| 选中后删除，删除归纳、外框、联系线 | Delete/Backspace             |
| 自由节点 | 拖动节点放在空白处即可             |

#### 后续待开发功能
1. 导出图片/PDF
2. 导入 Xmind zen 文件
3. 节点支持标注
4. 等待思源 API 完善后，更好的与思源 API 结合
5. 性能优化
6. 从思源块生成思维导图节点

