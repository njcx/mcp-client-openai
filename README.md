#### MCP-client
本项目实现了一个兼容 OpenAI API 格式的 MCP (Model Control Protocol) 客户端服务，允许通过标准的 OpenAI API 接口与本地 MCP 模型进行交互。


运行方法：

    1,  启动openai api :  python main-api.py

    2,  启动 stdio cli  :  python cli.py   # just for test


MCP-Server配置：

    修改mcp-server-config.json, 支持stdio 和sse两种。

LLM配置：

    修改mcp-server-config.json  llm字段， 支持所有 OpenAI API 格式的API， 需要支持 Function Call（工具调用）。


![test](92e24.jpg)