## 写在前面
* 在原插件[（伪）文档面包屑_V1.1.1](https://github.com/OpaqueGlass/syplugin-fakeDocBreadcrumb) 的基础上魔改
* 如果你想捐赠, 请[点击这里](https://wj.qq.com/s2/12395364/b69f/)给[原作者](https://github.com/OpaqueGlass)捐赠, 而不是我
* 如果有bug, 请在链滴社区联系我([HugZephyr](https://ld246.com/member/HugZephyr)), 或者提[issue](https://github.com/Hug-Zephyr/HZ-syplugin-fakeDocBreadcrumb/issues) (我不常看)
* 感谢 [OpaqueGlass](https://github.com/OpaqueGlass), 侵删!!!

### 改动点
* [增加] 支持通过配置修改兄弟列表最大显示数量, 且上下居中当前文档
* [修改] 点击父级文档打开, 改为 点击父级文档显示兄弟列表
* [修改] 取消点击折叠按钮显示兄弟列表
* [修改] 页面切换不触发
* [修改] 取消层级过深时的 ...
* [优化] 在兄弟列表显示的前提下, 需要点两次才能再次显示新的兄弟列表, 现在只需要点一次
* [优化] 同一个文档打开两个页面, 刷新思源的时候, 第二个页面不会显示面包屑
* [优化] 兄弟列表显示效果

### 待处理
* 点击父级文档和点击折叠按钮的动作 由配置控制
* 悬浮显示详细信息, 配置
* 页面切换不触发, 配置

---
原readme

## fakeDocBreadcrumb （伪）文档面包屑

> 在编辑器上方显示当前文档路径信息的[思源笔记](https://github.com/siyuan-note/siyuan)插件。

> 当前版本：v1.1.1 **改进**：为面包屑加入文档图标；
>
> 详见[更新日志](CHANGELOG.md)

> 插件最初在2023年4月发布，感谢陪伴！插件现已进入维护阶段，停止功能新增和较大的改进变动；如遇到bug缺陷请反馈。
> 
> 也请关注官方的推进计划：[全局面包屑](https://github.com/siyuan-note/siyuan/issues/3007)。

### 快速开始

- 从集市下载 或 1、解压Release中的`package.zip`，2、将文件夹移动到`工作空间/data/plugins/`，3、并将文件夹重命名为`syplugin-fakeDocBreadcrumb`;
- 开启插件即可；
- 可以到插件设置页面浏览设置，**提示**：设置页可以上下滑动哦；

#### 说明

本插件：
- 不支持在移动端显示，请使用层级导航插件中的面包屑；
- 导致原有的块面包屑和“更多”操作选项下移；
- 如果主题将面包屑中文档间的分隔符显示为“/”，可能无法点击显示子文档选择菜单，需要在设置项中启用“覆盖主题面包屑分隔符“>”样式”；

## 反馈bug

（推荐）请前往[github仓库](https://github.com/OpaqueGlass/syplugin-fakeDocBreadcrumb)反馈问题。

如果您无法访问github，请[在此反馈](https://wj.qq.com/s2/12395364/b69f/)。

### 参考&感谢

| 开发者/项目                                                  | 描述                                                         | 说明         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ |
| [leolee9086](https://github.com/leolee9086) / [cc-template](https://github.com/leolee9086/cc-template) | 使用挂件渲染模板；[木兰宽松许可证， 第2版](https://github.com/leolee9086/cc-template/blob/main/LICENSE) | 点击打开文档 |
| [zuoez02](https://github.com/zuoez02)/[siyuan-plugin-system](https://github.com/zuoez02/siyuan-plugin-system) | 插件系统                                                     |              |
