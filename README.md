<div align="center">

# 👋 嗨，我是 Neo

**✨ 专注于打造优雅后端系统的技术探索者**

**🚀 Python 后端开发工程师 | 🤖  实践家 | 🔧 开源项目贡献者**

</div>

---

<div align="center">
  <img src="images/设计之美.png" alt="Programming background" style="width: 100%; border-radius: 16px; margin-bottom: 30px; box-shadow: 0 8px 32px rgba(0,0,0,0.15); transition: all 0.3s ease; transform: scale(1);" />
  <p style="color: #888; font-size: 0.9em; margin-top: -25px; margin-bottom: 30px;">设计之美，技术之魂</p>
</div>

## 🛠️ 技术栈

<div align="center">

| 领域 | 技术栈 |
|:-----|:-------|
| **后端开发** | <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" /> <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" alt="FastAPI" />
| **AI & ML** | Context-Engineering | RAG | Multi-agent-system |
| **DevOps** | <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" /> <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" /> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
| **数据库** | <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" /> <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/Tortoise%20ORM-4B8BBE?style=for-the-badge" alt="Tortoise ORM" />
| **API开发** | RESTful API | <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge" alt="Pydantic" /> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" alt="Swagger" />
    
    
</div>

<div align="center">
      <p align="center" style="margin-bottom: 20px; font-size: 1.1em; color: #666;">不断进化的技术武器库，为创造卓越产品赋能</p>
</div>

---

## 🌟 开源项目

<div align="center">
  <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixlib=rb-4.0.3&auto=format&fit=crop&w=1740&q=80" alt="编程协作" style="width: 80%; border-radius: 16px; margin-bottom: 30px; box-shadow: 0 8px 32px rgba(0,0,0,0.15); transition: all 0.3s ease;" />
  <p style="color: #888; font-size: 0.9em; margin-top: -25px; margin-bottom: 30px;">协作创新，开源未来</p>
</div>

### 📦 项目矩阵

| 项目 | 一句话 | 技术关键词 |
|:--|:--|:--|
| **Fast Generic Api** | 让 FastAPI 开发像 DRF 一样优雅高效 | FastAPI · Pydantic · Tortoise |
| **Rich Utils** | 终端输出/交互增强工具集（更美观、更工程化） | Rich · CLI · Tooling |


### 🚀 Fast Generic Api

