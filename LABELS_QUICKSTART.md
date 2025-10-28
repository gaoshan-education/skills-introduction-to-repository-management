# 快速入门：为本项目添加自定义标签 / Quick Start: Adding Custom Labels for This Project

本指南将帮助你快速为 Mergington High 课外活动网站项目添加有用的自定义标签。

*This guide will help you quickly add useful custom labels for the Mergington High Extracurricular Activities website project.*

## 🚀 快速步骤 / Quick Steps

### 1. 访问标签管理页面 / Navigate to Labels Page

**方法 1：通过仓库界面 / Method 1: Through Repository UI**

1. 进入仓库主页 / Go to repository home
2. 点击 **"Issues"** 标签 / Click **"Issues"** tab
3. 点击 **"Labels"** 按钮 / Click **"Labels"** button

**方法 2：直接访问 URL / Method 2: Direct URL Access**

访问以下格式的 URL（替换为你的仓库信息）：
*Visit URL in the following format (replace with your repository info):*

```
https://github.com/YOUR-USERNAME/YOUR-REPOSITORY/labels
```

例如本仓库：
*For example, this repository:*

```
https://github.com/gaoshan-education/skills-introduction-to-repository-management/labels
```

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

如果你想快速创建所有标签，可以使用 GitHub CLI 或 API。以下是使用 GitHub CLI 的完整示例：

*If you want to quickly create all labels, you can use GitHub CLI or API. Here's a complete example using GitHub CLI:*

### 准备工作 / Preparation

```bash
# 1. 安装 GitHub CLI / Install GitHub CLI
# macOS: brew install gh
# Windows: choco install gh
# Linux: See https://cli.github.com/

# 2. 登录 / Login
gh auth login

# 3. 进入你的仓库目录 / Navigate to your repository directory
cd /path/to/your/repository
```

### 创建所有标签的脚本 / Script to Create All Labels

将以下内容保存为 `create-labels.sh` 或直接在终端执行：
*Save the following as `create-labels.sh` or execute directly in terminal:*

```bash
#!/bin/bash

# 俱乐部分类 / Club Categories
gh label create "club:art" --color "FF69B4" --description "艺术俱乐部相关功能 / Art Club features"
gh label create "club:chess" --color "8B4513" --description "国际象棋俱乐部功能 / Chess Club features"
gh label create "club:sports" --color "FF6347" --description "体育活动相关 / Sports activities"
gh label create "club:music" --color "9370DB" --description "音乐俱乐部功能 / Music Club features"
gh label create "club:general" --color "4169E1" --description "影响所有俱乐部的功能 / Features affecting all clubs"

# 优先级 / Priority
gh label create "priority:critical" --color "FF0000" --description "关键问题，需立即处理 / Critical issues, needs immediate attention"
gh label create "priority:high" --color "FF6B6B" --description "高优先级 / High priority"
gh label create "priority:medium" --color "FFD93D" --description "中等优先级 / Medium priority"
gh label create "priority:low" --color "95E1D3" --description "低优先级 / Low priority"

# 问题类型 / Issue Type
gh label create "type:bug" --color "DC143C" --description "软件缺陷 / Software bugs"
gh label create "type:feature" --color "32CD32" --description "新功能请求 / New feature request"
gh label create "type:enhancement" --color "87CEEB" --description "改进现有功能 / Improve existing features"
gh label create "type:documentation" --color "4682B4" --description "文档相关 / Documentation related"
gh label create "type:refactor" --color "9370DB" --description "代码重构 / Code refactoring"
gh label create "type:security" --color "FF4500" --description "安全问题 / Security issues"

# 状态 / Status
gh label create "status:todo" --color "D3D3D3" --description "待处理 / To be done"
gh label create "status:in-progress" --color "FFA500" --description "进行中 / In progress"
gh label create "status:review" --color "9370DB" --description "需要审查 / Needs review"
gh label create "status:blocked" --color "DC143C" --description "被阻塞 / Blocked"
gh label create "status:ready" --color "32CD32" --description "准备就绪 / Ready to deploy"

# 学期/活动周期 / Semester/Activity Cycle
gh label create "semester:fall" --color "D2691E" --description "秋季学期功能 / Fall semester features"
gh label create "semester:spring" --color "98FB98" --description "春季学期功能 / Spring semester features"
gh label create "event:fair" --color "FFD700" --description "活动展会相关 / Activity fair related"

# 特殊标签 / Special Labels
gh label create "good-first-issue" --color "7057FF" --description "适合新手的任务 / Good for newcomers"
gh label create "help-wanted" --color "008672" --description "需要帮助 / Extra attention needed"
gh label create "teacher-review" --color "FFA500" --description "需要教师审查 / Needs teacher review"
gh label create "student-feedback" --color "87CEEB" --description "学生反馈 / Student feedback"
gh label create "breaking-change" --color "FF0000" --description "破坏性变更 / Breaking changes"

echo "所有标签创建完成！/ All labels created!"
```

### 运行脚本 / Run the Script

```bash
# 给脚本执行权限 / Make the script executable
chmod +x create-labels.sh

# 运行脚本 / Run the script
./create-labels.sh
```

**注意 / Note:** 如果标签已存在，命令会失败。你可以添加 `--force` 标志来更新现有标签。
*If a label already exists, the command will fail. You can add the `--force` flag to update existing labels.*

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
