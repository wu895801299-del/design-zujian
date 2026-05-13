---
version: alpha
name: KiGen Creator Dashboard
description: "A professional enterprise-grade dashboard design system for short drama creator monetization platform. Features a clean, functional aesthetic with a deep indigo primary accent against a subtle warm-gray surface. The design emphasizes data clarity, hierarchy through typography weight rather than color saturation, and generous whitespace that allows dense information without visual clutter."
$$escape: false

colors:
  primary: "#3855D5"
  primary-hover: "#5F7CE3"
  primary-active: "#253AB0"
  primary-disable: "#B0C4FF"
  primary-bg: "#F0F5FF"
  primary-bg-hover: "#E6EEFF"
  primary-border: "#BBCDFC"
  primary-border-hover: "#8BA4F0"
  primary-text: "#3855D5"
  primary-text-hover: "#5F7CE3"
  primary-text-active: "#253AB0"
  primary-foreground: "#FAFAFA"
  destructive: "#E54D2E"
  destructive-foreground: "#FAFAFA"
  background: "#F5F6FA"
  foreground: "#1A1D2E"
  card: "#FFFFFF"
  card-foreground: "#1A1D2E"
  popover: "#FFFFFF"
  popover-foreground: "#1A1D2E"
  secondary: "#F3F4F8"
  secondary-foreground: "#1A1D2E"
  muted: "#F7F7F8"
  muted-foreground: "#5C6178"
  accent: "#ECEEF5"
  accent-foreground: "#1A1D2E"
  border: "#D4D7E2"
  input: "#E3E6F0"
  ring: "#3855D5"
  surface-elevated: "#FFFFFF"
  surface-container: "#FFFFFF"
  surface-layout: "#F7F8F9"
  surface-layout-adm: "#F7F9FD"
  surface-mask: "rgba(0, 0, 0, 0.45)"
  surface-spotlight: "rgba(40, 44, 51, 0.65)"
  surface-tooltips: "rgba(0, 0, 0, 0.75)"
  fill: "#F4F5F6"
  fill-secondary: "#F8F8F8"
  fill-hover: "#EBEDF2"
  fill-tertiary: "rgba(26, 29, 46, 0.04)"
  fill-quaternary: "rgba(26, 29, 46, 0.02)"
  text-title: "#3D3E42"
  text-secondary: "#6B7083"
  text-tertiary: "#9CA0B0"
  text-quaternary: "#C5C9D6"
  divider: "rgba(200, 210, 210, 0.7)"

typography:
  display-xl:
    fontFamily: PingFang SC
    fontSize: 86px
    fontWeight: 340
    lineHeight: 1.00
  display-lg:
    fontFamily: PingFang SC
    fontSize: 64px
    fontWeight: 340
    lineHeight: 1.10
  headline:
    fontFamily: PingFang SC
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.50
  title-1:
    fontFamily: PingFang SC
    fontSize: 24px
    fontWeight: 500
    lineHeight: 36px
  title-2:
    fontFamily: PingFang SC
    fontSize: 20px
    fontWeight: 500
    lineHeight: 20px
  title-3:
    fontFamily: PingFang SC
    fontSize: 18px
    fontWeight: 500
    lineHeight: 28px
  title-4:
    fontFamily: PingFang SC
    fontSize: 16px
    fontWeight: 500
    lineHeight: 26px
  body:
    fontFamily: PingFang SC
    fontSize: 14px
    fontWeight: 400
    lineHeight: 22px
  body-sm:
    fontFamily: PingFang SC
    fontSize: 14px
    fontWeight: 500
    lineHeight: 14px
  caption:
    fontFamily: PingFang SC
    fontSize: 12px
    fontWeight: 400
    lineHeight: 18px
  caption-bold:
    fontFamily: PingFang SC
    fontSize: 12px
    fontWeight: 500
    lineHeight: 12px
  number-display:
    fontFamily: DIN Alternate
    fontSize: 24px
    fontWeight: 500
    lineHeight: 24px
  number-title:
    fontFamily: DIN Alternate
    fontSize: 16px
    fontWeight: 500
    lineHeight: 16px
  number-body:
    fontFamily: DIN Alternate
    fontSize: 14px
    fontWeight: 500
    lineHeight: 14px
  number-caption:
    fontFamily: DIN Alternate
    fontSize: 12px
    fontWeight: 500
    lineHeight: 12px

rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 8px
  lg: 12px
  xl: 16px
  2xl: 1000px

spacing:
  hair: 1px
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px

shadow:
  sm: "0 1px 2px 0 rgba(0, 0, 0, 0.05)"
  base: "0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px -1px rgba(0, 0, 0, 0.1)"
  md: "0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.1)"
  lg: "0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -4px rgba(0, 0, 0, 0.1)"
  xl: "0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1)"

motion:
  duration-fast: 150ms
  duration-normal: 200ms
  duration-slow: 300ms
  easing-standard: cubic-bezier(0.4, 0, 0.2, 1)
  easing-decelerate: cubic-bezier(0, 0, 0.2, 1)
  easing-accelerate: cubic-bezier(0.4, 0, 1, 1)

