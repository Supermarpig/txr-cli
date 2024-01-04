# chi 工具

這是一個用於管理 ChangeLog 的命令行工具（CLI），它提供了一系列命令來創建和維護 ChangeLog 文件。

## 功能

- `init`：新增一個新的空白 ChangeLog 文件。
- `add`：向 ChangeLog 文件添加一條新條目。
- `release`：將當前的 ChangeLog 標記為已發布。
- `add-version`：向 ChangeLog 添加一個新的版本標記。
- `test`：運行一組基本的測試來確保 ChangeLog 功能正常。

## 安裝

clone此存儲庫，然後在您的項目目錄中運行：

```bash
npm install 
```

## 使用

在命令行中使用 chi 命令，後跟相應的子命令。例如：

```bash
chi init              # 創建一個新的 ChangeLog
chi add -m "新功能"    # 添加一條包含消息 "新功能" 的條目
chi release           # 標記 ChangeLog 為已發布
chi add-version -v "版本" -d "描述"
```

## 開發

此工具使用 Node.js 開發。您可以查看 src 目錄中的代碼來了解更多實現細節。

## 測試

要運行測試，使用以下命令：

```bash
chi test
```

## 授權

MIT
