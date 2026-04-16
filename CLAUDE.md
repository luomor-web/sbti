# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概述

本项目包含两个独立的网站：

1. **SBTI 人格测试网站** - 基于大五人格理论的学生性格测试工具
2. **SBTi 企业气候目标成熟度评估** - 基于 SBTi 框架的企业气候评估工具

## 技术栈

- HTML5 (单文件结构，内联 CSS 和 JavaScript)
- Tailwind CSS (CDN)
- Font Awesome (CDN)
- Google Analytics / 百度统计
- Google AdSense

## 项目结构

```
sbti/
├── index.html          # 人格测试首页
├── test.html           # 人格测试页面
├── results.html        # 人格测试结果页面
├── about.html          # 关于页面
├── contact.html        # 联系页面
├── agent.md            # AI 阅读指引
├── v1/                 # 旧版本页面备份
├── sbti-assessment/
│   ├── index.html
│   └── sbti_assessment_website.html  # 企业气候评估主页面
└── docs/
    ├── README.md
    └── agent.md
```

## 开发命令

项目为纯静态 HTML 页面，无需构建步骤。直接在浏览器中打开 HTML 文件即可预览。

## SEO 优化要点

所有页面已包含：
- 完整的 meta 标签（title, description, keywords, robots）
- Open Graph / Facebook 分享标签
- Twitter Card 标签
- 结构化数据 (Schema.org JSON-LD)

修改页面时需保持这些 SEO 元素的完整性和准确性。

## 修改范围

- **允许修改**: `*.html`, `docs/README.md`, `docs/agent.md`, `agent.md`
- **不建议修改**: 外部统计脚本、广告脚本（除非有明确优化需求）

## 相关文档

- `agent.md` - 人格测试网站的 AI 阅读指引
- `sbti-assessment/agent.md` - 企业气候评估网站的 AI 阅读指引
- `docs/agent.md` - 详细开发指南和任务优先级
