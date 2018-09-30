<template>
  <div>
    <h3>JS Counter</h3>
    <div>{{count}}</div>
    <div>
    <button @click="increment()">INCREMENT</button>
    </div>
  </div>
</template>

<script lang="js">
export default  {
  data () {
    return {
      count: 0
    }
  },
  methods: {
    increment() {
      this.count++
    }
  }
}
</script>
