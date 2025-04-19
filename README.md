# Unity 版本链接列表

这个仓库收集整理了Unity各个版本的Hub启动链接，方便开发者快速安装和切换不同版本的Unity编辑器。

## 快速访问链接

🌐 **在线预览**: [HTML 预览页面](http://cdn.zhuzhuyun.cn/UnityVs/Versions.html)
📋 **版本链接列表**: [Unity-Version-Links](https://github.com/YiJiu-Li/Unity-Versions/blob/master/Unity-Version-Links.md)

## 特性

- 按版本号从高到低排序的完整Unity版本列表
- 支持通过unityhub协议直接启动安装
- 涵盖从Unity 5.6到Unity 6000的所有版本
- 提供HTML和JSON格式的版本信息

## 如何使用

### 直接点击链接安装

在已安装Unity Hub的情况下，只需点击对应版本的链接，Unity Hub将自动打开并提示安装该版本。例如：

```
unityhub://2022.3.10f1/316c1fd686f6
```

### 查看版本列表

所有版本都按主要版本号分类整理在Markdown文件中，您可以：

1. 访问 [**Unity-Version-Links.md**](https://github.com/YiJiu-Li/Unity-Versions/blob/master/Unity-Version-Links.md) 查看完整版本列表
2. 使用 [**HTML 预览页面**](http://cdn.zhuzhuyun.cn/UnityVs/Versions.html) 获得更好的浏览体验
3. 使用浏览器搜索功能（Ctrl+F）快速定位特定版本

### 数据格式

本仓库提供三种格式的版本信息：

| 格式         | 说明                       | 链接                                                                                                    |
| ------------ | -------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Markdown** | 人类可读的版本列表         | [Unity-Version-Links.md](https://github.com/YiJiu-Li/Unity-Versions/blob/master/Unity-Version-Links.md) |
| **HTML**     | 可在浏览器中查看的网页版本 | [HTML 预览页面](http://cdn.zhuzhuyun.cn/UnityVs/Versions.html)                                          |
| **JSON**     | 便于程序处理的数据格式     | -                                                                                                       |

## Unity 版本链接使用说明

### 关于 unityhub:// 链接

本仓库中的 Unity 版本链接使用了 `unityhub://` 协议，这是 Unity Hub 应用程序特有的协议，用于直接启动 Unity Hub 并指向特定版本的安装或下载页面。

### 为什么在 GitHub 上链接不能点击跳转？

浏览器默认情况下不支持 `unityhub://` 协议，所以在 GitHub 或其他网页平台上查看时，这些链接可能显示为普通文本或不可点击的链接。

### 如何使用这些链接

#### 方法一：复制链接到浏览器

1. 确保已安装 Unity Hub
2. 复制完整的链接，例如 `unityhub://2023.2.20f1/0e25a174756c`
3. 粘贴到浏览器地址栏并访问
4. 浏览器会询问是否打开 Unity Hub，选择"打开"
5. Unity Hub 会自动打开并导航到相应的版本安装页面



### 其他信息

Unity 版本链接的格式为：`unityhub://<版本号>/<哈希值>`，其中：
- 版本号：例如 2023.2.20f1
- 哈希值：特定版本的唯一标识符，例如 0e25a174756c

## 贡献

欢迎提交Pull Request添加新版本或修正错误。添加新版本时，请遵循现有的格式并按版本号排序。

## 许可

[**MIT License**](https://github.com/YiJiu-Li/Unity-Versions/blob/master/LICENSE)


## 相关链接

- [Unity官方下载页面](https://unity.com/download)
- [Unity Hub下载](https://unity.com/download)
- [Unity发布说明](https://unity.com/releases)