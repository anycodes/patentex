# LaTeX专利申请模板

本仓库提供了一套用于起草专利申请文件的LaTeX模板和工具。这些模板旨在简化专利申请过程，提高文档的专业性和一致性。

## 仓库内容

- `font/`: 包含所需的字体文件
  - TimesNewRomanPS...（多个字体文件）
- `images/`: 存放说明书中使用的图片
- `权利要求书.tex`: 权利要求书的LaTeX模板
- `说明书.tex`: 专利说明书的主要LaTeX模板
- `说明书摘要.tex`: 说明书摘要的LaTeX模板
- `说明书附图.tex`: 说明书附图部分的LaTeX模板

## 使用方法

1. 克隆或下载本仓库到您的本地机器。
2. 确保您的系统已安装LaTeX编译环境。
3. 根据您的需求，编辑相应的.tex文件：
   - 在`说明书.tex`中填写您的发明详细说明
   - 在`权利要求书.tex`中列出您的权利要求
   - 在`说明书摘要.tex`中提供发明摘要
   - 如需添加图片，请将图片文件放在`images/`文件夹中，并在`说明书附图.tex`中引用
4. 使用LaTeX编译器（如XeLaTeX）编译主文档（通常是`说明书.tex`）。

## 效果预览

<img width="416" alt="image" src="https://github.com/user-attachments/assets/07384add-cf0b-47ad-a2e3-ff9e3de70c34" />

<img width="412" alt="image" src="https://github.com/user-attachments/assets/0f403277-53ab-4f72-9874-8735aa3786dd" />

<img width="409" alt="image" src="https://github.com/user-attachments/assets/1273f051-82f8-4caf-be58-8399f236801f" />

## 注意事项

- 请确保使用与模板兼容的LaTeX编译器。我们推荐使用XeLaTeX，特别是在处理中文内容时。
- 字体文件已包含在`font/`文件夹中。如果遇到字体问题，请检查字体是否正确安装或路径是否正确。
- 在编辑模板时，请遵循相关专利局的格式要求。

## 贡献

欢迎提交问题报告、功能请求或直接贡献代码。请遵循标准的GitHub工作流程：fork本仓库，创建您的特性分支，提交更改，并发起pull请求。

## 联系方式

如有任何问题或建议，请通过GitHub问题(Issues)与我们联系。
