# GitHub 发布与 Supadata 激励申请说明

## 新仓库

地址：https://github.com/hubao201198/supadata-transcript-markdown-python

- 类型：Public（公开）
- 英文教程：README.md（超过 600 英文单词）
- 可运行脚本：video_to_notes.py
- 异步轮询独立示例：examples/quickstart_async.py
- 单元测试：tests/；GitHub Actions：.github/workflows/tests.yml
- 个人链接：https://supadata.ai/r/9YW9BZ05

## 如何领取

1. 打开仓库，确认所有代码、测试和 .github/workflows 都可访问。
2. 打开 Actions 查看自动测试状态，或本地运行 `python3 -m unittest discover -s tests -v`。
3. 将仓库地址粘贴到 Supadata 的 Link to your post or page 栏，并点击 Verify and claim。
4. 根据活动规则，内容公开并持续存活七天后，额度才可能解锁；以 Supadata 实际审核结果为准。

## 如何运行

macOS/Linux：

```bash
export SUPADATA_API_KEY="YOUR_OWN_API_KEY"
python3 video_to_notes.py "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
python3 -m unittest discover -s tests -v
```

Windows PowerShell：

```powershell
$env:SUPADATA_API_KEY = "YOUR_OWN_API_KEY"
python video_to_notes.py "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
```

真实 API 调用可能消耗 Supadata credits，离线单元测试不消耗 credits。
不要上传真实密钥，也不要把未实际运行的 API 请求写成已验证结果。

## 这次复审注意事项

旧 URL 不能重新提交时，可以使用这个新的公开仓库地址。
不过，新仓库仍与旧仓库共享教程内容；Supadata 可能判定为重复投稿。
建议补充自己真正运行过的输出、经验和原创实践。请保留推广链接的披露声明。
