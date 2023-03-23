<script>
import NewTitle from "./components/AppTitle.vue"
import Image from "./components/AppHero.vue"

export default {
    data() {
        return {

        }
    },

    components: {
        NewTitle,
        Image,
    }
}

</script>

<template>
    <div class="container">

        <Image></Image>
        <NewTitle></NewTitle>

    </div>
</template>

<style>
.container {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>