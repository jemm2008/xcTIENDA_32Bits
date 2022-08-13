<template>
    <div>
        <h3>Stock de Juegos: {{getJuegos}}</h3>
    </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
    name: 'juegos-stock',
    data: function(){
        return {}
    },
    computed: {
        ...mapGetters(['getJuegos'])
    },
}
</script>

<style scoped>
    
</style>