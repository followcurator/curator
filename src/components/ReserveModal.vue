<template>
    <div class="modal-mask">
      <div class="modal-wrapper">
        <div class="modal-container">
          <div class="modal-header">
            <div class="small-logo logo-shadow"></div>
          </div>
          <div class="modal-body">
            <div class="people-ahead-cont">
                <h2 class="people-ahead-text">8,465,903 People ahead of you</h2>
                </div>
                <div class="people-behind-cont"> 
                <p class="people-behind-text">1,560 People behind you</p>
            </div>
            
            <div class="admit-one-cont">
                <div class="admit-one-image">
                    <img src="https://s3.us-east-2.amazonaws.com/follow-curator/ticket%403x.png">
                </div>
                <p>This reservation is held for [%usergiven_email%]. Is this not you?</p> 
            </div>
            <div class="line-break"></div>
            <div class="priority-access-cont">
                <h1>Interested in priority access?</h1>
                <p>Get early be referring your friends. The more friends that join, the sooner you’ll get access.</p>
            </div>
          </div>
          <div class="modal-footer">
            <div class="social-links-cont">
                <div class="social-box">
                    
                </div>
                 <div class="social-box">
                    
                </div>
                 <div class="social-box">
                    
                </div>
                 <div class="social-box">
                    
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
  display: table-cell;
  vertical-align: middle;
}

.modal-container {
  height: 60rem;
  width: 80rem;
  margin: auto;
  background-color: #593cbe;
  border-radius: 2px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, .33);
  transition: all .3s ease;

}


.modal-header {
    padding-top: .62rem;
}

.people-ahead-cont{
    width: 607px;
    height: 57px;
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
    width: 196px;
    height: 22px;
    margin: auto;
    .people-behind-text{
        font-family: OpenSans;
    font-size: 16px;
    letter-spacing: 0.5px;
    color: #ffffff;
    }
}



.admit-one-image {
    // padding-top-top: 1rem;
     width: 198px;
    height: 88px;
    margin: auto;
    img{
        width: 100%;
    object-fit: contain;
    }
}
.logo-shadow{
    // background-color: #ffffff;
    box-shadow: 0 5px 26px 0 #ffffff, 0 6px 5px 3px rgba(72, 46, 174, 0.5), 0 3px 0 0 rgba(0, 0, 0, 0.1);

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