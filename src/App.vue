<template>
  <div>
  <!--แสดงหน้าเมนูล-->
<Navbar />

<!--แสดงหน้าเพจ-->
  <router-view/>
  </div>

</template>

<script>
import Navbar from "./components/Navbar.vue";


export default {
  name: "App",
  components: { Navbar }
};
</script>