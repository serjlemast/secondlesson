<template>
  <div class="root">
    <h1>{{ t1 }}</h1>
  </div>
</template>
<script>
export default {
  name: "MyComponent",
  data() {
    return {
      usersName: [
        { name: "misha" },
        { name: "kesha" },
        { name: "nasky" },
        { name: "nasty" },
      ],
      t1: "Поиск имен",
      searchName: "",
      i: 0,
      nothing: "совпадение!!!",
    };
  },
};
</script>