<template>
<<<<<<< HEAD
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
=======
    <div class="root">
 <h1>{{ t1 }}</h1>

    </div>
</template>
<script>
export default {
    name:'MyComponent',
    data(){
        return{
usersName:[
 {name:'misha'},
 {name:'kesha'},
 {name:'nasky'},
 {name:'nasty'}
],
t1:'Поиск имен', 
searchName:'',
i:0,
nothing:"совпадение!!!"
        }  
    }
     
}
>>>>>>> 363c94af6d338a088808b53166a0e07eb810b578
</script>