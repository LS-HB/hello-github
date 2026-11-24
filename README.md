# hello-github

SSH 连通性测试仓库 —— 用于验证 `clone → commit → push` 全链路。

## 环境

- 平台：Windows 10/11
- Git：PortableGit（WorkBuddy 内置）
- 认证方式：SSH（ed25519 密钥）
- 提交身份：LS-HB <627279137@qq.com>

## 测试记录

| 步骤 | 状态 |
|---|---|
| 生成密钥 | OK |
| 公钥上传 GitHub | OK |
| `ssh -T git@github.com` | OK |
| 本地提交 | OK |
| 远程推送 | 待验证 |
