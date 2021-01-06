<template>
  <div>
    <sidebar-menu :menu="menu" style="margin-top: 4rem;" />
  </div>
</template>

<script>
// https://www.npmjs.com/package/vue-sidebar-menu
import { SidebarMenu } from 'vue-sidebar-menu'

export default {
  components: {
    SidebarMenu
  },
  data () {
    return {
      menu: [
        {
          header: true,
          title: 'Main Navigation',
          hiddenOnCollapse: true
        },
        {
          href: '/',
          title: 'Home',
          icon: 'fa fa-home'
        },
        {
          href: '',
          title: 'User',
          icon: 'fa fa-user',
          child: [
            {
              href: '/user',
              title: 'User'
            },
            {
              href: '/user/profile',
              title: 'Profile'
            }
          ]
        }
      ]
    }
  }
}
</script>
