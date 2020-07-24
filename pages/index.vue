<template>
    <section>
        <o-button @click="clickMe">Click Me</o-button>
    </section>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
    methods: {
        clickMe() {
            alert('Clicked!')
        }
    }
})
</script>
