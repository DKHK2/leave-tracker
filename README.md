# 公司年假管理 App

## 简介
一个纯静态的 Web App，让管理者和员工记录已放年假天数、查看剩余年假。适合分享到 WhatsApp 群组使用。

## 功能
- **输入页**：每位员工可输入 2024/2025/2026 三年已放年假天数，自动计算剩余
- **管理者总览**：全公司汇总表格，含 WhatsApp 分享按钮
- **设定页**：可编辑员工姓名、入职日期、年假额度规则

## 部署到 GitHub Pages

### 步骤

1. **登入 GitHub**（账号：DKHK2），点击右上角 **+** → **New repository**
2. 仓库名称填 `leave-tracker`（或任意名称）
3. 选择 **Public**（公开）
4. 勾选 **Add a README file**
5. 点击 **Create repository**

### 上传 index.html

1. 在仓库页面点击 **Add file** → **Upload files**
2. 将 `index.html` 拖入上传区
3. 点击 **Commit changes**

### 开启 GitHub Pages

1. 进入仓库 → **Settings** → 左侧菜单 **Pages**
2. **Source** 选择 **Deploy from a branch**
3. **Branch** 选择 `main`，文件夹选 `/ (root)`
4. 点击 **Save**
5. 等待约 1-2 分钟，页面顶部会显示公网网址：
   ```
   https://dkhk2.github.io/leave-tracker/
   ```

### 分享到 WhatsApp

1. 复制上面的网址
2. 贴到公司 WhatsApp 群组
3. 同事点开即可使用

## 备注
- 数据储存在各人浏览器的 localStorage，不同手机之间不会同步
- 适合「各自记录自己已放年假」的场景
- 若需要全公司数据同步，需另设后端数据库
