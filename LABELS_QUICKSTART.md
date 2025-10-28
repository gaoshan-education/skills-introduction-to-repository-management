# 快速入门：为本项目添加自定义标签 / Quick Start: Adding Custom Labels for This Project

本指南将帮助你快速为 Mergington High 课外活动网站项目添加有用的自定义标签。

*This guide will help you quickly add useful custom labels for the Mergington High Extracurricular Activities website project.*

## 🚀 快速步骤 / Quick Steps

### 1. 访问标签管理页面 / Navigate to Labels Page

点击此链接直接访问（请替换为你的实际仓库地址）：
*Click this link to access directly (replace with your actual repository URL):*

```
https://github.com/gaoshan-education/skills-introduction-to-repository-management/labels
```

或者：
*Or:*

1. 进入仓库主页 / Go to repository home
2. 点击 **"Issues"** 标签 / Click **"Issues"** tab
3. 点击 **"Labels"** 按钮 / Click **"Labels"** button

### 2. 创建推荐的标签 / Create Recommended Labels

点击 **"New label"** 按钮，然后按照下表创建标签：
*Click **"New label"** button, then create labels according to the table below:*

## 📋 推荐标签列表 / Recommended Labels List

### 俱乐部分类 / Club Categories

| 标签名 / Name | 颜色 / Color | 描述 / Description |
|--------------|--------------|-------------------|
| `club:art` | `#FF69B4` | 艺术俱乐部相关功能 / Art Club features |
| `club:chess` | `#8B4513` | 国际象棋俱乐部功能 / Chess Club features |
| `club:sports` | `#FF6347` | 体育活动相关 / Sports activities |
| `club:music` | `#9370DB` | 音乐俱乐部功能 / Music Club features |
| `club:general` | `#4169E1` | 影响所有俱乐部的功能 / Features affecting all clubs |

### 优先级 / Priority

| 标签名 / Name | 颜色 / Color | 描述 / Description |
|--------------|--------------|-------------------|
| `priority:critical` | `#FF0000` | 🔥 关键问题，需立即处理 / Critical issues, needs immediate attention |
| `priority:high` | `#FF6B6B` | ⬆️ 高优先级 / High priority |
| `priority:medium` | `#FFD93D` | ➡️ 中等优先级 / Medium priority |
| `priority:low` | `#95E1D3` | ⬇️ 低优先级 / Low priority |

### 问题类型 / Issue Type

| 标签名 / Name | 颜色 / Color | 描述 / Description |
|--------------|--------------|-------------------|
| `type:bug` | `#DC143C` | 🐛 软件缺陷 / Software bugs |
| `type:feature` | `#32CD32` | ✨ 新功能请求 / New feature request |
| `type:enhancement` | `#87CEEB` | 💡 改进现有功能 / Improve existing features |
| `type:documentation` | `#4682B4` | 📚 文档相关 / Documentation related |
| `type:refactor` | `#9370DB` | 🔧 代码重构 / Code refactoring |
| `type:security` | `#FF4500` | 🔒 安全问题 / Security issues |

### 状态 / Status

| 标签名 / Name | 颜色 / Color | 描述 / Description |
|--------------|--------------|-------------------|
| `status:todo` | `#D3D3D3` | 📋 待处理 / To be done |
| `status:in-progress` | `#FFA500` | 🚧 进行中 / In progress |
| `status:review` | `#9370DB` | 👀 需要审查 / Needs review |
| `status:blocked` | `#DC143C` | 🚫 被阻塞 / Blocked |
| `status:ready` | `#32CD32` | ✅ 准备就绪 / Ready to deploy |

### 学期/活动周期 / Semester/Activity Cycle

| 标签名 / Name | 颜色 / Color | 描述 / Description |
|--------------|--------------|-------------------|
| `semester:fall` | `#D2691E` | 🍂 秋季学期功能 / Fall semester features |
| `semester:spring` | `#98FB98` | 🌸 春季学期功能 / Spring semester features |
| `event:fair` | `#FFD700` | 🎪 活动展会相关 / Activity fair related |

