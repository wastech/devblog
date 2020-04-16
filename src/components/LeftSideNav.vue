<template>
  <div class="hello">
    <nav class="navbar navbar-expand-lg navbar-dark">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse flex-column" id="navbarSupportedContent">
        <h1 class="head pt-lg-4 mb-0">Wastech</h1>
        <div class="image">
          <img src="@/assets/ne.jpg" />
        </div>
        <div class="text">
          <p>
            Hi, my name is Aremu, and I'm a senior software engineer. Welcome to
            my personal website!
          </p>
        </div>
        <div class="icon1">
          <div class="icon" v-for="(item, i) in items" v-bind:key="i">
            <i :class="item.icon"></i>
          </div>
        </div>
        <div class="work mt-5">
          <ul v-for="(icon, i) in icons" v-bind:key="i">
            <li>
              <a :class="icon.icon" :href="icon.link">&nbsp; &nbsp; {{ icon.title }}</a>
            </li>
          </ul>
        </div>
        <div style="text-align:center;">
          <button class="btn">
            <i class="fa fa-home"></i> hire me
          </button>
        </div>
        <div class="dark" style="text-align : center;width:80%; margin-top:2rem; color:white;">
          <span>
            <i class="fas fa-toggle-on"></i> dark mode
          </span>
        </div>
        <div style="text-align:center; margin-top:1rem; margin-bottom:4rem; width:80%;">
          <label class="switch">
            <input type="checkbox" checked />
            <span class="slider round"></span>
          </label>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  data() {
    return {
      items: [
        {
          icon: "fab fa-twitter "
        },
        {
          icon: "fab fa-linkedin-in "
        },
        {
          icon: "fab fa-github-alt "
        },
        {
          icon: "fab fa-stack-overflow "
        },
        {
          icon: "fab fa-codepen "
        }
      ],
      icons: [
        {
          icon: "fas fa-user-shield",
          title: "About me",
          link: "/"
        },
        {
          icon: "fas fa-laptop",
          title: "portfolio",
          link: "portfolio"
        },
        {
          icon: "fas fa-shopping-bag",
          title: "services & princing",
          link: "/service"
        },
        {
          icon: "fas fa-file",
          title: "resume"
        },
        {
          icon: "fas fa-file",
          title: "blog",
          link: "/blog"
        },
        {
          icon: "fas fa-id-card-alt ",
          title: "contact",
          link: "/contact"
        }
      ]
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
.fa-twitter,
.fa-linkedin-in,
.fa-github-alt,
.fa-stack-overflow,
.fa-codepen {
  color: white;
}

.hello .navbar {
  padding-top: 1.5rem;
  padding-left: 0rem;
}

.hello {
  background-color: #54b689;
  width: 100%;
  border-right: 7px solid teal;
  height: 100%;
}

h1.head {
  color: white;
  text-align: center;
}

.image {
  margin: 0 auto;
  text-align: center;
}

img {
  max-width: 70%;
  border-radius: 50%;
  height: 170px;
  object-fit: cover;
}

.text {
  text-align: center;
  width: 100%;
  margin: 0 auto;
  color: white;
  font-size: 1rem;
}

.icon1 {
  display: flex;
  justify-content: space-around;
  width: 100%;
  margin: 0 auto;
}

li a {
  display: block;
  color: white;
  padding: 8px 16px;

  text-decoration: none;
}

ul {
  list-style-type: none;

  max-width: 100%;
}

.btn {
  font-weight: bold;
  height: 2.5rem;
  background-color: rgba(0, 0, 0, 0.3);
  border: none;
  color: white;
  padding: 12px 16px;
  font-size: 16px;
  cursor: pointer;
}

.switch {
  position: relative;
  display: inline-block;
  width: 60px;
  height: 34px;
  text-align: center;
}

.switch input {
  opacity: 0;
  width: 0;
  height: 0;
}

.slider {
  position: absolute;
  cursor: pointer;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #ccc;
  -webkit-transition: 0.4s;
  transition: 0.4s;
}

.slider:before {
  position: absolute;
  content: "";
  height: 26px;
  width: 26px;
  left: 4px;
  bottom: 4px;
  background-color: white;
  -webkit-transition: 0.4s;
  transition: 0.4s;
}

input:checked + .slider {
  background-color: #2196f3;
}

input:focus + .slider {
  box-shadow: 0 0 1px #2196f3;
}

input:checked + .slider:before {
  -webkit-transform: translateX(26px);
  -ms-transform: translateX(26px);
  transform: translateX(26px);
}

/* Rounded sliders */
.slider.round {
  border-radius: 34px;
}

.slider.round:before {
  border-radius: 50%;
}
</style>
