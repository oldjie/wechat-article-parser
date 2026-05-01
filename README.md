# 微信公众号文章解析器

解析微信公众号文章，提取核心要点和干货。让 AI 帮你快速读完一篇公众号文章，不漏重点。

## 功能

- 解析微信公众号文章链接
- 提取标题、作者、发布时间
- 提取正文内容
- 智能总结核心要点

## 安装

```bash
# 安装依赖
npm install playwright cheerio

# 安装浏览器（仅需一次）
npx playwright install chromium
```

## 使用方法

```bash
node scripts/fetch-wechat.js <公众号文章链接>
```

## 示例

```bash
node scripts/fetch-wechat.js https://mp.weixin.qq.com/s/xxxxx
```

## 适用场景

- 快速了解公众号文章核心内容
- 批量处理多个公众号文章
- 信息收集与整理

## 相关话题

- `ai-skill`
- `agent-skill`