components:
  button-base:
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    height: 36px
    padding: 0 15px
  button-colors:
    primary:        { bg: "{colors.primary}",  text: "{colors.primary-foreground}", border: "{colors.primary}" }
    default:        { bg: "transparent",       text: "{colors.primary}",            border: "{colors.primary}",  borderStyle: solid }
    third:          { bg: "transparent",       text: "#242529",                     border: "#D5D6D9",           borderStyle: solid }
    dashed:         { bg: "transparent",       text: "{colors.primary}",            border: "{colors.primary}",  borderStyle: dashed }
    text:           { bg: "transparent",       text: "{colors.primary}",            border: none }
    link:           { bg: "transparent",       text: "{colors.primary}",            border: none, textDecoration: "underline", textUnderlineOffset: "2px" }
    success-primary:  { bg: "#36A854", text: "#FFFFFF", border: "#36A854" }
    success-default:  { bg: "transparent", text: "#36A854", border: "#36A854" }
    warning-primary:  { bg: "#FA8C16", text: "#FFFFFF", border: "#FA8C16" }
    warning-default:  { bg: "transparent", text: "#FA8C16", border: "#FA8C16" }
    danger-primary:   { bg: "#F5222D", text: "#FFFFFF", border: "#F5222D" }
    danger-default:   { bg: "transparent", text: "#F5222D", border: "#F5222D" }
  button-icon:
    backgroundColor: "transparent"
    textColor: "{colors.muted-foreground}"
    rounded: "{rounded.md}"
    size: 40px
  button-sizes:
    large:    { height: 40px, minWidth: 76px, padding: "0 15px", fontSize: 14px }
    middle:   { height: 36px, minWidth: 76px, padding: "0 15px", fontSize: 14px }  # ✦ 默认
    middleSM: { height: 32px, minWidth: 68px, padding: "0 12px", fontSize: 14px }
    small:    { height: 28px, minWidth: 58px, padding: "0 8px",  fontSize: 14px }
    smallSM:  { height: 24px, minWidth: 58px, padding: "0 8px",  fontSize: 12px }
  button-disabled:
    opacity: 0.4
    cursor: not-allowed
  button-loading:
    opacity: 0.6
    cursor: not-allowed
  input:
    backgroundColor: "{colors.background}"
    textColor: "{colors.foreground}"
    borderColor: "{colors.border}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 12px 14px
  input-focused:
    backgroundColor: "{colors.background}"
    textColor: "{colors.foreground}"
    borderColor: "{colors.ring}"
    ringColor: "{colors.ring}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 12px 14px
  card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.card-foreground}"
    borderColor: "{colors.border}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
    shadow: "none"
  card-elevated:
    backgroundColor: "{colors.surface-elevated}"
    textColor: "{colors.card-foreground}"
    borderColor: "{colors.border}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
    shadow: "{shadow.md}"
  data-card:
    backgroundColor: "{colors.card}"
    borderColor: "{colors.border}"
    rounded: "{rounded.lg}"
    padding: 20px
  data-card-item:
    borderColor: "{colors.border}"
  badge:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-foreground}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: 2px 8px
  badge-secondary:
    backgroundColor: "{colors.muted}"
    textColor: "{colors.muted-foreground}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: 2px 8px
  tag:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.accent-foreground}"
    typography: "{typography.caption}"
    rounded: "{rounded.sm}"
    padding: 4px 8px
  progress:
    trackColor: "{colors.muted}"
    indicatorColor: "{colors.primary}"
    rounded: "{rounded.full}"
  avatar:
    backgroundColor: "{colors.muted}"
    textColor: "{colors.muted-foreground}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    size-sm: 32px
    size-md: 40px
    size-lg: 48px
  list-item:
    borderColor: "{colors.border}"
    typography: "{typography.body}"
    padding: 12px 0
  divider:
    color: "{colors.divider}"
    thickness: 1px
  select:
    backgroundColor: "{colors.background}"
    textColor: "{colors.foreground}"
    borderColor: "{colors.border}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 6px 12px
  select-option:
    backgroundColor: "{colors.background}"
    textColor: "{colors.foreground}"
    typography: "{typography.body}"
    padding: 8px 12px
  select-option-selected:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-foreground}"
  tooltip:
    backgroundColor: "{colors.surface-tooltips}"
    textColor: "#FFFFFF"
    typography: "{typography.caption}"
    rounded: "{rounded.sm}"
    padding: 6px 10px
  cascader:
    backgroundColor: "#ffffff"
    borderColor: "#eaecf3"
    rounded: 8px
    typography: "{typography.body-sm}"
    placeholderColor: "{colors.text-tertiary}"
  cascader-option:
    minHeight: 36px
    rounded: 6px
    padding: 8px
    lineHeight: 20px
  cascader-option-selected:
    backgroundColor: "#e6eaff"
    fontWeight: 500
  cascader-option-hover:
    backgroundColor: "#f6f8f9"
  cascader-disabled:
    backgroundColor: "#f6f8f9"
    textColor: "{colors.text-tertiary}"
  cascader-readonly:
    textColor: "#242529"
  form-action-bar:
    marginTop: 24px
    gap: 8px
    buttonHeight: 36px
    buttonMinWidth: 76px
    confirmType: primary
    confirmPosition: right
    cancelType: secondary   # aiop-ui type="secondary"；不要用 "third"（不存在）也不要用裸 antd Button（无 hover）
    cancelPosition: left
---

## Overview

KiGen Creator Dashboard 是一个面向短剧创作者的数据驾驶舱设计系统。它采用了企业级中后台常见的设计语言，以功能性和信息密度为核心，同时保持视觉的清爽与专业。

设计系统的核心特点包括：

- **深邃紫罗兰主色调** (`{colors.primary}`) 传递科技感与专业性
- **温暖灰白背景层次** 通过明度的细微差异区分内容层级
- **PingFang SC + DIN Alternate** 字体组合兼顾中文阅读与数字展示
- **8px 基础间距系统** 保持布局的节奏感与一致性
- **轻阴影卡片** 通过柔和的投影而非边框来区分层级

## Colors

### Primary & Semantic

- **{colors.primary}** — 品牌主色 `#3855D5`，用于按钮、链接、强调元素、进度条指示器
- **{colors.primary-hover}** — 主色 hover 态 `#5F7CE3`
- **{colors.primary-active}** — 主色按下/激活态 `#253AB0`
- **{colors.primary-disable}** — 主色禁用态 `#B0C4FF`
- **{colors.primary-bg}** — 主色浅背景 `#F0F5FF`，用于选中态、tag 底色
- **{colors.primary-bg-hover}** — 主色浅背景 hover `#E6EEFF`
- **{colors.primary-border}** — 主色边框 `#BBCDFC`
- **{colors.primary-border-hover}** — 主色边框 hover `#8BA4F0`
- **{colors.primary-text}** — 主色文字 `#3855D5`（同主色）
- **{colors.primary-text-hover}** — 主色文字 hover `#5F7CE3`
- **{colors.primary-text-active}** — 主色文字 active `#253AB0`
- **{colors.primary-foreground}** — 主色上的文字，白色保证对比度
- **{colors.destructive}** — 危险/错误状态，橙色（用于下降指示）
- **{colors.destructive-foreground}** — 危险色上的文字

### Backgrounds

