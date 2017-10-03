<style scoped>

.header-logo {
	width: 35px;

	height: 33px;
	object-fit: contain;
	background-color: #ffffff;
	background-image: url('https://s3.us-east-2.amazonaws.com/social-curator/curator-logo.svg');

}

</style>

<template>
	<div class="header-logo"></div>

</template>

<script>

export default {
    name: 'siteHeader',
    data() {
        return {
            email: ""


        }
    }
}

</script>
