<template>
<div>
    <div class="main">
        <div class="text-center">
            <h1 style="padding-top:3rem"> aremu</h1>
            <p class="p">Welcome to my online portfolio. Lorem ipsum dolor sit amet, consectetuer
                adipiscing elit. Aenean commodo ligula eget dolor. I'm tst some help building your software?</p>
            <button type="button" class="btn btn-primary mt-5 mb-5">view blog</button>
        </div>
    </div>
    <div class="container">

        <form>
            <h1>Get in touch</h1>
            <div class="row">

                <div class="col-sm-6">
                    <input type="text" class="form-control" placeholder="First name">
                </div>
                <div class="col-sm-6 ">
                    <input type="text" class="form-control" placeholder="Last name">
                </div>

                <div class="col-sm-12 mt-4 mb-4">
                    <select class="custom-select" id="validationDefault04" required>
                        <option selected disabled value="">Choose...</option>
                        <option>ifon</option>
                        <option>ifon</option>
                        <option>ifon</option>
                        <option>ifon</option>
                        <option>ifon</option>
                    </select>

                </div>
            </div>
            <small class="mt-5">hhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhh</small>
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
</style>
