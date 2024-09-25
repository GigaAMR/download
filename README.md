## 项目介绍

<div style="text-align: center;">


**练手项目，go实现的简约文件下载器，通过服务器中转下载文件，解决本地网络无法下载文件问题**
</div>

**功能特点：**
* **简单易用：** 用户界面简洁直观，操作方便。
* **高效下载：** 支持多线程下载，加速文件传输。
* **环境支持：** 支持`docker`和所有`linux-amd64`系统
* **镜像下载：** 支持下载`docker镜像`并自动打包为压缩包

**1**：用户从前端输入链接

**2**：后端调用`cavaliergopher/grab/v3`模块

**3**：下载文件到服务器`downloads`文件夹

**4**：服务器`downloads`文件内容渲染到前端

**5**：用户从服务器`downloads`文件内下载指定文件到本地

---

### Docker部署

```
git clone https://github.com/sky22333/download.git
```

```
cd download
```
```
docker compose up -d
```
**项目默认运行在`8080`端口**

---

### 预览

<img src="https://github.com/user-attachments/assets/39c638b0-2f2e-46ca-9ae0-b8c152c5f222" alt="PC截图" width="600">

---
<img src="https://github.com/user-attachments/assets/3ce12bef-95e0-48b3-8c81-2ea80049f264" alt="手机截图" width="300">



### 免责声明

* 本程序仅供学习了解, 非盈利目的，请勿下载有版权的文件，请勿下载非法文件，下载和使用本项目即默认接受此条款。
* 使用本程序必循遵守部署免责声明。使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责。
