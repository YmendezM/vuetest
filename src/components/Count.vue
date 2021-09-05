<template>
    <div>
        <button v-on:click="increments">++</button>
        <span>Valor de contador {{ count }}</span>
    </div>
</template>
<script>
export default {
    name:"Count",
    data(){
        return{
            count: 0
        }
    },
    methods: {
        increments: function(){
            this.count++
        }
    },
}
</script>