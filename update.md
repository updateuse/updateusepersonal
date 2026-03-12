# Style

<details>
<summary>5.7.8</summary>

- 之前的偷懒没写
- 修复Win右键标签页无`分配到标签组`的bug

</details>

<details>
<summary>5.3.2</summary>

- AI生成简记支持生成没有摘要的条目（会读取pdf第一页进行生成）
- PDF预览支持选中文本并复制

</details>

<details>
<summary>5.1.9</summary>

- 修复附件预览只显示一页

</details>

<details>
<summary>5.1.5</summary>

- 近期版本主要修复鉴定Pro失败
- 文献矩阵的核心字段支持自动配置
- 文献矩阵的标注支持用评论替换标注文本，避免标注文本为英文且过长，影响阅读体验

</details>

<details>
<summary>5.0.8</summary>

- 文献矩阵核心字段支持自动根据标注颜色配置，只需要点击配置核心字段，清空里面内容，再关闭就会提示是否自动配置
- Explore面板笔记预览变更，双击可独立窗口打开笔记以预览全部/编辑笔记

</details>

<details>
<summary>5.0.7</summary>

- 嵌套标签搜索不区分大小写
- 修复标注侧边栏颜色名称被误修改bug

</details>

<details>
<summary>5.0.0</summary>

- Annotation Manager 搜索不区分大小写
- Annotation Manager 搜索关键词高亮

</details>

<details>
<summary>4.9.8</summary>

- Add Tags 增加选择的tags编辑框
- 列设置增加重置按钮，防止设置出错找不到默认值

</details>

<details>
<summary>4.9.3</summary>

文献矩阵支持插件注册列，比如期刊标签，则在辅助字段填写`publicationTags`，英文逗号与之前的字段分开。

下表的Field都可以写入辅助字段中。

|列名称|Field|
|---|---|
|期刊标签|publicationTags|
|被引数|citedCount|
|影响因子|IF|
|简记|remark|
|标签|tags|
|评级|rating|
|#标签|textTags|

效果预览
![效果预览](https://ice.frostsky.com/2024/09/18/3c612ba7135fc1d2a90ce545d7bb8160.png)


</details>


<details>
<summary>4.9.2</summary>

修复标签选择器黑色标签（本应有颜色）

</details>

<details>
<summary>4.9.0</summary>

新增侧边栏`TLDR`，太长不读，数据来自Semantics Scholar API，基于AI总结文章，用一句话概括文章。可理解为精简版摘要。支持翻译

</details>

<details>
<summary>4.8.9</summary>

修复图片粘贴到笔记不显示bug

</details>

<details>
<summary>4.8.8</summary>

支持快速`展开/折叠`左右侧边栏：
* 支持设定快捷键
* 支持主界面
* 支持阅读界面
* 支持笔记界面（安装Better Notes后笔记可在Tab打开，此处指这个界面）
* 主界面添加展开/折叠按钮
</details>

<details>
<summary>4.8.7</summary>

修复`嵌套标签`页面过滤bug

</details>

<details>
<summary>4.8.6</summary>
标注管理支持显示快照的标注
</details>

# GPT

<details>
<summary>2.1.2</summary>

- 支持上传笔记
- 侧边栏支持上传更多附件，比如补充材料或笔记

**需要同时升级插件+GPT Connector脚本**

</details>

<details>
<summary>1.3.4</summary>

- 修复侧边栏公式渲染错误bug
- 修复侧边栏保存bug
- 侧边栏公式居中

</details>

<details>
<summary>1.2.5</summary>

- 优化阅读划词弹出GPT命令溢出

</details>

<details>
<summary>1.2.3</summary>

- 重构设置界面

</details>

<details>
<summary>1.2.2</summary>

- 支持Zotero PDF矩形标注（矩形内图片）像GPT提问
- 支持跨页按Alt拼接上次选择的文字

</details>


<details>
<summary>1.2.1</summary>

侧边栏输入框菜单支持`显示文件`，便于拖入联动的网页，然后提问

</details>
