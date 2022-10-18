Intellij & Spring Boot
===
###### tags: `Spring Boot` `Intellij`

## Notes 
<!--  <max@example.com>-->
- **Reference:** - [github](https://github.com/dyc87112/SpringBoot-Learning/tree/master/2.x/chapter2-3)


:mag: 常用快捷鍵列表
---
- 選中文字，按Ctrl+Shift+F7 ，高亮顯示所有該文字，按Esc高亮消失。
- Ctrl+Shift+Space 自動補全程式碼
- Ctrl+Shift+Up/Down 程式碼向上/下移動。
- Ctrl+/ 或 Ctrl+Shift+/  註釋（// 或者/*...*/ ）
- Ctrl+Shift+F 查詢檔案
- Ctrl+Shift+N 查詢檔案
- Ctrl+F 查詢文字
- Ctrl＋F7查詢當前元素在當前檔案中的引用，然後按F3可以選擇
- Ctrl+R 替換文字
- Ctrl+Q 顯示註釋文件
- Ctrl+H 顯示類結構圖
- Ctrl＋F12，顯示當前檔案的結構
- Ctrl+X 刪除行
- Ctrl+D 複製行
- Ctrl+Alt+L  格式化程式碼
- Alt+ left/right 切換程式碼檢視
- Alt+ Up/Down 在方法間快速移動定位
- Alt+ENTER 匯入包,自動修正
- Alt+F1 查詢程式碼所在位置
- Alt+1 快速開啟或隱藏工程皮膚
- Shift+F6  重構-重新命名
- F2 或Shift+F2 高亮錯誤或警告快速定位


:books: Spring Boot
---
- **Stereotype Annotations (刻板印象標注):**
1. 自動識別這個類別的角色與用途 `45min`
	> [name=Yukai]
2.  Framework 可以透過 Component scanning 快速的找到相對應的服務。 `45min`
** **
- **@EnableAutoConfiguration:**
1. Spring Boot 自動找出所有相依套件中 JAR 檔的類別，並自動建立與註冊成 Spring Beans 元件，好讓 Spring Boot 可以在需要的時候使用這些可重複利用這些的 Spring Beans 元件。


    - Ctrl+Shift+N 查詢檔案

:dart: MAVEN
---
- Nested JAR 的封裝方式- 發佈一個自我包含所有 JAR 檔的 JAR 可執行檔(self-contained executable jar file)


:closed_book: Tasks
--
==Importance== (1 - 5) / Name / **Estimate** (1, 2, 3, 5, 8, 13)
### Development Team:
- [ ] ==5== Email invite
  - [x] ==4== Email registration page **5**
- [ ] ==4== Setup e2e test in production **2**

