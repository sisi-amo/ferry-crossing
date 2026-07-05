# 渡口

渡口不渡人。它只是停在那里，等你自己决定哪条路沉下去。

一个 AI 人生模拟小游戏，单文件 Python 实现。

## 怎么玩

1. 下载 `server.py` 到本地
2. 确保有 Python 3
3. 运行：

```bash
python server.py --cli
```

4. 按提示输入指令，开始你的一生

输入 `帮助` 查看所有指令。

## MCP 模式

不带参数运行即启动 MCP Streamable HTTP 服务：

```bash
python server.py
```

环境变量：
- `UNIVERSE_PORT` — 端口（默认 8765）
- `UNIVERSE_KEY` — API Key（为空则不校验）
