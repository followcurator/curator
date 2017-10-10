<template>
<div class="contact-wrapper">
    <div class="contact">
        <p>Sign up to reserve your spot on the waitlist!</p>
    </div>
    <div class="email-input-wrapper">
        <input type="text" class="email-input" v-model="email" name="email" placeholder="">
        <label class="input-label">Enter your email</label>
    </div>
        <button class="reserve-button">
            <div class="reserve-my-spot">
                Reserve My Spot
            </div>
        </button>
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

<style lang="scss">

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


.email-input-wrapper {
    margin: auto;
    margin-top: 2rem;
    font-family: Nunito;
    position: relative;
    width: 32.8rem;
    height: 4.5rem;

}

.input-label {
      font-size:18px;
      font-weight:normal;
      position:absolute;
      pointer-events:none;
      left:35rem;
      top:10px;
      transition:0.2s ease all; 
      -moz-transition:0.2s ease all; 
      -webkit-transition:0.2s ease all;
      width: 118px;
    height: 22px;
    font-family: Nunito;
    font-size: 16px;
    font-weight: 300;
    letter-spacing: 0.2px;
    text-align: left;
    color: #000000;
}


.email-input {
    width: 100%;
    height: 100%;
}

.input-label{
    position: absolute;
    left: 0px;
    
}
// .email-input {
//     width: 32.8rem;
//     height: 4.5rem;
//     border: none;
//     border-radius: 2px;
//     background-color: #ffffff;
    
//     font-size: 16px;
//     font-weight: 300;
//     letter-spacing: 0.2px;
//     text-align: left;
//     color: #000000;
//     padding-left: 22px;
//     box-shadow: 0 10px 15px 0 rgba(31, 32, 34, 0.3), 0 0 5px 0 rgba(31, 32, 34, 0.15);
//     &:focus{
//         height: 75px;
//         // border-radius: 2px;
//         // background-color: #ffffff;
//         // box-shadow: 0 30px 25px 0 rgba(39, 20, 112, 0.5), 0 0 5px 0 rgba(31, 32, 34, 0.15);
//         // border: solid 1px #1ab640;width: 200rem;
//     }
// }



.reserve-button {
    margin-top: 2.1rem;
    border-style: none;
    width: 35rem;
    height: 5.5rem;
    border-radius: .8rem;
    background-image: linear-gradient(to bottom, #1dba74, #1a4f8d);
    box-shadow: 0 20px 25px 0 rgba(39, 20, 112, 0.5), 0 0 5px 0 rgba(31, 32, 34, 0.15);
    &:hover{
        background-image: linear-gradient(rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0.05)), linear-gradient(to bottom, #1dba74, #1a4f8d);
        box-shadow: 0 30px 25px 0 rgba(39, 20, 112, 0.5), 0 0 5px 0 rgba(31, 32, 34, 0.15);
    }
    &:active + clicked{
        background-image: linear-gradient(rgba(0, 0, 0, 0.08), rgba(0, 0, 0, 0.08)), linear-gradient(to bottom, #1dba74, #1a4f8d);
        box-shadow: 0 6px 10px 0 rgba(39, 20, 112, 0.2), 0 0 5px 0 rgba(31, 32, 34, 0.15);
    }
    /*&:hover {
        opacity: 0;
        background-color: black;
        background-image: linear-gradient(rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0.05)), linear-gradient(to bottom, #1dba74, #1a4f8d);
        box-shadow: 0 30px 25px 0 rgba(39, 20, 112, 0.5), 0 0 5px 0 rgba(31, 32, 34, 0.15);
    }*/
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
