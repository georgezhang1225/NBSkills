# AI 开发 Skills & Rules 资源总览

> 收集时间：2026-07-28
> 收集工具：Trae Agent
> 技术栈：Vue2 + Element UI + ECharts + Maptalks / .NET Core 6 / MySQL + SQL Server
> 总计资源：229 个 | 前端：80 | 后端：35 | 通用：85 | Rules：14

---

## 统计摘要

| 分类 | 数量 | 说明 |
|------|------|------|
| 前端 (Vue2 技术栈) | 93 | 设计美学 70 + UI 组件 16 (taste-skill 系列 10 + impeccable 1 + maptalks, big-screen, anti-ui-slop 等) + Element UI Vue2 技能 + Vue2 Options API + Vue Router + Vue 调试 + Vue 测试 |
| 后端 (.NET Core 6) | 35 | API 设计 6 + 数据库 3 + DevOps 8 + 性能 3 + 安全 5 + 测试 10 |
| 通用 | 85 | 代码质量 50 + 文档 5 + Git 18 + 项目设置 1 + AI 协作 11 |
| Rules 规范 | 14 | Claude 书籍 14 + Cursor 规则 29 |
| **总计** | **242** | |

---

## 前端 (Frontend) — Vue2 + Element UI + ECharts + Maptalks

### UI 设计与组件

| 名称 | 描述 | ⭐ | 适用工具 | 路径 | 评级 |
|------|------|---|---------|------|------|
| element-ui-vue2 | Element UI Vue2 全套 69 组件 API 文档（消灭组件 API 幻觉） | 开源 | Cursor/Claude/Trae | frontend/ui-design/element-ui-vue2 | A |
| vue-options-api-best-practices | Vue 2 Options API 最佳实践（data/methods/computed/watch） | 官方 | Cursor/Claude/Trae | frontend/ui-design/vue-options-api-best-practices | A |
| vue-router-best-practices | Vue Router 最佳实践指南 | 官方 | Cursor/Claude/Trae | frontend/ui-design/vue-router-best-practices | A |
| vue-debug-guides | Vue 调试指南 & 常见问题排查 | 官方 | Cursor/Claude/Trae | frontend/ui-design/vue-debug-guides | A |
| maptalks-map-visualization | Maptalks.js 2D/3D 地图可视化指南 | 自定义 | Cursor/Claude/Trae | frontend/ui-design/maptalks-map-visualization | B |
| big-screen-dashboard | 大屏数据驾驶舱设计规范（ECharts 等） | 自定义 | Cursor/Claude/Trae | frontend/ui-design/big-screen-dashboard | B |
| anti-ui-slop | 通用 UI 质量门禁，避免泛化 UI | 37k | Cursor/Claude/Trae | frontend/ui-design/anti-ui-slop | A |
| penpot-uiux-design | Penpot 开源 UI/UX 设计工具 | 37k | Cursor/Claude/Trae | frontend/ui-design/penpot-uiux-design | A |
| premium-frontend-ui | 高质量前端 UI 设计规范 | 37k | Cursor/Claude/Trae | frontend/ui-design/premium-frontend-ui | A |
| markdown-to-html | Markdown 转 HTML 工具 | 37k | Cursor/Claude/Trae | frontend/ui-design/markdown-to-html | A |
| oo-component-documentation | 面向对象组件文档生成 | 37k | Cursor/Claude/Trae | frontend/ui-design/oo-component-documentation | A |
| ui-screenshots | UI 截图参考 | 37k | Cursor/Claude/Trae | frontend/ui-design/ui-screenshots | A |
| taste-skill | 🆕 AI Agent 反模板化前端设计框架 — 三旋钮调参（DESIGN_VARIANCE/MOTION_INTENSITY/VISUAL_DENSITY），含 13 个细分设计技能 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/taste-skill | A |
| taste-skill-v1 | 🆕 taste-skill v1 原版，供依赖旧行为的项目使用 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/taste-skill-v1 | A |
| gpt-tasteskill | 🆕 GPT/Codex 专用强化版，更高的布局方差、更强的 GSAP 约束 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/gpt-tasteskill | A |
| redesign-skill | 🆕 现有项目改版：先审计 UI，再修复布局/间距/层级 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/redesign-skill | A |
| soft-skill | 🆕 高端质感 UI：柔和对比、留白、高级字体、弹簧动效 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/soft-skill | A |
| minimalist-skill | 🆕 编辑风格产品 UI（Notion/Linear 感），克制配色 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/minimalist-skill | A |
| brutalist-skill | 🆕 瑞士字体、锐利对比、实验性布局 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/brutalist-skill | A |
| output-skill | 🆕 强制完整输出，禁止 // ... 占位符 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/output-skill | A |
| image-to-code-skill | 🆕 图片优先流程：生成参考图 → 分析 → 实现代码 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/image-to-code-skill | A |
| stitch-skill | 🆕 兼容 Google Stitch 的规则集 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/stitch-skill | A |
| imagegen-frontend-web | 🆕 网站设计稿生成：Hero、Landing、多段落排版 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/imagegen-frontend-web | A |
| imagegen-frontend-mobile | 🆕 移动端界面和流程设计 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/imagegen-frontend-mobile | A |
| brandkit | 🆕 品牌套件：Logo 方向、配色、字体、视觉识别 | 45k+ | Cursor/Claude/Trae | frontend/ui-design/brandkit | A |
| impeccable | 🆕 AI 设计工作系统 — 23 条设计命令（/audit /critique /polish 等）+ 46 条确定性检测规则，实时浏览器迭代 | 47.8k+ | Cursor/Claude/Trae/Codex | frontend/ui-design/impeccable | A |

