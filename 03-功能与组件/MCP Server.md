# MCP Server (Model Context Protocol)

## 简介
MCP 是一种由 Anthropic 发起的开放标准，旨在通过统一的协议让 AI 模型安全、无缝地访问本地或远程的数据源。

## 核心能力
- **数据解耦**：模型不需要直接集成每个工具，而是通过 MCP 服务器间接访问。
- **本地安全**：让 AI 能够在不将所有隐私数据上传云端的情况下，读取本地文件系统。
- **灵活性**：支持多种连接方式，包括 STDIO 和 HTTP/SSE。
- **可复用性**：一个 MCP 服务器可以为不同的 AI 助手（如 Claude, Antigravity）提供服务。