<div align="center">
  <p style="margin-bottom: 15px; font-size: 1.1em; font-weight: 500;">让FastAPI开发像DRF一样优雅高效</p>

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-green.svg)](https://fastapi.tiangolo.com/)
[![Tortoise ORM](https://img.shields.io/badge/Tortoise%20ORM-0.20+-orange.svg)](https://tortoise-orm.readthedocs.io/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

一个为开发者而生的FastAPI自动化API框架，将Django REST Framework的开发便捷性与FastAPI的性能完美结合，让API开发效率提升数倍。

#### ✨ 核心特性
<div align="center">

| 特性 | 描述 |
|:-----|:-----|
| **🎯 CRUD自动化** | 内置完整CRUD操作，减少80%重复代码 |
| **⚡ 快速开发** | 几行代码即可创建生产级API服务 |
| **🛡️ 类型安全** | 基于Pydantic 2.0的严格类型检查，消灭运行时错误 |
| **📈 智能过滤** | 灵活的查询过滤和分页系统，满足复杂业务需求 |
| **🏗️ 模块化设计** | 松耦合架构，易于扩展和定制，适应不同规模项目 |

</div>

#### 📝 快速开始

```python
from fast_generic_api import mixins, GenericAPIView
# 🚀 5分钟创建完整CRUD API
class UserViewSet(
    mixins.ListModelMixin,
    mixins.CreateModelMixin,
    mixins.RetrieveModelMixin,
    mixins.UpdateModelMixin,
    mixins.DestroyModelMixin,
    GenericAPIView
):
    router = router          # 注册到路由
    prefix = "/users"       # API路径前缀
    queryset = User         # 数据查询集
    serializer_class = UserInDB  # 序列化器
    # ✨ 自动生成完整CRUD路由和功能
```

<div align="center">
  <p style="margin-top: 15px; color: #666; font-size: 0.9em;">🔗 项目地址：<a href="https://github.com/fzf54122/fast_generic_api/">GitHub Repository</a></p>
</div>

---

### 🧰 Rich Utils

<div align="center">
  <p><b>让终端输出像 Dashboard 一样清晰优雅</b></p>

  <a href="https://github.com/fzf54122/rich-utils">
    <img src="https://img.shields.io/badge/GitHub-rich--utils-black?logo=github" alt="repo" />
  </a>
  <img src="https://img.shields.io/badge/CLI-Rich-informational.svg" alt="cli" />
  <img src="https://img.shields.io/badge/Focus-Engineering-success.svg" alt="focus" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License" />
</div>

一个面向工程化场景的 **终端 UI / 输出增强工具集**：将 Rich 的 Table / Panel / Progress / Layout 等能力沉淀为可复用组件，让脚本、运维工具、压测平台输出更一致、更可读。

#### ✨ 核心能力

| 能力 | 说明 |
|:--|:--|
| **📊 结构化展示** | 统一表格/面板样式，关键指标一眼可读 |
| **⏱️ 进度与状态** | 进度条、步骤状态、耗时统计更直观 |
| **🧱 可复用组件** | 常用输出组件封装，减少重复代码 |
| **🧰 工程友好** | 适配脚本/CLI/压测平台，输出一致可维护 |

#### 📝 快速开始（示例）

```python
from rich.console import Console
from rich.table import Table

console = Console()

table = Table(title="Run Summary")
table.add_column("Item", style="bold")
table.add_column("Value")

table.add_row("Tasks", "128")
table.add_row("Success", "127")
table.add_row("Fail", "1")

console.print(table)
```
<p align="center"> 🔗 项目地址：<a href="https://github.com/fzf54122/rich-utils/">GitHub Repository</a> </p> 

---

## 🔍 当前工作

<div align="center">
  <img src="images/当前工作.gif" alt="专注工作" style="width: 60%; border-radius: 16px; margin-bottom: 30px; box-shadow: 0 8px 32px rgba(0,0,0,0.15); transition: all 0.3s ease;" />
  <p style="color: #888; font-size: 0.9em; margin-top: -25px; margin-bottom: 30px;">专注投入，匠心打造</p>
</div>

**在技术的海洋中航行，我专注于以下方向**：

- **🚀 打造高性能后端**：基于Python生态，构建稳定、高效的后端服务，让技术成为业务发展的坚实后盾
- **🤖 探索AI落地边界**：将AI Agent技术融入实际业务场景，解锁智能化应用的无限可能
- **🔧 架构与性能优化**：持续打磨系统架构，追求代码的优雅与性能的平衡，为用户带来流畅体验
- **📚 技术分享与成长**：在学习前沿技术的同时，乐于分享知识，与技术社区共同成长

---

## 💡 个人信念

<div align="center">
  <img src="images/个人信念.png" alt="Programming background" style="width: 100%; border-radius: 16px; margin-bottom: 30px; box-shadow: 0 8px 32px rgba(0,0,0,0.15); transition: all 0.3s ease; transform: scale(1);" />
  <p style="color: #888; font-size: 0.9em; margin-top: -15px; margin-bottom: 20px;">灵感无限，未来可期</p>
</div>

> "**AI与后端的融合，将重新定义智能系统的边界。**"

**我始终坚信**：

- 优雅的代码是对未来自己和团队最大的善意
- 技术的价值在于解决实际问题，创造真正的用户价值
- 持续学习与创新，是技术人保持生命力的源泉
- 开放与分享，让技术的光芒照亮更多前行的道路

---

## 📫 联系我

<div align="center">
  <p style="margin-bottom: 15px; font-size: 1.1em; color: #666;">期待与您交流技术，共同成长</p>

<a href="https://github.com/fzf54122" target="_blank" style="margin: 0 10px;">
  <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

<a href="mailto:fzf54122@163.com" target="_blank" style="margin: 0 10px;">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

[//]: # (<a href="https://blog.csdn.net/your-csdn-id" target="_blank" style="margin: 0 10px;">)

[//]: # (  <img src="https://img.shields.io/badge/CSDN-000000?style=for-the-badge&logo=csdn&logoColor=white" alt="CSDN" />)

[//]: # (</a>)

</div>

---

<div align="center" style="padding: 30px 0; border-top: 1px solid #eee;">
  <p style="margin: 0 0 10px 0; color: #666;">✨ 感谢您的访问！</p>
  <p style="margin: 0; font-size: 0.9em; color: #999;">
    如果我的项目对您有帮助，请给个星标支持一下吧～
    <br>
    <span style="margin-top: 5px; display: inline-block;">
      <img src="https://komarev.com/ghpvc/?username=fzf54122&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
    </span>
  </p>
</div>
