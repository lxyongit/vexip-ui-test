<template>
  <div>
    <div @click="onMessage">click</div>
  </div>
</template>

<script lang="ts" setup>
import { Message } from 'vexip-ui';

const onMessage = () => {
  console.log(3333)
  Message.success('33', 1000 * 60)
}
</script>