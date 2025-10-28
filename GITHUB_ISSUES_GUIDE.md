# GitHub Issues 完整指南 / Complete Guide to GitHub Issues

## 目录 / Table of Contents

1. [什么是 GitHub Issues？/ What are GitHub Issues?](#什么是-github-issues--what-are-github-issues)
2. [Issues 的主要功能 / Main Features of Issues](#issues-的主要功能--main-features-of-issues)
3. [如何添加自定义标签 / How to Add Custom Labels](#如何添加自定义标签--how-to-add-custom-labels)
4. [标签最佳实践 / Label Best Practices](#标签最佳实践--label-best-practices)

---

## 什么是 GitHub Issues？/ What are GitHub Issues?

GitHub Issues 是一个强大的项目管理工具，用于：
- 🐛 跟踪 bug 和问题
- 💡 收集功能建议和想法
- 📋 管理任务和待办事项
- 💬 与团队成员讨论项目相关话题

*GitHub Issues is a powerful project management tool used for:*
- *🐛 Tracking bugs and problems*
- *💡 Collecting feature suggestions and ideas*
- *📋 Managing tasks and to-do lists*
- *💬 Discussing project-related topics with team members*

---

## Issues 的主要功能 / Main Features of Issues

### 1. 创建和管理 Issues / Creating and Managing Issues

**如何创建 Issue / How to Create an Issue:**

1. 进入仓库页面，点击 **"Issues"** 标签
   *Navigate to the repository page and click the **"Issues"** tab*

2. 点击 **"New issue"** 按钮（绿色按钮）
   *Click the **"New issue"** button (green button)*

3. 填写以下信息：
   *Fill in the following information:*
   - **标题 (Title)**: 简洁描述问题
     *A concise description of the issue*
   - **描述 (Description)**: 详细说明问题、复现步骤、期望结果等
     *Detailed explanation of the problem, reproduction steps, expected results, etc.*
   - **标签 (Labels)**: 分类标签（如 bug、enhancement、documentation 等）
     *Classification tags (e.g., bug, enhancement, documentation)*
   - **指派人员 (Assignees)**: 指定负责人
     *Assign responsible person(s)*
   - **项目 (Projects)**: 关联到项目看板
     *Link to project board*
   - **里程碑 (Milestone)**: 关联到版本里程碑
     *Associate with version milestone*

4. 点击 **"Submit new issue"** 创建
   *Click **"Submit new issue"** to create*

### 2. 标签 (Labels) 系统

标签用于分类和组织 Issues，使团队更容易筛选和管理。
*Labels are used to categorize and organize Issues, making it easier for teams to filter and manage them.*

**默认标签 / Default Labels:**
- `bug` 🐛 - 报告软件缺陷 / Report software bugs
- `documentation` 📚 - 文档改进 / Documentation improvements
- `duplicate` 🔄 - 重复的 Issue / Duplicate issue
- `enhancement` ✨ - 新功能请求 / New feature request
- `good first issue` 👶 - 适合新手的任务 / Good for newcomers
- `help wanted` 🙋 - 需要帮助 / Extra attention needed
- `invalid` ❌ - 无效的 Issue / Invalid issue
- `question` ❓ - 提问 / Further information requested
- `wontfix` 🚫 - 不会修复 / This will not be worked on

### 3. 评论和讨论 / Comments and Discussion

Issue 支持：
*Issues support:*
- 💬 **评论功能** - 团队成员可以讨论和提供反馈
  *Comment functionality - Team members can discuss and provide feedback*
- 📎 **附件上传** - 可以上传图片、日志文件等
  *Attachment uploads - Upload images, log files, etc.*
- 🔗 **引用** - 使用 `#123` 引用其他 Issue 或 PR
  *References - Use `#123` to reference other Issues or PRs*
- 👍 **反应表情** - 使用表情符号快速表达意见
  *Reactions - Use emoji to quickly express opinions*

### 4. 指派和通知 / Assignment and Notifications

- **指派人员 (Assignees)**: 可以指派一个或多个负责人
  *You can assign one or more responsible persons*
- **订阅通知 (Notifications)**: 关注感兴趣的 Issue 获取更新
  *Subscribe to Issues of interest to receive updates*
- **提及功能 (@mention)**: 使用 `@username` 提醒特定用户
  *Use `@username` to notify specific users*

### 5. 项目管理集成 / Project Management Integration

- **里程碑 (Milestones)**: 将 Issues 组织到版本发布周期中
  *Organize Issues into release cycles*
- **项目看板 (Projects)**: 使用看板视图管理工作流
  *Use board view to manage workflow*
- **自动化 (Automation)**: 通过 GitHub Actions 自动化 Issue 管理
  *Automate Issue management through GitHub Actions*

### 6. 搜索和筛选 / Search and Filter

强大的搜索功能让你能够：
*Powerful search capabilities allow you to:*
- 按标签筛选：`label:bug`
  *Filter by label: `label:bug`*
- 按状态筛选：`is:open` 或 `is:closed`
  *Filter by status: `is:open` or `is:closed`*
- 按指派人筛选：`assignee:username`
  *Filter by assignee: `assignee:username`*
- 按作者筛选：`author:username`
  *Filter by author: `author:username`*
- 组合搜索：`is:open label:bug assignee:@me`
  *Combined search: `is:open label:bug assignee:@me`*

---

## 如何添加自定义标签 / How to Add Custom Labels

### 方法一：通过仓库设置添加 / Method 1: Add Through Repository Settings

**步骤 / Steps:**

1. **进入标签管理页面 / Navigate to Labels Management**
   - 进入你的仓库 / Go to your repository
   - 点击 **"Issues"** 标签 / Click the **"Issues"** tab
   - 点击 **"Labels"** 按钮（在搜索框旁边）/ Click the **"Labels"** button (next to the search box)
   
   或者直接访问：`https://github.com/用户名/仓库名/labels`
   *Or visit directly: `https://github.com/username/repository/labels`*

2. **创建新标签 / Create New Label**
   - 点击绿色的 **"New label"** 按钮
     *Click the green **"New label"** button*
   
3. **填写标签信息 / Fill in Label Information**
   - **Label name**: 标签名称（例如：`priority:high`、`status:in-progress`、`type:security`）
     *Label name (e.g., `priority:high`, `status:in-progress`, `type:security`)*
   - **Description**: 标签描述（可选，但建议添加以说明用途）
     *Label description (optional but recommended to explain usage)*
   - **Color**: 选择颜色（点击颜色框可以自定义颜色代码）
     *Choose a color (click the color box to customize color code)*

4. **保存标签 / Save Label**
   - 点击 **"Create label"** 按钮
     *Click the **"Create label"** button*

### 方法二：在创建 Issue 时添加 / Method 2: Add While Creating an Issue

1. 创建或编辑 Issue 时，在右侧找到 **"Labels"** 部分
   *When creating or editing an Issue, find the **"Labels"** section on the right*

2. 点击 **"Labels"** 齿轮图标
   *Click the **"Labels"** gear icon*

3. 在标签列表底部，点击 **"Edit labels"** 链接
   *At the bottom of the label list, click the **"Edit labels"** link*

4. 这会跳转到标签管理页面，按方法一的步骤 2-4 操作
   *This will redirect to the labels management page, follow steps 2-4 from Method 1*

### 编辑现有标签 / Edit Existing Labels

在标签管理页面，每个标签旁边都有：
*On the labels management page, next to each label there are:*
- ✏️ **Edit** 按钮 - 修改名称、描述或颜色
  *Edit button - Modify name, description, or color*
- 🗑️ **Delete** 按钮 - 删除标签（会同时从所有 Issues 中移除）
  *Delete button - Remove label (will also remove from all Issues)*

---

## 标签最佳实践 / Label Best Practices

### 1. 使用分类系统 / Use a Classification System

建议使用前缀组织标签：
*Recommended to use prefixes to organize labels:*

```
类型 (Type):
  - type:bug 🐛
  - type:feature ✨
  - type:documentation 📚
  - type:refactor 🔧

优先级 (Priority):
  - priority:critical 🔥
  - priority:high ⬆️
  - priority:medium ➡️
  - priority:low ⬇️

状态 (Status):
  - status:todo 📋
  - status:in-progress 🚧
  - status:review 👀
  - status:blocked 🚫

区域 (Area):
  - area:frontend 💻
  - area:backend ⚙️
  - area:database 🗄️
  - area:security 🔒
```

### 2. 颜色编码建议 / Color Coding Suggestions

- 🔴 **红色系 (Red)** - 紧急、严重问题、安全问题
  *Urgent, critical issues, security issues*
- 🟠 **橙色系 (Orange)** - 高优先级、需要注意
  *High priority, needs attention*
- 🟡 **黄色系 (Yellow)** - 中等优先级、警告
  *Medium priority, warnings*
- 🟢 **绿色系 (Green)** - 新功能、改进、已完成
  *New features, improvements, completed*
- 🔵 **蓝色系 (Blue)** - 文档、信息、问题
  *Documentation, information, questions*
- 🟣 **紫色系 (Purple)** - 依赖、外部因素
  *Dependencies, external factors*
- ⚫ **灰色系 (Gray)** - 已关闭、无效、重复
  *Closed, invalid, duplicate*

### 3. 常用自定义标签示例 / Common Custom Label Examples

```
团队管理 (Team Management):
  - needs-review 👀 - 需要代码审查
  - needs-testing 🧪 - 需要测试
  - needs-documentation 📝 - 需要文档
  - good-first-issue 🌟 - 适合新手

技术分类 (Technical Classification):
  - performance ⚡ - 性能优化
  - accessibility ♿ - 无障碍访问
  - i18n 🌍 - 国际化
  - breaking-change ⚠️ - 破坏性变更

工作流程 (Workflow):
  - awaiting-response 💤 - 等待回应
  - on-hold ⏸️ - 暂停处理
  - ready-for-deployment 🚀 - 准备部署
```

### 4. 标签使用技巧 / Label Usage Tips

1. **保持简洁** - 不要创建太多标签，通常 10-20 个核心标签即可
   *Keep it simple - Don't create too many labels, typically 10-20 core labels are sufficient*

2. **描述清晰** - 为每个标签添加描述，说明何时使用
   *Clear descriptions - Add descriptions to each label explaining when to use it*

3. **定期维护** - 删除不再使用的标签，合并相似标签
   *Regular maintenance - Remove unused labels, merge similar labels*

4. **团队共识** - 确保团队成员理解标签含义和使用场景
   *Team consensus - Ensure team members understand label meanings and usage scenarios*

5. **自动化标签** - 使用 GitHub Actions 根据 Issue 内容自动添加标签
   *Automated labels - Use GitHub Actions to automatically add labels based on Issue content*

### 5. 示例：为本项目添加自定义标签 / Example: Adding Custom Labels for This Project

针对 Mergington High 课外活动网站项目，可以创建：
*For the Mergington High Extracurricular Activities website project, you can create:*

```
- club:art 🎨 (颜色: #FF69B4)
  描述: Issues related to Art Club features
  
- club:chess ♟️ (颜色: #8B4513)
  描述: Issues related to Chess Club features
  
- club:general 🏫 (颜色: #4169E1)
  描述: Issues affecting all clubs
  
- needs:teacher-review 👨‍🏫 (颜色: #FFA500)
  描述: Needs review from faculty advisor
  
- semester:fall 🍂 (颜色: #D2691E)
  描述: Features for fall semester
  
- semester:spring 🌸 (颜色: #98FB98)
  描述: Features for spring semester
```

---

## 快速参考 / Quick Reference

### 创建标签快捷方式 / Label Creation Shortcut

直接访问：`https://github.com/你的用户名/仓库名/labels/new`
*Direct access: `https://github.com/your-username/repository-name/labels/new`*

### Issue 标签语法 / Issue Label Syntax

在 Issue 中快速添加标签：
*Quickly add labels in Issues:*
- 点击右侧 "Labels" 区域
  *Click the "Labels" area on the right*
- 搜索并选择标签
  *Search and select labels*
- 可以选择多个标签
  *You can select multiple labels*

### 批量管理 / Bulk Management

选择多个 Issues 后，可以批量添加或删除标签：
*After selecting multiple Issues, you can bulk add or remove labels:*
1. 在 Issues 列表页勾选多个 Issue
   *Check multiple Issues in the Issues list page*
2. 点击 "Label" 下拉菜单
   *Click the "Label" dropdown menu*
3. 选择要添加或删除的标签
   *Select labels to add or remove*

---

## 相关资源 / Related Resources

- 📖 [GitHub Issues 官方文档 / Official Documentation](https://docs.github.com/en/issues)
- 🏷️ [标签管理文档 / Labels Documentation](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels)
- 🤖 [Issue 模板 / Issue Templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests)
- ⚡ [GitHub Actions 自动化 / Automation](https://docs.github.com/en/actions)

---

## 总结 / Summary

GitHub Issues 是一个功能强大的项目管理工具，通过合理使用标签系统，可以：
*GitHub Issues is a powerful project management tool. By properly using the label system, you can:*

✅ 更好地组织和分类问题
   *Better organize and categorize issues*

✅ 提高团队协作效率
   *Improve team collaboration efficiency*

✅ 快速定位和筛选相关 Issues
   *Quickly locate and filter relevant Issues*

✅ 建立清晰的工作流程
   *Establish clear workflows*

现在你已经掌握了如何添加和管理自定义标签，可以开始为你的项目创建适合的标签体系了！🎉
*Now that you've learned how to add and manage custom labels, you can start creating a suitable label system for your project! 🎉*
