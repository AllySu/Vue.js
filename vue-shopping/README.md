
# Vue.js 购物车实战

## 介绍

为什么选择购物车做示例呢？首先是因为它很常见，而且大家都对购物车的功能十分熟悉；其次，它的交互相对复杂，一个基本的购物车包括：选择商品、修改数量／属性、价格的计算，其中还包括判断库存、全选状态的联动等等。如果能搞定购物车，那么大部分的应用开发也不在话下了。

项目共 2 个页面：商品列表 和 购物清单。涉及列表展示、分类筛选、条件排序、购物车等电商项目常用的功能，尽可能覆盖到了Vue基础部分的所有知识点（模板语法、计算属性、样式绑定、条件渲染、列表渲染、事件处理），每段代码也有相应的注释以便参考。UI设计和交互也参考了天猫、京东的手机web端，尽量还原线上项目。


## 功能

### 商品列表

- 分类筛选
- 根据销量、价格进行排序
- 添加到购物车

### 购物清单

- 商品的选择、全选
- 数量增减
- 计算总价
- 删除

## 总结

从读取数据并展示到列表（读）、把商品添加到购物车（增）、修改数量（改）再到删除选中的商品（删），一套流程下来后，对使用Vue来开发项目有了基本认识。在解决开发过程中遇到的问题时，也对Vue的数据绑定原理有了更深的认识。

虽然这个项目没有用到vue-cli，或者那些“高大上”的构建工具，但我始终认为javascript语言本身和各类前端框架的思想才是精髓，对于有追求和真正热爱前端的开发者来说，打好基础再去上手它们也不迟。

