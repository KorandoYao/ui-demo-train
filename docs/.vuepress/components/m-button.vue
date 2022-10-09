<template>
  <div class="m-button">
    <button :disabled="disabled" :style="bgColor ? {backgroundColor: bgColor} : {}">
        <span>{{text}}</span>
    </button>
  </div>
</template>

<script>
export default {
  name: 'm-button',
  props: {
    text:{
        type:String,
        default:''
    },
    disabled:{
        type:Boolean,
        default:false
    },
    bgColor:{
        type:String,
        default:''
    }
    
  }
}
</script>

<style lang="scss">
  @import "./button.scss";
</style>
