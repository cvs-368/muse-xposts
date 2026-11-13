# X 财经帖子采集日志

每天从 X 直接抓取 11 个财经账号的公开帖子（未登录），供晚间简报与早间检查使用。

- 账号：@DeItaone @FirstSquawk @LiveSquawk @RedboxWire @niubi @caixin @HAOHONG_CFA @michaelxpettis @ShanghaiMacro @markets @ReutersBiz
- 时间：北京时间（Asia/Shanghai）；时间戳由帖子雪花 ID 解码，精确到分钟
- 转推已剔除；跨账号相同内容只保留一条
- 采集器跑在 serv00 上，每 5 分钟轮询一次；本仓库每 30 分钟同步一次
- 2026-11-13 及之前：agent 采集器（镜像站）日志，时间戳多为 `[*]`（未知）；2026-11-13 晚间起：脚本直采，时间戳精确
- @markets 自 2026-07-14 起未发帖（账号停更，非采集缺失）

文件：`posts/YYYY-MM-DD-posts.md`，每天一个文件。
