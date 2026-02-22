---

# 📘 Quant Portfolio Project – Setup Guide

# 📘 量化投資專案 – 環境設定說明

This guide explains how to install the required tools and correctly load the project Agent settings.
Please follow the steps carefully.

本說明將指導你正確安裝必要軟體並載入專案 Agent 設定。
請依照步驟操作。

---

# 1️⃣ Install Required Software

# 1️⃣ 安裝必要軟體

## Install VS Code

Download and install:

👉 [https://code.visualstudio.com/](https://code.visualstudio.com/)

After installation:

* Open VS Code
* Sign in with your GitHub account

---

## 安裝 VS Code

請下載並安裝：

👉 [https://code.visualstudio.com/](https://code.visualstudio.com/)

安裝完成後：

* 開啟 VS Code
* 使用 GitHub 帳號登入

---

## Install Git (Recommended but optional for beginners)

Download and install:

👉 [https://git-scm.com/](https://git-scm.com/)

Verify installation in Terminal:

```bash id="09z4vt"
git --version
```

If a version number appears, Git is installed correctly.

---

## 安裝 Git（推薦，但新手可略過）

請下載並安裝：

👉 [https://git-scm.com/](https://git-scm.com/)

在 Terminal 輸入：

```bash id="3m9z7v"
git --version
```

若出現版本號代表安裝成功。

---

# 2️⃣ Install GitHub Copilot

# 2️⃣ 安裝 GitHub Copilot

1. Open VS Code

2. Go to Extensions (Ctrl + Shift + X)

3. Search for:

   * **GitHub Copilot**
   * **GitHub Copilot Chat**

4. Install both

5. Sign in with your GitHub account

⚠ You must have Copilot access enabled.

---

1. 開啟 VS Code

2. 點選 Extensions（Ctrl + Shift + X）

3. 搜尋：

   * **GitHub Copilot**
   * **GitHub Copilot Chat**

4. 安裝兩個套件

5. 使用 GitHub 帳號登入

⚠ 必須有 Copilot 使用權限。

---

# 3️⃣ Download the Project Files

# 3️⃣ 下載專案檔案

You have TWO options:

你有兩種方式：

---

## ✅ Option A (Recommended): Clone with Git

Open Terminal and run:

```bash id="azn3jo"
git clone <REPOSITORY_URL>
cd <REPOSITORY_NAME>
code .
```

To update later:

```bash id="flc1zn"
git pull
```

This method keeps your project up to date automatically.

---

## 🟡 Option B (Beginner Method): Download ZIP

1. Go to the GitHub repository page
2. Click the green **Code** button
3. Click **Download ZIP**
4. Extract the ZIP file
5. Open the extracted folder in VS Code

⚠ Important:

* Every time the project updates, you must download the ZIP again.
* Old versions will NOT update automatically.

---

## 🟡 新手方式：下載 ZIP

1. 打開 GitHub 專案頁面
2. 點擊綠色 **Code** 按鈕
3. 點擊 **Download ZIP**
4. 解壓縮
5. 用 VS Code 開啟該資料夾

⚠ 注意：

* 專案更新時必須重新下載 ZIP
* 不會自動更新

---

# 4️⃣ Verify Agent Settings

# 4️⃣ 確認 Agent 成功載入

After opening the project in VS Code:

1. Open **Copilot Chat**
2. Check the Agent dropdown
3. You should see:

* **Team Assistant**
* **Output Reviewer**

If they do not appear:

Make sure this folder exists:

```id="y9ulb1"
.github/agents/
```

And contains:

* `TeamAssistant.agent.md`
* `OutputReviewer.agent.md`

---

開啟專案後：

1. 開啟 **Copilot Chat**
2. 查看 Agent 下拉選單
3. 應該會看到：

* **Team Assistant**
* **Output Reviewer**

若沒有出現：

請確認存在：

```
.github/agents/
```

並包含：

* `TeamAssistant.agent.md`
* `OutputReviewer.agent.md`

---

# 5️⃣ How to Use the Agents

# 5️⃣ 如何使用 Agent

## Team Assistant

Use for:

* Asking project-related questions
* Understanding requirements
* Clarifying methodology

This agent answers strictly based on project files.

---

## Output Reviewer

Use for:

* Submitting code
* Submitting report sections
* Checking performance results

This agent evaluates strictly against repository requirements.

---

# 6️⃣ Common Mistakes

# 6️⃣ 常見錯誤

❌ Downloading ZIP and forgetting to update
❌ Not signing into GitHub
❌ Not installing Copilot Chat
❌ Opening the wrong folder in VS Code

---

If everything is set up correctly, no additional configuration is needed.

若以上步驟完成，即可正常使用專案與 Agent 模式。
