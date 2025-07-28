# Long Long - 好玩的长链接生成器

![GitHub stars](https://img.shields.io/github/stars/chksz/long_url_maker?style=for-the-badge) 
![GitHub forks](https://img.shields.io/github/forks/chksz/long_url_maker?style=for-the-badge)

一个将短链接转换为超长、有趣链接的工具，支持自动跳转功能。纯前端实现，无需服务器即可免费部署到CloudFlare Pages上！

## 🌟 功能特性

- **短链变长链**：将普通URL转换为由 `l` 和 `I` 组成的长字符串
- **自动跳转**：访问生成的长链接会自动重定向到原始URL
- **永久有效**：生成的链接不会过期
- **纯前端实现**：无需后端服务器，仅需一个HTML文件
- **美观UI**：现代化渐变设计，响应式布局
- **一键复制**：方便分享生成的长链接

## 🚀 快速使用

1. **直接访问**：[在线演示](https://iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii.iiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiiii.qzz.io/)
2. **部署到CF Pages**：[Bilibili教程视频]()

## 🛠️ 配置说明

在 `index.html` 文件中找到以下配置部分，按需修改：

```javascript
const config = {
    "domain": window.location.origin, // 自动获取当前域名
    "zero": "l", // 代表二进制0的字符
    "one": "I"   // 代表二进制1的字符
};
```

## 📸 截图预览

![界面截图](https://github.com/user-attachments/assets/e44ce33c-33ab-40ea-a850-3f6c79fbade8)

## 🤝 贡献指南

欢迎提交Pull Request！对于重大更改，请先创建Issue讨论。

1. Fork项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开Pull Request

## 📜 开源协议

本项目采用 [MIT License](LICENSE) 开源。

## 👨‍💻 作者

**ChKSz**  
- GitHub: [@ChKSz](https://github.com/ChKSz)
- 项目主页: [Long Long](https://github.com/chksz/long_url_maker)

---

⭐ 如果这个项目对你有帮助，请给个Star支持一下！
