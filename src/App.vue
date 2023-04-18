<template>
  <div class="container">
    <h1>지키고 싶은 나만의 루틴</h1>
    <img class="rabbit" src="/images/rabbit.png" alt="토끼로고">
    <a href="/components/"></a>
    <Todo />
  </div>
</template>

<script>
import Todo from "./components/TodoList.vue"
export default {
  components: {
    Todo,
  }

}
</script>

<style>
.container {
  max-width: 700px;
  margin: 0 auto;
  background: rgb(245, 245, 245);
}

.rabbit {
  width: 50%;
  display: block;
  margin: 0 auto;
}
</style>