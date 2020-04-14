<template>
<div>
    <div class="main">
        <div class="text-center">
            <h1 style="padding-top:3rem"> aremu</h1>
            <p class="p">Welcome to my online portfolio. Lorem ipsum dolor sit amet, consectetuer
                adipiscing elit. Aenean commodo ligula eget dolor. I'm tst some help building your software?</p>
            <button type="button" class="btn btn-primary mt-2">view blog</button>
        </div>
    </div>
    <div class="container mt-5">
        <form>
            <h1>Get in touch</h1>
            <div class="row">
                <div class="col-sm-6 mt-2 ">
                    <input type="text" class="form-control" placeholder="First name">
                </div>
                <div class="col-sm-6 mt-2 ">
                    <input type="text" class="form-control" placeholder="Last name">
                </div>
                <div class="col-sm-12 mt-4 mb-4">
                    <select class="custom-select" id="validationDefault04" required>
                        <option selected disabled value="">Choose...</option>
                        <option>osun</option>
                        <option>ogun</option>
                        <option>eko</option>
                        <option>ekiti</option>
                        <option>edo</option>
                    </select>
                </div>
            </div>
            <textarea class="form-control mt-4 mb-4" rows="10" placeholder="Required example textarea"></textarea>
            <button type="button" class="btn btn-primary btn-lg btn-block">Submit</button>
        </form>
    </div>
</div>
</template>

<style scoped>
form {
    width: 50%;
    margin: 0 auto;
}

h1 {
    text-align: center;
}

.main {
    height: 16rem;
    background-color: #fafafa !important;
}

p .p {
    width: 53%;
    text-align: center;
    margin: 0 auto;
}

@media screen and (max-width: 750px) {
    form {

        width: 90%;
        margin: 0 auto;
    }
}
</style>
