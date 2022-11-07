<template>
  <div class="container">
    <b-navbar spaced fixed-top :class="{ change_color: scrollPosition > 50 }">
      <template #brand>
        <b-navbar-item tag="router-link" :to="{ path: '/' }">
          <img
            src="~/assets/img/peter.png"
          />
        </b-navbar-item>
      </template>
      <template #end>
        <b-navbar-item href="#"> Home </b-navbar-item>
        <b-navbar-item href="#"> Services </b-navbar-item>
        <b-navbar-item href="#"> About Me </b-navbar-item>
        <b-navbar-item href="#"> Resume </b-navbar-item>
        <b-navbar-item href="#"> Contact </b-navbar-item>
      </template>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'NavbarComponent',
  data() {
    return {
      scrollPosition: null,
    }
  },
  mounted() {
    window.addEventListener('scroll', this.updateScroll)
  },
  methods: {
    updateScroll() {
      this.scrollPosition = window.scrollY
    },
  },
}
</script>

<style scoped>
.navbar {
  background: #e1e1e3;
}
.change_color {
  background-color: #fff;
}
.navbar-item {
  font-size: 22px;
  padding: 0.5rem 2rem;
  font-weight: 500;
}
a.navbar-item:focus, 
a.navbar-item:focus-within, 
a.navbar-item:hover, 
a.navbar-item.is-active, 
.navbar-link:focus, 
.navbar-link:focus-within, 
.navbar-link:hover, 
.navbar-link.is-active {
  background-color: transparent;
  color: #43a7ff;
  transition: all 0.5s ease;
}
</style>
