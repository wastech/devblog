<template>
  <div class="home">
    <HelloWorld/>
	<SideNave/>
	<whatido/>
	<experience/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import SideNave from '@/components/SideNave'
import whatido from '@/components/whatido'
import experience from '@/components/experience'
export default {
  name: 'Home',
  components: {
	HelloWorld,
	SideNave,
	whatido,
	experience
  }
}
</script>
