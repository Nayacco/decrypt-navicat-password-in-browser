# 🌐 Navicat Password Decryption in Browser

## English Version

🔒 **Secure Navicat Password Decryption** 🔒

Welcome to the **Navicat Password Decryption** repository! This project implements the decryption of Navicat passwords entirely within your browser. It ensures that no requests are sent out, guaranteeing that your passwords remain secure and never leave your device.

### 🚀 Features
- **Pure Browser Implementation**: All decryption operations are performed within the browser.
- **No External Requests**: Ensures that no data is sent to any external server, keeping your information private.
- **Inspired by**: [HyperSine/how-does-navicat-encrypt-password](https://github.com/HyperSine/how-does-navicat-encrypt-password)

### 📖 Usage

#### 📄 How to Export and Get Encrypted String

To decrypt a Navicat password, you first need to export and obtain the encrypted string. Follow these steps:

1. Open Navicat.
2. Click on "File" -> "Export Connections".
3. Check "Export Password".
4. Open the exported `connections.ncx` file with a text editor.
5. Locate the `Password` attribute in the XML file. This attribute contains the encrypted password.
6. Copy the encrypted password string.

**You can directly visit the following link to perform the decryption without cloning the repository:**

👉 [https://Nayacco.github.io/decrypt-navicat-password-in-browser](https://Nayacco.github.io/decrypt-navicat-password-in-browser) 👈

Alternatively, you can:
1. Clone or download this repository.
2. Open the `index.html` file in your favorite browser.
3. Enter your encrypted Navicat password in the provided input field.
4. Click the "Decrypt" button to view the decrypted password.

### 📜 Note
All decryption processes are handled locally within your browser. Your password will not be sent to any server or external entity.

---

## 中文版

🔒 **Navicat 密码解密，确保安全** 🔒

欢迎来到 **Navicat 密码解密** 仓库！此项目在浏览器内完全实现了 Navicat 密码的解密，确保不会发送任何请求，从而保证您的密码安全，不会泄露。

### 🚀 功能
- **纯浏览器实现**：所有解密操作均在浏览器中执行。
- **无外部请求**：确保没有数据发送到任何外部服务器，保障您的信息隐私。
- **参考项目**：[HyperSine/how-does-navicat-encrypt-password](https://github.com/HyperSine/how-does-navicat-encrypt-password)

### 📖 使用方法

#### 📄 如何导出和获取加密字符串

要解密 Navicat 密码，首先需要导出并获取加密的字符串。请按照以下步骤操作：

1. 打开 Navicat。
2. 点击“文件” -> “导出连接”。
3. 勾选“导出密码”。
4. 用文本编辑器打开导出的 `connections.ncx` 文件。
5. 找到 XML 文件中的 `Password` 属性。此属性包含加密的密码。
6. 复制加密的密码字符串。

**您可以直接访问以下链接进行解密，无需克隆仓库：**

👉 [https://Nayacco.github.io/decrypt-navicat-password-in-browser](https://Nayacco.github.io/decrypt-navicat-password-in-browser) 👈

或者，您也可以：
1. 克隆或下载此仓库。
2. 在您喜欢的浏览器中打开 `index.html` 文件。
3. 在输入框中输入加密的 Navicat 密码。
4. 点击“解密”按钮查看解密后的密码。

### 📜 注意
所有解密过程均在您的浏览器本地处理。您的密码不会发送到任何服务器或外部实体。
