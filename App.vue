<script setup>
//import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'

import Bai3 from './components/Bai3.vue';
import Bai4 from './components/Bai4.vue';
</script>
<!-- <script>
 export default {
 data() {
  return {
   count: 0,
   user: {
    name: 'Nam',
    age: 25
   }
  };
 }
 };
</script>

<script>
 export default {
 data() {
  return {
   count: 0
  };
 },
 methods: {
  increment() {
   this.count++;// Dùng this để truy cập biến trong data
  },
  reset() {
   this.count = 0; //đặt lại count về 0
  }
 }
 };

</script> -->
<!-- 
<script>
export default {
data() {
return {
message: 'Xin chào VueJS',
number: 10
}
},
methods: {
sayHi() {
return 'Đây là một phương thức'
}
}
}
</script> -->

<!-- <script>
export default {
data() {
return {
content: 'xin chào các bạn',
className: 'text-red',
styleData: 'font-size: 5rem'
}
}
}
</script> -->

<!-- <script>
export default {
data() {
return {
number : 22
}
},
methods: {
sayHi : function () {
return 'vuejs.org'
}
}
}
</script> -->

/

<!-- <script>
export default {
data() {
return {
message: 'qua lại khách chờ sông lặn sóng',
}
},
methods: {
showInfo: function(){
this.message = this.message.split(' ').reverse().join(' ');
}
}
}
</script> -->

<!-- <script>
export default {
data() {
return {
name: 'Vue',
url: 'https://www.google.com/',
}
}
}
</script> -->

<template>
  <!-- code này từ phần icons viết sang đây -->
<!-- <HelloWorld></HelloWorld> -->
  
<!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main> -->

<!-- <div>
  <h1>Hiển thị nội dung</h1>
<h2>{{ message }}</h2>
<h2>{{ number + 5 }}</h2>
<h2>{{ sayHi() }}</h2>
</div> -->

<!-- 
<div>
  <h2 v-bind:class="className" v-bind:style="styleData" v-html="content"></h2>
</div>

<p>Phương thức sayHi trả về: {{ sayHi() }}</p>
<p>Số này là số {{ number%2==0 ? 'Chẵn' : 'Lẻ' }}</p> -->

<!-- <p>Click vào button để xem kết quả</p>
<button class="btn btn-info" v-on:click="showInfo">
Click
 </button> -->

 <!-- <div class="container">
<button class="btn btn-danger">Danger</button>
<button class="btn btn-warning">Warning</button>
<button class="btn btn-success">Success</button>
<button class="btn btn-info">Info</button>
<button class="btn btn-primary">Primary</button>
</div> -->

<!-- 
<p>{{ message }}</p>
<button class="btn btn-info" @click="showInfo">
Click</button> -->
<!-- 
<p>
Name: <input type="text" :value="name"> -->
<!-- Name: <input type="text" v-bind:value="name"> -->
<!-- </p>
<a class = 'btn btn-primary' :href="url">click me</a> -->

<Bai3/> 
<Bai4/>
</template>
  
<style scoped>
/* header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
} */

.text-red{color: red;}
</style>
