<template>
    <p>Register for the event here</p>
    <button @click="register" >Register me</button>
</template>

<script> 
export default {
  props: ['event'],
  methods:{
    register(){
      // call to api
      // if registerd then redirect to event details

      this.$router.push({
        name:'EventDetails',
        //params:{id: this.event.id}
      })



    }
  }
}
</script>