## 在 TypeScript 中指定组件的类型

```html
<script lang="ts">
// 需要引入这个
// import { ElDataTreeType } from '@femessage/el-data-tree'
// 如果你用的是 @femessage/element-ui
// import { ElDataTreeType } from '@femessage/el-data-tree/src/femessage'
export default {
  mounted() {
    (this.$refs.dataTree as ElDataTreeType).fetchData()
  },
}
</script>
```