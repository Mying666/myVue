[demo页面](https://mying666.github.io/myVue/)
## 替换{{}}里的内容
1. 获取el内所有dom
2. 判断nodetype类型
3. 标签类型正则匹配{{}}并存储name
4. 引用data.name触发getter
5. getter触发watcher的update,把name赋值给text节点

---

## 监听数据变化
1. 通过object.defineProperty监听data数据

---

## 代理data数据，vm.name操作vm.data.name

