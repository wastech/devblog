<template>
<div class="home">
    <SideNave />
    <whatido />
    <experience />
    <Testimonial />
    <FeatureProject />
    <LatestBlog />
</div>
</template>

<script>
// @ is an alias to /src
import LatestBlog from "@/components/LatestBlog";
import SideNave from "@/components/SideNave";
import whatido from "@/components/whatido";
import experience from "@/components/experience";
import Testimonial from "@/components/Testimonial.vue";
import FeatureProject from "@/components/FeatureProject";

export default {
    name: "Home",
    components: {
        SideNave,
        whatido,
        experience,
        Testimonial,
        FeatureProject,
        LatestBlog
    }
};
</script>

<style scoped></style>
