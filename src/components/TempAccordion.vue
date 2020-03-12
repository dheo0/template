<template>
    <div class="accordion">
        <ul>
            <li>
                <div class="acco-head">
                    <a href="#none">
                        <span class="icon"></span>
                        <em>{{ headTitle }}</em>
                    </a>
                </div>
                <div class="acco-body">
                    <div class="acco-body-content">
                        {{ accoContent }}
                    </div>
                </div>
            </li>
        </ul>
    </div>
</template>
<script>
export default {
  props: {
    headTitle: {
      type: String,
      default: '타이틀'
    },
    accoContent: {
      type: String,
      default: '내용'
    }
  }

}
</script>
