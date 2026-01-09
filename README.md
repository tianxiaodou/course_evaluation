# 课程评估系统

这是一个课程评估系统的前端页面集合，包含以下功能页面：

## 页面列表

- **首页**：`index.html` - 系统入口，提供所有功能页面的访问链接
- **课程评估系统**：`course_evaluation_system.html` - 主要的课程评估功能
- **课程树选择**：`course_tree_selection.html` - 课程树结构选择功能
- **专家数据库管理**：`expert_database_management.html` - 专家信息管理功能
- **专家分组管理**：`expert_group_management.html` - 专家分组功能

## GitHub Pages 部署说明

1. **创建GitHub仓库**
   - 在GitHub上创建一个新仓库
   - 将本目录下的所有文件上传到仓库中

2. **启用GitHub Pages**
   - 进入仓库的「Settings」
   - 找到「Pages」选项
   - 在「Source」中选择「main」分支
   - 选择「/ (root)」作为发布目录
   - 点击「Save」按钮

3. **访问方式**
   - 首页：`https://[your-username].github.io/[repository-name]/`
   - 课程评估系统：`https://[your-username].github.io/[repository-name]/course_evaluation_system.html`
   - 课程树选择：`https://[your-username].github.io/[repository-name]/course_tree_selection.html`
   - 专家数据库管理：`https://[your-username].github.io/[repository-name]/expert_database_management.html`
   - 专家分组管理：`https://[your-username].github.io/[repository-name]/expert_group_management.html`

## 本地测试

直接在浏览器中打开 `index.html` 文件即可访问所有功能页面。

## 文件说明

- `index.html`：系统首页，提供导航链接
- `course_evaluation_system.html`：课程评估系统主页面
- `course_tree_selection.html`：课程树选择页面
- `expert_database_management.html`：专家数据库管理页面
- `expert_group_management.html`：专家分组管理页面
- `404.html`：页面不存在时的错误提示页面
- `内江师范学院本科课程评估标准.xlsx`：评估标准文件

## 注意事项

- 请确保所有HTML文件在同一目录下
- 如果页面中引用了外部资源（如CSS、JavaScript文件或图片），请确保路径正确
- GitHub Pages部署后，可能需要等待几分钟才能正常访问