# Ruyi 开发板教程与示例文档库

[中文](./README_zh.md) / [English](./README.md)

欢迎来到 RuyiSDK 的开发板教程与示例文档中心。本仓库主要存放各款 RISC-V 开发板的环境初始化指南、基础示例、外设示例、多媒体、AI等示例教程文档。

## 📚 目录结构说明

- `/boards`: 存放按开发板型号分类的教程文档（Markdown 格式）。
- `/templates`: 存放新增开发板的 PR 模板和文档模板。

## 🚀 支持的开发板矩阵

目前本仓库已包含但不限于以下硬件的文档资源：

| 支持设备         | 示例文档                                                                   | 芯片厂商                                                             |
| ------------ | ---------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Lichee Pi 4A | [LicheePi4A](https://board-docs-frontend.pages.dev/boards/LicheePi4A/) | [XuanTie](https://docs.revyos.dev/docs/Installation/licheepi4a/) |
| Duo          | [Duo](https://board-docs-frontend.pages.dev/boards/Duo/)               | [Sophgo](https://docs.revyos.dev/docs/Installation/milkv-meles/) |
| Duo_256m     | [Duo_256m](https://board-docs-frontend.pages.dev/boards/Duo_256m/)     | [Sophgo](./Installation/licheepi4a.md)                           |
| Duo_S        | [Duo_S](https://board-docs-frontend.pages.dev/boards/Duo_S/)           | [Sophgo](./Image%20flashing/licheeconsole4a.md)                  |
| BPI-F3       | [BPI-F3](https://board-docs-frontend.pages.dev/boards/BPI-F3/)         | [SpaceMIT](./Image%20flashing/licheebook.md)                     |

*(注：完整的支持状态请访问我们的前端示例库网站查阅)*

## 🛠️ 如何参与贡献

我们非常欢迎开发者或实习生提交新的开发板评测或修正现有文档。请遵循以下步骤：

1. **Fork 本仓库** 并拉取到本地。
2. **使用模板**：在 `/templates` 目录下找到标准的文档模板，按照要求填写初始化过程和测试结果。
3. **格式检查**：请确保 Markdown 语法正确，特别注意检查是否包含失效的死链（Broken Links）。
4. **提交 PR**：请在 PR 描述中清晰说明你所测试的开发板型号和使用的工具链版本。

## 📄 版权与许可协议

- 本仓库中的**所有文档与教程内容**均采用 [CC BY 4.0 协议](https://creativecommons.org/licenses/by/4.0/)。转载或二次创作请注明出处。
- 本仓库中的**示例代码与脚本**采用 [Apache 2.0 协议](./LICENSE)。