- **{colors.background}** — 页面底色，极浅灰蓝 (97.5% 亮度)
- **{colors.foreground}** — 主文字色，深灰蓝 (14.7% 亮度)
- **{colors.card}** — 卡片底色，纯白
- **{colors.popover}** — 弹出层底色，同卡片
- **{colors.secondary}** — 次要背景，淡紫灰
- **{colors.muted}** — 静音背景，极浅灰
- **{colors.accent}** — 强调背景，淡灰蓝

### Surface Layers

- **{colors.surface-elevated}** — 悬浮层表面，纯白 `#FFFFFF`
- **{colors.surface-container}** — 容器表面，同纯白 `#FFFFFF`
- **{colors.surface-layout}** — 布局背景，浅灰 `#F7F8F9`
- **{colors.surface-layout-adm}** — 管理后台布局背景，浅蓝灰 `#F7F9FD`
- **{colors.surface-mask}** — 遮罩层，纯黑 45% 透明 `rgba(0, 0, 0, 0.45)`
- **{colors.surface-spotlight}** — 聚光/引导高亮层，深灰 65% 透明 `rgba(40, 44, 51, 0.65)`
- **{colors.surface-tooltips}** — Tooltip 背景，纯黑 75% 透明 `rgba(0, 0, 0, 0.75)`

### Fill

- **{colors.fill}** — 填充色，淡灰蓝
- **{colors.fill-secondary}** — 次要填充，极浅灰
- **{colors.fill-hover}** — 悬停填充，深一度灰
- **{colors.fill-tertiary}** — 三级填充，4% 透明度的深紫蓝
- **{colors.fill-quaternary}** — 四级填充，2% 透明度的深紫蓝

### Text

- **{colors.text-title}** — 标题文字，深灰蓝，同 foreground
- **{colors.text-secondary}** — 次要文字，中灰 (L=47.65%)
- **{colors.text-tertiary}** — 三级文字，浅灰 (L=67.51%)
- **{colors.text-quaternary}** — 四级文字，淡灰 (L=82.30%)

### Border & Divider

- **{colors.border}** — 标准边框，深灰紫
- **{colors.input}** — 输入框边框，淡灰紫
- **{colors.divider}** — 分隔线，70% 透明度淡灰

### Ring

- **{colors.ring}** — 聚焦环颜色，同主色，用于 focus 状态

## Typography

### Font Families

- **PingFang SC** — 中文默认字体，苹方体，Mac/Windows 双平台支持
- **DIN Alternate** — 数字专用字体，窄体设计，适合数据展示，fallback: system-ui

### Hierarchy

| Token | Size | Weight | Line Height | Use |
|---|---|---|---|---|
| `{typography.display-xl}` | 86px | 340 | 1.00 | 超大标题 |
| `{typography.display-lg}` | 64px | 340 | 1.10 | 大标题 |
| `{typography.headline}` | 24px | 500 | 1.50 | 区块标题 |
| `{typography.title-1}` | 24px | 500 | 36px | 一级标题 |
| `{typography.title-2}` | 20px | 500 | 20px | 二级标题 |
| `{typography.title-3}` | 18px | 500 | 28px | 三级标题 |
| `{typography.title-4}` | 16px | 500 | 26px | 四级标题 |
| `{typography.body}` | 14px | 400 | 22px | 正文段落 |
| `{typography.body-sm}` | 14px | 500 | 14px | 小号正文/按钮 |
| `{typography.caption}` | 12px | 400 | 18px | 注释文字 |
| `{typography.caption-bold}` | 12px | 500 | 12px | 粗体注释 |
| `{typography.number-display}` | 24px | 500 | 24px | 数字展示（大） |
| `{typography.number-title}` | 16px | 500 | 16px | 数字标题 |
| `{typography.number-body}` | 14px | 500 | 14px | 数字正文 |
| `{typography.number-caption}` | 12px | 500 | 12px | 数字注释 |

### Principles

- **权重传达层级**：正文使用 400，标题使用 500，数字使用 500 突出显示
- **数字独立排版**：使用 DIN Alternate 替代 PingFang SC 的数字，保证表格对齐
- **行高宽松舒适**：正文行高 22px (1.57)，段落可读性优先
- **紧凑标题行高**：标题行高 1.50 紧凑排列，节省垂直空间

## Spacing System

基础单位：8px

| Token | Value | Use |
|---|---|---|
| `{spacing.hair}` | 1px | 极细分隔线 |
| `{spacing.xxs}` | 4px | 紧凑间距 |
| `{spacing.xs}` | 8px | 小间距、图标与文字间距 |
| `{spacing.sm}` | 12px | 组件内紧凑间距 |
| `{spacing.md}` | 16px | 默认间距、组件内间距 |
| `{spacing.lg}` | 24px | 区块间距、卡片内间距 |
| `{spacing.xl}` | 32px | 大区块间距 |
| `{spacing.xxl}` | 48px | 页面级大间距 |

## Border Radius

| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0px | 无圆角 |
| `{rounded.xs}` | 2px | 微小圆角 |
| `{rounded.sm}` | 4px | 小圆角、标签 |
| `{rounded.md}` | 8px | 默认圆角、按钮、输入框 |
| `{rounded.lg}` | 12px | 大圆角、卡片 |
| `{rounded.xl}` | 16px | 超大圆角 |
| `{rounded.2xl}` | 1000px | 胶囊形/全圆角 |

## Shadows

- `{shadow.sm}` — 轻微悬浮效果
- `{shadow.base}` — 基础卡片悬浮
- `{shadow.md}` — 中等深度悬浮
- `{shadow.lg}` — 大型悬浮元素
- `{shadow.xl}` — 模态层

## Motion

- 快速过渡 (150ms) — 交互反馈
- 标准过渡 (200ms) — 状态切换
- 慢速过渡 (300ms) — 页面元素

## Components

### Button

引入：`import {Button} from '@baidu/aiop-ui'`

#### 基础样式（button-base）

所有按钮变体共享：typography `{typography.body-sm}`, rounded `{rounded.md}`, height 36px, padding 0 15px。

#### TYPE 变体（button-colors）

各变体仅覆盖颜色/边框属性，其余继承 button-base：

