<template>
    <div>
        <juegos-lista></juegos-lista>
        <juegos-stock></juegos-stock>
    </div>
</template>

<script>
import JuegosStock from '@/components/juegos/JuegosStock.vue'
import JuegosLista from '@/components/juegos/JuegosLista.vue'

export default {
    name: 'juegos-view',

    data: function(){
        return {}
    },

    components: {
        'juegos-lista': JuegosLista,
        'juegos-stock': JuegosStock
    },

}
</script>

<style scoped>
    
</style>