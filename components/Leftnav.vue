<template>
  <div class="columns leftnavbar">
    <aside class="menu column is-3">
      <p class="menu-label">General</p>
      <ul class="menu-list">
        <li>
          <a v-bind:class="{'is-active' : activeMenu.dashboard }">Dashboard</a>
        </li>
        <li>
          <a>Summary</a>
        </li>
      </ul>
      <p class="menu-label">Administration</p>
      <ul class="menu-list">
        <li>
          <a>Team Settings</a>
        </li>
        <li>
          <a>Invitations</a>
        </li>
      </ul>
    </aside>
    <div class="column is-9 pagecontent">
        <!-- the contents of the page -->
      <slot></slot>
    </div>
  </div>
</template>
<script>
export default {
  props: ['activeMenu']
}
</script>

<style lang="scss" scoped>
.leftnavbar {
  margin-top: 65px;
  height: 100%;
  min-height: calc(100vh - 65px);
  .menu {
    background-color: #dddddd;
  }
  .pagecontent {
      padding: 3rem 2rem;
  }
}
</style>

