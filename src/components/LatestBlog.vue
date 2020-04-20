<template>
  <div class="container">
    <div class="title">
      <h2>Latest Blog Posts</h2>
    </div>
    <div class="row">
      <div class="col-sm-4" v-for="(item, index) in items" :key="index">
        <div class="card mb-3">
          <img :src="item.src" class="card-img-top" alt="..." />
          <div class="card-body">
            <h5 class="card-title">{{ item.title }}</h5>
            <p class="card-text">{{ item.text }}</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
      <button type="button" class="btn btn-success mt-3 text-center">
        View Blog
      </button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          src:
            "https://cdn.dribbble.com/users/604891/screenshots/6177907/mishax-work.png",
          title: "page heading",
          text:
            "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
          updatedtime: "Last updated 3 mins ago",
        },
        {
          src:
            "https://cdn.dribbble.com/users/499731/screenshots/6679284/floating.png",
          title: "page heading",
          text:
            "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
          updatedtime: "Last updated 3 mins ago",
        },
        {
          src:
            "https://cdn.dribbble.com/users/3632054/screenshots/6918680/whatsapp_image_2019-08-05_at_12.01.55_am.jpeg",
          title: "page heading",
          text:
            "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
          updatedtime: "Last updated 3 mins ago",
        },
      ],
    };
  },
};
</script>

<style scoped>
.container {
  margin-top: 3rem;
}

button {
  margin: 0 auto;
}

.title h2 {
  border-left: 8px solid #54b689;
  padding: 0.3em;
  margin-bottom: 2rem;
}

img {
  height: 100%;
  object-fit: cover;
}
</style>
