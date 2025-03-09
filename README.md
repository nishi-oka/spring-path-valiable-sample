## 依存関係
- Spring Boot DevTools
- Thymeleaf
- Spring Web

# 表示URL
http://localhost:8080/show

# エラーした点
エラー文：`org.attoparser.ParseException: (Line = 10, Column = 1) Incomplete structure: "</h"`
- ボタンBを押したときに遷移できない
  →headerタグが欠けていた　`<h1>Submit B Page</h`
  
