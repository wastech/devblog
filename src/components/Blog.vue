<template>
<div>
    <div class="main">
        <div class="text-center">
            <h1 style="padding-top:3rem"> aremu</h1>
            <p class="p">Welcome to my online portfolio. Lorem ipsum dolor sit amet, consectetuer
                adipiscing elit. Aenean commodo ligula eget dolor. I'm tst some help building your software?</p>
            <input type="email" id="exampleInputEmail1" aria-describedby="emailHelp">
        </div>
    </div>
    <div class="container mt-2">
        <div class="row">
            <div class="col-sm-4" v-for="item in items" :key="item">
                <div class="card mt-5" style="width: 100%;">
                    <img :src="item.src" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">{{item.title}}</h5>
                        <p class="card-text">{{item.text}}</p>
                        <a href="#" class="btn btn-primary">Go somewhere</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <button type="button" class="btn btn-primary btn-lg btn-block mt-5 mb-5">Block level button</button>
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
                }

            ]
        }
    }
}
</script>

<style scoped>
.main {
    height: 16rem;
    background-color: #fafafa !important;
}
</style><style scoped>
p .p {
    width: 50%;
    text-align: center;
    margin: 0 auto;
}
</style>