### 前端测试

| 名称 | 描述 | ⭐ | 适用工具 | 路径 | 评级 |
|------|------|---|---------|------|------|
| vue-testing-best-practices | Vue 应用测试最佳实践（单元测试、组件测试） | 官方 | Cursor/Claude/Trae | frontend/testing/vue-testing-best-practices | A |

### 设计美学 (通用设计风格，适用于 Vue2 前端)

| 名称 | 描述 | 路径 |
|------|------|------|
| design-agentic ~ design-vintage | 70+ 种设计风格（企业、现代、简约、专业等） | frontend/aesthetics/design-* |

---

## 后端 (Backend) — .NET Core 6

### API 设计

| 名称 | 描述 | ⭐ | 适用工具 | 路径 | 评级 |
|------|------|---|---------|------|------|
| api-doc-generator | API 文档生成器 | 37k | Cursor/Claude/Trae | backend/api-design/api-doc-generator | A |
| openapi-to-application-code | OpenAPI 规范生成应用代码 | 37k | Cursor/Claude/Trae | backend/api-design/openapi-to-application-code | A |
| typespec-api-operations | TypeSpec API 操作定义 | 37k | Cursor/Claude/Trae | backend/api-design/typespec-api-operations | A |
| typespec-create-api-plugin | TypeSpec API 插件创建 | 37k | Cursor/Claude/Trae | backend/api-design/typespec-create-api-plugin | A |
| pdftk-server | PDFtk 服务端工具 | 37k | Cursor/Claude/Trae | backend/api-design/pdftk-server | A |
| winmd-api-search | Windows API 搜索 | 37k | Cursor/Claude/Trae | backend/api-design/winmd-api-search | A |

### 数据库 (MySQL + SQL Server)

| 名称 | 描述 | ⭐ | 适用工具 | 路径 | 评级 |
|------|------|---|---------|------|------|
| sql-code-review | 通用 SQL 代码审查（MySQL/SQL Server/Oracle） | 37k | Cursor/Claude/Trae | backend/database/sql-code-review | A |
| sql-optimization | 通用 SQL 性能优化（MySQL/SQL Server/Oracle） | 37k | Cursor/Claude/Trae | backend/database/sql-optimization | A |
| sql-server-table-reconciliation | SQL Server 表对比与同步 | 37k | Cursor/Claude/Trae | backend/database/sql-server-table-reconciliation | A |

