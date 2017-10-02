<style>

.contact {
    margin-top: 20px;
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
.email-button-wrapper {
  margin-top: 21px;
}

.reserve-button-wrapper {
  margin-top: 21px;
}
.email-button {
  border-style: none;
    width: 350px;
    height: 45px;
    border-radius: 2px;
    background-color: #ffffff;
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
</style>

<template>

<div class="contact-wrapper">
    <div class="contact">
        <p>Sign up to reserve your spot on the waitlist!</p>
    </div>
    <div class="email-button-wrapper">
        <button class="email-button">Enter your email</button>
    </div>
    <div class="reserve-button-wrapper">
        <button class="reserve-button">Reserve My Spot</button>
    </div>
</div>

</template>

<script>

export default {
    name: 'contact',
    data() {
        return {

        }
    }
}

</script>
