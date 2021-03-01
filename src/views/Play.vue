<template>
  <div class="play">
    <h1>Welcome to the Play Area</h1>
    <Prompt/>
    <UserCode/>
    <Tips/>
    <Output/>
  </div>
</template>

<script>
// @ is an alias to /src
import Prompt from '@/components/Prompt.vue'
import UserCode from '@/components/UserCode.vue'
import Tips from '@/components/Tips.vue'
import Output from '@/components/Output.vue'

export default {
  name: 'Play',
  components: {
    Prompt,
    UserCode,
    Tips,
    Output
  }
}
</script>