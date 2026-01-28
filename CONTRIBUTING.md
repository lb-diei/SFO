# 贡献指南

感谢您对文件整理技能项目的关注！我们欢迎各种形式的贡献。

## 如何贡献

### 报告问题

如果您发现了 bug 或有功能建议，请：

1. 检查 [Issues](https://github.com/your-username/file-organizer-skill/issues) 确认问题未被报告
2. 创建新的 Issue，包含：
   - 清晰的标题
   - 详细的描述
   - 重现步骤
   - 预期行为和实际行为
   - 环境（操作系统、Claude Code 版本等）

### 提交代码

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

### 代码规范

- 保持代码简洁清晰
- 添加必要的注释
- 遵循现有的文件结构
- 更新相关文档

### 技能文件格式

技能文件（`skill.md`）应遵循以下结构：

```markdown
# 技能名称

## 概述
简要描述技能的功能

## 触发条件
何时使用此技能

## 输入参数
- 必需参数
- 可选参数

## 执行步骤
1. 步骤一
2. 步骤二
...

## 错误处理
处理常见问题

## 输出结果
成功时的输出格式

## 使用示例
提供具体示例
```

### 文档贡献

- 修正错别字
- 改善文档清晰度
- 添加更多示例
- 翻译文档

## 开发设置

1. 克隆仓库
```bash
git clone https://github.com/your-username/file-organizer-skill.git
```

2. 将技能文件复制到 Claude Code skills 目录
```bash
cp skill.md ~/.claude/skills/
```

3. 在 Claude Code 中测试技能

## 测试

在提交代码前，请确保：

- 功能在多种文件类型下正常工作
- 边界情况得到正确处理
- 错误信息清晰明确
- 文档已更新

## 许可证

通过贡献代码，您同意您的贡献将使用 MIT License 许可。

## 联系方式

如有疑问，请通过以下方式联系：

- 提交 Issue
- 发送邮件

---

再次感谢您的贡献！
