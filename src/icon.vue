<template>
    <svg class="g-icon">
        <use :xlink:href="`#i-${name}`"></use>
        <!--         $ 是模板字符串插值 -->
    </svg>
</template>
<script>
    import './svg'
    export default {
        props:['name']
    }
</script>
<style lang="scss">
    .g-icon {
        width: 1em;
        height: 1em;
    }
    </style>