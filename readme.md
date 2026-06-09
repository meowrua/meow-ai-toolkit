此仓库为个人前端开发常用的 Skills、MCPs、Rules、Commands、Agents 的配置合集。

## 已集成配置

### Taste Skills（设计方向）
- `design-taste-frontend` — 反模板化前端设计 skill，落地页、作品集、重设计
- `full-output-enforcement` — 强制完整代码输出，禁止占位符模式
- `gpt-taste` — GPT 风格设计
- `high-end-visual-design` — 高端视觉设计
- `image-to-code` — 图片转代码
- `industrial-brutalist-ui` — 工业粗野主义 UI
- `minimalist-ui` — 极简 UI
- `redesign-existing-projects` — 已有项目重设计
- `stitch-design-taste` — 拼合设计风格

### ECC Skills（前端开发方向）
- `react-patterns` — React 18/19 模式：Hooks、RSC、Suspense、表单、数据获取
- `react-performance` — React 性能优化：memo、虚拟化、代码分割、bundle 分析
- `react-testing` — React Testing Library + Vitest/Jest 测试模式
- `frontend-patterns` — 跨框架前端模式：组件组合、状态管理、动效、表单、无障碍
- `vite-patterns` — Vite 配置、插件、HMR、环境变量、构建优化、库模式
- `nextjs-turbopack` — Next.js 16+ 和 Turbopack 模式
- `e2e-testing` — Playwright E2E 测试：POM、CI/CD 集成、防抖策略
- `design-system` — 设计系统生成与审计（色彩、排版、间距、暗色模式等 10 维度）
- `accessibility` — WCAG 2.2 无障碍模式（Web + iOS/Android）
- `frontend-a11y` — 前端专项无障碍：语义化 HTML、ARIA、焦点管理、键盘导航
- `browser-qa` — 浏览器自动化视觉测试与 UI 交互验证

### Agents（智能体）
- `react-reviewer` — React/JSX 专项代码审查（Hooks 正确性、RSC 边界、无障碍、安全）
- `react-build-resolver` — React 构建错误诊断修复（Vite/webpack/Next.js/CRA/Parcel）
- `a11y-architect` — 无障碍架构师（WCAG 2.2 AA 合规）
- `typescript-reviewer` — TypeScript 代码审查（类型安全、异步正确性）

### Commands（斜杠命令）
- `/react-review` — React 代码审查命令
- `/react-build` — React 构建修复命令
- `/react-test` — React TDD 命令（RTL + Vitest/Jest）
- `/code-review` — 通用代码审查命令

### Rules（始终遵循的规则）
- `rules/react/` — React 规则：编码风格、Hooks、模式、安全、测试
- `rules/typescript/` — TypeScript 规则：编码风格、模式、安全、测试
- `rules/web/` — Web 规则：编码风格、设计质量、性能、安全、测试
- `rules/common/` — 通用规则：代码审查、开发工作流、Git 工作流、安全

### MCP 配置
- `mcp-configs/mcp-servers.json` — MCP Server 配置集合（Playwright、Magic UI、Vercel、Cloudflare 等）
