<template>
  <nav class="main-navigation-container">
    <ul class="link-list">
      <li class="link-item" v-for="link in links" :key="link.name">
        <router-link :to="link.path">
          {{ link.name }}
        </router-link>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'MainNavigation',
  data() {
    return {
      links: [
        {
          name: 'Home',
          path: '/'
        },
        {
          name: 'About',
          path: '/about'
        },
        {
          name: 'My Work',
          path: '/my-work'
        },
        {
          name: 'Contact',
          path: '/contact'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
.main-navigation-container {
  position: sticky;
  top: $space-m;
  left: 100%;
  padding-right: $space-xl;
  display: inline-block;
  right: 100px;

  .link-list {
    display: flex;
    justify-content: flex-end;
    list-style: none;
    
    .link-item {
      a {
        color: $white-blue;
        text-decoration: none;
        padding: $space-xs $space-m;

        :active {
          background: $white-blue;
          color: $blue;
        } 
      }
    }
  }
}
</style>