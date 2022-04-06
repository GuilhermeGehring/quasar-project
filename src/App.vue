<template>
  <div id="q-app">
    <router-view />
  </div>
</template>

<script>
import { CapacitorUpdater } from 'capacitor-updater'
CapacitorUpdater.notifyAppReady()
export default {
  name: 'App'
}
</script>
