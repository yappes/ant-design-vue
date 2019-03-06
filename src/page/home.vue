<template>
    <div class="home">
        hello word
    </div>
</template>
<script>
import Service from '@/services/service.js'
export default {
    name:'Home',
    mounted(){
        console.log(Service.getCountInfo)
    }
}
</script>
<style lang="sass" scoped>

</style>



