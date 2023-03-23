<script>
import NewTitle from "./components/AppTitle.vue"

export default {
    data() {
        return {

        }
    },

    components: {
        NewTitle,
    }



}

</script>

<template>
    <div class="container">

        <NewTitle></NewTitle>

    </div>
</template>


<style>
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;


}
</style>