| 变体 | Background | Text | Border | 备注 |
|---|---|---|---|---|
| `primary` | `{colors.primary}` | `{colors.primary-foreground}` | `{colors.primary}` | 主按钮，紫罗兰填充 |
| `default` | transparent | `{colors.primary}` | `{colors.primary}` solid | 次按钮，主色描边 |
| `third` | transparent | #242529 | #D5D6D9 solid | 三级按钮，灰色描边。⚠️ aiop-ui **不支持**此 type，传入无效果且无 hover；实际取消按钮用 `type="secondary"` |
| `dashed` | transparent | `{colors.primary}` | `{colors.primary}` dashed | 虚线按钮 |
| `text` | transparent | `{colors.primary}` | none | 文字按钮，无边框 |
| `link` | transparent | `{colors.primary}` | none | 链接按钮，underline offset 2px |
| `success-primary` | #36A854 | #FFFFFF | #36A854 | 成功，填充绿色 |
| `success-default` | transparent | #36A854 | #36A854 | 成功，绿色描边 |
| `warning-primary` | #FA8C16 | #FFFFFF | #FA8C16 | 警示，填充橙色 |
| `warning-default` | transparent | #FA8C16 | #FA8C16 | 警示，橙色描边 |
| `danger-primary` | #F5222D | #FFFFFF | #F5222D | 危险，填充红色 |
| `danger-default` | transparent | #F5222D | #F5222D | 危险，红色描边 |

**`button-icon`** — 图标按钮，40×40px 方形，transparent bg, text `{colors.muted-foreground}`, rounded `{rounded.md}`

#### 尺寸（button-sizes）

| Size | 高度 | 最小宽 | 内边距 | 字号 |
|---|---|---|---|---|
| `large` | 40px | 76px | 0 15px | 14px |
| `middle` ✦ | 36px | 76px | 0 15px | 14px |
| `middleSM` | 32px | 68px | 0 12px | 14px |
| `small` | 28px | 58px | 0 8px | 14px |
| `smallSM` | 24px | 58px | 0 8px | 12px |

✦ 默认尺寸（与 button-base height 一致，仅在显式切换尺寸时使用 size token）

> ⚠️ **实现陷阱**：`@baidu/aiop-ui` 的 `style.js` 通过 emotion 注入了一条高优先级覆盖规则：
> ```css
> &.ant-btn:not(.ant-btn-lg):not(.ant-btn-sm) { height: 32px; }
> ```
> 该选择器等效 3 个 class，优先级 `(0,3,0)`，**高于任何外部 CSS Module 类 `(0,1,0)`**。
> 因此，用 CSS 类（包括 CSS Module）设置 `height: 36px` 对 aiop-ui Button **无效**。
> **唯一可靠方案：使用 inline style**，`style={{height: 36}}` 优先级为 `(1,0,0,0)`，不可被类选择器覆盖。
> 对 antd 原生 Button（非 aiop-ui 封装），同样建议用 inline style 统一高度，避免 antd 自身 CSS-in-JS 干扰。

#### 状态

**`button-disabled`** — 禁用：opacity 0.4, cursor not-allowed

**`button-loading`** — 加载中：opacity 0.6, cursor not-allowed，左侧显示旋转 spinner

### Form Label 布局规范

> Form、Form.Item 从 `antd` 导入（aiop-ui 暂未封装 Form）。

水平布局表单（`layout="horizontal"`）的 label 对齐规则。

#### 基础设置

```tsx
<Form
    layout="horizontal"
    colon={false}
    labelAlign="right"
    labelCol={{flex: '126px'}}
    className={styles.form}
>
```

| 属性 | 值 | 说明 |
|---|---|---|
| `labelAlign` | `"right"` | label 文字右对齐，`*` 号贴近输入框侧 |
| `labelCol.flex` | `'126px'` | label 列总宽 = 文字区 114px + 右侧间距 12px |
| label 文字区最大宽度 | 114px | 含必填 `*` 号（`labelCol 126px - padding-inline-end 12px`） |
| label 到输入控件间距 | 12px | 与 antd 默认 `paddingSM` 一致，需显式声明防止 token 变更 |

**必须在 Less Module 中覆盖 antd 的默认 label 内边距：**

```less
// index.module.less
.form {
    :global {
        .ant-form-item-label {
            padding-inline-end: 12px !important;
        }
    }
}
```

> antd v5 Form 的 label 右侧间距由 `padding-inline-end: token.paddingSM`（默认 12px）控制，CSS-in-JS 注入，需要 `!important` 覆盖。

---

#### 嵌套容器内的 label 对齐补偿

当 Form.Item 位于有左内边距的**嵌套容器**（如灰色指标行 `padding-left: 24px`）内时，直接继承外层 `labelCol: 126px` 会导致内层 label 文字右边缘偏右 24px，与外层 label 错位。

**补偿公式：**

```
内层 labelCol = 外层 labelCol - 容器 padding-left
             = 126px - 24px = 102px
```

**实现方式：** 在容器内的每个 Form.Item 上单独声明 `labelCol`：

```tsx
// 灰色容器 padding-left = 24px，labelCol 缩减为 102px
<Form.Item
    label="指标"
    labelCol={{flex: '102px'}}
    ...
>
```

**对齐原理：**

```
外层 Form.Item：
  [label 126px 含 12px gap] [输入框]
  label 文字右边缘 = x:114 ←──────────────────────────────┐
                                                           │ 视觉对齐
灰色容器（padding-left: 24px）内的 Form.Item：             │
  [+24px offset] [label 102px 含 12px gap] [输入框]       │
  label 文字右边缘 = 24 + 90 = x:114 ←──────────────────┘
  输入框起点 = 24 + 102 = x:126（与外层对齐）
```

> 规律：每多一层嵌套容器，内层 `labelCol` 减去该容器的 `padding-left`，保持 label 文字右边缘不变。

---

#### 同行多字段 flex-wrap 布局间距规范

当多个 Form.Item 在同一容器内水平排列（`flex-wrap: wrap`）时，间距统一由容器的 `gap` 控制：

| 属性 | 值 | 说明 |
|---|---|---|
| `row-gap`（换行后行间距） | 24px | 控制多行时上下相邻行的垂直间距 |
| `column-gap`（同行字段间距） | 32px | 控制同一行内相邻字段的水平间距 |
| Form.Item `margin-bottom` | 0 | **必须清零**，否则与 `row-gap` 双重叠加造成双倍行间距 |

