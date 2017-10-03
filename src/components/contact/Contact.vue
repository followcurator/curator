<style scoped>

.contact {
    margin-top: 50px;
    display: inline-block;
    width: 285px;
    height: 19px;
    font-family: Nunito;
    font-size: 14px;
    font-weight: 600;
    letter-spacing: 0.2px;
    text-align: center;
    color: #ffffff;
}


.reserve-button-wrapper {
    margin-top: 21px;
}

.email-input-wrapper {
    margin-top: 20px;
}
.email {
    width: 328px;
    height: 45px;
    border: none;
    border-radius: 2px;
    background-color: #ffffff;
    font-family: Nunito;
    font-size: 16px;
    font-weight: 300;
    letter-spacing: 0.2px;
    text-align: left;
    color: #000000;
    padding-left: 22px;
    box-shadow: 0 10px 15px 0 rgba(31, 32, 34, 0.3), 0 0 5px 0 rgba(31, 32, 34, 0.15);
}


.reserve-button {
    border-style: none;
    width: 350px;
    height: 55px;
    border-radius: 8px;
    background-image: linear-gradient(to bottom, #1dba74, #1a4f8d);
    box-shadow: 0 20px 25px 0 rgba(39, 20, 112, 0.5), 0 0 5px 0 rgba(31, 32, 34, 0.15);
}

.reserve-my-spot {
    height: 22px;
    font-family: Nunito;
    font-size: 16px;
    font-weight: 800;
    letter-spacing: 0.5px;
    text-align: center;
    color: #ffffff;
}

.enter-your-email {
    width: 118px;
    height: 22px;
    font-family: Nunito;
    font-size: 16px;
    font-weight: 300;
    letter-spacing: 0.2px;
    text-align: left;
    color: #000000;
}

.enter-your-email .text-style-1 {
    letter-spacing: normal;
}

</style>

<template>
<div class="contact-wrapper">
    <div class="contact">
        <p>Sign up to reserve your spot on the waitlist!</p>
    </div>
    <div class="email-input-wrapper">
        <input type="text" class="email" v-model="email" name="email" placeholder="Enter your email">
    </div>
    <div class="reserve-button-wrapper">
        <button class="reserve-button">
            <div class="reserve-my-spot">
                Reserve My Spot
            </div>
        </button>
    </div>
</div>
</template>

<script>

export default {
    name: 'contact',
    data() {
        return {
            email: ""


        }
    }
}

</script>
