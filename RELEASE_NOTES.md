## PCL LCP 修改版 2.15.1

第三方基于 PCL 的修改版（LCP Edition），**非官方发布**。原作者：龙腾猫跃。

### 本版改动

- 品牌：窗口/文件图标、标题栏字标、关于页头像、启动画面 Logo 替换为 LCP；窗口标题显示 `LCP`
- 正版登录：补上微软 OAuth 客户端 ID 回退
- 联机大厅：补上 `LINK_SERVER_ROOT` 回退
- 大厅 Natayark 登录：使用内置 `pclce2025` 客户端，修复 401 / `invalid_request`
- 解除下载与安装时的「地区不可用」限制
- 离线验证入口默认可用
- 更新源改为 Naids 优先，失败仅记录 WARN

### 下载

- `PCL-LCP-Edition_2.15.1_x64.exe`
- `windowsdesktop-runtime-10.0.15-win-x64.exe`（.NET 10 Desktop Runtime，x64）

### 校验

```
SHA256  c7fd5b0ee4ada8952b1327a9f715dbbbe0d5fd9e95f2e995c2a99a70e789c72e
```

### 许可

依据 PCL《分发有限许可》与合理使用指南发布：第三方修改版、名称以 PCL 开头、保留原作者署名与赞助链接、开源发布。
详见仓库 README 与 `LICENCE-PCL.txt`。
