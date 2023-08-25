# Notion Token 和 Database Id 获取

[TOC]

# 获取 Notion Token 和 Database ID - 教程-中文

以下是详细的步骤指南：

## **步骤 1：在 Notion 中创建集成**

1. 在网页浏览器中登录你的 [Notion](https://www.notion.so/) 账户。
2. 进入 [Integration](https://www.notion.so/my-integrations) 页面
3. 点击 "+ New Integration"（+ 创建集成）按钮，以创建一个新的集成。

## **步骤 2：生成 API Token**

1. 为你的集成命名（例如 "GitHub Star Integration"）。
2. 在 "Select a workspace"（选择工作区）中，选择你想要创建集成的工作区。
3. 点击 "Submit"（提交）或 "Create"（创建）按钮，以创建集成。
4. 创建集成后，你会看到提供的 API Token。这是你将用于以编程方式访问 Notion 账户的令牌。

## **步骤 3：找到 Database ID**

1. 在 Notion 中，打开你想要查找的 Database。
2. 复制浏览器地址栏中数据库的 URL。
3. Database ID 是 URL 最后一个斜杠 ("/") 后的部分，到 （”?”）前为止。

示例：

```bash
# 网页链接
https://www.notion.so/jiangjiwei/q234234342234234234?v=asdfadfsdfsdf

# Database Id
q234234342234234234
```

## **步骤 4：保护你的 Token 和 ID**

1. API Token 是敏感信息。保持其私密性，不要与他人分享。
2. 同样要安全存储 Database ID。它用于识别你将存储 GitHub 仓库信息的 Notion 数据库。

请记住，本教程基于截至 2021 年 9 月的 Notion 状态提供信息。如果自那时以来有任何更改，请参考最新的官方 Notion 文档以获取准确的说明。

# How to Get Notion Token and Database ID - Tutorial-English

Below are the detailed steps:

## **Step 1: Create an integration in Notion**

1. Log in to your [Notion](https://www.notion.so/) account in a web browser.
2. Go to the [Integration](https://www.notion.so/my-integrations) page.
3. Click the "+ New Integration" button to create a new integration.

## **Step 2: Generate an API Token**

1. Name your integration (e.g. "GitHub Star Integration").
2. In "Select a workspace", select the workspace where you want to create the integration.
3. Click the "Submit" or "Create" button to create the integration.
4. After creating the integration, you will see the provided API Token. This is the token you will use to programmatically access your Notion account.

## **Step 3: Find the Database ID**

1. In Notion, open the Database you want to find.
2. Copy the URL of the database from the address bar.
3. The Database ID is the part after the last slash ("/") in the URL up to the "?" before the parameters.

Example:

```bash
# Webpage link
https://www.notion.so/jiangjiwei/q234234342234234234?v=asdfadfsdfsdf

# Database Id
q234234342234234234

```

## **Step 4: Secure your Token and ID**

1. The API Token is sensitive information. Keep it private and do not share it with others.
2. Also securely store the Database ID. It is used to identify the Notion database where you will store GitHub repo information.

Please note this tutorial provides information based on the state of Notion as of September 2021. Refer to the latest official Notion documentation if there have been any changes since then to get accurate instructions.