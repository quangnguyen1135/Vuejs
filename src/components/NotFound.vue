<template>
    <div>
        <section class="page_404">
            <div class="container">
                <div class="row">
                    <div class="col-sm-12">
                        <div class="col-sm-12 col-sm-offset-1 text-center">
                            <div class="four_zero_four_bg">
                                <h1 class="text-center">404</h1>
                            </div>

                            <div class="contant_box_404">
                                <h3 class="h2">
                                    Look like you're lost
                                </h3>
                                <p>The page you are looking for is not available!</p>
                                <a href="/" class="link_404">Go to Home</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: 'NotFoundComponent',
}
</script>

<style scoped>
.page_404 {
    padding: 40px 0;
    background: #fff;
    font-family: 'Arvo', serif;
}

.four_zero_four_bg {
    background-image: url(../Content/img/gif-erorr/dribbble_1.gif);
    height: 400px;
    background-position: center;
    background-repeat: no-repeat;
}

.four_zero_four_bg h1 {
    font-size: 80px;
}

.link_404 {
    color: #fff !important;
    padding: 10px 20px;
    background: #39ac31;
    margin: 20px 0;
    display: inline-block;
    border-radius: 8px;
}

.contant_box_404 {
    margin-top: -50px;
}
</style>
