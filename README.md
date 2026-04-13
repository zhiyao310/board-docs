# board-docs

[中文](./README_zh.md) / [English](./README.md)

Welcome to the RuyiSDK development board tutorial and example documentation center. This repository mainly contains environment initialization guides, basic examples, peripheral examples, multimedia, AI, and other tutorial documents for various RISC-V development boards.

## 📚 Directory Structure

- `/boards`: Stores tutorial documents categorized by development board model (in Markdown format).
- `/templates`: Contains PR templates and documentation templates for adding new development boards.

## 🚀 Supported Development Board Matrix

This repository currently includes, but is not limited to, documentation resources for the following hardware:

| Supported Device | Example Documentation                                                      | Chip Vendor                                                           |
| ---------------- | -------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| Lichee Pi 4A     | [LicheePi4A](https://board-docs-frontend.pages.dev/boards/LicheePi4A/)     | [XuanTie](https://docs.revyos.dev/docs/Installation/licheepi4a/)      |
| Duo              | [Duo](https://board-docs-frontend.pages.dev/boards/Duo/)                   | [Sophgo](https://docs.revyos.dev/docs/Installation/milkv-meles/)      |
| Duo_256m         | [Duo_256m](https://board-docs-frontend.pages.dev/boards/Duo_256m/)         | [Sophgo](./Installation/licheepi4a.md)                                |
| Duo_S            | [Duo_S](https://board-docs-frontend.pages.dev/boards/Duo_S/)               | [Sophgo](./Image%20flashing/licheeconsole4a.md)                       |
| BPI-F3           | [BPI-F3](https://board-docs-frontend.pages.dev/boards/BPI-F3/)             | [SpaceMIT](./Image%20flashing/licheebook.md)                          |

*(Note: For the complete support status, please visit our frontend example repository website.)*

## 🛠️ How to Contribute

We warmly welcome developers or interns to submit new development board evaluations or improve existing documentation. Please follow the steps below:

1. **Fork this repository** and clone it locally.  
2. **Use templates**: Find the standard documentation template in the `/templates` directory and fill in the initialization process and test results as required.  
3. **Format check**: Ensure correct Markdown syntax, and pay special attention to checking for broken links.  
4. **Submit a PR**: Clearly describe the development board model you tested and the toolchain version used in the PR description.  

## 📄 License

- All **documentation and tutorial content** in this repository is licensed under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/). Please provide proper attribution when redistributing or modifying.
- All **example code and scripts** in this repository are licensed under the [Apache 2.0 License](./LICENSE).