### DevOps

| 名称 | 描述 | ⭐ | 适用工具 | 路径 | 评级 |
|------|------|---|---------|------|------|
| multi-stage-dockerfile | 多阶段 Dockerfile 构建 | 37k | Cursor/Claude/Trae | backend/devops/multi-stage-dockerfile | A |
| create-github-action-workflow-specification | GitHub Actions 工作流规范 | 37k | Cursor/Claude/Trae | backend/devops/create-github-action-workflow-specification | A |
| devops-rollout-plan | DevOps 发布计划 | 37k | Cursor/Claude/Trae | backend/devops/devops-rollout-plan | A |
| github-actions-efficiency | GitHub Actions 效率优化 | 37k | Cursor/Claude/Trae | backend/devops/github-actions-efficiency | A |
| github-actions-hardening | GitHub Actions 安全加固 | 37k | Cursor/Claude/Trae | backend/devops/github-actions-hardening | A |
| github-actions-runtime-upgrade-conventions | GitHub Actions 运行时升级规范 | 37k | Cursor/Claude/Trae | backend/devops/github-actions-runtime-upgrade-conventions | A |
| import-infrastructure-as-code | IaC 导入 | 37k | Cursor/Claude/Trae | backend/devops/import-infrastructure-as-code | A |
| mcp-deploy-manage-agents | MCP 部署管理 Agent | 37k | Cursor/Claude/Trae | backend/devops/mcp-deploy-manage-agents | A |

### 性能

| 名称 | 描述 | ⭐ | 适用工具 | 路径 | 评级 |
|------|------|---|---------|------|------|
| prompt-optimizer | Prompt 优化器 | 37k | Cursor/Claude/Trae | backend/performance/prompt-optimizer | A |
| memory-merger | 内存合并工具 | 37k | Cursor/Claude/Trae | backend/performance/memory-merger | A |
| codebase-memory-mcp | 代码库内存 MCP | 37k | Cursor/Claude/Trae | backend/performance/codebase-memory-mcp | A |

### 安全

| 名称 | 描述 | ⭐ | 适用工具 | 路径 | 评级 |
|------|------|---|---------|------|------|
| security-review | AI 安全审查（SQL 注入/XSS/认证等） | 37k | Cursor/Claude/Trae | backend/security/security-review | A |
| secret-scanning | GitHub Secret 扫描配置 | 37k | Cursor/Claude/Trae | backend/security/secret-scanning | A |
| mcp-security-audit | MCP 安全审计 | 37k | Cursor/Claude/Trae | backend/security/mcp-security-audit | A |
| mcp-implementation-security-review | MCP 实现安全审查 | 37k | Cursor/Claude/Trae | backend/security/mcp-implementation-security-review | A |
| agent-owasp-compliance | OWASP 合规检查 | 37k | Cursor/Claude/Trae | backend/security/agent-owasp-compliance | A |

### 测试

