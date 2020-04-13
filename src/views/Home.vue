<template>
  <div class="home">
    
    <SideNave />
    <whatido />
    <experience />
	<FeatureProject/>>
  </div>
</template>

<script>
// @ is an alias to /src

import SideNave from "@/components/SideNave";
import whatido from "@/components/whatido";
import experience from "@/components/experience";
import FeatureProject from '@/components/FeatureProject'

export default {
  name: "Home",
  components: {
    SideNave,
    whatido,
	experience,
	FeatureProject
  }
};
</script>
