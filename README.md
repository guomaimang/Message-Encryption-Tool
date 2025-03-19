# 消息加密工具（Message Encryption Tool）

这是一个基于浏览器的AES加密解密小工具，可用于安全地加密和解密消息。该工具完全在客户端运行，所有加密解密过程均在本地浏览器中进行，不会将任何数据上传到服务器。

![cover](https://raw.githubusercontent.com/guomaimang/Message-Encryption-Tool/refs/heads/main/cover.png)

## 功能特点

- **AES加密与解密**：使用标准AES算法对消息进行加密和解密
- **密钥生成**：支持生成128位、192位和256位的AES密钥
- **聊天加密**：专为聊天应用设计的快速加解密功能
- **完全本地处理**：所有操作均在浏览器本地进行，不会传输数据到服务器
- **简洁直观的界面**：用户友好的界面设计，使用简单

## 使用方法

### 生成AES密钥

1. 打开 `genaes.html` 文件
2. 选择需要的密钥长度（128位、192位或256位）
3. 点击"Generate Key"按钮
4. 密钥将自动下载到本地

### 加密与解密

1. 打开 `index.html` 文件
2. 输入或上传AES密钥
3. 在"明文"框中输入要加密的文本，点击"加密"按钮
4. 在"密文"框中输入要解密的文本，点击"解密"按钮

### 聊天加密

1. 打开 `chat.html` 文件
2. 使用下方的加密功能生成加密消息并复制到剪贴板
3. 使用上方的解密功能解密收到的加密消息

## 技术实现

本项目使用以下技术：

- **HTML/CSS/JavaScript**：前端界面和逻辑实现
- **CryptoJS**：用于AES加密和解密的JavaScript库
- **Web Crypto API**：用于生成安全的随机密钥

## 安全说明

- 使用标准的AES加密算法
- 密钥应妥善保管，请勿共享给不信任的人
- 所有操作均在本地完成，不涉及网络传输

## 许可证

本项目采用Apache License 2.0许可证。详情请查看[LICENSE](LICENSE)文件。

## 相关链接

- [GitHub仓库](https://github.com/guomaimang/Inscription)
- [作者博客](https://guomaimang.github.io) 
