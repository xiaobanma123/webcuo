<template>
  <section class="navbar">
    <div v-for="item in list" :key="item.id"
    :class="['navbar-item', +item.id === +$parent.selected && 'selected']"
    @click="$emit('input', item.id)">{{item.text}}</div>
  </section>
</template>
<script>
export default {
  name: 'navbar',
  data () {
    return {
    }
  },
  props: {
    selected: {
      default: 1
  
  },
    list: {
      type: Array,
      require: true
    }
  },
  methods: {
    clickItem (index) {
      alert(index)
      this.$emit('input', id)
    }
  }
}
</script>
<style scoped>
.navbar{
  width: 100%;
  height: 88px;
  display: flex;
  flex-direction: row;
}
.navbar-item{
  flex: 1;
  color: #fefefe;
  line-height: 88px;
  font-size: 28px;
}
.selected{
  color: #e69800;
  border-bottom: 6px solid #e69800;
}
</style>

