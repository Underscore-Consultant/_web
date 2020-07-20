<template>
    <div class="contain">
        <nav class="navbar navbar-expand-lg navbar-light bg-transparent">
            <a class="navbar-brand" href="#">
                <img src="../assets/svg/logo.svg"/>
            </a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ml-auto">
                    <a class="nav-item nav-link active" href="#">Expertise</a>
                    <a class="nav-item nav-link" href="#">Services</a>
                    <a class="nav-item nav-link" href="#">Estimator</a>
                    <a class="nav-item nav-link" href="#">About</a>
                    <a class="nav-item nav-link" href="#">Contact Us</a>
                </div>
            </div>
        </nav>

        <section class="container">
            <div class="row">
                <div class="col"></div>
                <div class="col-4">
                    <h1 class="bebas text-left">
                        SOFTWARE<br/> 
                        DEVELOPMENT<br/> 
                        OUTSOURCING
                    </h1>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name:'FirstSection'
}
</script>

<style scoped>

.contain{
    background-color: #ffffff;
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='200' height='200' viewBox='0 0 200 200'%3E%3Cdefs%3E%3ClinearGradient id='a' gradientUnits='userSpaceOnUse' x1='88' y1='88' x2='0' y2='0'%3E%3Cstop offset='0' stop-color='%23003989'/%3E%3Cstop offset='1' stop-color='%23005bda'/%3E%3C/linearGradient%3E%3ClinearGradient id='b' gradientUnits='userSpaceOnUse' x1='75' y1='76' x2='168' y2='160'%3E%3Cstop offset='0' stop-color='%238f8f8f'/%3E%3Cstop offset='0.09' stop-color='%23b3b3b3'/%3E%3Cstop offset='0.18' stop-color='%23c9c9c9'/%3E%3Cstop offset='0.31' stop-color='%23dbdbdb'/%3E%3Cstop offset='0.44' stop-color='%23e8e8e8'/%3E%3Cstop offset='0.59' stop-color='%23f2f2f2'/%3E%3Cstop offset='0.75' stop-color='%23fafafa'/%3E%3Cstop offset='1' stop-color='%23FFFFFF'/%3E%3C/linearGradient%3E%3Cfilter id='c' x='0' y='0' width='200%25' height='200%25'%3E%3CfeGaussianBlur in='SourceGraphic' stdDeviation='12' /%3E%3C/filter%3E%3C/defs%3E%3Cpolygon fill='url(%23a)' points='0 174 0 0 174 0'/%3E%3Cpath fill='%23000' fill-opacity='.5' filter='url(%23c)' d='M121.8 174C59.2 153.1 0 174 0 174s63.5-73.8 87-94c24.4-20.9 87-80 87-80S107.9 104.4 121.8 174z'/%3E%3Cpath fill='url(%23b)' d='M142.7 142.7C59.2 142.7 0 174 0 174s42-66.3 74.9-99.3S174 0 174 0S142.7 62.6 142.7 142.7z'/%3E%3C/svg%3E");
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-position: top left;
    height: 100vh;
}
h1 {
    height: auto;
    margin-top: 45%;
    font-size: 96px;
    font-style: normal;
    font-stretch: normal;
    line-height: 1;
    letter-spacing: 1.3px;
    color: #000000;
}
.rel{
    position: relative;
}
</style>