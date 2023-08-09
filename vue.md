1. 计算属性 `computed` 会将结果自动进行缓存，在模版 `template` 中使用计算属性时 如果计算属性依赖的数据没有发生变化时 不会重复进行计算，使用方法 `methods` 每次都会重新计算，存在不必要的性能开销
2. v-if 比 v-for 的优先级更高
3. 侦听器 `watch` 参数只能是 `Object` `watchEffect` 可以监听多个对象的变化
4. `HTML` 标签和属性名称是不分大小写的，浏览器会把任何字符解释为小写，并转换为 `kebab-case` (短横线连字符) 形式