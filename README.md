# ChatGPT MD 汉化版

这是 [ChatGPT MD](https://github.com/bramses/chatgpt-md) 的汉化版本，增加了以下功能：

- 完整的中文界面
- 支持自定义 API 地址，可使用任何兼容 OpenAI 格式的第三方服务
- 默认支持 GPT-4 Turbo

## 主要特点

- 支持在任何 MD 笔记中使用 ChatGPT
- 支持自定义 API 地址
- 支持选择不同的 GPT 模型
- 使用 frontmatter 配置 ChatGPT API 参数
- 实时流式响应
- 支持常规 Markdown 格式
- 支持从选中文本创建对话
- 支持自动推断标题
- 支持在光标位置或文件末尾生成内容

## 第三方 API 服务推荐

本插件支持使用第三方 API 服务来降低使用成本和提高连接稳定性。以下是推荐的服务：

### Burn.hair API

- 官方网站：[https://burn.hair/](https://burn.hair/)
- 注册链接：[https://burn.hair/register?aff=z5VQ](https://burn.hair/register?aff=z5VQ)

特点：
- 支持 GPT-4 Turbo
- 稳定的连接速度
- 合理的价格
- 完全兼容 OpenAI API 格式

使用方法：
1. 注册并获取 API Key
2. 在插件设置中填写 API 地址：`https://burn.hair/v1/chat/completions`
3. 填入你的 API Key

## 安装方法

1. 下载此仓库到你的 Obsidian 插件目录：
   `你的笔记库/.obsidian/plugins/`

2. 进入插件目录并安装依赖：
   ```bash
   cd chatgpt-md-zh
   npm install
   npm run build
   ```

3. 在 Obsidian 中启用插件

4. 在插件设置中：
   - 设置 API 密钥
   - 设置 API 地址（如果使用第三方服务）
   - 设置对话文件夹和模板文件夹
   - 选择默认模型

## 使用说明

1. 创建新的对话：
   - 使用快捷键（推荐设置为 alt-[）
   - 或使用命令面板中的 "Chat" 命令

2. 自定义 API 地址：
   - 在设置中填写默认 API 地址
   - 或在对话的 frontmatter 中使用 url 参数指定

3. 选择模型：
   - 在设置中选择默认模型
   - 或在对话的 frontmatter 中使用 model 参数指定

## 致谢

- 原项目作者：[Bram Adams](https://github.com/bramses)
- 原项目地址：[chatgpt-md](https://github.com/bramses/chatgpt-md)

## 许可证

MIT License