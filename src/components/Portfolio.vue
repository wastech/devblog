<template>
<div>
    <div class="main">
        <div class="text-center">
            <h1>aremu</h1>
            <p>
                Welcome to my online portfolio. Lorem ipsum dolor sit amet,
                consectetuer adipiscing elit. Aenean commodo ligula eget dolor. I'm
                tst some help building your software?
            </p>
            <button type="button" class="btn btn-success mt-5 mb-5">
                hire me
            </button>
        </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-sm-6 mt-3" v-for="item in items" :key="item.id">
                <div class="card mb-3">
                    <div class="row no-gutters">
                        <div class="col-md-4">
                            <img :src="item.src" class="card-img" alt="..." />
                        </div>
                        <div class="col-md-8">
                            <div class="card-body">
                                <h5 class="card-text">{{ item.title }}</h5>
                                <p class="card-text">{{ item.text }}</p>
                                <p class="card-text">
                                    <small class="text-muted">{{ item.updatedtime }}</small>
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
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
                    text: "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
                    updatedtime: "Last updated 3 mins ago",
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
                    updatedtime: "Last updated 3 mins ago",
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
                    updatedtime: "Last updated 3 mins ago",
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
                    updatedtime: "Last updated 3 mins ago",
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
                    updatedtime: "Last updated 3 mins ago",
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
                    updatedtime: "Last updated 3 mins ago",
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
                    updatedtime: "Last updated 3 mins ago",
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    title: "page heading",
                    text: "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
                    updatedtime: "Last updated 3 mins ago",
                },
            ],
        };
    },
};
</script>

<style scoped>
.main {
    height: 16rem;
    background-color: #fafafa !important;
}

p.p {
    width: 70%;
    text-align: center;
    margin: 0 auto;
}

img {
    object-fit: cover;
    height: 100%;
}

.container {
    margin-top: 3rem;
}
</style>
