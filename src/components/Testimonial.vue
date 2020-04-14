<template>
<div class="container" style="margin-top:2rem">
    <div class="title">
        <h2>Testimonials</h2>
    </div>
    <div class="row">
        <div class="col-sm-4" v-for="item in items" :key="item">
            <div class="card p-3 mt-3">
                <blockquote class="blockquote mb-0 card-body">
                    <p>{{item.text}}</p>
                    <footer class="blockquote-footer">
                        <li class="media">
                            <img :src="item.src" class="mr-3" alt="..." style="border-radius: 50% ;height:5em; width:34%;">
                            <div class="media-body">
                                {{item.name}}<br>
                                {{item.position}}.
                            </div>
                        </li>
                    </footer>
                </blockquote>
            </div>
        </div>
        <button type="button" class="btn btn-success mt-3 text-center" style="margin:0 auto;">Testimonials</button>
    </div>
</div>
</template>

<script>
export default {
    data() {
        return {
            items: [{
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    name: "heading",
                    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.',
                    position: 'Last updated 3 mins'
                },
                {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    name: "name heading",
                    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.',
                    position: 'Last updated 3 mins'
                }, {
                    src: "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
                    name: "page heading",
                    text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.',
                    position: 'Last updated 3 mi'
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
    margin-bottom: 2rem;
}
</style>
