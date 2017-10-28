<template>
    <div class="modal-mask">
      <div class="modal-wrapper">
        <div class="modal-container">
<!--         <div class="modal-left-wave"></div>
        <div class="modal-right-wave"></div> -->
          <div class="modal-header">
            <div class="small-logo logo-shadow"></div>
            <div class="close-button"></div>
          </div>
          <div class="modal-body">
            <div class="people-ahead-cont">
                <h2 class="people-ahead-text"><span class="bold">8,465,903</span> People ahead of you</h2>
                </div>
                <div class="people-behind-cont"> 
                <p class="people-behind-text alt-font"><span class="bold">1,560</span> People behind you</p>
            </div>
            <div class="admit-one-cont">
                <div class="admit-one-image">
                    <img src="https://s3.us-east-2.amazonaws.com/follow-curator/ticket%403x-min.png">
                </div>
                <p class="reservation-text open-sans">This reservation is held for [%usergiven_email%]. <span style="text-dec">Is this not you?</span></p> 
            </div>
            <div class="line-break"></div>
            <div class="priority-access-cont">
                <h1 class="priority-access-text">Interested in priority access?</h1>
                <p class="priority-access-text-sub">Get early be referring your friends. The more friends that join, the sooner you’ll get access.</p>
            </div>
          </div>
          <div class="modal-footer">
            <div class="social-links-cont">
                <div class="social-box">
                  <div class="modal-facebook"></div>
                  <div class="social-text">share</div>
                    
                </div>
                 <div class="social-box">
                     <div class="modal-twitter"></div>
                  <div class="social-text">tweet</div>
                    
                </div>
                  <div class="social-box">
                     <div class="modal-email"></div>
                  <div class="social-text">email</div>
                    
                </div>
                 <div class="social-box">
                     <div class="modal-instagram"></div>
                  <div class="social-text">share</div>
                    
                </div>
            </div>
            <div class="unique-link-cont">
                <h3>Or share this unique link:</h3>
                <p>https://www.curator.com/#%link%#</p>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>

export default {
    name: 'reserveModal',
    data() {
        return {
           
        }
    }
}

</script>

<style lang="scss">
.modal-mask {
  position: fixed;
  z-index: 9998;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(16, 10, 37, 0.8);
  display: table;
  transition: opacity .3s ease;
  text-align: center;

}

.modal-wrapper {
  // margin-top: 11.2rem;
  // margin-bottom: 11.2rem;

  display: table-cell;
  vertical-align: middle;
}

.modal-container {
  height: 85%;
  width: 83%;
  max-width: 850px;
  margin: auto;
  background-color: #593cbe;
  border-radius: 2px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .33);
  transition: all .3s ease;
  // background-image: url('https://s3.us-east-2.amazonaws.com/follow-curator/modal-leftwave.svg');

}

.reservation-text{
  width: 260px;
  height: 38px;
  font-family: OpenSans;
  font-size: 14px;
  letter-spacing: 0.2px;
  text-align: center;
  color: #ffffff;
  margin: auto;
  margin-top: 2.5rem;

}
.modal-header {
    padding-top: .62rem;
}
.close-button{
  width: 5rem;
  float: right;
  height: 5rem;
  background-repeat: no-repeat;
  // margin: auto;
  margin-top: 3rem;
  // background-color: #ffffff;
  // box-shadow: 0 2px 14px 0 rgba(0, 0, 0, 0.7), 0 3px 17px 0 #ffffff, 0 4px 3px 2px rgba(72, 46, 174, 0.5), 0 2px 0 0 rgba(0, 0, 0, 0.1);
  background-image: url("https://s3.us-east-2.amazonaws.com/follow-curator/close.svg");
}

.people-ahead-cont{
    width: 73%;
    height: 7%;
    margin: auto;
.people-ahead-text{
    font-family: Nunito;
    font-size: 42px;
    font-weight: 200;
    letter-spacing: 1px;
    color: #ffffff;
    }
}

.people-behind-cont{
    width: 37%;
    height: 22px;
    margin: auto;
    margin-top: 1rem;
    .people-behind-text{
        font-family: 'Open Sans', sans-serif;
    font-size: 16px;
    letter-spacing: 0.5px;

    color: #ffffff;
    }
}


.priority-access-text{
    font-family: 'Nunito', sans-serif;
    font-size: 28px;
  font-weight: bold;
  letter-spacing: 1px;
  padding-top: 3rem;
}

.priority-access-text-sub{
  width: 450px;
  margin: auto;
  padding-top: 1.3rem;
  font-family: 'Open Sans', sans-serif;
  font-size: 16px;
  line-height: 1.38;
  letter-spacing: 0.5px;

}
.line-break{
  width: 200px;
  height: 0.02rem;
  border: solid .02rem #351d8a;
  margin: auto;
  margin-top: 4.2rem;
}

.admit-one-image {
    width: 198px;
    margin: auto;
    margin-top: 2rem;
    img{
        width: 100%;
    object-fit: contain;
    }
}
.logo-shadow{
    box-shadow: 0 5px 26px 0 #ffffff, 0 6px 5px 3px rgba(72, 46, 174, 0.5), 0 3px 0 0 rgba(0, 0, 0, 0.1);

}


.email {
    width: 20px;
  height: 16px;
  object-fit: contain;
  background-color: #ffffff;
}

.bold {
  font-weight: bold;
}

.social-box{
  margin: auto;
  display: inline-block;
  margin-right: 1.5rem;
  margin-top: 4rem; 
  width: 120px;
  height: 40px;
  border-radius: 6px;
  background-image: linear-gradient(to bottom, #1dba74, #1a4f8d);
  box-shadow: 0 20px 25px 0 rgba(39, 20, 112, 0.5), 0 0 5px 0 rgba(31, 32, 34, 0.15);

}
.social-text{
  width: 61px;
  height: 19px;
  font-family: 'Nunito', sans-serif;
  text-transform: uppercase;
  font-size: 14px;
  font-weight: 900;
  letter-spacing: 2px;
  text-align: center;
  font-size: 14px;
  font-weight: 900;
  letter-spacing: 2px;
  text-align: center;
  color: #ffffff;


}
.open-sans {
  font-family: 'Open Sans', sans-serif;
}

.unique-link-cont{
  width: 450px;
  height: 27px;
  font-family: Nunito;
  margin: auto;
  font-size: 20px;
  font-weight: bold;
  letter-spacing: 0.5px;
  text-align: center;
  color: #ffffff;
}



.modal-left-wave {
  width: 85rem;
  height: 90%;
  object-fit: contain;
  // background-image: linear-gradient(131deg, #835fdc, #4c31b5);
  position: absolute;
  z-index: -1;
  left: 30px;
  background-size: cover;
  background-color: black;
  background-image: url('https://s3.us-east-2.amazonaws.com/follow-curator/modal-leftwave.svg');
}

.modal-email {
  position: relative;
  top: 25%;
  width: 20px;
  height: 16px;
  object-fit: contain;
  // background-color: #ffffff;
  background-image: url('https://s3.us-east-2.amazonaws.com/follow-curator/modal-email.svg');
}
/*
 * The following styles are auto-applied to elements with
 * transition="modal" when their visibility is toggled
 * by Vue.js.
 *
 * You can easily play with the modal transition by editing
 * these styles.
 */

// .modal-enter .modal-container,
// .modal-leave-active .modal-container {
//   -webkit-transform: scale(1.1);
//   transform: scale(1.1);
// }



</style>