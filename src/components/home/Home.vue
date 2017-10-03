<template>

<div class="hero">
    <div class="wrapper"></div>
    <div class="curator-logo"></div>
    <div class="shaping-your-social">
        <p>Shaping your social empire through the power of Ai.</p>
    </div>
    <div class="bots-be-gone-curator">
        <p><span class="text-style-1">Bots be gone!</span> <span class="text-style-2">Curator uses Ai to engage with actual humans; delivering meaningful followers, likes, and insights.</span></p>
    </div>
    <contact></contact>
   <!--  <div>
        <div class="leftwave">
            <img src="https://s3.us-east-2.amazonaws.com/social-curator/leftwave.svg" class="leftwave">
        </div>
        <div class="rightwave">
            <img src="https://s3.us-east-2.amazonaws.com/social-curator/rightwave.svg" class="rightwave">
        </div>
    </div> -->

</div>

</template>

<script>

import contact from '../contact/contact';
import siteHeader from '../SiteHeader';
export default {
    name: 'home',
    components: {
        contact,
        siteHeader,
    },
    data() {
        return {}
    }
}

</script>

<style scoped>

.hero {
    background-color: #4c31b5;
    height: 100%;
    width: 100%;
    text-align: center;
}

.wrapper {
    height: 200px;
}

.curator-logo {
    display: block;
    width: 317px;
    height: 52px;
    object-fit: contain;
    text-align: center;
    margin: auto;
    background-image: url('https://s3.us-east-2.amazonaws.com/social-curator/curator-logo.svg');
}

.shaping-your-social {

    display: inline-block;
    width: 600px;
    height: 92px;
    font-family: Nunito;
    font-size: 40px;
    font-weight: 200;
    line-height: 1.15;
    letter-spacing: 1px;
    color: #ffffff;
}

.bots-be-gone-curator {
  margin-top: 29px;
    margin-left: auto;
    margin-right:auto;
    width: 500px;
    height: 48px;
    font-family: 'Open Sans', sans-serif;
    font-size: 16px;
    font-weight: 300;
    line-height: 1.5;
    letter-spacing: 0.2px;
    text-align: center;
    color: #ffffff;
}

.text-style-1 {
    font-weight: 600;
}

.text-style-2 {
    letter-spacing: normal;
    font-weight: 200;

}

.leftwave {
    width: 1440px;
    /*display: inline;*/
    height: 701.2px;
    object-fit: contain;
    background-image: linear-gradient(114deg, #835fdc, #4c31b5);
}

.rightwave {
    /*display: inline-block;*/
    width: 1440px;
    height: 558.4px;
    object-fit: contain;
    background-image: linear-gradient(110deg, #835fdc, #4c31b5);
    box-shadow: 0 0 120px 0 rgba(0, 0, 0, 0.1);
}

</style>