### 特殊标签 / Special Labels

| 标签名 / Name | 颜色 / Color | 描述 / Description |
|--------------|--------------|-------------------|
| `good-first-issue` | `#7057FF` | 🌟 适合新手的任务 / Good for newcomers |
| `help-wanted` | `#008672` | 🙋 需要帮助 / Extra attention needed |
| `teacher-review` | `#FFA500` | 👨‍🏫 需要教师审查 / Needs teacher review |
| `student-feedback` | `#87CEEB` | 💬 学生反馈 / Student feedback |
| `breaking-change` | `#FF0000` | ⚠️ 破坏性变更 / Breaking changes |

## 🎨 批量创建标签 / Batch Create Labels

如果你想快速创建所有标签，可以使用 GitHub CLI 或 API。以下是使用 GitHub CLI 的示例：

*If you want to quickly create all labels, you can use GitHub CLI or API. Here's an example using GitHub CLI:*

```bash
# 安装 GitHub CLI / Install GitHub CLI
# https://cli.github.com/

# 登录 / Login
gh auth login

# 创建标签 / Create labels
gh label create "club:art" --color "FF69B4" --description "艺术俱乐部相关功能"
gh label create "club:chess" --color "8B4513" --description "国际象棋俱乐部功能"
gh label create "priority:critical" --color "FF0000" --description "关键问题，需立即处理"
# ... 继续添加其他标签 / Continue adding other labels
```

## 📖 使用示例 / Usage Examples

### 示例 1: 报告艺术俱乐部的 Bug
*Example 1: Reporting a Bug for Art Club*

创建 Issue 时添加标签：
*Add labels when creating Issue:*
- `club:art`
- `type:bug`
- `priority:high`

### 示例 2: 请求春季学期的新功能
*Example 2: Requesting New Feature for Spring Semester*

创建 Issue 时添加标签：
*Add labels when creating Issue:*
- `club:general`
- `type:feature`
- `semester:spring`
- `priority:medium`

### 示例 3: 适合新手参与的文档任务
*Example 3: Documentation Task Suitable for Beginners*

创建 Issue 时添加标签：
*Add labels when creating Issue:*
- `type:documentation`
- `good-first-issue`
- `priority:low`

## 🔍 搜索示例 / Search Examples

创建标签后，你可以使用以下搜索来筛选 Issues：
*After creating labels, you can use the following searches to filter Issues:*

```
# 查找所有艺术俱乐部的高优先级问题
# Find all high priority issues for Art Club
is:open label:club:art label:priority:high

# 查找适合新手的任务
# Find tasks suitable for beginners
is:open label:good-first-issue

# 查找秋季学期的所有功能请求
# Find all feature requests for fall semester
is:open label:type:feature label:semester:fall

# 查找被阻塞的问题
# Find blocked issues
is:open label:status:blocked
```

## 📚 相关文档 / Related Documentation

- [完整 GitHub Issues 指南 / Complete GitHub Issues Guide](./GITHUB_ISSUES_GUIDE.md)
- [GitHub 官方文档 / GitHub Official Documentation](https://docs.github.com/en/issues)

---

## ✅ 完成检查清单 / Completion Checklist

- [ ] 访问标签管理页面
- [ ] 创建俱乐部分类标签（至少 3 个）
- [ ] 创建优先级标签（4 个）
- [ ] 创建问题类型标签（至少 4 个）
- [ ] 创建状态标签（至少 3 个）
- [ ] （可选）创建学期/活动标签
- [ ] （可选）创建特殊标签
- [ ] 在现有 Issue 上尝试添加标签
- [ ] 使用搜索功能筛选带标签的 Issues

恭喜！你现在已经为项目建立了一个完整的标签系统！🎉

*Congratulations! You've now established a complete label system for your project! 🎉*
