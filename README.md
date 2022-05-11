# Note Attrs

Note Attrs 是一个简单的组件，用于显示一个笔记的属性。由于它是嵌入在文档页面中的，所以比官方的属性面板操作起来更加便捷和直观。

Note Attrs 与 Note Views 搭配起来使用更佳，它同样也支持属性字段类型，对于字段展示名称、类型的设置，将会在所有 Note Attrs 和 Note Views 挂件中同步生效。这意味着，你只需要维护一份全局属性字段，就可以在多个挂件实例中使用。

**使用需知：**

- 第一次添加挂件时将无法加载数据，请务必**重新载入笔记**使挂件生效。如果不重新载入，点击“保存属性到文档”时会导致内核错误，后续版本将修复；

**更新日志：**

- v1.2.1 自动判断网络请求协议（http/https）
- v1.2.0 新增属性类型：网络链接
- v1.1.0 首次安装挂件后点击「保存属性到文档」会提示重新载入挂件


![preview](https://raw.githubusercontent.com/langzhou/siyuan-note/main/widgets/note-attrs/preview/note-attrs-1.png)