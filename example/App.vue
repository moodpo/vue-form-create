<!--suppress ALL -->
<script lang="ts">
// import { toRaw } from 'vue'
// 引入相关的依赖
export default {
  name: 'TestApp'
}
</script>

<script setup lang="ts">
// const dataJson = {
//   list: [
//     {
//       label: '单行文本',
//       type: 'input',
//       options: {
//         width: '100%',
//         defaultValue: '',
//         placeholder: '',
//         maxlength: null,
//         prefix: '',
//         suffix: '',
//         prepend: '',
//         append: '1',
//         disabled: false,
//         clearable: false,
//         readonly: false,
//         rules: {
//           trigger: 'blur',
//           enum: '',
//           message: '',
//           pattern: '',
//           required: false,
//           type: 'any'
//         }
//       },
//       key: '733a3709e38f481aa36a1ec73cfa4a77',
//       model: 'input_733a3709e38f481aa36a1ec73cfa4a77',
//       rules: []
//     },
//     {
//       label: '多行文本',
//       type: 'textarea',
//       options: {
//         width: '100%',
//         defaultValue: '',
//         placeholder: '',
//         maxlength: null,
//         rows: 4,
//         autosize: false,
//         showWordLimit: false,
//         disabled: false,
//         clearable: false,
//         readonly: false,
//         rules: {
//           trigger: 'blur',
//           enum: '',
//           message: '',
//           pattern: '',
//           required: false,
//           type: 'any'
//         }
//       },
//       key: 'ad1cb09c208f427594b3bff17ab67284',
//       model: 'textarea_ad1cb09c208f427594b3bff17ab67284',
//       rules: []
//     }
//   ],
//   config: {
//     size: 'default',
//     hideRequiredAsterisk: false,
//     labelWidth: 100,
//     labelPosition: 'right'
//   }
// }

// const handleSelectParam = (val: any) => {
//   console.log('handleSelectParam', toRaw(val))
// }

// const valueJson = {}
</script>

<template>
  <ElDesignForm />
  <!-- <div class="form-wrapper">
    <ElGenerateForm
      :data="dataJson"
      :value="valueJson"
      @handleSelectParam="handleSelectParam"
    />
  </div> -->
</template>
<style scoped>
  .form-wrapper {
    margin: 20px auto;
    width: 500px;
  }
</style>