| 名称 | 描述 | ⭐ | 适用工具 | 路径 | 评级 |
|------|------|---|---------|------|------|
| csharp-mstest | MSTest 3.x/4.x 单元测试最佳实践 | 37k | Cursor/Claude/Trae | backend/testing/csharp-mstest | A |
| unit-test-generator | 单元测试生成器 | 37k | Cursor/Claude/Trae | backend/testing/unit-test-generator | A |
| webapp-testing | Web 应用测试 | 37k | Cursor/Claude/Trae | backend/testing/webapp-testing | A |
| breakdown-test | 测试分解 | 37k | Cursor/Claude/Trae | backend/testing/breakdown-test | A |
| javascript-typescript-jest | JS/TS Jest 测试 | 37k | Cursor/Claude/Trae | backend/testing/javascript-typescript-jest | A |
| playwright-explore-website | Playwright 网站探索 | 37k | Cursor/Claude/Trae | backend/testing/playwright-explore-website | A |
| playwright-generate-test | Playwright 测试生成 | 37k | Cursor/Claude/Trae | backend/testing/playwright-generate-test | A |
| scoutqa-test | ScoutQA 测试 | 37k | Cursor/Claude/Trae | backend/testing/scoutqa-test | A |
| unit-test-vue-pinia | Vue Pinia 单元测试 | 37k | Cursor/Claude/Trae | backend/testing/unit-test-vue-pinia | A |
| legacy-circuit-mockups | 遗留电路 Mockup | 37k | Cursor/Claude/Trae | backend/testing/legacy-circuit-mockups | A |

---

## 通用 (General)

### 代码质量（.NET/C# 相关）

| 名称 | 描述 | 路径 |
|------|------|------|
| dotnet-best-practices | .NET/C# 最佳实践 | general/code-quality/dotnet-best-practices |
| dotnet-design-pattern-review | .NET 设计模式审查 | general/code-quality/dotnet-design-pattern-review |
| dotnet-timezone | .NET 时区处理 | general/code-quality/dotnet-timezone |
| dotnet-upgrade | .NET 框架升级分析 | general/code-quality/dotnet-upgrade |
| ef-core | Entity Framework Core 最佳实践 | general/code-quality/ef-core |
| efcore-d2-db-diagram | EF Core 数据库关系图 | general/code-quality/efcore-d2-db-diagram |
| containerize-aspnetcore | ASP.NET Core Docker 容器化 | general/code-quality/containerize-aspnetcore |
| containerize-aspnet-framework | ASP.NET Framework 容器化 | general/code-quality/containerize-aspnet-framework |
| csharp-async | C# 异步编程最佳实践 | general/code-quality/csharp-async |
| csharp-nunit | C# NUnit 测试 | general/code-quality/csharp-nunit |
| csharp-tunit | C# TUnit 测试 | general/code-quality/csharp-tunit |
| csharp-xunit | C# xUnit 测试 | general/code-quality/csharp-xunit |
| code-review | 通用代码审查 | general/code-quality/code-review |
| codeql | CodeQL 代码分析 | general/code-quality/codeql |
| code-tour | 代码导览 | general/code-quality/code-tour |
| debug-helper | 调试助手 | general/code-quality/debug-helper |
| dependabot | Dependabot 配置 | general/code-quality/dependabot |
| diagnose | 诊断工具 | general/code-quality/diagnose |
| doublecheck | 双重检查 | general/code-quality/doublecheck |
| eval-driven-dev | 评估驱动开发 | general/code-quality/eval-driven-dev |
| eyeball | 代码审查辅助 | general/code-quality/eyeball |
| refactor | 代码重构 | general/code-quality/refactor |
| refactor-plan | 重构计划 | general/code-quality/refactor-plan |
| refactor-method-complexity-reduce | 方法复杂度降低 | general/code-quality/refactor-method-complexity-reduce |
| review-and-refactor | 审查与重构 | general/code-quality/review-and-refactor |
| write-coding-standards-from-file | 编写编码规范 | general/code-quality/write-coding-standards-from-file |

### 文档与 Git

| 名称 | 描述 | 路径 |
|------|------|------|
| create-readme | README 生成 | general/documentation/create-readme |
| csharp-docs | C# 文档生成 | general/documentation/csharp-docs |
| documentation-writer | 文档编写 | general/documentation/documentation-writer |
| md-to-docx | Markdown 转 Word | general/documentation/md-to-docx |
| readme-blueprint-generator | README 蓝图生成 | general/documentation/readme-blueprint-generator |
| git-commit | Git 提交信息 | general/git-workflow/git-commit |
| conventional-commit | 约定式提交 | general/git-workflow/conventional-commit |
| conventional-branch | 约定式分支命名 | general/git-workflow/conventional-branch |
| git-flow-branch-creator | Git Flow 分支创建 | general/git-workflow/git-flow-branch-creator |
| gitmoji | GitMoji 提交表情 | general/git-workflow/gitmoji |

