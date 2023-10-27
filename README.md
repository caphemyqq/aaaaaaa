## 步驟 1：編輯 setting.xml 檔案
打開名為 setting.xml 的XML檔案，您可以使用文本編輯器（如Notepad++、Visual Studio Code等）來進行編輯。

您會看到以下XML內容，它包含了本金、年利率和投資年份的設定：

```
xml
Copy code
<data>
    <x>10000</x><!--本金-->
    <s>10</s><!--利率-->
    <y>20</y><!--年份-->
</data>

修改 <x> 內的數字以設定您的本金。例如，如果您的本金是 20000，請將 <x> 改為 <x>20000</x>。

修改 <s> 內的數字以設定您的年利率。例如，如果您的年利率是 5%，請將 <s> 改為 <s>5</s>。

修改 <y> 內的數字以設定您希望投資的年份。例如，如果您打算投資 10 年，請將 <y> 改為 <y>10</y>。
```

儲存 setting.xml 檔案。

## 步驟 2：運行複利計算程式
開啟您的Python開發環境（例如，IDLE、PyCharm等）。

在Python環境中，運行您的複利計算程式。程式將自動讀取 setting.xml 檔案並計算複利。

## 步驟 3：查看計算結果
程式將在終端窗口上顯示計算結果，包括本金、年利率、投資年份以及您可能得到的金額。請仔細檢查這些結果。

## 步驟 4：儲存結果
程式會將計算結果儲存在一個名為 result.txt 的檔案中。您可以在該檔案中找到計算結果的詳細內容。

開啟 result.txt 檔案，您將看到本金、年利率、投資年份以及您可以得到的金額的詳細資訊。

現在，您已經成功使用複利計算程式來估算未來的投資回報。希望這些詳細的步驟能幫助您順利使用這個小工具！
