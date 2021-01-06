<template>
  <q-layout>
    <q-page-container>
      <sidemenu />
      <router-view />
      <topbar />
    </q-page-container>
  </q-layout>
</template>

<script>
import Topbar from 'src/components/topbar'
import Sidemenu from 'src/components/sidemenu'

export default {
  components: {
    Topbar,
    Sidemenu
  },
  name: 'MainLayout',
  data () {
    return {
      // ...
    }
  }
}
</script>
