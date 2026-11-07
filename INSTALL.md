# 安装与尺寸调整教程

## 已创建的小码

当前 ChatGPT Work 账户里已经创建并激活“小码”。在 ChatGPT 桌面应用中，打开个人资料菜单并选择 Pets，然后选择小码。输入 /pet 或在命令菜单中选择 Show pet 可显示桌宠。

若只想把小码显示得更大，请打开 Settings > Pets > Customize > Pet size，将 Pet size 控件调到比默认值约大 20% 的位置。这个设置调整桌面显示大小，不需要改动图集。

## 从仓库素材创建新宠物

1. 使用 GitHub Desktop 克隆本私有仓库，或从 GitHub 下载 ZIP 并解压。
2. 在 ChatGPT Work 中开启 Pets 工具/插件。
3. 将 assets/pet/xiaoma-spritesheet-v2.png 附加到 ChatGPT Work 对话。
4. 使用下面的提示词，让 Pets 按原图集创建；不要选择 20% 预览图集。

提示词：

> 使用附件中的透明 PNG 原样创建 ChatGPT Work 自定义桌宠，名字叫“小码”，使用 Pets v2 图集。保留真人形象和所有动作，不重新生成或改动漫化。校验通过后创建并激活。

5. 创建完成后打开 Settings > Pets 或 Pets 选择器并刷新，选择新宠物。
6. 在 ChatGPT 桌面应用中打开 Settings > Pets > Customize > Pet size，按需调大显示尺寸。

## 选用正确的文件

- 安装文件：assets/pet/xiaoma-spritesheet-v2.png，透明 PNG，1536×2288 像素，Pets v2。
- 20% 展示动画：assets/previews/20-percent/xiaoma-all-states-20-percent.gif。
- 20% 展示大画布：assets/previews/20-percent/xiaoma-atlas-20-percent-preview-only.png，1840×2750 像素，仅用于预览，不能用来安装。

## Desktop、Web 与工作区说明

OpenAI 官方 Pets 文档说明，桌面应用可在 Settings > Pets > Customize 调整 Pet size；桌面应用中创建的自定义宠物保存在本机，不会自动同步到 ChatGPT Web。

ChatGPT Web 的上传入口为 Settings > Personalization > Pet。官方文档当前列出的 Web 上传图集规格是透明 PNG 或 WebP、1536×1872 像素、最大 20 MiB。本项目图集是 1536×2288 的 v2 图集；请在 Pets v2 工作流中使用它，不要将它误认为 Web 页面所列的 v1 格式。

参考：
- OpenAI 官方 Pets 文档：https://learn.chatgpt.com/docs/pets
- OpenAI 官方 Pets 安装链接说明：https://learn.chatgpt.com/docs/reference/commands

