<template>
  <div>
    <div class="main">
      <section class="cta-section theme-bg-light py-5">
        <div class="container text-center">
          <h2 class="heading">A Blog About Software Development And Life</h2>
          <div
            class="intro"
          >Welcome to my blog. Subscribe and get my latest blog post in your inbox.</div>
          <form class="signup-form form-inline justify-content-center pt-3">
            <div class="form-group">
              <label class="sr-only" for="semail">Your email</label>
              <input
                type="email"
                id="semail"
                name="semail1"
                class="form-control mr-md-1 semail"
                placeholder="Enter email"
              />
            </div>
            <button type="submit" class="btn btn-primary">Subscribe</button>
          </form>
        </div>
      </section>
    </div>
    <div class="container mt-2">
      <div class="row">
        <div class="col-sm-4" v-for="item in items" :key="item">
          <div class="card mt-5" style="width: 100%;">
            <img :src="item.src" class="card-img-top" alt="..." />
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
      items: [
        {
          src:
            "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
          title: "page heading",
          text:
            "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
          updatedtime: "Last updated 3 mins ago"
        },
        {
          src:
            "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
          title: "page heading",
          text:
            "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
          updatedtime: "Last updated 3 mins ago"
        },
        {
          src:
            "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
          title: "page heading",
          text:
            "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
          updatedtime: "Last updated 3 mins ago"
        },
        {
          src:
            "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
          title: "page heading",
          text:
            "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
          updatedtime: "Last updated 3 mins ago"
        },
        {
          src:
            "https://cdn.dribbble.com/users/604891/screenshots/6177907/mishax-work_4x.png?compress=1&resize=800x600",
          title: "page heading",
          text:
            "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
          updatedtime: "Last updated 3 mins ago"
        },
        {
          src:
            "https://cdn.dribbble.com/users/1171505/screenshots/11018981/media/296e5c43b1fe9fe3ed5f78251e94cd3d.png",
          title: "page heading",
          text:
            "This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.",
          updatedtime: "Last updated 3 mins ago"
        }
      ]
    };
  }
};
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
img {
  object-fit: cover;
}
</style>
