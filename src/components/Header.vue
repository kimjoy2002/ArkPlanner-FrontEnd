<template lang="pug">
div
    span(style='font-size: 150%;') ArkPlanner Vanilla
    span(style="float: right;")
        a(href='https://planner.penguin-stats.io/') ArkPlanner @ 企鹅物流
</template>


<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class ArkplannerHeader extends Vue {

}
</script>

<style scoped lang='stylus'>
a
    color: white
    text-decoration: none

a:hover 
    color: rgb(217, 236, 255);
</style>
