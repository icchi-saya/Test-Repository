<template>
  <div>
    <h1>カウント: {{ count }}</h1>
    <button @click="increment">カウントアップ</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    };
  },
  methods: {
    increment() {
      this.count++;
    }
  }
};
</script>

<style scoped>
h1 {
  color: #42b983;
}
button {
  background-color: #42b983;
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}
button:hover {
  background-color: #367a6e;
}
</style>
