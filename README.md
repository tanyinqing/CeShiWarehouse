

- 框架结构
   - [Element](app/src/main/java/crazy/tyq/ceshiwarehouse/treeview/Element.java)
   - [TreeViewAdapter](app/src/main/java/crazy/tyq/ceshiwarehouse/treeview/TreeViewAdapter.java)
   - [TreeViewItemClickListener](app/src/main/java/crazy/tyq/ceshiwarehouse/treeview/TreeViewItemClickListener.java)
   - [ListViewActivity 列表显示](app/src/main/java/crazy/tyq/ceshiwarehouse/ListViewActivity.java)
   - [MainActivity 构建手势探测器](app/src/main/java/crazy/tyq/ceshiwarehouse/MainActivity.java)
   - [TreeViewDialog 自定义封装的弹出框](app/src/main/java/crazy/tyq/ceshiwarehouse/TreeViewDialog.java)



**精髓代码重构**

----------
- 代码最重要的是重构，一个产品要经过很多次重构才会最终产生，包括页面和功能。
所以，产品要划分模块，模块要划分功能，功能要对应页面，页面划分业务部分，方法逻辑部分，页面适配部分。这样就像人体骨骼一样，比较清晰。

- 快速重构别人的代码
res文件夹下的代码，全部复制。包下的文件，也全部复制。清单文件复制。这样就比较
快乐。