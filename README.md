## 概要
全面重写的 layDate 包含了大量的更新，其中主要以：年选择器、年月选择器、日期选择器、时间选择器、日期时间选择器 五种类型的选择方式为基本核心，并且均支持范围选择（即双控件）。内置强劲的自定义日期格式解析和合法校正机制，含中文版和国际版，主题简约却又不失灵活多样。由于内部采用的是零依赖的原生 JavaScript 编写，因此又可作为独立组件使用。毫无疑问，这是 layui 的虔心之作。

## 官网
[http://www.layui.com/laydate/](http://www.layui.com/laydate/)

## 相关
[文档](http://www.layui.com/doc/modules/laydate.html)、[社区](http://fly.layui.com)

## fork后的修改

### 2019-04-29
选择type为datetime的时候，增加一个参数setLastSeconds，允许默认的时间为23:59:59（之前默认时间为00:00:00）; setLastSeconds为true的时候，默认为23:59:59，setLastSeconds为false的时候，还是默认为00:00:00