```less
.indicatorFields {
    display: flex;
    flex-wrap: wrap;
    // row-gap 控制换行后行间距，column-gap 控制同行字段间距
    // Form.Item margin-bottom 必须清零，否则与 row-gap 双重叠加
    gap: 24px 32px;

    :global {
        .ant-form-item {
            margin-bottom: 0;
        }
    }
}
```

> ⚠️ **双重叠加陷阱**：在 `flex-wrap` 容器设置 `gap`（或 `row-gap`）的同时，若 flex 子项保留 `margin-bottom`，垂直间距会翻倍。统一用 `row-gap` 控制，子项 `margin-bottom` 清零。

> ⚠️ **column-gap 只作用于同行**：当字段换行显示时，`column-gap` 对换行后的上下视觉间距**无影响**，视觉上看到的行间距完全由 `row-gap` 决定。

---

### Input

引入：`import {Input} from '@baidu/aiop-ui'`

**`input`** — 标准输入框
- Background `{colors.background}`, border `{colors.border}`
- Typography `{typography.body}`, rounded `{rounded.md}`, padding 12px 14px

**`input-focused`** — 聚焦状态
- Border `{colors.ring}`, ring shadow
- Focus ring color: `{colors.ring}`

#### 输入框宽度规范

输入框宽度按**行排列方式**分两种场景，所有 `Select` / `TreeSelect` 宽度必须用 `style={{width: N}}` inline style 设置（antd CSS-in-JS 会覆盖外部 className）。

---

**场景一：独占一行**（label 右侧仅有单个控件，无并排字段）→ 统一 **460px**

| 组件类型 | 宽度 | 设置方式 |
|---|---|---|
| `Input`（文本、链接、URL 等） | 460px | `className={styles.wideInput}` |
| `Select mode="multiple"`（多选 Tag） | 460px | `style={{width: 460}}` |

---

**场景二：同行多个控件**（同一行排列两个及以上选择控件）

**核心原则：同类型控件宽度必须一致；不同类型可差异化。**

| 控件类型 | 宽度 | 说明 |
|---|---|---|
| `Select`（单选）/ `TreeSelect` | **220px** | 同行所有单选控件统一 220px，不得各自不同 |
| `Select mode="multiple"`（多选 Tag） | **220px** | 同行时与单选对齐，保持视觉整齐；独行时用 460px |
| `InputNumber`（数字） | 不强制 | 按内容需要设定（如 120px），豁免宽度统一要求 |
| `Input`（文本） | 不强制 | 按内容需要设定，豁免宽度统一要求 |

> **为什么单选/多选 220px**：线上团队监控「指标行」中指标、监控分层、异常规则三个选择框均为 220px，实际视觉验证通过，以此作为同行选择控件的统一基准。

```tsx
// ✓ 正确：同行三个选择控件统一 220px
<TreeSelect style={{width: 220}} />          // 单选（指标）
<Select mode="multiple" style={{width: 220}} />  // 多选（监控分层）
<Select style={{width: 220}} />              // 单选（异常规则）
<InputNumber style={{width: 120}} />         // 数字，豁免

// ✗ 错误：同行选择控件宽度不一致
<TreeSelect style={{width: 220}} />
<Select style={{width: 160}} />              // ← 与同行 220px 不一致
```

> ⚠️ `Select` / `TreeSelect` 的宽度必须用 `style={{width: N}}`，用 `className` 设置无效（antd CSS-in-JS 优先级更高覆盖外部类）。`Input` / `InputNumber` 无此限制。

### Tag

引入：`import {Tag} from '@baidu/aiop-ui'`（包装 antd Tag，追加 `success`/`warning`/`processing`/`error`/`default`/`primary` 预设色值类）

### Badge（表格状态展示）

引入：`import {Badge} from '@baidu/aiop-ui'`

**表格内状态列统一使用 `Badge` 的 `status` 用法**，渲染彩色圆点 + 文字，不使用 `Tag`。

#### status 取值

| status | 圆点颜色 | 典型场景 |
|---|---|---|
| `success` | 绿色 | 已开启、已生效、正常 |
| `default` | 灰色 | 已关闭、未启用 |
| `processing` | 蓝色（脉冲动效） | 进行中、运行中 |
| `warning` | 黄色 | 警告、待处理 |
| `error` | 红色 | 异常、失败 |

#### 尺寸

| statusSize | 圆点大小 | 字号 |
|---|---|---|
| `middle` ✦ | 8px | 默认 |
| `small` | 6px | fontSizeSM |

✦ 默认，无需显式传入

#### 代码示例

```tsx
import {Badge} from '@baidu/aiop-ui';

// ✓ 正确：表格状态列使用 Badge status
{
    title: '监控状态',
    dataIndex: 'status',
    render: (status: string) => (
        <Badge
            status={status === 'on' ? 'success' : 'default'}
            text={status === 'on' ? '已开启' : '已关闭'}
        />
    ),
}

// ✗ 错误：表格状态列不使用 Tag
render: (status: string) => (
    <Tag color={status === 'on' ? 'success' : 'default'}>已开启</Tag>
)
```

### Modal

引入：`import {Modal} from '@baidu/aiop-ui'`

### Card

**`card`** — 标准卡片，无阴影，有边框
- Background `{colors.card}`, border `{colors.border}`
- Rounded `{rounded.lg}`, padding 24px

**`card-elevated`** — 悬浮卡片，有阴影
- Shadow `{shadow.md}`, no border
- Used for dropdown menus, tooltips

**`data-card`** — 数据卡片组件
- Background `{colors.card}`, border `{colors.border}`
- Rounded `{rounded.lg}`, padding 20px
- 包含 `data-card-item` 子组件用于水平排列指标

### Cascader

引入：`import {Cascader} from 'antd'`（aiop-ui 暂未封装 Cascader，直接使用 antd 原版）

**基础外观**
- 圆角 8px，边框色 #eaecf3，白色背景，无阴影
- 占位符颜色：`{colors.text-tertiary}`
- 右侧后缀图标：BjhBasicXia，16px；allowClear 时 hover 显示清除图标 BjhBasicGuanbiteshu，16px

**扩展属性**

