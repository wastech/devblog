<template>
<div class="container " style="margin-top:4rem;">
    <div class="title">
        <h2>Featured Projects</h2>
    </div>
    <div class="row">
        <div class="col-sm-6 mt-3 " v-for="item in items" :key="item.id">
            <div class="card mb-3" style="max-width: 540px;">
                <div class="row no-gutters">
                    <div class="col-md-4">
                        <img :src="item.src" class="card-img" alt="..." style="height:100%">
                    </div>
                    <div class="col-md-8">
                        <div class="card-body">
                            <h5 class="card-text"> {{item.title}}</h5>
                            <p class="card-text">{{item.text}}</p>
                            <p class="card-text"><small class="text-muted">{{item.updatedtime}}</small></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <button type="button" class="btn btn-success mt-3 text-center" style="margin:0 auto;">View Portfolio</button>
    </div>
</div>
</template>

<script>
export default {
    data() {
        return {
            items: [{
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.',
                    updatedtime: 'Last updated 3 mins ago'
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.',
                    updatedtime: 'Last updated 3 mins ago'
                }, {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.',
                    updatedtime: 'Last updated 3 mins ago'
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: 'This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.',
                    updatedtime: 'Last updated 3 mins ago'
                }
            ]
        }
    }
}
</script>

<style scoped>
.title h2 {
    border-left: 8px solid #54b689;
    padding: 0.3em;
}
</style>
