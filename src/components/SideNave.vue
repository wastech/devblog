<template>
<div class="main">
    <div class="container">
        <div class="row">
            <div class="col-sm-8">
                <div class="bio">
                    <h1>Aremu Wasiu</h1>
                    <h3>Senior Software Engineer</h3>
                    <p>
                        I am a software engineer specialised in frontend and backend
                        development for complex scalable web apps. I write about software
                        development on
                        <span style="color: #54b689;">my blog</span>. Want to know how I
                        may help your project? Check out my project
                        <span style="color: #54b689;">portfolio</span> and
                        <span style="color: #54b689;">online resume.</span>
                    </p>
                    <button class="btn1">
                        <i class="fa fa-home"></i> view portfolio
                    </button>
                    <button class="btn"><i class="fa fa-bars"></i> view resume</button>
                </div>
            </div>
            <div class="col-sm-4">
                <div class="image">
                    <div class="image">
                        <img src="@/assets/ne.jpg" />
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<style scoped>
.main {
    background-color: #fafafa;
    margin-left: 0;
}

div.bio {
    width: 100%;
    margin-top: 2em;
}

img {
    width: 100%;
    height: 15em;
    margin-top: 2em;
    object-fit: cover;
}

.btn1 {
    background-color: #54b689;
    /* Blue background */
    border: none;
    /* Remove borders */
    color: white;
    /* White text */
    padding: 12px 16px;
    /* Some padding */
    font-size: 16px;
    /* Set a font size */
    cursor: pointer;
    /* Mouse pointer on hover */
    margin: 1em;
    border-radius: 0.5em;
}

.btn {
    background-color: black;
    /* Blue background */
    border: none;
    /* Remove borders */
    color: white;
    /* White text */
    padding: 12px 16px;
    /* Some padding */
    font-size: 16px;
    /* Set a font size */
    cursor: pointer;
    /* Mouse pointer on hover */
    margin: 1em;
    border-radius: 0.5em;
}
</style>
