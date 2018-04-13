<template>
  <div>
    <mt-button type="default">default</mt-button>
    <mt-button type="default">default2</mt-button>
    <mt-button type="primary">primary</mt-button>
    <mt-button type="danger">danger</mt-button>
    <mt-button icon="back">back</mt-button>
    <mt-button icon="more">更多</mt-button>
    <mt-button plain>plain</mt-button>
  </div>
</template>

<script>
import { Button } from 'mint-ui'
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  component: { Button }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
