<template>
    <div class="footer-cont">
	<div class="small-logo"></div>
    <div class="footer-text-cont">
        <p class="footer-text"> Terms & Conditions</p>
        <p class="footer-text"> Privacy Policy</p>
        <p class="footer-text">@ copyright 2017 Curator</p>
    </div>
</div>
</template>

<script>

export default {
    name: 'sitefooter',
    data() {
        return {
           
        }
    }
}

</script>

<style lang="scss">
.footer-text-cont {
    float: right;
    margin-top: 2.5rem;
    width: 455px;
    height: 20px;
    font-family: 'Open Sans', sans-serif;
    font-size: 14px;
    font-weight: 300;
    line-height: 1.43;
    letter-spacing: 0.2px;
    text-align: center;
    // margin-bottom: 3rem;
    color: #ffffff;
    .footer-text {
        margin-right: 1.5rem;
        display: inline-block;

    }


}

</style>