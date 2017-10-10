<template>
    <div class="modal-mask">
      <div class="modal-wrapper">
        <div class="modal-container">
          <div class="modal-header">
            <div class="small-logo"></div>
          </div>
          <div class="modal-body">
          </div>
          <div class="modal-footer">
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