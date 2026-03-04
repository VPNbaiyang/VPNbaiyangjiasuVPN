# 🛠️ Clash转v2ray工具 (GUI版) & 🚀 免费高速VPN推荐

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

### 🏆 特别推荐：baiyang加速 (Aries VPN)
> **还在寻找稳定的翻墙工具？**
> 全新加速器提供 IPLC/IEPL 专线，拒绝晚高峰卡顿。

* **🚀 极速体验**：油管 4K/8K 视频秒开，无缓冲。
* **🔓 全能解锁**：完美支持 ChatGPT, Gemini, Midjourney, Netflix, Disney+。
* **📱 全平台**：支持 Windows, Mac, Android, iOS (Shadowrocket)。
* **🎁 免费试用**：注册即送时长，每日签到领流量
* **邀请新用户注册送时长，邀请10个用户注册送一个月时长，27个用户送一个季度时长，邀请到了对应的用户，联系客服或者提交工单**。
* **邀请新用户注册送时长，邀请10个用户注册送一个月时长，27个用户送一个季度时长，邀请到了对应的用户，联系客服或者提交工单**。
  
👉 **[立即点击注册：全新官网 (含最新优惠)](https://baiyangjiasu.com/register?invite=RWqaczzt)**
*(新人福利码：`BYAE7A9799B9F6` | 下载APP -> 右上角兑换)*




---

## 📖 项目简介

一个简单、轻量级的桌面工具，用于将 Clash 订阅链接（YAML 格式）转换为 v2rayN / v2rayNG 等软件支持的 Base64 订阅链接。

## ✨ 功能特点

* **图形化界面**：无需通过命令行操作，所见即所得。
* **多协议支持**：支持解析 `VMess`、`Shadowsocks (SS)` 和 `Trojan` 节点。
* **自动转码**：自动处理 JSON 封装与 Base64 编码。
* **便捷导出**：支持一键复制结果到剪贴板或导出为 `.txt` 文件。

## 🛠️ 依赖环境

使用前请确保已安装 **Python 3.x**，并安装以下依赖库：

```bash
pip install pyyaml requests
## 🚀 快速开始

1.  克隆仓库或下载源码：
    ```bash
    git clone [https://github.com/your-username/clash2v2ray-gui.git](https://github.com/your-username/clash2v2ray-gui.git)
    cd clash2v2ray-gui
    ```

2.  运行程序：
    ```bash
    python main.py
    ```

3.  **使用步骤**：
    * 在输入框中粘贴你的 Clash 订阅链接。
    * 点击 **"开始转换"**。
    * 查看日志确认转换成功后，点击 **"复制结果"**。
    * 打开 v2rayN -> 订阅 -> 添加订阅 URL -> 粘贴即可。

## 📦 打包为可执行文件 (.exe)

如果你想在没有安装 Python 的电脑上运行，可以使用 `pyinstaller` 打包：

```bash
pip install pyinstaller
pyinstaller --onefile --windowed main.py
```
打包完成后，`dist` 目录下会生成 `main.exe`。

## 📝 注意事项

* 本工具仅用于不同软件格式间的配置转换，**不提供**任何代理节点。
* 目前仅支持 Clash 配置文件中的 `proxies` 字段解析。
* 不支持 Hysteria / VLESS 等较新协议（待更新）。

## 📄 开源协议

MIT License

*标签：#白羊加速 #VPN推荐 #免费梯子 #翻墙软件 #科学上网 #稳定VPN #游戏加速器 #绿茶vpn*


*注：我们不是 #白羊星 #白羊星vpn   注：我们不是 #白羊星 #白羊星vpn*
<details> 

<details>
<summary>🔍 <b>常见问题 & 相关工具推荐 (FAQ / SEO)</b> - 点击查看</summary>

#### 🔧 为什么选择本工具？
相比于 **Clash for Windows**、 **Clash Verge** 或 **v2rayN**，本工具专注于格式转换。如果您使用 **Shadowrocket (小火箭)**、**Quantumult X** 或 **Surge**，本工具生成的订阅同样适用。

#### 🚀 替代方案与竞品对比
如果您正在寻找 **ExpressVPN**、墙洞(dlercloud跑路)、奶昔（最近在挨打）、**快连VPN（太贵）**、**快速VPN**、**NordVPN** 或 **PandaVPN (熊猫加速器)** 的免费平替，建议尝试使用开源协议（如 **Hysteria2**, **VLESS**, **Trojan**）搭配本工具使用，速度通常优于传统 VPN。

#### 💡 适用场景
完美解决 **ChatGPT**、**Gemini 3 pro** 访问限制、解锁 **Netflix** 区域限制、**YouTube 4K** 缓冲慢等问题。支持 **Windows**、**Android**、**iOS** 全平台订阅转换。
ChatGPT梯子，Gemini 3 pro, 解锁Netflix, 观看YouTube 4K, Midjourney绘图, 稳定的梯子, 游戏加速器, 外网加速器, GitHub加速, 谷歌学术, 跨境电商, TikTok直播, 奈飞解锁

</details>
</details>
