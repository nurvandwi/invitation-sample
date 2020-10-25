<template>
  <article>
    <header class="tabs">
      <ul class=" justify-content-evenly my-5 py-5">
        <li v-for="(tab, index) in tabs" :key="index">
          <div
            class="nav-item"
            :class="{ 'is-active': tab.isActive }"
            @click="selectTab(tab)"
          >
            {{ tab.name }}
          </div>
        </li>
      </ul>
    </header>
    <section class="tabs-details">
      <slot></slot>
    </section>
  </article>
</template>

<script>
export default {
  data: () => {
    return {
      tabs: []
    };
  },
  methods: {
    selectTab(selectedTab) {
      this.tabs.forEach(tab => {
        tab.isActive = tab.name === selectedTab.name;
      });
    }
  },
  created() {
    this.tabs = this.$children;
  }
};
</script>

<style scoped>
ul {
  display: flex;
  padding: 0;
  list-style: none;
  justify-content: space-evenly;
  font-size: 1.5rem;
}
li {
  color: #fff;
  font-weight: bold;
}

.nav-item {
  cursor: pointer;
}

.nav-item:hover {
  color: #d3d3d3;
}
.nav-item:active {
  color: red;
}
</style>