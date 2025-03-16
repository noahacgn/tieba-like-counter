# 百度贴吧点赞数据显示

一个简单而强大的油猴脚本，用于在百度贴吧显示帖子的点赞数据，让浏览体验更加丰富！

## 📝 功能介绍

- 🌟 **显示主题帖点赞数**：在帖子标题旁边直观显示点赞数量
- 🏢 **显示楼层点赞数**：在每个楼层回复尾部显示点赞数量
- 🔄 **适配翻页**：支持贴吧翻页后自动加载点赞数据
- 💼 **设置菜单**：通过油猴菜单轻松设置BDUSS
- 🚀 **智能加载**：自动适应网络延迟和页面加载速度

## 💻 安装方法

### 方法一：通过油猴商店安装

1. 在浏览器中安装 [Tampermonkey](https://www.tampermonkey.net/) 或类似的用户脚本管理器
2. 前往 [Greasy Fork](https://greasyfork.org/zh-CN/scripts/529982) 页面安装本脚本

### 方法二：手动安装

1. 在浏览器中安装 [Tampermonkey](https://www.tampermonkey.net/) 或类似的用户脚本管理器
2. 点击本仓库中的 `tieba_like_counter.user.js` 文件
3. 点击 `Raw` 按钮查看原始文件
4. Tampermonkey 会自动检测并提示安装，点击安装即可

## 🔑 使用说明

1. 安装脚本后，首次访问百度贴吧的帖子页面时，会弹出提示输入BDUSS
2. 输入您的BDUSS值后，页面将自动显示点赞数据
3. 之后访问贴吧时将自动使用保存的BDUSS值
4. 如需更换BDUSS，可点击油猴菜单中的"设置BDUSS"选项

### 如何获取BDUSS

1. 登录百度贴吧网页版
2. 按F12打开浏览器开发者工具
3. 切换到"应用"或"Application"标签页
4. 在左侧找到"Cookies" → "tieba.baidu.com"
5. 在右侧列表中找到名为"BDUSS"的cookie，复制其值即可

## ✨ 特色功能

- **高效缓存机制**：缓存已获取的数据，减少重复请求
- **智能重试机制**：页面加载慢时自动延迟处理，确保数据正确显示
- **优雅的UI设计**：简洁美观的点赞数显示，不影响贴吧原有界面
- **轻量级实现**：使用原生JavaScript编写，无需任何外部依赖

## 📊 兼容性

- ✅ Chrome / Edge / Firefox 等主流浏览器
- ✅ 兼容PC端百度贴吧
- ✅ 兼容夜间模式

## 📌 注意事项

- 本脚本需要用户提供自己的BDUSS才能正常工作
- BDUSS仅保存在本地浏览器中，不会上传至任何服务器
- 请不要将您的BDUSS泄露给他人

## 🤝 支持项目

如果您觉得这个脚本对您有帮助，请考虑：

- ⭐ 在GitHub上给项目[加星标](https://github.com/noahacgn/tieba-like-counter)
- 🔄 向您的朋友推荐本脚本
- 🐛 如果发现问题，请在GitHub上提交Issue
- 🧩 欢迎贡献代码，提交Pull Request

## 📄 开源协议

本项目采用 MIT 许可证开源。

---

Made with ❤️ by [noahacgn](https://github.com/noahacgn) 