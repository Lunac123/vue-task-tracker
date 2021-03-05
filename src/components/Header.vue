<template>
  <header>
    <h1>{{ title }}</h1>
    <Button text="Add task" color="green" />
  </header>
</template>

<script>
import Button from './Button';
export default {
  components: {
    Button,
  },
  name: 'Header',
  //props: ['title', 'span'],
  props: {
    title: String,
  },
};
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
