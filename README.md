[TOC]

# Github-Star 油猴脚本使用说明

# 中文说明

**油猴脚本 - GitHub Star 自动记录到 Notion Database**

## 脚本说明：

这个油猴脚本允许你在 GitHub 仓库页面点击 Star 按钮时，自动将当前仓库信息记录到 Notion 数据库中。这可以帮助你更好地管理你的 GitHub Stars，并将相关信息整理到你的 Notion 数据库中。

## **步骤 1：安装脚本**

1. 首先，确保你已经在浏览器中安装了油猴插件。如果没有安装，你可以在你的浏览器插件商店中找到它并进行安装。
2. 安装完油猴插件后，在浏览器中打开脚本安装页面。

## **步骤 2：配置**

1. 打开 GitHub 仓库页面，确保你已经登录到你的 GitHub 账号。
2. 在 GitHub 仓库页面，按下键盘上的 F9 键。这将触发脚本的配置模式。
3. 在弹出的配置窗口中，你需要提供以下信息：
    - Notion 的 Token：这是用于访问你的 Notion 账号的 API Token。你可以在 Notion 设置中生成它。
    - Notion 的 Database Id：这是你想要将仓库信息存储的 Notion 数据库的唯一标识符。

## **步骤 3：使用**

1. 配置完毕后，回到 GitHub 仓库页面。
2. 浏览你感兴趣的仓库，点击 Star 按钮。
3. 脚本将自动捕捉仓库信息，并将其记录到你在 Notion 中指定的数据库中。

通过遵循上述步骤，你可以方便地将 GitHub 仓库的 Star 记录到你的 Notion 数据库中，使你更加高效地管理你的 Stars 和相关信息。

请注意，脚本的效果可能会因为 GitHub 或 Notion 的页面结构变化而受到影响。在这种情况下，你可能需要更新脚本以适应新的页面布局。

Notion Database 模板页面链接 🔗：[Github Star Notion Database 模板](https://www.notion.so/3ad1ccd895434812ae2335f7617a50a6?pvs=21)。

如果你想修改 Database 配置或使用自己的 Database，请保证 Database 至少有以下属性：

1. Name： Title 类型
2. URL：URL 类型

你可以在这个[链接🔗](https://notion-b-sigma.vercel.app/how%20to%20get%20notion%20token%20and%20database%20id)找到如何获取 Token 和 Databa Id 的相关说明

# Instructions in English

**Tampermonkey Script - Automatically Recording GitHub Stars to Notion Database**

## Script Description

This Tampermonkey script allows you to automatically record information about a GitHub repository into a Notion database when you click the Star button on the repository page. This enables you to better manage your GitHub Stars by organizing relevant information into your Notion database.

## **Step 1: Install the Script**

1. First, ensure that you have the Tampermonkey extension installed in your browser. If not, you can find and install it from your browser's extension store.
2. Once Tampermonkey is installed, open the script installation page in your browser.

## **Step 2: Configuration**

1. Open the GitHub repository page and ensure that you are logged into your GitHub account.
2. On the GitHub repository page, press the F9 key on your keyboard. This will trigger the script's configuration mode.
3. In the popped-up configuration window, you need to provide the following information:
    - Notion Token: This is the API Token used to access your Notion account. You can generate it in your Notion settings.
    - Notion Database Id: This is the unique identifier of the Notion database where you want to store repository information.

## **Step 3: Usage**

1. After configuring, return to the GitHub repository page.
2. Browse the repository you're interested in and click the Star button.
3. The script will automatically capture the repository information and record it in the Notion database you specified.

By following the steps above, you can conveniently record GitHub repository stars into your designated Notion database, allowing you to efficiently manage your Stars and related information.

Please note that the effectiveness of the script might be affected by changes in the page structure of GitHub or Notion. In such cases, you may need to update the script to accommodate the new page layout.

**Notion Database Template Page Link** 🔗: **[GitHub Star Notion Database Template](https://www.notion.so/3ad1ccd895434812ae2335f7617a50a6?pvs=21)**.

If you wish to modify the Database configuration or use your own Database, ensure that the Database includes at least the following properties:

1. Name: Title Type
2. URL: URL Type

You can find instructions on how to obtain the Token and Database ID at [this link 🔗](https://www.jiangjiwei.space/how%20to%20get%20notion%20token%20and%20database%20id).