# Security Policy

## Supported versions

安全支持从正式 `v1.0.0` Release 开始。预览阶段不应部署到生产环境。

## Reporting a vulnerability

请通过 GitHub 的私密安全报告功能提交漏洞，不要在公开 Issue 中披露可利用细节、密钥、用户数据或生产地址。

报告建议包含：受影响版本、复现步骤、影响范围、必要日志和建议修复。请先删除密码、Token、API Key、用户文件和个人信息。

## Secret handling

- 不接受包含真实凭据的提交。
- `.env`、数据库、上传文件、模型密钥和管理员密码不得进入 Git。
- 即使密钥已经失效，也应从当前代码和公开 Git 历史删除。
- 测试凭据必须明显不可用于真实服务。