| 属性 | 类型 | 默认值 | 说明 |
|---|---|---|---|
| size | `'smallXS' \| 'small' \| 'middle' \| 'large'` | `'middle'` | 选择器高度 |
| width | number | 自适应 | 固定宽度 |
| readonly | boolean | false | 只读：禁用样式但文字色保持 #242529 |

**尺寸**

| size | 高度 |
|---|---|
| large | 40px |
| middle ✦ | 36px |
| small | 32px |
| smallXS | 28px |

✦ 默认尺寸

**模式**
- 单选：选择项高度 = 组件高度 - 2px，行高 = 高度 - 2px
- 多选：最小高度 = 组件高度，每项高度 = 组件高度 - 8px，行高 = 高度 - 10px，每项显示删除图标 BjhBasicGuanbi

**下拉面板**
- 每个选项最小高度 36px，圆角 6px，内边距 8px，内容行高 20px
- 选中项：浅蓝背景 #e6eaff，字重 500
- hover 项：浅灰背景 #f6f8f9
- 展开图标：BjhBasicGengduoSmall，16px，`{colors.text-secondary}`
- 勾选框圆角：4px

**状态**

| 状态 | 表现 |
|---|---|
| normal | 边框 #eaecf3，白色背景 |
| hover | 选项背景 #f6f8f9 |
| active | 选项文字主题色 |
| disabled | 背景 #f6f8f9，文字 `{colors.text-tertiary}` |
| readonly | 同 disabled 外观，但文字色保持 #242529 |
| error | 错误态边框色 |

### Table

引入：`import {Table} from 'antd'`（aiop-ui 暂未封装 Table，直接使用 antd 原版）

