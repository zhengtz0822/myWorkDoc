### 背景

在工作流流程审批后往往需要处理客户端交互页面的额外逻辑，如刷新页面或改变其他显示样式等。

#### 解决方案

实现工作流审批通过后对应的回调方法,在对应的前端代码中加入如下代码:

```javascript
    workflow.subscribeApprovalCallback(function (evt, data) {
    	//业务逻辑
        //ns.refresh();
    });
```