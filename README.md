# ppt

声享产品需求收集。如果使用过程中遇到一些 bug 或者建议，请提 issue。

## 更新历史

### 2018.04.04

* 添加了会议功能，将各种大会的 PPT  汇集起来，顺便汇总大咖数据。
* 服务端从 ThinkJS 2 升级到 ThinkJS 3，重写了所有代码
* 编辑器优化了截图生成封面的功能，并在第一页提供手动生成封面的按钮
* 编辑器提交的复杂数据，服务端做了严格的校验，避免安全漏洞
* 去除导入 PPT 的功能，只允许导入 PDF。重构了 PDF 生成图片的功能
* 添加了搜索的功能
* 重写了管理端功能
* 优化了访问别人页面的策略（将用户名改为 user_url）
