<template>
<div id="app">
    <div class="row">
        <div class="col-sm-2">
            <HelloWorld />
        </div>
		 <div class="col-sm-10">
           <router-view />
        </div>
       

    </div>


</div>
</template>
<script>
import HelloWorld from "@/components/HelloWorld.vue";
export default {
	 components: {
    HelloWorld,
    
  }
	
}
</script>

<style scoped>
#app {
    margin: 0px;
}
</style>
