<template>
  <div id="app">
<<<<<<< HEAD
    <my-component />
=======
<my-component />
>>>>>>> 363c94af6d338a088808b53166a0e07eb810b578
  </div>
</template>

<script>
// import MyComponent from './components/MyComponent'
<<<<<<< HEAD
import MyComponent from "./components/MyComponent.vue";
=======
import MyComponent from './components/MyComponent.vue'
>>>>>>> 363c94af6d338a088808b53166a0e07eb810b578
export default {
  name: "App",
  components: {
<<<<<<< HEAD
    MyComponent,
  },
};
=======
    MyComponent
    
  }
}
>>>>>>> 363c94af6d338a088808b53166a0e07eb810b578
</script>
export default {
    name:'MyComponent',
    data(){
        return{
            productValue:0,
            text:'Выбирите кол-во продуктов'
        }
    }
    
     
}