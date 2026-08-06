这是 bitchat 的 OpenWiki 生成简报。OpenWiki 在 init/update 时会读取此文件来确定范围和侧重点；它不是生成物，不会被自动重写。

- 项目性质：基于蓝牙 Mesh 的去中心化聊天应用（Swift/iOS/macOS）。
- 文档范围：仅分析 `bitchat/` 目录；不要将 `wecom_bot` 仓库的工作流或配置当作 bitchat 产品代码。
- 重点关注：应用架构、BLE Mesh 传输、消息协议与加密、身份与密钥管理、Nostr/Tor 集成、文件和语音传输，以及 iOS/macOS 构建与测试。
- 生成的文档应包含足够的 source map，让下游 agent（Hermes）能对照具体源码文件核验文档描述是否属实。
- 涉及密钥、token、设备标识或网络端点等敏感配置时，只写“从哪个环境变量/配置文件读取”，不要把真实值写进文档。
