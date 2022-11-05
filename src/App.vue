<template>
  <MyBtn
    @nothingct="log"
    @change-msg="logMsg">
    Banana
  </MyBtn>
</template>

<script>
import MyBtn from '~/components/Mybtn';

export default {
  components: {
    MyBtn
  },
  methods : {
    log(event){
      console.log('click!!')
      console.log(event)
    },
    logMsg(msg){
      console.log(msg)
    }
  }
}
</script>

