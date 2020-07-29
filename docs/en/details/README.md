# § Details

It would be better for you to understand the structure of this Datatable before the details.

The source tree [`src/`](https://github.com/LaravelDaily/vue2-ld-datatable/tree/master/src) is shown as below:

```
 ├─ _mixins/
 ├─ _utils/
 ├─ HeaderSettings/
 │   ├─ ColumnGroup.vue
 │   └─ index.vue
 ├─ Table/
 │   ├─ HeadSort.vue
 │   ├─ index.vue
 │   ├─ MultiSelect.vue
 │   ├─ TableBody.vue
 │   ├─ TableFooter.vue
 │   ├─ TableFrame.vue
 │   └─ TableHeader.vue
 ├─ index.vue
 ├─ main.js
 ├─ PageSizeSelect.vue
 └─ Pagination.vue
```

Here is the illustration for the tree above, which is captured from the advanced example (source: [`examples/src/Advanced/index.vue`](https://github.com/LaravelDaily/vue2-ld-datatable/blob/master/examples/src/Advanced/index.vue), demo: [examples#advanced](https://laraveldaily.github.io/vue2-ld-datatable/examples/dist#advanced)):

<a href="images/structure.png" target="_blank" title="Click to enlarge">
  <img src="images/structure.png" alt="Structure">
</a>
