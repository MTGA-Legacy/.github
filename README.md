# MTGA-Legacy

Make LegacyTV Great Again

本仓库保存组织级协作规范和社区健康文件。组织主页位于 [`profile/README.md`](profile/README.md)，保持简洁；各软件项目在独立仓库中维护。

## 当前仓库

| 仓库 | 用途 | 上游 | 老电视基线 | 许可证状态 |
| --- | --- | --- | --- | --- |
| [`blbl`](https://github.com/MTGA-Legacy/blbl) | Bilibili 安卓客户端 | [`cat3399/blbl`](https://github.com/cat3399/blbl) | 默认分支 `blbl-api19`（API 19）；`main` 跟踪上游 | 上游未声明许可证，暂作上游跟踪副本 |
| [`HTV`](https://github.com/MTGA-Legacy/HTV) | 电视直播 | [`HTWMedia/HTV`](https://github.com/HTWMedia/HTV) | 上游声明 Android 4.4+，优先验证 `armeabi-v7a` | Apache-2.0 |
| [`LauncherTV`](https://github.com/MTGA-Legacy/LauncherTV) | 轻量电视桌面 | [`alescdb/LauncherTV`](https://github.com/alescdb/LauncherTV) | 上游最低 API 14 | Apache-2.0 |

## 维护原则

- 先记录设备事实：型号、Android API、CPU ABI、内存、显示和遥控器行为。
- 适配提交应同时说明构建命令、APK 最低 API、ABI 和真实设备结果。
- 保留上游来源、许可证和版权声明；不把没有授权的代码重新发布为自己的项目。
- 直播源、账号、密钥和个人数据不进入仓库。
- 旧设备兼容性以真实电视安装和播放结果为准，不能只用 CI 通过代替验收。

详细的仓库分层和后续扩展建议见 [`docs/REPOSITORY-STRUCTURE.md`](docs/REPOSITORY-STRUCTURE.md)。

组织级兼容性看板：[LegacyTV 兼容性与维护](https://github.com/orgs/MTGA-Legacy/projects/1)。
