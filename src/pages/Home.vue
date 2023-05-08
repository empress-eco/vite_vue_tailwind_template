<template>
  <div class="max-w-3xl py-12 mx-auto">
    <Button icon-left="code" @click="ping.fetch" :loading="ping.loading">
      Click to send 'ping' request
    </Button>
    <div>
      {{ ping.data }}
    </div>
    <pre>{{ ping }}</pre>

    <Button @click="showDialog = true">Open Dialog</Button>
    <Dialog title="Title" v-model="showDialog"> Dialog content </Dialog>
  </div>
</template>

<script setup>
import { ref } from 'vue'
import { Dialog } from 'frappe-ui'
import { createResource } from 'frappe-ui'

const ping = createResource({
  url: 'ping',
  auto: true,
})

const showDialog = ref(false)
</script>
