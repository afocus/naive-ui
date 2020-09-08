# Dark Debug 4
```html
<n-button @click="modalActive = !modalActive">Toggle</n-button>
<n-drawer
  v-model="modalActive"
  width="800"
>
  <n-popover>
    <template v-slot:activator>
      <n-button style="margin:0;">
        悬浮
      </n-button>
    </template>
    <span>或许不想知道你的花园长得咋样</span>
  </n-popover>
</n-drawer>
```
```js
export default {
  data() {
    return {
      modalActive: false
    }
  }
}
```