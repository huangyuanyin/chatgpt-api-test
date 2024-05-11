# 2024 Node.js 调用 ChatGPT API 实现 Stream 流式效果

运行效果如下

![](./bak/chat.gif)

ChatGPT API 文档 https://platform.openai.com/docs/overview

## 背景

- 网上很多资料过时了，不再符合 OpenAI 的开发文档
- 我要做一个 Node 全栈 AIGC 知识库项目，需要用到 ChatGPT API

## 前置条件

- 有一个可以访问 ChatGPT API 的机器
- 有 ChatGPT 账号，且开通了 API key 并且可以被调用（配额充足）

## 下载和运行

保证你的机器上有 git 和 nodejs

git clone 这份代码

代码根目录，将 `.env.example` 文件重命名为 `.env` ，然后修改内容， 写上你自己的 API key

控制台进入代码目录，执行

```
npm install
npm start
```

## 测试

访问该机器 `3001` 端口。PS：云服务器可能需要开通 OS 防火墙端口，以及平台的安全组。

## 关于我的 Node 全栈 AIGC 项目

如果你也对 Node 全栈 AIGC 感兴趣，可以私信我。
