<template>
    <button class="btn">
        <span>{{ text }}</span>
    </button>
</template>
<script>
export default {
  props: {
    text: {
      type: String,
      default: '버튼텍스트'
    }
  }

}
</script>
