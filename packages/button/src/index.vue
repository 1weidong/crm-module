<template>
    <div @click="clickMe">
        点我
    </div>
</template>

<script lang="ts">
import { Vue } from 'vue-property-decorator';
export default class Botton extends Vue {
    clickMe() {
        alert(1111)
    }
}
</script>