### 背景

在工作流流程流转后需刷新当前列表、表单的状态，或增加其他的的业务逻辑时.



#### 解决方案

在对应的前端代码中加入如下代码:

```javascript
    workflow.subscribeApprovalCallback(function (evt, data) {
    	//业务逻辑
        //ns.refresh();
    });
```

