# ☁️ Cloud & DevOps 6-Month Learning Plan (Git Practice Edition)
 
**目标：**
> 在 6 个月内系统学习 Cloud / DevOps 技能，在 GitHub 上留下可验证的成长轨迹，完成可展示的云端项目，并获得主流证书。
 
---
 
## 🧭 总体方向
- 核心技能：Linux、Python、Docker、Kubernetes、CI/CD、Terraform、AWS  
- 产出成果：
  - 6 个主题仓库（每月一个主项目）
  - 1 个综合项目（完整云架构）
  - 1~2 张权威证书（AWS / Terraform）
  - 每周至少一次 Git 提交（commit）
 
---
 
# 📆 学习计划总览
 
| 月份 | 主题 | 主要成果 |
|------|------|----------|
| 月 1 | Linux + Python 基础 | 系统工具脚本 + Git 基础仓库 |
| 月 2 | Docker 容器化 | Flask 容器化项目 |
| 月 3 | AWS 云平台入门 | 部署 Web 应用到云端 |
| 月 4 | Kubernetes + CI/CD | 自动部署流水线 |
| 月 5 | Terraform + 监控 | 云基础设施自动化 |
| 月 6 | 综合项目 + 认证 | 完整云系统 + 证书通过 |
 
---
 
# 🗓️ 详细周计划
 
---
 
## 🗓️ Month 1 — Linux, Python, Git 基础
 
**目标：**
- 熟悉 Linux 命令、文件系统、进程管理  
- 掌握 Python 自动化脚本  
- 熟练 Git/GitHub 操作  
 
**仓库：** `system-tools-practice`
 
| 周次 | 内容 | 实践任务 | Git 提交建议 |
|------|------|----------|--------------|
| Week 1 | Linux 基础：文件系统、权限、用户 | 在虚拟机中搭建 Ubuntu，创建用户与目录结构 | `init: linux basic environment setup` |
| Week 2 | Bash 脚本编写 | 写 2 个脚本：系统状态监控 & 日志清理 | `feat: add system monitor script` |
| Week 3 | Python 自动化 | 编写 Python 脚本：文件批量处理、系统调用 | `feat: add python automation scripts` |
| Week 4 | Git 基础 | 建立 GitHub 仓库，规范 commit message，写 README | `docs: add learning summary and README` |
 
