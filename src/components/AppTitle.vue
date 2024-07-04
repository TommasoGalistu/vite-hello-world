<script>
import JamboComponent from './AppHero.vue'

export default {
    name: 'FirstComponent',
    components: {
        JamboComponent
    }
}
</script>

<template>
    <div>

        <h1>La mia prima app con Vite!</h1>
        <JamboComponent />
    </div>
</template>

<style scoped>
    div{
        text-align: center;
    }
</style>