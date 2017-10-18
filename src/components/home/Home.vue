<template>

<div class="hero">
    <div class="curator-logo"></div>
    <div class="shaping-your-social">
        <p>Shaping your social empire through the power of Ai.</p>
    </div>
    <div class="bots-be-gone-curator">
        <p><span class="text-style-1">Bots be gone!</span> <span class="text-style-2">Curator uses Ai to engage with actual humans; delivering meaningful followers, likes, and insights.</span></p>
    </div>
    <contact></contact>
    <div class="social-icons">
        <a target="_blank" href="https://www.instagram.com/vestfinancial/?hl=en" class="social-link instagram"></a>
            <a target="_blank" href="https://www.facebook.com/askvest/" class="social-link facebook"></a>
        <a target="_blank" href="https://twitter.com/vestfinancial" class="social-link twitter"></a>
    </div>
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

<style  lang='scss'>
 @import '../../styles/_variables.scss';

.hero {
    text-align: center;
    margin-top: 10rem;
}

.social-link {
    display: inline-block;
    overflow: hidden;
    background-repeat: no-repeat;
    margin-top: 4.7rem;
    margin-right: 2rem;
    margin-left: 2rem;
    text-align: center;


}

.instagram {
    width: 21px;
    height: 21px;
    object-fit: contain;

 background-image: url('https://s3.us-east-2.amazonaws.com/follow-curator/instagram.svg');
}

.facebook{
    width: 21px;
    height: 21px;
    object-fit: contain;


    background-image: url('https://s3.us-east-2.amazonaws.com/follow-curator/facebook.svg');

}

.twitter {
    width: 21px;
    height: 21px;
    object-fit: contain;

 background-image: url('https://s3.us-east-2.amazonaws.com/follow-curator/twitter.svg');
}

.curator-logo {
    display: block;
    width: 31.7rem;
    height: 5.2rem;
    object-fit: contain;
    text-align: center;
    margin: auto;
    background-image: url('https://s3.us-east-2.amazonaws.com/follow-curator/curator-logo.svg');
}

.shaping-your-social {
    margin-top: 3rem;
    display: inline-block;
    width: 60rem;
    height: 9.2rem;
    font-family: Nunito;
    font-size: 4rem;
    font-weight: 200;
    line-height: 1.15;
    letter-spacing: .1rem;
    color: #ffffff;
}

.bots-be-gone-curator {
    margin-top: 3rem;
    margin-left: auto;
    margin-right:auto;
    width: 50rem;
    height: 4.8rem;
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


</style>