**推荐资源：**
- 📘 [Linux Foundation LFS101x](https://training.linuxfoundation.org)
- 📘 [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
- 📘 [Pro Git Book](https://git-scm.com/book/en/v2)
 
---
 
## 🗓️ Month 2 — Docker 容器化入门
 
**目标：**
- 掌握 Docker 基础与 Compose  
- 将 Python Web 服务容器化  
 
**仓库：** `docker-lab`
 
| 周次 | 内容 | 实践任务 | Git 提交建议 |
|------|------|----------|--------------|
| Week 5 | Docker 基础命令 | 构建和运行简单镜像 | `feat: add hello-docker example` |
| Week 6 | Dockerfile 编写 | 为 Flask Web 服务创建 Dockerfile | `feat: add flask app dockerfile` |
| Week 7 | Docker Compose | 使用 Compose 运行 Flask + Redis | `feat: add docker-compose.yml for multi-service app` |
| Week 8 | 优化与总结 | 优化镜像体积、编写 README、添加运行截图 | `docs: add docker deployment guide` |
 
**推荐资源：**
- 📘 [Docker Official Docs](https://docs.docker.com/)
- 📺 YouTube: *TechWorld with Nana – Docker Tutorial*
- 💡 项目参考：[Flask + Redis Docker Sample](https://github.com/docker/awesome-compose)
 
---
 
## 🗓️ Month 3 — AWS 云平台实践
 
**目标：**
- 熟悉 AWS 基础服务（EC2, S3, IAM, VPC）  
- 实战部署 Docker 应用  
- 准备 AWS Cloud Practitioner 考试  
 
**仓库：** `aws-lab`
 
| 周次 | 内容 | 实践任务 | Git 提交建议 |
|------|------|----------|--------------|
| Week 9 | AWS 控制台入门 | 注册 AWS 账号、熟悉 IAM 与 EC2 | `chore: add aws account setup notes` |
| Week 10 | 部署 EC2 | 创建 EC2 实例并部署 Flask 容器 | `feat: deploy docker app to ec2` |
| Week 11 | 云存储 & 网络 | 创建 S3 存储桶，配置 VPC 子网 | `feat: add s3 and vpc setup` |
| Week 12 | 总结 + 认证准备 | 整理部署流程文档，准备 AWS 认证 | `docs: add aws deployment guide and notes` |
 
**推荐资源：**
- 📘 [AWS Skill Builder (Free)](https://skillbuilder.aws/)
- 📺 Stephane Maarek’s AWS Courses (Udemy)
- 🎓 Certification: **AWS Cloud Practitioner (CLF-C02)**
 
---
 
## 🗓️ Month 4 — Kubernetes & CI/CD 自动化
 
**目标：**
- 学会容器编排与服务部署  
- 建立 CI/CD 自动化流程  
 
**仓库：** `ci-cd-lab`
 
| 周次 | 内容 | 实践任务 | Git 提交建议 |
|------|------|----------|--------------|
| Week 13 | K8s 基础 | 使用 Minikube 部署容器 | `feat: deploy flask app on kubernetes` |
| Week 14 | 服务与 Ingress | 配置 Service、Ingress 实现访问 | `feat: add ingress and service yaml` |
| Week 15 | Jenkins Pipeline | 自动化构建 Docker 镜像并部署 | `ci: add jenkins pipeline for build/deploy` |
| Week 16 | GitHub Actions | 自动化测试 + 部署 | `ci: setup github actions workflow` |
 
**推荐资源：**
- 📺 *Kubernetes for Beginners (freeCodeCamp)*  
- 📘 [GitHub Actions Docs](https://docs.github.com/en/actions)
- 📘 [Jenkins Official Docs](https://www.jenkins.io/doc/)
 
---
 
## 🗓️ Month 5 — Terraform + 云监控
 
**目标：**
- 学习基础设施即代码（IaC）  
- 配置监控系统（Prometheus + Grafana）  
 
**仓库：** `cloud-infra-automation`
 
| 周次 | 内容 | 实践任务 | Git 提交建议 |
|------|------|----------|--------------|
| Week 17 | Terraform 基础 | 使用 Terraform 创建 EC2 | `feat: add terraform ec2 setup` |
| Week 18 | 模块与变量 | 编写可复用的 Terraform 模块 | `refactor: modularize terraform config` |
| Week 19 | 监控部署 | 配置 Prometheus + Grafana | `feat: add monitoring stack` |
| Week 20 | 综合应用 | Terraform + Docker + 监控结合 | `feat: add full infra automation demo` |
 
**推荐资源：**
- 📘 [Terraform Official Docs](https://developer.hashicorp.com/terraform/docs)
- 🎓 Certification: **HashiCorp Terraform Associate**
- 📺 YouTube: *DevOps Toolkit Series*
 
---
 
## 🗓️ Month 6 — 综合项目 & 证书冲刺
 
**目标：**
- 完成端到端云部署项目  
- 获得 AWS Solutions Architect / Terraform 认证  
 
**仓库：** `cloud-devops-demo`
 
| 周次 | 内容 | 实践任务 | Git 提交建议 |
|------|------|----------|--------------|
| Week 21 | 规划与架构设计 | 绘制系统架构图（draw.io） | `docs: add project architecture diagram` |
| Week 22 | 部署实现 | 整合 Terraform + Docker + CI/CD | `feat: deploy full cloud project` |
| Week 23 | 监控与优化 | 配置监控与告警，写总结报告 | `feat: add monitoring and final report` |
| Week 24 | 考证 & 整理作品集 | 上传成果截图、通过 AWS 认证 | `docs: add certification proof and final summary` |
 
**推荐证书：**
| 证书 | 推荐时间 | 说明 |
|------|------------|------|
| AWS Cloud Practitioner (CLF-C02) | 第 3 月 | 入门认证 |
| AWS Solutions Architect – Associate | 第 6 月 | 中级主流认证 |
| Terraform Associate | 第 5~6 月 | IaC 能力认证 |
 
---
 
# 🧠 Git 留痕技巧总结
 
| 做法 | 效果 |
|------|------|
| 每周至少一次提交 | 展示持续学习能力 |
| 每个阶段一个仓库 | 清晰分层次展示成长路径 |
| README 详写 | 研究生/招聘方快速了解项目 |
| 附上截图与架构图 | 证明你动手做过 |
| 写总结笔记（docs/） | 体现思考与反思能力 |
| 使用标签与版本号 | 呈现真实开发习惯 |
 
---
