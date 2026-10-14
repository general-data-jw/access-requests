# 代码仓库访问申请

本页面用于申请以下私有仓库的访问权限：

| 仓库 | 内容 |
| --- | --- |
| `general-data-pipeline` | 通用数据清洗管线 |
| `vlm-dim-operators` | 七维小算子打分与筛选流程 |

## 如何申请

> **申请获批后，还需要你接受邀请！** 管理员审核通过后会向提交申请的 GitHub 账号发送仓库邀请。请留意 GitHub 通知或绑定邮箱中的邀请邮件，打开邀请并点击 **Accept invitation（接受邀请）**。只有接受邀请后才能访问私有仓库；申请获批或 Issue 被关闭，都不代表已经可以访问。

1. 登录你的 GitHub 账号。
2. 点击 **[提交访问申请](https://github.com/general-data-jw/access-requests/issues/new?template=access-request.yml)**。
3. 选择需要访问的仓库，填写用途并提交。
4. 等待管理员审核。批准后，你会收到对应私有仓库的 GitHub 邀请。
5. 打开 GitHub 通知或邀请邮件，点击 **Accept invitation（接受邀请）**，之后即可查看、克隆和下载代码。申请两个仓库时，请分别接受两个仓库的邀请。

如果管理员已通知发送邀请，但你没有找到邀请，或邀请已失效，请在原申请 Issue 中留言，请管理员核对账号或重新发送。

提交申请不会自动获得权限。默认批准的是 **Read（只读）** 权限，不能直接推送修改。

**申请内容公开可见。请勿填写密码、API Key、私人联系方式或机密项目资料。** 提交申请的 GitHub 账号即为邀请对象。

## 管理员操作

1. 查看本仓库的 [待处理申请](https://github.com/general-data-jw/access-requests/issues)。
2. 核对申请人的 GitHub 账号、目标仓库及用途。
3. 批准后，进入目标私有仓库：**Settings → Collaborators and teams → Add people**。
4. 输入申请人的 GitHub 用户名，选择 **Read** 后发送邀请。按仓库邀请为外部协作者，无需加入整个组织。
5. 处理完后关闭申请 Issue。拒绝申请时不要发送仓库邀请。

邀请需要管理员手动执行，本仓库没有自动授权工作流。仓库代码继续保持 Private。
