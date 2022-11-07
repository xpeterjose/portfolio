<template>
  <section class="hero is-medium">
    <div class="hero-body">
      <div class="container is-fullhd">
        <p class="intro is-size-4 has-text-centered">My Portfolio</p>
        <p
          class="my-expertise is-size-1 has-text-weight-bold has-text-centered"
        >
          Recent Works
        </p>

        <div class="is-flex is-justify-content-center mt-6">
          <button @click="filter('all')">All</button>
          <button @click="filter('web')">Web App</button>
          <button @click="filter('mobile')">Mobile App</button>
        </div>

        <transition-group
          name="list-complete"
          class="list-complete mt-5"
          tag="section"
        >
          <div
            v-for="item in filteredItems"
            :key="item.id"
            class="list-complete-item"
          >
            <img
              class="list-complete-img"
              src="~/assets/img/peterjose2.jpg"
              alt=""
            />
          </div>
        </transition-group>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      items: [
        { id: 1, tags: ['all', 'web'] },
        { id: 2, tags: ['all', 'web'] },
        { id: 3, tags: ['all', 'mobile'] },
        { id: 4, tags: ['all', 'mobile'] },
        { id: 5, tags: ['all', 'web'] },
        { id: 6, tags: ['all', 'web'] },
        { id: 7, tags: ['all', 'mobile'] },
        { id: 8, tags: ['all', 'web'] },
      ],
      currentTag: 'all',
    }
  },
  computed: {
    filteredItems() {
      const filter = this.currentTag
      return this.items.filter(function (item) {
        // eslint-disable-next-line unicorn/prefer-includes
        return item.tags.indexOf(filter) !== -1
      })
    },
  },
  methods: {
    filter(tag) {
      this.currentTag = tag
    },
  },
}
</script>

<style scoped>
.hero {
  background: #f1f4fb;
}
.intro {
  color: #43a7ff;
}
.my-expertise {
  color: #0b224b;
  font-weight: 800 !important;
}

.list-complete {
  display: flex;
  width: 100%;
  flex-direction: row;
  flex-wrap: wrap;
}
.list-complete-item {
  transition: transform 1s;
  flex: 1 1 30%;
  height: 200px;
  padding: 10px;
  border-radius: 14px;
}
.list-complete-img {
  object-fit: cover;
  height: 100%;
  width: 100%;
  border-radius: 14px;
}
.list-complete-enter, .list-complete-leave-to
/* .list-complete-leave-active for <2.1.8 */ {
  opacity: 0;
  transform: translateX(10px);
}
.list-complete-leave-active {
  position: absolute;
}
button {
  background: transparent;
  outline: none;
  border: 0;
  font-size: 24px;
  cursor: pointer;
  margin: 0px 50px;
}
</style>