### AI 协作

| 名称 | 描述 | 路径 |
|------|------|------|
| dotnet-mcp-builder | .NET MCP 构建器 | general/ai-collaboration/dotnet-mcp-builder |
| mcp-cli | MCP 命令行工具 | general/ai-collaboration/mcp-cli |
| webmcpify | Web MCP 转换 | general/ai-collaboration/webmcpify |
| agent-governance | Agent 治理 | general/ai-collaboration/agent-governance |
| agent-skill-stack | Agent 技能栈 | general/ai-collaboration/agent-skill-stack |
| agentic-eval | Agent 评估 | general/ai-collaboration/agentic-eval |
| ai-ready | AI 就绪检查 | general/ai-collaboration/ai-ready |
| ai-team-orchestration | AI 团队编排 | general/ai-collaboration/ai-team-orchestration |

---

## Rules 规范

### Claude 书籍知识

| 名称 | 描述 | 路径 |
|------|------|------|
| book-clean-code | Clean Code 编码规范 | rules/claude-skills/book-clean-code |
| book-clean-architecture | 整洁架构 | rules/claude-skills/book-clean-architecture |
| book-domain-driven-design | 领域驱动设计 | rules/claude-skills/book-domain-driven-design |
| book-designing-data-intensive-applications | 数据密集型应用设计 | rules/claude-skills/book-designing-data-intensive-applications |
| book-refactoring | 重构 | rules/claude-skills/book-refactoring |
| book-the-pragmatic-programmer | 程序员修炼之道 | rules/claude-skills/book-the-pragmatic-programmer |
| book-working-effectively-with-legacy-code | 有效处理遗留代码 | rules/claude-skills/book-working-effectively-with-legacy-code |
| book-code-complete | 代码大全 | rules/claude-skills/book-code-complete |
| book-patterns-of-enterprise-application-architecture | 企业应用架构模式 | rules/claude-skills/book-patterns-of-enterprise-application-architecture |
| book-release-it | 发布管理 | rules/claude-skills/book-release-it |
| book-refactoring-guru | 重构大师 | rules/claude-skills/book-refactoring-guru |
| book-a-philosophy-of-software-design | 软件设计哲学 | rules/claude-skills/book-a-philosophy-of-software-design |
| book-domain-driven-design-distilled | DDD 精粹 | rules/claude-skills/book-domain-driven-design-distilled |
| book-implementing-domain-driven-design | 实现 DDD | rules/claude-skills/book-implementing-domain-driven-design |

### Cursor 规则（保留的与 Vue2/.NET/SQL 相关规则）

| 名称 | 路径 |
|------|------|
| anti-overengineering, clean-code, code-quality, code-review, database, docker, git* | rules/cursor-rules/*.mdc |
| csharp*, dotnet, ef-core, mysql, sql-server, sqlite | rules/cursor-rules/*.mdc |
| vue, vue-3-nuxt-3*, vue-claude-stack, vue-pinia, typescript-vuejs | rules/cursor-rules/*.mdc |
| security-devsecops, web-app-optimization, unit-testing* | rules/cursor-rules/*.mdc |

---

## 使用说明

1. **Trae 中使用**：将对应 Skill 文件夹复制到项目 `.trae/skills/` 目录
2. **Cursor 中使用**：复制到 `.cursor/rules/` 目录
3. **Claude Code 中使用**：复制到 `.claude/skills/` 目录
4. **Copilot 中使用**：复制到 `.github/skills/` 目录

> 由于 SKILL.md 是开放标准，大部分 Skills 跨工具通用。
