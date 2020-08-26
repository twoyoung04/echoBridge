<template>
  <div class="block">
  <mdb-container class="wrapper">
  <mdb-navbar expand="large" dark color="unique-color" class="navbar">
    <mdb-navbar-brand href="#">
      ECHOBRIDGE
    </mdb-navbar-brand>
    <mdb-navbar-toggler>
      <mdb-navbar-nav right>
        
        <mdb-dropdown tag="li" class="nav-item">
          <mdb-dropdown-toggle
            tag="a"
            navLink
            slot="toggle"
            waves-fixed>
            WHY US?
          </mdb-dropdown-toggle>
          <mdb-dropdown-menu>
            <mdb-dropdown-item>todo</mdb-dropdown-item>
            <mdb-dropdown-item>todo</mdb-dropdown-item>
            <mdb-dropdown-item>todo</mdb-dropdown-item>
          </mdb-dropdown-menu>
        </mdb-dropdown>
        <mdb-dropdown tag="li" class="nav-item">
          <mdb-dropdown-toggle tag="a" navLink color="unique-color" slot="toggle" waves-fixed>EXPERTISE</mdb-dropdown-toggle>
          <mdb-dropdown-menu>
            <mdb-dropdown-item>todo</mdb-dropdown-item>
            <mdb-dropdown-item>todo</mdb-dropdown-item>
            <mdb-dropdown-item>todo</mdb-dropdown-item>
          </mdb-dropdown-menu>
        </mdb-dropdown>
        <mdb-nav-item href="#">CLIENT</mdb-nav-item>
        <mdb-nav-item href="#">ABOUT</mdb-nav-item>
        <mdb-nav-item href="#">BLOG</mdb-nav-item>
        
      </mdb-navbar-nav>
    </mdb-navbar-toggler>
  </mdb-navbar>
  </mdb-container>
  </div>
</template>

<script>
import { mdbNavbar, mdbNavbarBrand, mdbNavItem, mdbNavbarNav, mdbNavbarToggler, mdbDropdown, mdbDropdownToggle, mdbDropdownMenu, mdbDropdownItem } from 'mdbvue'


export default {
  name: 'Navbar',
  components: {
    mdbNavbar,
    mdbNavbarBrand,
    mdbNavItem,
    mdbNavbarNav,
    mdbNavbarToggler,
    mdbDropdown,
    mdbDropdownToggle,
    mdbDropdownMenu,
    mdbDropdownItem
  },
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.navbar .nav-item {
  font-size: 16px;
}
main {
  background-color: #ededee;
}

.flexible-content {
  transition: padding-left 0.3s;
  padding-left: 270px;
}

.flexible-navbar {
  transition: padding-left 0.5s;
  padding-left: 270px;
}

@media (max-width: 1199.98px) {
  .sidebar-fixed {
    display: none;
  }
  .flexible-content {
    padding-left: 0;
  }
  .flexible-navbar {
    padding-left: 10px;
  }
  .navbar {
    position: -webkit-sticky;
    position: sticky;
    top: 0;
  }
  .wrapper {
    padding: 2rem 0;
  }
}

</style>
