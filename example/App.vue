<template>
  <div>
    运行vue
    <print-msg></print-msg>
  </div>
</template>

<script>
import { PrintMsg } from '../dist/index'

export default {
  components: {
    'print-msg': PrintMsg,
  },
}
</script>
