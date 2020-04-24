<template>
<div class="container">
    <div class="main">
        <div class="row">
            <div class="col-sm-6 col-12 col-md-6 col-lg-4" v-for="(icon, i) in icons" v-bind:key="i">
                <a :class="icon.icon" href="#home"></a>&nbsp; &nbsp;&nbsp;
                <a :class="icon.icon1" href="#home"></a>&nbsp;&nbsp;&nbsp;
                <a :class="icon.icon2" href="#home"></a>
                <h3>
                    <a>{{ icon.title }}</a>
                </h3>
                <p>
                    <a>{{ icon.text }}</a>
                </p>
            </div>
        </div>
        <button type="button" class="btn btn-success mt-5 mb-5">
            Services & pricing
        </button>
    </div>
</div>
</template>

<script>
export default {
    data() {
        return {
            icons: [{
                    icon: "fab fa-js fa-2x",
                    title: "Vanilla JavaScript",
                    text: "List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.aremu",
                },
                {
                    icon: "fab fa-vuejs fa-2x  ",
                    icon1: "fab fa-angular fa-2x  ",
                    icon2: "fab fa-react fa-2x  ",
                    title: "Angular, React & Vue",
                    text: "List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.",
                },
                {
                    icon: "fab fa-node-js fa-2x",
                    title: "Node.js",
                    text: "List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.",
                },
                {
                    icon: "fab fa-python fa-2x",
                    title: "Python & Django",
                    text: "List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.",
                },
                {
                    icon: "fab fa-php fa-2x",
                    title: "PHP",
                    text: "List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.",
                },
                {
                    icon: "fab fa-npm fa-2x",
                    icon1: "fab fa-gulp fa-2x",
                    icon2: "fab fa-grunt fa-2x",
                    title: "npm, Gulp & Grunt",
                    text: "List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.",
                },
                {
                    icon: "fab fa-html5 fa-2x",
                    icon1: "fab fa-css3-alt fa-2x",
                    title: "HTML & CSS",
                    text: "List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.",
                },
                {
                    icon: "fab fa-sass fa-2x",
                    icon1: "fab fa-less fa-2x",
                    title: "Sass & LESS",
                    text: "List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.",
                },
            ],
        };
    },
};
</script>

<style scoped>
.fa-less {
    color: darkblue;
}

.fa-sass {
    color: palevioletred;
}

.fa-css3 {
    background-color: white;
    color: blue;
}

.fa-html5 {
    background-color: white;
    color: orange;
}

.fa-grunt {
    background-color: yellow;
    color: white;
}

.fa-gulp {
    background-color: white;
    color: red;
}

.fa-npm {
    background-color: white;
    color: red;
}

.fa-vuejs {
    background-color: white;
    color: green;
}

.fa-js {
    background-color: white;
    color: yellow;
}

.fa-angular {
    background-color: white;
    color: red;
}

.fa-node-js {
    background-color: white;
    color: green;
}

.main {
    margin-top: 3em;
}

ul {
    list-style-type: none;
    display: grid;
    grid-column-gap: 50px;
    grid-template-columns: auto auto auto auto;
}

li {
    margin-bottom: 2em;
}

li a {
    color: black;
    /* margin-bottom: 1em; */
    text-decoration: none;
}

button {
    margin: 0 auto;
}
</style>