**基础外观**
- 圆角：`5px 5px 0 0`（仅顶部两角）
- 表体字重：500
- 链接默认色：`#5a5c66`，hover 色：`{colors.primary}` (#3855D5)

**表头 (`thead`)**
- 背景色：`#f6f8f9`
- 文字色：`#9296a6`
- 底部边框：无；分割线：透明
- 单元格水平内边距：24px
- 排序列 / 筛选列：flex 布局，左对齐，标题不 flex 伸缩
- 筛选触发器 padding：0
- hover 背景色：transparent

**表体 (`tbody`)**
- 文字色：`#5a5c66`
- 行 hover 背景色：`#F9FBFD`
- 选中行背景色：transparent；选中行 hover：transparent
- 排序列背景色：transparent
- 行边框颜色：`rgba(233, 236, 243, 0.7)`
- 占位区（空数据）字重：400，外边距：60px 0（使用 cheetah `<Empty />` 组件）

**选择列**
- 列宽：60px
- 单元格内边距：`16px 12px 16px 32px`

**固定列阴影**
- 右侧固定列（左侧阴影）：宽度 35px，`inset -25px 0 25px -25px rgba(213, 214, 217, 0.5)`
- 左侧固定列（右侧阴影）：宽度 35px，`inset 25px 0 25px -25px rgba(213, 214, 217, 0.5)`

**分页器**
- 边框色：`#d5d6d9`；圆角：`6px`
- 激活项背景：`#e6eaff`
- 禁用项文字色：`#bfc4d9`
- hover 背景：transparent
- `showSizeChanger` 默认 false

### Form Action Bar（页面级表单操作栏）

页面级表单底部的操作按钮区，适用于创建/编辑表单页。

| 属性 | 规格 |
|---|---|
| 与最后一个字段的间距 | `margin-top: 24px`（`{spacing.lg}`） |
| 按钮间距 | `marginRight: 8px` |
| 按钮高度 | 36px |
| 按钮最小宽度 | 76px |

**按钮顺序**（从左到右）：取消（左）→ 确认（右）

- **取消**：aiop-ui `type="secondary"`，蓝色描边，蓝色文字，有 hover 效果
- **确认**：aiop-ui `type="primary"`，主色填充，白色文字，触发表单提交

两个按钮都从 `@baidu/aiop-ui` 导入 `Button`，不使用裸 antd Button。

> ⚠️ **两个已知实现陷阱**：
>
> **陷阱一：不要用 `type="third"`**
> aiop-ui Button 只支持 `ButtonType | 'secondary'`，没有 `type="third"`。
> 传入 `type="third"` 时 aiop-ui 不添加任何特殊 class，antd 也忽略未知 type，结果是样式完全丢失且无 hover。
> 取消按钮统一使用 `type="secondary"`（与项目其他页面一致，如 `drawerFooter`）。
>
> **陷阱二：高度必须用 inline style，不能用 CSS 类**
> aiop-ui 的 `style.js` 通过 emotion 注入 `&.ant-btn:not(.ant-btn-lg):not(.ant-btn-sm){height:32px}`，
> 优先级 `(0,3,0)` 高于所有外部 CSS Module 类 `(0,1,0)`，导致任何 CSS 类写的 `height: 36px` 都被覆盖为 32px。
> **必须用 `style={{height: 36}}`**（inline style 优先级 `(1,0,0,0)`）。

```tsx
// ✓ 正确实现（两个按钮均来自 @baidu/aiop-ui）
import {Button} from '@baidu/aiop-ui';

<Form.Item style={{marginTop: 24}}>
    <Button type="secondary" style={{height: 36, minWidth: 76, marginRight: 8}} onClick={handleCancel}>
        取消
    </Button>
    <Button type="primary" htmlType="submit" style={{height: 36, minWidth: 76}}>
        确定
    </Button>
</Form.Item>
```

## 列表页规范（List Page Pattern）

> 以保量工作台「保量提报」页为基准验证，适用于所有通过侧边导航直接进入的列表型页面。

### 页面白卡结构

布局层 `.show` 已提供统一白卡容器：

| 属性 | 值 |
|---|---|
| `background` | `#fff` |
| `border-radius` | `8px` |
| `box-shadow` | `0 6px 14px 0 rgba(227,233,237,.35)` |
| `padding` | `12px 24px 28px` |

**页面组件内部不得再创建顶层白卡**（即不在组件根节点加 `background:#fff` + `border-radius` + `padding`），否则会形成白卡套白卡、双重内边距的问题。

```tsx
// ✓ 正确：内容直接渲染，依赖布局层白卡
const ListPage = () => (
    <>
        <Tabs ... />
        <FilterArea />
        <Table ... />
    </>
);

// ✗ 错误：在组件内部再套一层白卡
const ListPage = () => (
    <section style={{background: '#fff', borderRadius: 8, padding: 24}}>
        <Tabs ... />
        ...
    </section>
);
```

---

### 一级标题规则

| 场景 | 是否放一级标题（PageTitle） |
|---|---|
| 列表页 + 有 Tab 分栏 | ✗ 不放，Tab 本身提供导航上下文 |
| 列表页 + 无 Tab | ✓ 可放，使用 `<PageTitle>` 组件 |
| 创建 / 编辑表单页 | ✓ 放在白卡内第一行 |

---

### Tab 规范

引入：`import {Tabs} from '@baidu/aiop-ui'`

```tsx
<Tabs
    size="large"
    activeKey={activeKey}
    onChange={onChange}
    items={tabItems}
    className={styles.tabs}
/>
```

```less
// index.module.less
.tabs {
    margin-bottom: 24px;  // Tab 与下方筛选区的间距

    :global {
        .ant-tabs-nav {
            margin-bottom: 0 !important;  // 清除 antd 默认 nav margin，避免双重叠加
        }
    }
}
```

| 属性 | 值 | 说明 |
|---|---|---|
| `size` | `"large"` | 字号更大，层级更清晰 |
| Tab → 筛选区间距 | `24px` | 统一设在 `.tabs { margin-bottom }` |
| nav 内部 margin | `0 !important` | 防止 antd CSS-in-JS 与外层 margin 双重叠加 |

---

### 筛选区规范

筛选区无独立白卡包裹，直接在布局白卡内渲染。

#### 容器布局（CSS Grid）

```less
.filterGrid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);  // 3列；字段多时可改为 4～8 列
    grid-row-gap: 18px;
    grid-column-gap: 32px;
}
```

#### 筛选项（label + control）

```less
.filterItem {
    display: grid;
    grid-template-columns: 56px 1fr;  // label 固定宽，control 填充剩余
    align-items: center;
    column-gap: 16px;
}

.filterLabel {
    font-size: 14px;
    color: #666;
    font-weight: 400;
    white-space: nowrap;
}
```

#### 控件高度统一 40px

筛选区所有交互控件高度统一为 **40px**，与列表页视觉密度匹配（区别于表单页的 32px）。

引入：`import {Input, Select, DatePicker, Button} from '@baidu/aiop-ui'`

| 控件 | 来源 | 设置方式 |
|---|---|---|
| `Input` | `@baidu/aiop-ui` | `size="large"` |
| `Select` | `@baidu/aiop-ui` | `size="large"` |
| `DatePicker` / `RangePicker` | `@baidu/aiop-ui` | `size="large"` |
| `Button`（查询/重置） | `@baidu/aiop-ui` | `style={{height: 40}}`（emotion 强制 32px，必须 inline style 覆盖） |

```tsx
import {Input, Select, DatePicker, Button} from '@baidu/aiop-ui';
const {RangePicker} = DatePicker;

// ✓ 正确
<Input size="large" placeholder="请输入" allowClear />
<Select size="large" style={{width: '100%'}} options={options} />
<RangePicker size="large" style={{width: '100%'}} />
<Button type="primary" style={{height: 40}} onClick={handleSearch}>查询</Button>
<Button style={{height: 40}} onClick={handleReset}>重置</Button>
```

#### 列数选择参考

| 筛选项数量 | 推荐列数 |
|---|---|
| 3～6 项 | 3 列 |
| 7～12 项 | 4 列 |
| 13 项以上 | 8 列（保量提报同款，可加折叠展开） |

---

### 表格行内操作规范

行内操作以**纯文字链接**形式呈现，垂直叠放，不使用 Button 组件。

```less
.tableOp {
    color: #3855d5;       // 所有操作统一主色，包括删除

    div {
        cursor: pointer;
        &:hover { opacity: .8; }
    }

    div + div {
        margin-top: 16px;  // 操作项垂直间距
    }
}
```

```tsx
<section className={styles.tableOp}>
    <div onClick={handleToggle}>{record.status === 'on' ? '关闭' : '开启'}</div>
    <div onClick={handleEdit}>编辑</div>
    <div onClick={() => setDeleteTarget(record)}>删除</div>
</section>
```

| 规则 | 说明 |
|---|---|
| 颜色 | 统一 `#3855d5`，**包括删除**，不单独变红 |
| 危险色使用范围 | 仅限删除**确认弹窗**内的确认按钮（`okButtonProps={{danger: true}}`） |
| 布局 | 见下方"操作数量与布局"规则 |
| 交互 | `cursor: pointer`，hover `opacity: .8` |
| 组件 | 使用 `div` 文字链接，不使用 `Button type="link"` |

#### 操作数量与布局

| 操作数量 | 布局方式 | CSS 类 |
|---|---|---|
| ≤ 3 个 | 单列垂直叠放，`div + div { margin-top: 16px }` | `.tableOp` |
| > 3 个 | 两列网格，`grid-template-columns: 1fr 1fr; gap: 8px 16px` | `.tableOpGrid` |

```less
.tableOp {
    color: #3855d5;
    div { cursor: pointer; &:hover { opacity: .8; } }
    div + div { margin-top: 16px; }
}

.tableOpGrid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 8px 16px;
    color: #3855d5;
    div { cursor: pointer; &:hover { opacity: .8; } }
}
```

```tsx
// 根据操作数量动态切换样式类
const ops = [<div key="a">开启</div>, <div key="b">编辑</div>, <div key="c">删除</div>];
<section className={ops.length > 3 ? styles.tableOpGrid : styles.tableOp}>
    {ops}
</section>
```

---

---

## Visual Separation Principles

> 已在 `MonitorFormWithShell` 页面验证通过，纳入规范。

### 布局前置规则：页面标题与返回按钮放置规则

#### 返回按钮

只在**明确定义为二级页**的页面放返回按钮（例如：从列表页进入详情页、从汇总进入编辑页，且产品文档中有明确的层级描述）。

| 场景 | 是否放返回按钮 |
|---|---|
| 产品文档明确标注「二级页」「详情页」「编辑页」 | ✓ 放 |
| 通过侧边导航直接进入的功能页（即使有表单） | ✗ 不放 |
| 创建/配置表单（无明确上级页路径） | ✗ 不放，用底部「取消」代替退出 |

#### 页面标题

页面标题**放在第一张白色内容卡片内部**，不浮在灰色背景（`{colors.surface-layout}`）上。

```
✓ 正确：标题在白卡内
┌──────────────────────────────┐   ← 灰色 Main 区 #F5F5F5
│ ┌────────────────────────┐   │
│ │  创建团队监控           │   │   ← 标题在白卡首行（15px/600）
│ │  监控名称  [input]      │   │
│ │  监控团队  [select]     │   │
│ └────────────────────────┘   │
└──────────────────────────────┘

✗ 错误：标题 + 返回按钮浮在灰底上
┌──────────────────────────────┐
│  ← 创建团队监控              │   ← 浮在灰底，视觉上游离于内容
│ ┌────────────────────────┐   │
│ │  监控名称  [input]      │   │
│ └────────────────────────┘   │
└──────────────────────────────┘
```

#### 面包屑的作用

顶部 Header 的面包屑已提供当前位置的层级信息（如 `驾驶舱 / 监控规则配置 / 创建监控`），**不需要在页面内容区重复展示层级或返回路径**。

---

### 原则零：卡片按功能域分割（One Card per Functional Domain）

白色内容卡片代表一个**功能域（Functional Domain）**，不是一个表单区块或视觉分组。  
同一功能域内的多个字段组/子区块，用**间距 + SubSection 标签**分隔，不拆成多张卡片。

**判断是否需要新卡片的标准**：内容是否属于完全不同的用途或配置类型？

| 场景 | 正确做法 |
|---|---|
| 基础字段（名称、所属团队）+ 核心规则配置 → 同一实体定义 | 合并为一张卡，内部用 SubSection 分隔 |
| 监控定义 vs 推送通知配置 → 不同功能域 | 各自一张卡 |
| 同一表单的多个步骤（Step 1 / Step 2） | 各自一张卡，或用 Steps 组件 |

**SubSection 规格**（卡片内分组标签，不是卡片标题）：

| 属性 | 值 |
|---|---|
| 字号 / 字重 | 14px / 500 |
| 颜色 | `{colors.text-secondary}` |
| 与上方内容间距 | `margin-top: 24px`（`{spacing.lg}`） |
| 与下方内容间距 | `margin-bottom: 12px`（`{spacing.sm}`） |

```
✓ 正确：同实体用间距分割
┌──────────────────────────────────────┐
│  监控名称  [input]                    │  ← 基础字段，无需子标题
│  监控团队  [select]                   │
│                                      │
│  监控规则                   ← SubSection（14px/500/text-secondary）
│  ┌── 指标行 ─────────────────────┐   │
│  └──────────────────────────────┘   │
│  + 增加指标                          │
└──────────────────────────────────────┘

┌──────────────────────────────────────┐
│  推送规则                             │  ← 独立卡（不同功能域）
│  ...                                 │
└──────────────────────────────────────┘

✗ 错误：同实体拆成多张卡
┌────────────────┐  ┌────────────────┐  ┌────────────────┐
│  基础信息       │  │  监控规则       │  │  推送规则       │
│  监控名称       │  │  指标行...      │  │  ...           │
└────────────────┘  └────────────────┘  └────────────────┘
```

---

### 原则一：有色即无边（Color Separation Supersedes Border）

当元素通过**背景色差异**与周围环境形成视觉区分时，不再叠加 stroke / border。  
Border 只用于**同色背景**下需要明确边界的场景（如白色卡片内的白色输入框）。

| 场景 | 正确做法 | 错误做法 |
|---|---|---|
| 白色卡片 on 灰色页面背景 `#F5F5F5` | 无边框，色差自然分隔 | ✗ 再加 `border: 1px solid` |
| 灰色填充行 `#F7F8F9` on 白色卡片 | 无边框，填充色区分 | ✗ 再加 `border: 1px solid` |
| 蓝色提示区 `#F0F5FF` on 白色卡片 | 无边框，主色背景自成语义 | ✗ 再加 `border: 1px solid #BBCDFC` |
| 白色输入框 on 白色卡片背景 | 保留 border（交互元素必须有边界感） | ✗ 去掉边框 |

**例外**：Input、Select、Button 等**可交互元素**不受此规则约束，边框是操作可见性的必要组成。

### 原则二：间距代替分割线（Spacing Over Dividers）

区块标题与内容之间优先用**字重差异 + 间距**传递层级，不用 border-bottom 或分割线做人为切割。

| 项目 | 规格 |
|---|---|
| 区块标题字号 / 字重 | 15px / 600，色值 `{colors.text-title}` |
| 标题与内容间距 | `margin-bottom: 16px` |
| 卡片内统一 padding | `24px`（四边，不分 header zone / body zone） |

```
✓ 正确结构
┌─────────────────────────┐
│  基础信息                 │  ← 标题（15px 600）+ mb 16px
│                         │
│  监控名称                 │  ← 内容直接开始
│  ┌───────────────────┐  │
│  │ 输入框             │  │
│  └───────────────────┘  │
└─────────────────────────┘

✗ 错误结构
┌─────────────────────────┐
│  基础信息                 │  ← 标题区
├─────────────────────────┤  ← ✗ 不要这条分割线
│  监控名称                 │
│  ┌───────────────────┐  │
│  │ 输入框             │  │
│  └───────────────────┘  │
└─────────────────────────┘
```

---

## Do's and Don'ts

### Do

- 使用 `{colors.primary}` 作为主要操作和强调元素
- 通过字体权重 (400 vs 500) 区分内容层级，而非颜色
- 数字展示使用 DIN Alternate 字体
- 卡片使用 `{rounded.lg}` (12px) 圆角
- 按钮使用 `{rounded.md}` (8px) 圆角
- 列表项之间使用 1px 分隔线

### Don't

- 不要在同一个视口内使用多个 `{colors.primary}` 按钮，会造成视觉混乱
- 不要使用纯黑 (#000) 作为文字色，使用 `{colors.foreground}` (深紫灰)
- 不要给卡片添加过重的阴影，企业后台需要清晰的视觉层级
- 不要在数据展示中使用衬线字体或艺术字体
- 不要在中文内容中使用过大的行高，14px 字体行高 22px 即可

