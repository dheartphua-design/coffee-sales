# 咖啡店营业额

一个手机友好的网页，显示咖啡店每天卖了多少钱（RM）。

- `index.html`：网页本身
- `sales.csv`：销售记录，从 Google Sheet「sale record」的 Sale 页导出，列为 `timestamp,item,quantity,price`（price 是单价）

## 怎么更新数据

用新的销售记录替换 `sales.csv` 并推送到 GitHub，一两分钟后网页就会显示新数字。
